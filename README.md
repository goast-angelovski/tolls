# tolls
Web app project for calculating toll prices.

Group Members:<br>
Gorast Angelovski 181519<br>
Filip Najdoski 181555<br>
Filip Naumovski 181506<br>
Nenad Pantikj 181514<br>

I created a data folder to store the needed data

Using this command with Osmosis i got a osm file for all the pay tolls in Macedonia:<br>
osmosis --read-pbf macedonia-latest.osm.pbf --node-key-value keyValueList="barrier.toll_booth" --write-xml tolls.osm

Using osmconvert i converted the previous osm file to tolls.csv

We also gathered data from http://www.roads.org.mk/320/cenovnik-po-delnici?fbclid=IwAR3lv-FZhEpS_vZTMVtMcXg20ZKAA6AGmdem8pQ6pbYCW0dYmPHH0OxfQOM in order to update OSM with the most current available data.
