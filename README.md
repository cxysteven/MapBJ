#MapBJ
* There are two file in this dataset.
* traffic_condition.csv
	* This file contains four field as follows:
	* **id** is the Unique identification of a location.
	* **timestamp** is the time point when the traffic condition released.
	* **condition** has five value with {not released, fluency, slow, congestion, extrem congestion} corresponding to {0, 1, 2, 3, 4} repectively.
	* **limit level** is the speed limit level of different locations.
* graph.csv
	* This file represents a directed graph from source to destination with location ids.
