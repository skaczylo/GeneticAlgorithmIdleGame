# Geneti cAlgorithm

This notebook implements a solution to an idle game, inspired by games like Cookie Clicker, using a **Genetic Algorithm**. In this game, the player can buy different types of mines that generate benefits over time. As the game progresses, upgrades become more powerful, and strategic decisions about when and which mines to purchase have a significant impact on total rewards.

The main idea is to model the player's actions as a sequence of decisions over time, where each decision determines how many of each type of mine to buy at each turn or second. The **Genetic Algorithm** is used to explore possible strategies, evolve them, and select the ones that maximize the overall benefits for the player.

Key points of this project:

- **Idle Game Mechanics:** Players accumulate resources automatically over time, with the option to buy mines and upgrades to increase production.  
- **Genetic Algorithm Representation:** Each strategy is represented as a chromosome, encoding the number of mines purchased at each turn.  
- **Optimization Goal:** The algorithm searches for the optimal sequence of actions that yields the highest total benefit.  
- **Learning and Experimentation:** This project provides hands-on experience applying genetic algorithms to a dynamic, cumulative decision-making problem.

Overall, the goal is to demonstrate how evolutionary algorithms can be applied to optimize strategies in incremental games and to explore the effectiveness of this approach in a practical simulation environment.


