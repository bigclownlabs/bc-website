---
date: "2018-04-25"
title: "Measure air quality with VOC Tag"
description: "VOC multi pixel gas sensor SGP30 from Sensirion"
images:
    preview: "preview.jpg"
    main: "main.jpg"
author:
    name: "Martin Hubáček"
    post: "Firmware Designer"
    email: "martin.hubacek@hardwario.com"
    image: "martin.jpg"
---


The {{< shop "VOC Tag" >}} is a gas sensor for measuring volatile organic compounds (VOC) concentration. This is useful for indoor air quality monitoring applications. This module uses a metal-oxide multi pixel sensor SGP30 from Sensirion measuring total VOC level.

VOC (Volatile Organic Compounds) sensor is a great technology for indoor air quality measurement applications. Elevated VOC levels can have a negative impact on well being, comfort, and cognitive abilities.

With [Wireless VOC sensor project]({{< relref "doc/projects/wireless-voc-sensor.md" >}}) we are also releasing GFX graphic library, which can now render text and graphics not only on LCD Module, but on any display you connect to the Core Module. You can simply use WS2812B. You just need to write your initialization and write pixel functions and GFX library does the rest. The project also display chart of measured values on the display.

<div>
<img src="voc-lcd.jpg" align="center" style="margin:0 0 20px 0;"/>
</div>

# Related links:

  * [Wireless VOC sensor project]({{< relref "doc/projects/wireless-voc-sensor.md" >}})
  * [VOC Tag in Hardware documentation]({{< relref "doc/hardware/about-voc-tag.md" >}})
  * [Source code for VOC project](https://github.com/bigclownlabs/bcf-wireless-voc-sensor)
  * [GFX library](http://sdk.bigclown.com/group__bc__gfx.html)
