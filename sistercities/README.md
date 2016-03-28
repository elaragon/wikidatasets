# Sistercities

###Cities/
Network subfolders of sister cities:
* **all**: All sister cities that were obtained. Assortativity by degree
* **gdp**: Sister cities that identified to a country whose Gross Domestic Product (gdp) is known. Assortativity by gdp
* **gdppc**: Sister cities that identified to a country whose GDP per capita (gdppc) is known. Assortativity by gdppc
* **hdi**: Sister cities that identified to a country whose Human Development Index (hdi) is known. Assortativity by hdi
* **lat**: Sister cities whose lattitude (lat) is known. Assortativity by lat
* **long**: Sister cities whose longitude (long) is known. Assortativity by lon
* **ps**: Sister cities that identified to a country whose Political Stability Index (ps) is known. Assortativity by ps


Each network subfolder contains:
* **cities.csv**: edges of cities separated by tab
* **cities.net.arcs/vertices**: pajek format
* **cities_degree.txt**: degree distribution
* **cities_graph.csv**: structural properties
* **cities_nodes.csv**: node centrality values
<br/><br/>

###Countries/
Networks of sister cities at a country level. The folder structure is the same as above.
<br/><br/>

####assortativities.csv
Asortativity values for the city networks regarding  (gdp, gdppc, hdi, ps)
<br/><br/>

####city_country.csv
Cities and the corresponding country
<br/><br/>

####city_country_edges.csv
Edges between cities including the corresponding country
<br/><br/>

####kaltenbrunner_etal_2013_iwsos.pdf
Article of this study
<br/><br/>

![figure](https://raw.githubusercontent.com/elaragon/datasets/master/sitercities/kaltenbrunner_etal_2013_iwsos.png)
Country network: node size corresponds to degree and node colours indicate the four clusters obtained with the Louvain method.
