#Student should be able to describe the rules of Conway’s “Game of Life”

The basic rules are:

*   If a cell stands by itself, it dies.  No man is an island
*   If a cell has two or three neighbors, it's alive.
*   If a cell is dead, but has exactly three neighbors, those three neighbors will work to bring
    it back to life, and it will be live to the next generation.

Student should be able to explain what cellular automata are and describe how they are useful in real life

*   Conway's game is a very good example of cellular automata - a simple set of rules determine how a set 2D grid will change over
    time in the case of CGoL, in response to its neighbors.  The program of simulation will examine a curent state of the grid and use the rules to
    create a new grid reflecting the old state with rules applied.  The new grid become the current state and the process continues.

*    Cellular automata are used the real world in analyzing chemical or biological processes (COVID-19 and pandemics?)

Student should be able to correctly analyze the ‘Turing Completeness’ of Conway’s “Game of Life”

*   