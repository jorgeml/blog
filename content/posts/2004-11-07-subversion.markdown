---
author: jorgeml
date: 2004-11-07 13:01:44+00:00
draft: false
title: Subversion
type: 
- post
- posts
comments: true
url: /2004/11/07/subversion/
tags:
- ordenadores
---

Lo estaba pidiendo a gritos. Este fin de semana me he dedicado a instalar y poner en marcha [Subversion](http://subversion.tigris.org), un sistema de control de versiones. Para los que no tengais ni idea de para que sirve os lo explico.

Imaginaros que teneis que hacer unas prácticas de programación con un compañero. Una situación común es que los dos os bajais el mismo fichero de Internet y empezais a hacer cambios. También es común que cada uno empieze a tocar cosas por su cuenta. Luego llega el momento de tener que juntar el trabajo y ahí empiezan los líos. Normalmente hay que estar dandole al "Copy & Paste" a mansalva, buscando los trozos de código que son distintos. A veces dos cambios se solapan y se montan unos jaleos tremendos.

Por eso se inventaron los sistemas de control de versiones. El más conocido es CVS, que tiene ciertas limitaciones que Subversion no tiene (porque fue diseñado con los problemas de CVS en la mente). Como Subversion está ganando mucha popularidad, incluso grandes proyectos (KDE...) están migrando a Subversion o lo están considerando, he instalado subversion en mi ordenador, he puesto un sistema de autenticación para que no me copien las prácticas y he empezado a trabajar con el.

El funcionamiento es más o menos sencillo. Primero se crea un _repositorio_ donde se van a almacenar los ficheros del proyecto. Después, el el directorio de trabajo se hace un _check out_ y se descargan los ficheros desde el repositorio. Una vez que se ha terminado con ellos se suben haciendo un _commit_. Además se puede escribir un mensaje explicando los cambios. En caso de conflicto el sistema avisa y uno toma las decisiones apropiadas.

Aunque me ha llevado tiempo ponerlo en marcha, el sistema me gusta y creo que me va a ahorrar muchos quebraderos de cabeza. Veremos que tal.
