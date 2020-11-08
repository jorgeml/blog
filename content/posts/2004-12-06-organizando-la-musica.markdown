---
author: jorgeml
date: 2004-12-06 23:15:10+00:00
draft: false
title: Organizando la música
type: 
- post
- posts
comments: true
url: /2004/12/07/organizando-la-musica/
tags:
- internet
- música
- ordenadores
---

Soy un maniatico en lo que se refiere a tener organizada la música del ordenador. Algunos ya sabeis que para no andar trasteando con CDs (y no haber tenido que llevarmelos a Holanda), pasé toda mi colección de CDs a MP3 con la ayuda del audiocd:/ de KDE, una de las cosas que me llevaría a una isla desierta.

Si bien para escuchar y hacer pequeñas modificaciones a las etiquetas de los archivos con [Amarok](http://amarok.kde.org) me basta, a veces necesito algo más. Así que recurro a [Juk](http://developer.kde.org/~wheeler/juk.html), más parecido a uno de los mejores reproductores de música del momento, el [iTunes](http://www.apple.com/es/itunes/).

Si bien todas esas herramientas nos permiten editar las etiquetas a nuestro gusto, a veces es necesario rellenarlas todas sin tener ninguna información previa. Aquí es donde [MusicBrainz](http://www.musicbrainz.org) entra en juego. MusicBrainz es un índice de música, tienen una colección de música tremenda. Podemos buscar cualquier artista, album o canción. Si solo tenemos el fichero, podemos recurrir a programas que nos darán una identificación que podemos utilizar en MusicBrainz. Por ejemplo:

`
$ trm untitled.mp3
03729f96-752a-4140-8506-3ea419c7818b
`

Con este código nos vamos a MusicBrainz, Search, y lo introducimos en la caja TRM Id y voilá, ahí está (premio al que me diga que canción es). Para Windows existe una utilidad llamada _Tagger_ que promete.

Ya que hemos mencionado el tema de la musica en el ordenador, el ya mencionado Amarok me tiene loco. La interfaz es simple y bonita, utiliza MusicBrainz de manera integrada (aunque en mi versión no va por un tema de librerias), se baja las portadas de los discos de Amazon, clasifica la música según tus gustos, tiene plugins y visualizaciones para aburrir... le da mil vueltas al famoso WinAmp.
