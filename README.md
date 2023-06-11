# GeoDataScience
How to handle geo data for analytics, science, and visualization.

List of resources and background informations (my private favorites are set **bold**)  

* Insurance relevant Use Cases
	* Policing: demographic data, flood risk, … [Towergate Underwriting starts its journey to become Geo Underwriting](https://www.ardonagh.com/media/announcements/2018/towergate-underwriting-starts-its-journey-to-become-geo-underwriting/)
	* Market research, penetration [Insurance Geographics](https://www.casact.org/sites/default/files/2021-02/pubs_dpp_dpp97_97dpp141.pdf)
	* Risk calculation [Geospatial risk modeling - Predictive Policing](https://urbanspatial.github.io/PublicPolicyAnalytics/geospatial-risk-modeling-predictive-policing.html)
	* Claims handling: hail storm [Geospatial data reveals where unexpected storm risks lie](https://www.dig-in.com/opinion/geospatial-data-reveals-where-unexpected-storm-risks-lie)
* Domain Specific Tools
	* ArcGis: [2D, 3D & 4D GIS Mapping Software | ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)
	* **QGIS**: [Welcome to the QGIS project!](https://www.qgis.org/en/site/index.html)
* Projektionen: 
	* **WGS84** [World Geodetic System](https://en.wikipedia.org/wiki/World_Geodetic_System#WGS84)
	* Gauss-Krüger [Transform Coordinate Systems](https://gauss.svemir.co/#transform)
	* ETRS89 [European Terrestrial Reference System 1989](https://en.wikipedia.org/wiki/European_Terrestrial_Reference_System_1989)
	* GPS-Epochen (2.5 cm drift the year) [Is Britain on the move?](https://www.ordnancesurvey.co.uk/blog/is-britain-on-the-move#more-21842)
* Latitude, Longitude, Altitude, Accuracy
	* GPS Coordinates [Latitude and Longitude](https://sciencenotes.org/latitude-and-longitude/)
	* Degrees, Minutes, Seconds (DMS: 48° 12' 29.426" N 16° 22' 25.748" E) vs. **Decimal Degree (DD i.e. 48.208174, 16.373819)** 
	* **Latitude, Longitude** vs. Longitude, Latitude (you need to have a standard from begin on)
	* Accuracy depends on various parameters including receiver [GNSS/GPS ACCURACY EXPLAINED](https://junipersys.com/support/article/6614)
	* Differential GPS (relevant for IoT) [A Short Overview of Differential GPS](https://www.oc.nps.edu/oc2902w/gps/dgpsnote.html)
	* Asissted GPS (relevant for mobile phones) [What Is Assisted GPS?](https://www.iotforall.com/what-is-assisted-gps)
	* Raster vs. Vector [Difference between a GPS raster map and a vector map](https://www.youtube.com/watch?v=gaQs3yynSEo)
* Used Formats:
	* GeoJSON [GeoJSON](https://geojson.org)
	* SHP [What is a shapefile?—ArcMap | Documentation](https://desktop.arcgis.com/en/arcmap/latest/manage-data/shapefiles/what-is-a-shapefile.htm)
	* Xarray [Xarray: N-D labeled arrays and datasets in Python](https://xarray.dev)
	* [About PostGIS | PostGIS](https://postgis.net)
	* [SAS Help Center](https://documentation.sas.com/doc/de/vacdc/v_016/vaobj/n14ezqxeg2a195n1au1q980gbkte.htm)
	* GRIB [GRIB - Wikipedia](https://en.wikipedia.org/wiki/GRIB)
* **Geohash**
	* [Geohash encoding/decoding](https://www.movable-type.co.uk/scripts/geohash.html)
	* resolution
	* sorting
* Python examples with demographic data, flood risk, Post data
	* GeoPandas
		* contains, 
		* …
* Notebooks & Maps 
	* **Folium** (Python) [Folium Quickstart](https://python-visualization.github.io/folium/quickstart.html)
	* **Leaflet** (Generic JavaScript) [Tutorials](https://leafletjs.com/examples.html)
	* OpenStreetMap [OpenStreetMap Tile Map Server](https://openmaptiles.org/)
	* **CartoDB** [Free Map Server](https://carto.com/)
	* Velocity [Velocity — ipyleaflet  documentation](https://ipyleaflet.readthedocs.io/en/latest/layers/velocity.html)
	* …
* Geo Services
	* Address to Coordinates
	* Coordinates to Address
	* Routing
		* **Here** [here Developer](https://developer.here.com/)
		* Google [Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview?hl=de)
		* TomTom [tomtom developer](https://developer.tomtom.com/)
		* OSRM [Open Source Routing Machine](https://project-osrm.org/) 
