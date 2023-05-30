

## Introduction
- agent: 
- state: (s) agent in its environment
- initial state: starting point
- actions: (a) -> bring from state to state
- transition model:
- state space: 
-   -> graph
- goal state: end state(s)
- path cost: cost associated with given path

## Search problem
- initial state
- actions
- transition model
- goal test
- path cost function

## Node
data structure that keep track of
- a state
- a parent (node generated this node)
- an action (applied to parent to get node)
- a path cost (from initia;l state to node)

## Approach
- start with a frontier that contains the initial state
- start with an empty explored set
- repeat
    - frontier == empty -> no solution
    - remove a node from the frontier
    - if node == goal state -> return solution
    - add the node to the explored set
    - else 
        - expand node add resulting nodes to the frontier if they arent in the frontier or the explored set
        
## Stack (used for frontier)
- last in first out (LIFO)

### DEPTH-FIRST-SEARCH

### Breath-First-Search
- explore the shallowest node in the frontier
- first in first out (FIFO)

# knowledge

# learning
- Supervised Learning 
- Reinforcement Learning 
- Unsupervised Learning
