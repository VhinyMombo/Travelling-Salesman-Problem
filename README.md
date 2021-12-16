### Travelling-Salesman-Problem
### A way to solve the travelling salesman problem with a genetic Algorithm.


In computer science and operations research, a genetic algorithm (GA) is a 
metaheuristic inspired by the process of natural selection that belongs to the larger 
class of evolutionary algorithms (EA). Genetic algorithms are commonly used to generate
high-quality solutions to optimization and search problems by relying on biologically 
inspired operators such as mutation, crossover and selection.[1] Some examples of GA 
applications include optimizing decision trees for better performance, automatically 
solve sudoku puzzles,[2] hyperparameter optimization, etc. [wikipedia](https://en.wikipedia.org/wiki/Genetic_algorithm)

I tried to implement a genetic algorithm by introducing different methods
of crossover, mutation and selection.

We can find used method and more details on the [phd thesis (french version)](https://tel.archives-ouvertes.fr/tel-00126292/document)


Moreover, in order to add some challenges in the search of solution we added a <img src="https://render.githubusercontent.com/render/math?math=LIMIT"> parameter that constraint the number of iteration and the number of chromosomes in a generation so that 
<img src="https://render.githubusercontent.com/render/math?math=Nb\_chrom \times nb\_iter = LIMIT">

