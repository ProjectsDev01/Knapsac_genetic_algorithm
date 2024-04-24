# Knapsac Problem
## Table of contents
- [Introduction](#introduction)
- [How to use](#how-to-use)
    - [item_list.py](#item_list)
    - [main.py](#main)
- [Solved with](#solved-with)
    - [Genetic algorithm](#genetic-algorithm)
### Introduction
The program is made to solve common problem calles knapsac, where you have to put as many valuable items as possible into a backpack with limits. My solution is based on backpack ***max_weight*** and ***max_space*** and fitness function is the determinant on how good the solution is.
### How to use
#### item_list
In `/src` are two files one called `items_list.py` that generates database. To change the quantity of items change ***num_items***. Output file is calles `items_list.db` containing items with ***(id, weight, value, space)***, every single value is generated randomly.
#### main
The second file in `/src` is `main.py` that's the main core of the program containg solution. Firstly it takes the database and read all the information then it's inserted into algorithm.

#### Genetic algorithm
Genetic Algorithm (GA) works by iteratively evolving a population of candidate solutions towards optimal solutions through selection, crossover, and mutation operations. It mimics natural selection and genetic principles, evaluating and improving solutions based on their fitness until a termination criterion is met, yielding the best solution found.