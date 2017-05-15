# TileMapBase

Uses OpenStreetMap tiles, or other tile servers, to produce "basemaps" for use with matplotlib.  Uses a SQLite database to cache the tiles, so you can experiment with map production without re-downloading the same tiles.


## Requirements

Pure python.  Uses [requests](http://docs.python-requests.org/en/master/) to make HTTP requests for tiles, and [pillow](https://python-pillow.org/) for image manipulation.


## OpenStreetMap data

OpenStreetMap Data is "© OpenStreetMap contributors”, see http://www.openstreetmap.org/copyright

Please remember that tile set usage is subject to constraints: https://operations.osmfoundation.org/policies/tiles/