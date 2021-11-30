# London Undergrouund Graphs And Algorithms

#### Task
Your task is to design and implement data structures and algorithms to efficiently support the following API:
- loadStationsAndLines(): reads the provided files londonstations.csv and londonrailwaylines.csv, and initialises appropriate data structures to represent both stations and railway lines information;
- minStops(from, to): given in input two station names, returns the minimum number of stops that need to be travelled through, to go from one to the other; o minDistance(from, to): given in input two station names, returns the minimum
distance (in miles) that needs to be travelled to go from one to the other. To compute the distance between adjacent stations, compute the Euclidean distance between their latitude/longitude coordinates;
- newRailwayLine(stationSet): given in input stationSet (i.e., an unordered list of station names), computes how to connect them pairwise, so to minimise the sum of the distance (in miles) between adjacent stations, then returns an ordered list of station names connected pairwise. In other words, imagine
creating a new railway line that connects all stations in stationSet, so to use the least amount (in miles) of train tracks overall; then return the ordered list of station names from one end of the line to the other. No branching of the line is allowed.

#### Constraints
For this coursework, you are expected to implement your own algorithms and data structures. You are NOT allowed to use (import) python libraries, with the exception of csv (to read csv files), math (to compute Euclidean distances from pairs of latitude/longitude coordinates) and timeit (to experimentally measure the computational cost of your solution).
