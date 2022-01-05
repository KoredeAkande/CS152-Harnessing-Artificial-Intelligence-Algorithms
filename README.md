# CS152-Harnessing-Artificial-Intelligence-Algorithms

Overview
------------
Select coding assignments and exercises from the CS152: Harnessing Artificial Intelligence Algorithms class, taken in Fall 2020. The course covered and honed in an a range of AI and python skills including propositional logic, logic programming, predicate calculus, computational reasoning, object-oriented programming, and data structures and algorithms.

Topics addressed include search algorithms (both naive and informed), logical deduction and resolution, conjunctive normal form, DPLL, forward and backward chaining, to name a few. 

Final Project Discussion
------------
The course culminated in a self-selected final project where I build a basic (interactive) Connect 4 Human vs. AI game. The AI player is implemented using the [minimax algorithm with alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning#Improvements_over_native_minimax), thus reducing the effective search tree depth. A brief dummy run/gameplay from the project is shown below. The full project can be viewed [here](https://github.com/KoredeAkande/CS152-Harnessing-Artificial-Intelligence-Algorithms/blob/main/Final%20Project:%20Interactive%20Connect%204%20Game/Pygame%20Connect%204%20Implementation.ipynb) as well as a brief accompanying [report](https://github.com/KoredeAkande/CS152-Harnessing-Artificial-Intelligence-Algorithms/blob/main/Final%20Project:%20Interactive%20Connect%204%20Game/CS152%20-%20Final%20Project.pdf).

![Connect 4 Gameplay](https://github.com/KoredeAkande/CS152-Harnessing-Artificial-Intelligence-Algorithms/blob/main/Final%20Project:%20Interactive%20Connect%204%20Game/connect4.gif)

**Note:** The aim of the assignment was to depict a strong usage of skills learnt in class, in this case search algorithms. Hence, my major aim was to get an accurately working implementation of the minimax algorithm in the context of the Connect4 game. Less emphasis is paid to the UI and aesthetics of the developed game.

Requirements
------------
To setup the core libraries for the projects in the repo, the command below can be run
```
pip install pygame pyswip 
```

