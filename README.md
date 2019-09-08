# 🗺️ Maps 🗺️
This repository is for sharing maps I have created. Most maps were rendered with D3 or Leaflet. In some maps, the underlying geospatial data was edited or entirely generated with Python and Python GIS libraries like GeoPandas.

* [Chicago Municipal Elections](https://spencerchan.github.io/maps/chicago-municipal-elections.html) (D3+Leaflet)
  * Data scraped from Chicago Board of Election's website using this [Python script](https://github.com/spencerchan/chicago-elections-scraper).
* [Nearest 'L' Station](https://spencerchan.github.io/nearest-L-station/index.html) (Python/Leaflet)
	* Edge Network Voronoi diagram partitioning Chicago's walkable street network into "regions" consisting of all paths with a shorter walking distance to a particular 'L' station than any other. Be patient, as the map could take a couple of seconds to load and to zoom in and out.
	* [GitHub repo](https://github.com/spencerchan/nearest-L-station)
* [U.S. State Hexagonal Cartogram](https://bl.ocks.org/spencerchan/222736951b6a8f63bba50b7e8566417d) (Python/D3)
	* A cartogram of the United States with the size of each state scaled in proportion to the number of representatives in its congressional delegation.
	* Read this [blog post](https://spencerchan.github.io/data-blog/building-a-hexagonal-cartogram.html) to learn how it was made.
* [Choropleth with selectable regions](https://spencerchan.github.io/maps/selectable-regions.html) (D3+Leaflet)