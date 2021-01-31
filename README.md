# fourmis-voyageur-commerce - Simple agent research
## Created by Guillaume Grosse

## Project in a nutshell
Research with simple agents and Genetic parameter tuning applied to travelling salesman problem.


## Running the project
- run fourmis-voyageur-commerce.ipynb python notebook


## Context
Project : Research
Course : Artificial Intelligence
Enginneering Schools Associated : ENSC and ENSEIRB  
Duration : 2 month


## Main features

Goal is to find the shortest path between a dozen of french cities by sending simple agents to explore the "world".

Each pair of cities has an associated pheromone value, updated during research.

When searching for the best route, the agents will favor the more pheromone-heavy and shortest routes, updating the pheromone values of the routes taken.

This research relies on 4 parameters (Q,alpha,beta,gamma) of which I tried to tune the values with a genetic algorithm. This experimentation was unfortunately not successful.


## Possible improvements

Obviously, trying to tune the parameters with another approach could very much benefit the project.

There also are real perspectives of optimization for computations.
