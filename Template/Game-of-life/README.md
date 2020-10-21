# Conway's Game of Life

The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves. It is Turing complete and can simulate a universal constructor or any other Turing machine.
At each step in time, the following transitions occur:

**1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.**

**2. Any live cell with two or three live neighbours lives on to the next generation.**

**3. Any live cell with more than three live neighbours dies, as if by overpopulation.**

**4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.**

### These rules, which compare the behavior of the automaton to real life, can be condensed into the following:

**1. Any live cell with two or three live neighbours survives.**
**2. Any dead cell with three live neighbours becomes a live cell.**
**3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.**

# How to play ?

- Clone the repo
- Run `npm install` in the terminal to install the required npm packages .
- Run `npm start`
- Play the game in your browser

## Here's how the example patterns looks like :

- its a Toad

<img src="https://github.com/spantheslayer/game-of-life/blob/master/Example1.gif" />

- Glider

<img src="https://github.com/spantheslayer/game-of-life/blob/master/Glider.gif" />
