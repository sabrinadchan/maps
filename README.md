# 🗺️ Maps 🗺️
This repository is for sharing maps I have created. Most maps were built with D3 or Leaflet. In some maps, the underlying geospatial data was edited or entirely generated with Python and Python GIS libraries like GeoPandas.

* **Election Results**
  * [Chicago Municipal Election Results](https://sabrinadchan.github.io/chi-election-results-map/) (D3+Leaflet)
    * Election results were scraped from the Chicago Board of Election Commissioner's website and cleaned using this [Python script](https://github.com/sabrinadchan/chicago-elections-scraper).
  * [2020 NY State Dem Primary / DSA for the Many](https://sabrinadchan.github.io/dsa-for-the-many/index.html) (D3+Leaflet)
    * Adapted from the Chicago results map
* [Nearest 'L' Station](https://sabrinadchan.github.io/nearest-L-station/index.html) (Python/Leaflet)
	* Edge Network Voronoi diagram partitioning Chicago's walkable street network into "regions" consisting of all paths with a shorter walking distance to a particular 'L' station than any other. Be patient, as the map could take a couple of seconds to load and to zoom in and out.
	* [GitHub repo](https://github.com/sabrinadchan/nearest-L-station)
	* Read this [blog post](https://sabrinadchan.github.io/data-blog/computing-a-network-voronoi-diagram.html) to learn how it was made.
* [U.S. State Hexagonal Cartogram](https://bl.ocks.org/sabrinadchan/222736951b6a8f63bba50b7e8566417d) (Python/D3)
	* A cartogram of the United States with the size of each state scaled in proportion to the number of representatives in its congressional delegation.
	* [Blog post](https://sabrinadchan.github.io/data-blog/building-a-hexagonal-cartogram.html).
* [Choropleth with selectable regions](https://sabrinadchan.github.io/maps/selectable-regions.html) (D3+Leaflet)
