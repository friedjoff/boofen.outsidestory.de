### Update data

Run the following query on http://overpass-turbo.eu/ and export data as GeoJSON into the boofen.js file.

```xml
<query type="node">
	<has-kv k="name" regv="[Bb]oofe"/>
	<bbox-query s="50.8083" w="13.9972" n="51.0226" e="14.4247"/>
</query>
<print/>
```

### Todo

* OSM Attribution
* Offline Cache
* More advanced geolocation

