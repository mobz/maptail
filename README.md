# maptail.js

Creates a server, monitors a tail -f output for IP addresses, GeoIPs them and sends them to a map. 
Run it and visit http://yourhost.com/map

<img src="http://dl.dropbox.com/u/396087/maptail.png" border="0" />

### Installation

Clone this repository.
You'll also need [node.js](http://nodejs.org) installed, and [npm](http://npmjs.org) to install dependencies.

Tested and working with node.js v0.3.1.

### Usage

    node maptail.js <file_to_tail> [host] [port]

You also need to download GeoIP City Lite Edition [Download](http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz) 
and extract it into the repository folder.

### Credits

This is based on [mape's wargames](https://github.com/mape/node-wargames).

Could not be possible without [kuno's GeoIP](https://github.com/kuno/GeoIP) module.
