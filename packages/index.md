---
layout: default
title:  Packages
---

# Optimization-Related Packages
The ecosystem of [Julia packages](http://pkg.julialang.org) is growing very fast. There are JuliaOpt packages that are not introduced in the [home](/) page and other optimization related packages that are not part of JuliaOpt.

- [NEOS.jl](https://github.com/odow/NEOS.jl): an interface to the [NEOS Optimization Server](http://www.neos-server.org/).

- [BlackBoxOptim.jl](https://github.com/robertfeldt/BlackBoxOptim.jl): a derivative-free, global optimizer that supports multi-objective optimization problems

## JuMP Extensions

- [JuMPeR.jl](https://github.com/IainNZ/JuMPeR.jl): for robust optimization

- [MultiJuMP.jl](https://github.com/anriseth/MultiJuMP.jl): for multi-objective optimization

- [JuMPChance.jl](https://github.com/mlubin/JuMPChance.jl): for probabilistic chance constraints.

- [StochDynamicProgramming.jl](https://github.com/JuliaOpt/StochDynamicProgramming.jl): for discrete-time stochastic optimal control problems.


## Equilibrium Problems

- [VariationalInequality.jl](https://github.com/chkwon/VariationalInequality.jl): uses JuMP modeling language for [variational inequality](https://en.wikipedia.org/wiki/Variational_inequality) problems.

- [Complementarity.jl](https://github.com/chkwon/Complementarity.jl): uses JuMP modeling language for [linear](https://en.wikipedia.org/wiki/Linear_complementarity_problem)/[nonlinear](https://en.wikipedia.org/wiki/Nonlinear_complementarity_problem)/[mixed](https://en.wikipedia.org/wiki/Mixed_complementarity_problem) complementarity problems and solves using [a Julia interface](https://github.com/chkwon/PATHSolver.jl) to [the PATH Solver](http://pages.cs.wisc.edu/%7Eferris/path.html).


## Graph and Network

- [Graphs.jl](https://github.com/JuliaLang/Graphs.jl): Julia’s standard package for shortest path algorithms, minimum spanning tree algorithms, random graph generation, etc.

- [LightGraphs.jl](https://github.com/JuliaGraphs/LightGraphs.jl): a similar package to Graphs.jl

- [NetworkFlows.jl](https://github.com/Azzaare/NetworkFlows.jl): solves max-flow problems, min-cut problems, etc.

- [Munkres.jl](https://github.com/FugroRoames/Munkres.jl): solves optimal assignment problems using the Hungarian algorithm.

- [RobustShortestPath.jl](https://github.com/chkwon/RobustShortestPath.jl): solves robust shortest path problems.

- [TrafficAssignment.jl](https://github.com/chkwon/TrafficAssignment.jl): solves network user equilibrium problems.

## Heuristics

- [Evolutionary.jl](https://github.com/wildart/Evolutionary.jl): evolutionary strategies and genetic algorithms.

- [GeneticAlgorithms.jl](https://github.com/WestleyArgentum/GeneticAlgorithms.jl): genetic algorithms

- [StochasticSearch.jl](https://github.com/phrb/StochasticSearch.jl): stochastic local search algorithms such as simulated annealing and tabu search.

- [TravelingSalesmanHeuristics.jl](https://github.com/evanfields/TravelingSalesmanHeuristics.jl): a heuristic algorithm for solving the Traveling Salesman Problem (TSP).
