---
toc: true
layout: post
description: Definition of dynamic optimization
categories: [optimization-problems]
title: Dynamic optimization problems
---
# Dynamic optimization problems

## Basic description


The dynamism occurs in many real-world problems which is originated from factors such as variation in the demand market, unpredicted events, variable resources, or estimated parameters that may change over time. 
These problems in which the objective function or/and the constraints change over time, are called as dynamic constrained optimization problems.  
The goal in these problems is to find the optimum in each instance of the dynamic problem given a limited computational budget. One approach is to apply an independent optimization method to separately solve each problem instance. Although, a more efficient approach solves them through an ongoing search, in which the algorithm detects and responds to changes dynamically. 
Our focus is the second approach in which we equip standard evolutionary algorithm with extra mechanisms like change detection and change reaction mechanisms to handle the dynamic problems.

In real-world applications, a dynamic problem might change very fast or only allow limited time for the algorithm to react. For example, in high-frequency trading, the system needs to continually make an efficient decision to deal with rapid changes in financial asset price. Also, an automatic driving system
needs to rapidly adjust its operation to deal with the changing
road condition. In another scenario, a dynamic load-balancing
algorithm must complete task assignments with very short time
limits. All of these problems are examples of dynamic problems.



