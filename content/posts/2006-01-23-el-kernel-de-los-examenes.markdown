---
author: jorgeml
date: 2006-01-23 18:15:55+00:00
draft: false
title: El kernel de los exámenes
type: 
- post
- posts
comments: true
url: /2006/01/23/el-kernel-de-los-examenes/
tags:
- ordenadores
---

Todo sistema operativo tiene un _kernel_ o núcleo, que se encarga de realizar las tareas más básicas. En el se insertan los _drivers_, controladores o módulos que hacen que el metal funcione. Sobre el núcleo se ejecutan los programas.

Una de las ventajas de Linux es que el kernel está en contínua evolución, y así de vez en cuando sale una nueva versión. En cambio, el kernel de Windows apenas sufre grandes cambios entre versiones.

Una de las cosas que vengo notando es que cuando se acercan los exámenes, o en pleno cogollo, el señor Linus Torvalds tiene a bien publicar una nueva versión del kernel, que al rato es distribuida por los empaquetadores.

Hace un par de días le llegó la versión 2.6.15 a mi Gentoo. No es imprescindible actualizarse al momento, aún así opté por ello.

El problema ha venido hoy al iniciar la máquina con el nuevo kernel: no van los drivers de ATI. Los drivers de ATI son el peor cacho de software que han visto estos ojos que se tiene que comer la tierra. Inestables, incompletos, tienen todo lo que empieza por in- y al ritmo al que van mis nietos no verán unos drivers decentes. Y eso que la propia ATI está detrás.

Harto de los drivers de ATI he instalado los drivers libres, hechos por programadores independientes. No tengo aceleración 3D, tampoco la necesito para las prácticas, pero **funcionan**.

En la próxima versión del servidor gráfico X.org, estos drivers libres vienen integrados, con aceleración 3D y todo. No veo el momento en el que esté disponible para mi Gentoo, los recibiré con lágrimas en los ojos.

También ha habido un par de actualizaciones que han roto cosas (HAL y DBUS), pero parece que por el momento están controladas.
