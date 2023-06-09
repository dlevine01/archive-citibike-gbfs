This repo pulls station information and station status data from citibike [gbfs feed](http://gbfs.citibikenyc.com/gbfs/gbfs.json) every fifteen minutes and saves the raw json files in the [/data_p](/data_p) folder. 

Files are labeled with their Unix time taken from `last_updated` timestamp in the gbfs data. 

e.g. [1686250704_stations.json](data_p/1686250704_stations.json) is the `station_information` data pulled at 1686250704 (i.e. Thu Jun 08 2023 14:58:24 GMT-0400 (EDT));  [1686250704_status.json](data_p/1686250704_status.json) is the `station_status` pulled at 1686250704
