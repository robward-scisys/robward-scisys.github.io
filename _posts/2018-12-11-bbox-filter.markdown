---
layout: post
title:  "Release 0.8.3 - BBox filter function issue"
date:   2018-12-11 11:49:38 +0100
categories: sldeditor release
---

SLDEditor Release 0.8.3 BBox filter function issue
==================================================

Version 0.8.3 of the SLD Editor has been released and available [here][sldeditor-release].  The release ensures that UTF-8 is used throughout the application as per the SLD specification.

Whilst working on another project I needed to check how GeoTools handled geometry in the BBox filter function.  I got the SLD Editor to open an SLD file with a BBox filter and discovered that an error was reported.  After some investigation I've raised an issue on the GeoTools project [here][geotools-ticket].  I have a fix but a couple of queries need to be ironed out before submitting a pull request.

[sldeditor-release]: https://github.com/robward-scisys/sldeditor/releases/tag/v0.8.3
[geotools-ticket]: https://osgeo-org.atlassian.net/browse/GEOT-6201

