Energy Data Prototype
======
# Summary
This project is a prototype to demonstrate mapping capabilities using data from the [U.S. Energy Information Administration](http://www.eia.gov/). Initially, it uses a subset of [oil and gas data](http://www.eia.gov/cfapps/ipdbproject/IEDIndex3.cfm) but may expand as necessary. The purpose of this product is to easily visualize energy data in order to assist in knowledge sharing with and between U.S. State Department Foreign Service Officers specializing in energy issues.

# Tech Details
* [Leaflet](http://www.leafletjs.com/) is used to make the map interface;
* All the data is static: downloaded as XLS files, manipulated in MS Excel, joined to country polygons in [QGIS](http://www.qgis.org/), saved as [GeoJson](http://geojson.org/) files, and brought in as individual variables;
* The webpage itself is all the javascript we put here on [this git](https://github.com/brodydittemore-edip/energy).

# Possible Expansion
* Include additional energy data, such as shale gas, solar and wind;
* Use a legitimate source for pipelines (what is shown is from an unattributed [source](http://geocommons.com/overlays/193236);
* Integrate IHS data;
* Make web app mobile compliant (i.e., replace roleovers with on-click events if the user is on a mobile device);
* Add a timeslider.

## License

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105.

The project utilizes code licensed under the terms of the GNU General Public License and therefore is licensed under GPL v2 or later.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
