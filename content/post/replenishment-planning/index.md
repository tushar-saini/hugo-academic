---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Replenishment Planning"
subtitle: ""
summary: "Replenishment Planning to find optimal transport planner which minimizes the transportation costs, reduce inventory days, reduce stocks-out"
authors: []
tags: []
categories: []
date: 2022-07-01T20:00:00+05:30
lastmod: 2022-07-01T20:00:00+05:30
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

#### Problem Statement
Planning inventory and transportation is a significant challenge for enterprises. Balancing the right amount of inventory is crucial, as over-planning can lead to capital, labor, and space being tied up, along with an increased risk of wastage, particularly for products with limited shelf life. On the other hand, under-planning may result in stock-outs and significant sales losses. Achieving this balance is essential. One approach to tackle this is adopting a demand-driven approach to replenishment planning. To forecast demand, various factors such as historical trends, festivals, seasons, promotions, and more can be taken into account. However, discussing the intricacies of demand forecasting is beyond the scope of this topic, and warrants a dedicated article of its own.

In this article, we will explore replenishment planning, which encompasses methods for optimizing inventory levels across different levels of the supply chain. The primary objective is to ensure that each level maintains sufficient stock to meet the demands of its downstream counterparts and that with minimal cost.

Once we have the end node demand of products, we can start out to find the best optimal solution which minimizes the transportation costs, reduce inventory days, reduce stocks-out. However, finding the optimal solution involves considering several constraints. These constraints include factors such as the available types of trucks between nodes, the weight and volume capacity of trucks, warehouse capacities, and the optimal path between nodes (especially in cases where overlapping regional warehouses can fulfill the demand).

#### Solution
Given these constraints, there can be numerous permutations and combinations that satisfy the conditions. However, identifying the best optimal solution is a challenging task due to the large number of possibilities. It often requires sophisticated optimization techniques and algorithms to evaluate and select the most efficient configuration that minimizes costs, optimizes inventory levels, and ensures timely order fulfillment.

In our use case, we employed mixed-integer linear programming to address the optimization challenge. This programming paradigm involves formulating an objective function, which can be either a cost function to minimize or a reward function to maximize, along with a set of constraints. The solver then seeks the optimal solution that satisfies these constraints while optimizing the objective function. Mixed-integer linear programming allows for both continuous and discrete decision variables, enabling us to model real-world scenarios with binary or integer requirements.

We used gurobi solver wrapped in a python script and deployed as a microservice on server. The solver consumed various inputs such including product demand at end nodes, box volume and weight, warehouse capacities, available truck types between nodes, cost of each truck type per kilometer, distances between nodes, truck capacities, and other relevant factors. By leveraging this comprehensive set of inputs, we generated an optimal replenishment allocation plan and transport plan at each node.
