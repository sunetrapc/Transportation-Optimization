# Transportation Cost Optimization 🚛

##  Overview

Welcome to the **Transportation Cost Optimization** repository! This project optimizes the transportation of goods between supply and demand locations, minimizing the total transportation cost while fulfilling supply and demand constraints. 

Using the **Gurobi optimizer** and a **network flow diagram**, this model ensures that goods are transported from warehouses (supply locations) to stores (demand locations) in the most cost-efficient way.

## Problem Overview

Imagine a supply chain where goods are transported from multiple warehouses (sources) to various stores (destinations). Each transportation route has a cost associated with it, and each warehouse has a limited amount of goods it can send, while each store has a fixed demand.

Your objective is to find the optimal transportation plan that minimizes the total cost while ensuring:

1. **Supply constraints**: The amount transported from each warehouse should not exceed its supply.
2. **Demand constraints**: Each store must receive the exact amount of goods it requires.

## Objective

Minimize the total transportation cost while satisfying all supply and demand constraints.

## Features

- **Linear Programming**: Solves the transportation problem using linear programming with **Gurobi**.
- **Cost Optimization**: Finds the least-cost way to transport goods from supply to demand.
- **Flow Network Visualization**: Displays the optimal transportation plan in a visually appealing **network graph**.
- **Edge Labels**: Each transportation route is labeled with both the flow (amount of goods) and the transportation cost.

