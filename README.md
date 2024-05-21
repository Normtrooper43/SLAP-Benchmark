# SLAP-benchmark
A benchmark dataset for the search location assignment problem. Includes data, function evaluator and instance generator.

This readme is meant to provide details on the structure of the instance files for this benchmark. Each file is its own instance. 

The file format is as follows:

number of assets: the number of rescue assets. 
number of locations: the number of saerch locations.
<List of values>: A comma-delimited list of each of the values associated with each search location.
[S][S] 2D matrix for the rescue success probabilities: This is a 2D matrix based on the number of assets and the number of locations. Each is the intersection of the indices is the probability that a given asset can be successful at performing a rescue at a given location.
