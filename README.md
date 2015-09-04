## leaflet osm notes

[![Join the chat at https://gitter.im/julien-noblet/leaflet-osm-notes](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/julien-noblet/leaflet-osm-notes?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Pull notes from OpenStreetMap into Leaflet.

## example

```js
var notesLayer = new leafletOsmNotes();
notesLayer.addTo(map);
```

## api

`var notesLayer = new leafletOsmNotes()`

Makes a notes layer. You can customize the underlying `L.geoJson` instance
by its exposed `notesLayer.notesLayer` property.
