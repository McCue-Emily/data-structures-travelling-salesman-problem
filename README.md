# Homework 6

## Project Goals
The goal of this project is to:
1.	Familiarize students with **graphs**

## Program
### Traveling Salesman Problem
Consider 5 cities of interest, namely a) Reno, b) San Francisco, c) Salt Lake City, d) Seattle, and e) Las Vegas. Use information on the road network and derive the miles from one city to the other. Assume a fixed metric of Miles Per Gallon = 40 and derive the cost of each transition **in terms of miles**. Then on that basis, conduct the following:
- Create a graph with each of its vertices corresponding to one of these cities and its edges being weighted by the associated miles for each trip. Note that if (and only if) to go from city A to B you must go through C then you must add one edge from A to C and one edge from C to B and there is no need to add an edge directly from A to B.
- Solve the Traveling Salesman Problem such that traveling salesman starts from Reno, visits all cities in the above list and returns to list. Solve this problem in the brute force-way, i.e. by identifying all possible paths.

Your submission should include 
- Your source code
- a .txt file with your initial values for the miles from one city to the other
- a .txt file which includes all possible paths and the best one selected by the algorithm
