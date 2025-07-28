# Inverted Pendulum Simulation – Exercise 1

## Course Information

This repository contains Exercise 1 of the *Fundamentals of Embedded and Real-Time Systems* course, Spring 1404, Shahid Beheshti University. The project focuses on modeling, simulating, and controlling an inverted pendulum mounted on a motorized cart.

## Project Overview

In this exercise, we modeled the dynamics of an inverted pendulum system using Newtonian mechanics and implemented the plant in MATLAB Simulink. Then, we designed and tested a feedback controller to stabilize the pendulum in its upright position.

### Mathematical Model

The equations of motion used for the inverted pendulum system are:


$$
(M + m)\ddot{x} + ml\ddot{\theta} = u
$$

$$
ml^2\ddot{\theta} + ml\ddot{x} = mgl\theta
$$


Where:
- x: horizontal position of the cart  
- θ: angle of the pendulum  
- u: control input force  
- M, m: masses of cart and pendulum respectively  
- l: distance to the center of mass

We implemented a Simulink model based on these equations, performed open-loop simulations, and then added a feedback controller with integral action to improve performance.

## Summary of Work

- Derived the system equations  
- Built the continuous-time plant model in Simulink  
- Simulated the system response  
- Designed a state feedback controller  
- Tuned gains to improve stability and convergence


## Theoretical Questions

The written part of this assignment included two theoretical questions:

1. **Successive Refinement**: We described the successive refinement methodology as an iterative software development model and compared it to other models like the waterfall and agile approaches.

2. **Design Review Team**: We explained the role of a design review team in identifying problems early in the development process and listed its typical members and responsibilities.

## Report

All simulation results, diagrams, and theoretical answers are documented in the submitted report: [`EMD-HW1.pdf`](./EMD-HW1.pdf).

## Authors
- Ali Tabatabei
- [Danial Hamidi](https://github.com/mdanialh)
