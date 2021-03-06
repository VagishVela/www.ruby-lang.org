---
layout: news_post
title: "Ruby 2.6.6 Released"
author: "nagachika"
translator: "vtamara"
date: 2020-03-31 12:00:00 +0000
lang: es
---

Ruby 2.6.6 ha sido publicado.

Esta versión incluye correcciones de seguridad.
Por favor revise detalles en los siguientes temas.

* [CVE-2020-10663: Vulnerabilidad de Creación Insegura de Objetos en JSON (Corrección adicional)]({% link es/news/_posts/2020-03-19-json-dos-cve-2020-10663.md %})
* [CVE-2020-10933: Vulnerabilidad de exposición del montón (heap) en la librería de zócalos (sockets)]({% link es/news/_posts/2020-03-31-heap-exposure-in-socket-cve-2020-10933.md %})

Ver detalles en la [bitácora de cambios](https://github.com/ruby/ruby/compare/v2_6_5...v2_6_6).

## Descargas

{% assign release = site.data.releases | where: "version", "2.6.6" | first %}

* <{{ release.url.bz2 }}>

      SIZE: {{ release.size.bz2 }}
      SHA1: {{ release.sha1.bz2 }}
      SHA256: {{ release.sha256.bz2 }}
      SHA512: {{ release.sha512.bz2 }}

* <{{ release.url.gz }}>

      SIZE: {{ release.size.gz }}
      SHA1: {{ release.sha1.gz }}
      SHA256: {{ release.sha256.gz }}
      SHA512: {{ release.sha512.gz }}

* <{{ release.url.xz }}>

      SIZE: {{ release.size.xz }}
      SHA1: {{ release.sha1.xz }}
      SHA256: {{ release.sha256.xz }}
      SHA512: {{ release.sha512.xz }}

* <{{ release.url.zip }}>

      SIZE: {{ release.size.zip }}
      SHA1: {{ release.sha1.zip }}
      SHA256: {{ release.sha256.zip }}
      SHA512: {{ release.sha512.zip }}


## Comentario de la versión

Muchos contribuyentes, desarrolladores y usuarios aportaron
reportes de fallas y nos ayudar a hacer esta versión.
Gracias por sus contribuciones.
