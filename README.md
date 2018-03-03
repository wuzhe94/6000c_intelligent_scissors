# 6000c_intelligent_scissors
Implementation of Intelligent Scissors

- Structure
  - Part I: Implemented the algorithm based on the paper published on 1995
  - Part II: GUI programming

- Algorithm
  - Part I: Calculate the cost of any two near nodes. In order to achieve that, we should defind many other fundamental functions to obtain the neighbors of a certain node, or calculate the gradient, magnitude, direction and so on. In this project, I just use Canny opertor, gradient magnitude and gradient direction to decide the cost between two near nodes.
  - Part II: Calculate the optimal path between two seeds provided by user. Specifically, the optimal path must be the path with the minimum cost, so the problem is changed to find out the shortest path.

- Usage
  - Click left to start a new seed
  - Click right to stop the scissor and close the coutour
  - Press S key to save the result

- Result
  - ![]
  - ![]
  - ![]

- TODO
  - Improve the efficienty of the code.
  - zoom in and zoom out
  - Improve the GUI
