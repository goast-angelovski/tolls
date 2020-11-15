# tolls
Web app project for calculating toll prices.

Using this command with Osmosis i got a osm file for all the pay tolls in Macedonia:
osmosis --read-pbf macedonia-latest.osm.pbf --node-key-value keyValueList="barrier.toll_booth" --write-xml tolls.osm

Using osmconvert i converted the previous osm file to tolls.csv
