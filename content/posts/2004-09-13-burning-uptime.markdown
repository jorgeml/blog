---
author: jorgeml
date: 2004-09-13 18:33:41+00:00
draft: false
title: Burning uptime
type: 
- post
- posts
comments: true
url: /2004/09/13/burning-uptime/
tags:
- ordenadores
---

Para aquellos que no lo sepan, se llama ''uptime'' al tiempo que permanece encendido un PC. Exactamente se mide como el tiempo desde el último reinicio. Los administradores de sistemas compiten entre ellos a ver quién mantiene la máquina encendida durante más tiempo. Una comparativa de servidores se puede ver [aquí](http://uptime.netcraft.com/). La información sobre mi servidor se puede ver [aquí](http://uptime.netcraft.com/up/graph?site=www.jorgeml.com). Mi record personal está en mes y pico. Hoy he tenido un ''downtime'' de varias horas, os lo cuento.

Todo ha empezado por un pequeño apagón en la zona donde vivo. Al volver la luz vuelvo a apreciar ese olor a quemado que había ultimamente en la habitación. Compruebo si procede del ordenador y miro en la parte de atrás. Para mi sorpresa y desgracia el ventilador de la fuente de alimentación está parado. WARNING. Se enciende la luz roja en mi palabra y apago el ordenador echando leches. Ahora entiendo por que el pc estaba calentito últimamente. Pa'haberme matao o haber convertido el ordenador en barbacoa. Acudo a la tienda habitual donde compro una fuente nueva más potente.

Aprovecho que tengo el ordenador en modo "Mad Max" para arreglar la disquetera (un cable estaba suelto) y desinstalar el segundo disco duro (de 4 Gb y sin uso). Al volver a encender el ordenador protesta por la falta de cable de 80 pines, pero arranca. Mi Mandrake 10 protesta después por la desaparición del disco duro, arrancando en modo mantenimiento. Toco fondo.

Cojo mi disco de [Knoppix](http://www.cylnux.org/knoppix-es/) y arranco el ordenador. Accedo a mis particiones y edito la configuración de Mandrake a mano. Además me conecto a Internet e investigo el mensaje del cable de 80 pines. Descubro la existencia de cables de 80 pines y el por que de la protesta. Abro la caja de la placa base y observo el cable. Lo enchufo y... no funciona. Tras varios minutos dandole vueltas al problema, cambio el jumper del disco duro de la posición "Master" a "Cable Select". Arranca sin ningún problema y hasta noto cierta mejoría en cuanto a velocidad.

Así que niños, un par de consejos:

* Cuando cambieis algo del ordenador, haced una cosa cada vez. Así identificareis antes los fallos.
* El olor a quemado no es normal. Revisad los ventiladores. Comprobad que ningún cable los obstruya.
* No intenteis seguir mis pasos en casa sin la debida supervisión paterna.
