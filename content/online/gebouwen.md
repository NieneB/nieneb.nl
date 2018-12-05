---
title: "Building heights of the Netherlands"
date: 2018-08-18T10:40:43+02:00
showonlyimage : false
draft : false
image : "https://nieneb.nl/img/online/utrecht.png"
weight : 10
hashtags: "webmapper,Top10NL3D"
appurl: "https://apps.webmapper.nl/gebouwen/"
screenname: "BNiene @Webmappery"
---

This interactive map shows the height of all the buildings in the Netherlands.

* [Application](https://apps.webmapper.nl/gebouwen/)

<!--more-->

The information comes from the product [3D gebouwhoogte NL](https://www.kadaster.nl/-/3d-gebouwhoogte-nl) from the Kadaster.

The challenge was to convert a 3.3 GB dataset with 2.992.613 into an interactive 3D viewer. I transformed the GML to [Mapbox Vector Tiles (MVT)](https://www.mapbox.com/vector-tiles/specification/) with <i class="fa fa-github"></i> [Tippecanoe](https://github.com/mapbox/tippecanoe). 
The application is made with HTML, CSS and JavaScript. Using Node and browserify to manage the packages. With the MapboxGL.js library the map was made and styled. Using Typeahead and Bloodhound for the search bar. The location suggest and lookup is based on the [PDOK locatieserver](https://www.pdok.nl/nl/producten/pdok-locatieserver) API.

Later on I added a scroll story, which shows some information about the highest buildings in the Netherlands. Here we show some information about the geographic information this app is based on. 

![Het eindresultaat](https://webmapper.net/images/2018/hoogstegebouwennl.png "Viewer")

At Foss4G-NL 2018 my map was used as the background for their promotion materials! [Matthew Petroff](http://mpetroff.net/) build a tool <i class="fa fa-github"></i> [print maps](https://github.com/mpetroff/print-maps) to export MapboxGL maps to hight resolution images for printing. I <i class="fa fa-github"></i> [forked this tool](https://github.com/NieneB/print-maps) to insert my own map on order to export a high resolution image to make the banner from.

<img src="{{< baseurl >}}img/online/IMG_20180710_093753.jpg">

<img src="{{< baseurl >}}img/online/IMG_20180711_094602.jpg">


Inspiration:

* [Amsterdam](http://tulpinteractive.com/amsterdam-campus/)
* [Berlin](http://interaktiv.morgenpost.de/berlins-neue-skyline/)
* [Melbourne](http://lbutler.github.io/MelbBuildingHeights/)
* [Vancouver](http://maps.nicholsonroad.com/heights/)



Made for webmapper: <a href="https://webmapper.net">![](/img/logo_reverse.svg)</a>