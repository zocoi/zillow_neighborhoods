# zillow_neighborhoods

Use `ogr2ogr` to convert shapefile to geojson

```
for f in *.shp; do ogr2ogr -f "geojson" ${f:r}.geojson $f done
```

### Credit: Zillow

![zillow](https://www.zillowstatic.com/vstatic/41c25c3/static/logos/Zillow_Logo_HoodsProvided_RightAligned.gif)

https://www.zillow.com/howto/api/neighborhood-boundaries.htm
