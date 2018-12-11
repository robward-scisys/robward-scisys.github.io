---
layout: post
title:  "GeoTools/GeoServer BBox filter function issue"
date:   2018-12-11 11:51:38 +0100
categories: sldeditor release
---

BBox filter function issue
-=========================

Whilst working on another project I needed to check how GeoTools handled geometry in the BBox filter function.  I got the SLD Editor to open an SLD file with a BBox filter and discovered that an error was reported.  After some investigation I've raised an issue on the GeoTools project [here][geotools-ticket].  I have a fix but a couple of queries need to be ironed out before submitting a pull request.

[geotools-ticket]: https://osgeo-org.atlassian.net/browse/GEOT-6201

