---
title: "Blend Mode Map"
date: 2019-08-20T14:56:06+02:00
draft: false
appurl: "https://nieneb.github.io/blendmode_map/"
weight : 1
image: "/img/blend_mode_map.png"
screenname: "BNiene"
hashtags: "webmapper"
---


[Application](https://nieneb.github.io/blendmode_map/)

Press the `[L]` button on your keyboard for some mouse over action!


<!--more-->

This was a test to see if CSS blend-modes have a effect on the WebGL rendered map form MapboxGL.js. And yes they do! The trick is to put an image right behind your map container and put a blend-mode on the image. 

Of course it is limited to one blend-mode on the whole map! But leaving out a lot of layers and simply making a white map of the road structures and water bodies gives a pretty neat effect. 

Press the `[L]` on you keyboard to play around with some mouse over effects. It creates bubbles where your mouse moves. The bubbles have a different blend-mode with the map and background image and another blend-mode with themselves. 

Blend-mode on the map: `overlay`

Blend-mode on the bubbles:  `difference`

Blend-mode between the bubbles: `sorf-light`

This is all implemented with the CSS of the application. 

<i class="fa fa-github"></i> Check the [github repro](https://github.com/NieneB/blendmode_map) for the code!

![](/img/blendmodemap_2.gif)

Made for Webmapper: <a href="https://webmapper.net">![](/img/logo_reverse.svg)</a>