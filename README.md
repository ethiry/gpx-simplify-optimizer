Track Simplifier / Optimizer online [![Build Status](https://travis-ci.org/stefanocudini/gpx-simplify-optimizer.svg?branch=master)](https://travis-ci.org/stefanocudini/gpx-simplify-optimizer)
============

Online Simplifier and Optimizer for GPX / GeoJSON / KML tracks.

Copyright 2014 [Stefano Cudini](http://labs.easyblog.it/stefano-cudini/)

Demo
----
[labs.easyblog.it/maps/gpx-simplify-optimizer](http://labs.easyblog.it/maps/gpx-simplify-optimizer/)

![Image](https://raw.githubusercontent.com/stefanocudini/gpx-simplify-optimizer/master/images/gpx-optimizer.png)

Usage
-----
1. Upload GPX / KML / GeoJSON file
2. Simplify the track on the map by reducing the number of nodes
3. Save or view the simplified track in different formats : GPX / KML / GeoJSON / Mediawiki Maps

Install 
-------
```bash
git clone https://github.com/stefanocudini/gpx-simplify-optimizer.git
cd gpx-simplify-optimizer
git submodule init
git submodule update
```

Build
-----
```bash
npm install
grunt
```

