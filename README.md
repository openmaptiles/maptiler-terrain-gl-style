# Klokantech Terrain
[![Build Status](https://travis-ci.org/openmaptiles/klokantech-terrain-gl-style.svg?branch=master)](https://travis-ci.org/openmaptiles/klokantech-terrain-gl-style)

A Mapbox GL basemap style it is using the vector tile
schema of [OpenMapTiles](https://github.com/openmaptiles/openmaptiles) as well as the contour lines and hillshading from [openmaptiles.com](https://openmaptiles.com).

## Preview

**[:globe_with_meridians: Browse the map](https://openmaptiles.github.io/klokantech-terrain-gl-style)**

<img src="http://demo.tileserver.org/styles/klokantech-terrain/static/8.540587,47.370555,15.08/600x400@2x.png" width="600" title="Klokantech Terrain Preview Zurich">

<img src="http://demo.tileserver.org/styles/klokantech-terrain/static/8.619184,47.336203,10.07/600x400@2x.png" width="600" title="Klokantech Terrain Preview Lake Zurich">

<img src="http://demo.tileserver.org/styles/klokantech-terrain/static/8.243967,46.916315,7.21/600x400@2x.png" width="600" title="Klokantech Terrain Preview Switzerland">

<img src="http://demo.tileserver.org/styles/klokantech-terrain/static/10.987258,46.453150,4.02/600x400@2x.png" width="600" title="Klokantech Terrain Preview Europe">

## Edit the Style

Use the [Maputnik CLI](http://openmaptiles.org/docs/style/maputnik/) to edit and develop the style.
After you've started Maputnik open the editor on `localhost:8000`.

```
maputnik --watch --file style.json
```
