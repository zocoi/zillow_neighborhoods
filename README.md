# zillow_neighborhoods (Updated Apr 2018 from Zillow)

### Convert shapefile to geojson
Use `ogr2ogr` to convert shapefile to geojson

```
for f in *.shp; do ogr2ogr -f "geojson" ${f:r}.geojson $f done
```

### Merge all geojson into one big file

```
npm install --save @mapbox/geojson-merge
geojson-merge *.geojson > combined.geojson
```

### Credit: Zillow

![zillow](https://www.zillowstatic.com/vstatic/41c25c3/static/logos/Zillow_Logo_HoodsProvided_RightAligned.gif)

https://www.zillow.com/howto/api/neighborhood-boundaries.htm
