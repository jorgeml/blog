---
author: jorgeml
date: 2011-10-12 16:49:18+00:00
draft: false
title: How I solved a big problem with a few lines of code
type: 
- post
- posts
comments: false
url: /2011/10/12/how-i-solved-a-big-problem-with-a-few-lines-of-code/
tags:
- asterisk
---

**Problem statement**

In the last weeks my girlfriend got some calls from a guy in Iran in her fixed number from Madrid. It seems the guy got the wrong number and he hanged immediately after hearing her voice. He is quite persisting and keeps trying, maybe hoping that the little goblins on the Internet will route him to the right person eventually. On top of that there is quite a time zone difference between the Netherlands and Iran so he was not calling at convenient times for our daily dose of sleep.

**Solution**

Fortunately we use a software PBX called Asterisk, which is quite flexible and powerful and moreover it is free software.

After a little bit of Googling I could solve the Iranian problem with just 4 lines of code in the dialplan:

{{< highlight text >}}
exten => XXXXXXXXX/YYYYYYYYY,1,NoOp(Phone call from Iran)
exten => XXXXXXXXX/YYYYYYYYY,n,Set(LANGUAGE()=en)
exten => XXXXXXXXX/YYYYYYYYY,n,Playback(privacy-stop-calling-not-welcome2)
exten => XXXXXXXXX/YYYYYYYYY,n,Hangup()
{{< /highlight >}}

Being XXXXXXXXX my girlfriend's phone number and YYYYYYYYY the number from the Iranian guy. The four lines do the following: the first one is just used for logging, the second one switches the language to English from our default Spanish, the third one plays the announcement "_You are not welcome here, please stop calling this number!_" and the fourth line just hungs up. Since the guy also blocks his caller ID from time to time I also added similar code to _invite_ anonymous calls to show their number.

The guy has just called once since the introduction of the new dialplan, I guess he got the message.

It is amazing how fast the telecom world evolves. Some years ago I could not imagine you could solve this with your own free PBX.
