---
title: "Workshop Vector tiles"
date: 2018-08-18T13:40:04+02:00
showonlyimage : false
draft : false
image : "https://nieneb.nl/img/online/screenshot_background.png"
weight : 0
---

Vector Tile workshop for Foss4G-NL 2018

* [The presentation](https://nieneb.github.io/foss4gNL_vector_tiles/)
* [The online workshop](https://github.com/NieneB/foss4gNL_vector_tiles/wiki)

<!--more-->

Vector tile technologie is een nieuw alternatief op de traditionele raster image tiles voor web maps. Zij maken web maps sneller te publiceren en flexibeler vorm te geven.

Hoe werken vector tiles en hoe kom je er aan? In deze workshop maken we zelf een web map op basis van vector tiles. We gebruiken vector tiles van PDOK en OpenMapTiles of maken vector tiles van eigen geo-data (PostGIS/GeoPackage). Er zijn voorbeelden voor beginners en gevorderden.

Voor beginners ligt de focus op de front-end ontwikkeling. We maken een kaart te maken met [Mapbox Studio](https://www.mapbox.com/studio/). Daarna zetten we zelf een eenvoudige web-pagina met een kaart-viewer op te zetten met [MapboxGL.js](https://www.mapbox.com/mapbox-gl-js/api). We gebruiken de [Mapbox Style Specification](https://www.mapbox.com/mapbox-gl-js/style-spec/) om een eigen cartografische vormgeving te specificeren in de vorm van een style.json bestand. De vector tiles komen van [PDOK](https://github.com/PDOK/vectortiles-bgt-brt). Enige voorkennis van HTML, CSS en JavaScript is hierbij handig.

Voor gevorderden zijn er voorbeelden om vanuit PostGIS je eigen data te serveren als vector tiles met [Tegola](https://github.com/go-spatial/tegola) of [T-rex](https://github.com/t-rex-tileserver/t-rex) en om OpenStreetMap data te serveren met [OpenMapTiles Server](https://openmaptiles.com/server/). Als extra kan je de cartografische vormgeving verder uitwerken door zelf iconen (sprites) te maken en eigen lettertypes (glyphs) te gebruiken. Deze voorbeelden gebruiken Docker of NodeJS/NPM om de tools te installeren en draaien.

Kennis nodig:

* Beginners : HTML, CSS & JS
* Gevorderden: Docker, NodeJS/NPM, PostGIS

Na afloop kan je:

* Een vector tile web map vormgeven met Mapbox studio.
* Een kaart-viewer voor vector tiles opzetten met MapboxGL.js
* Openbare vector tiles vormgeven en tonen met een style.json bestand volgens de [Mapbox Style Specification](https://www.mapbox.com/mapbox-gl-js/style-spec/).
* Eigen vector tiles maken en publiceren met Openmaptiles, Tegola of T-rex.
* Eigen sprites en glyphs ontwikkelen.


<i class="fa fa-github"></i>
[repro](https://github.com/NieneB/foss4gNL_vector_tiles/)


Made for webmapper: <a href="https://webmapper.net">![](/img/logo_reverse.svg)</a>