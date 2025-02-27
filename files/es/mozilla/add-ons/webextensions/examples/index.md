---
title: Ejemplos de extensiones
slug: Mozilla/Add-ons/WebExtensions/Examples
tags:
  - WebExgtensions
translation_of: Mozilla/Add-ons/WebExtensions/Examples
---
{{AddonSidebar}}

Para ayudar en la ilustración de cómo desarrollar las extension, se mantiene un repositorio de ejemplos simples de extensions en <https://github.com/mdn/webextensions-examples>. Este artículo describe las extensiones en ese repositorio.

Estos ejemplo funcionan en Firefox Nightly: la mayoría funcionan en versiones más recientes de Firefox, pero revise la clave [strict_min_version](/en-US/Add-ons/WebExtensions/manifest.json/applications) en el manifest.json del complemento para estar seguro.

Si quiere probar estos ejemplo, tiene tres opciones principales:

1.  Clone el repositorio, entonces, carge el complemento directo desde su directorio, utilizando la función ["Cargar complemento temporalmente"](/en-US/Add-ons/WebExtensions/Temporary_Installation_in_Firefox). El complemento estará cargado hasta que se reinicie Firefox.
2.  Clone el repositorio, luego utilice la herrmienta [web-ext](/es/Add-ons/WebExtensions/Getting_started_with_web-ext) en la línea de comando para ejecutar Firefox con el complemento instalado.
3.  Clone el repositorio, luego diríjase al directorio [build](https://github.com/mdn/webextensions-examples/tree/master/build). Este contiene todos los ejemplos firmados y compilados, así que usted puede abrilos en Firefox (utilizando Archivo/Abrir archivo) e instalarlos permanentemente, justamente como cuando se instala un complemento desde [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/).

Si quiere contribuir al repositorio, [¡envíe una petición de pull!](https://github.com/mdn/webextensions-examples/blob/master/CONTRIBUTING.md)

{{WebExtAllExamples}}
