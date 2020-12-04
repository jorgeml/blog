---
author: jorgeml
date: 2010-11-21 11:54:08+00:00
draft: false
title: Jugando con el router
type: 
- post
- posts
comments: false
url: /2010/11/21/jugando-con-el-router/
tags:
- internet
- openwrt
- red
- router
---

Hace unas semanas me decidí a cambiar el router de casa, entre otras cosas porque la tele _recomienda_ utilizar WiFi tipo N para el streaming de video en alta definición.

En lugar de comprar el último modelo con todas las prestaciones de alguna marca conocida (Linksys, Netgear, etc.) me decidí por el económico [TP-Link TL-WR1043ND](http://www.tp-link.com/products/productDetails.asp?class=wlan&pmodel=TL-WR1043ND) por menos de la mitad de lo que cuesta un router de los caros.

Aunque el hardware es relativamente decente, el software tiene algunas lagunas, por ejemplo la calidad de servicio (QoS) no es nada intuitiva de configurar.

El siguiente paso en mi plan fue instalar [OpenWRT](http://www.openwrt.org/).  OpenWRT es un firmware alternativo para routers y dispositivos similares basado en Linux. Con OpenWRT es posible instalar nuevos programas que añaden funcionalidad extra al router con la única limitación de la memoria disponible. En mi caso, a pesar de solo contar con 8 Mb he podido instalar y configurar:

* La funcionalidad estándar de cualquier router: DHCP, cortafuegos, etc.
* [IPv6](http://es.wikipedia.org/wiki/IPv6) via un túnel con [SixXS](http://www.sixxs.net/).
* [Calidad de servicio (QoS)](http://es.wikipedia.org/wiki/QoS) para poder navegar por Internet y utilizar [VoIP](http://es.wikipedia.org/wiki/VoIP) con rapidez incluso cuando el [BitTorrent](http://es.wikipedia.org/wiki/BitTorrent_%28protocolo%29) está funcionando.
* DNS dinámico para poder conectarme al router desde Internet sin necesidad de saber la dirección IP (que en mi caso es dinámica).
* OpenVPN para poder acceder a la red de mi casa incluso desde el móvil y para establecer una comunicación segura con este servidor.

Estoy muy satisfecho con la compra y la posterior instalación y configuración de OpenWRT, ya que me permite tener funcionalidades avanzadas a un precio económico. La documentación sobre OpenWRT es extensa aunque no siempre actualizada por lo que solo la recomiendo para valientes (y gente que tenga un router de backup por si las moscas).
