# Optimization for Learning
This repo holds our assignments in the course _optimization for (machine) learning_. While the focus was on theoretical concepts, models were also built and trained with PyTorch.

Co-authored with Jesper Arnwald.

---

## Assignment 1: Proximal Gradient Method
The goal of this assignment is to become familiar with some of the steps involved in solving an optimization problem. In this assignment, you will form Fenchel dual problems, find gradients and proximal operators, and implement the proximal gradient method.

- Task 1 - Theory - show convexity
- Task 2 - Theory - compute the conjugate functions
- Task 3 - Theory - find the dual problem
- Task 4 - Theory - prove smoothness
- Task 5 - Theory - subdifferentials and prox
- Task 6 - Theory - compute explicit update rules for the proximal gradient method
- Task 7 - Theory - Prove dual/primal correspondence
- Task 8 - Practice- Code the building blocks
- Task 9 - Practice- Code an optimizing algorithm for the primal
- Task 10 - Practice- Code an optimizing algorithm for the dual

---

## Assignment 2: Convergence study of Stochastic Gradient Descent (SGD) and Adaptive Moment Estimation (Adam)

The purpose of this assignment is to empirically explore some convergence and implicit regularization properties of the stochastic gradient descent (SGD) method and some of its variants. These properties are mainly explored by considering simple polynomial fitting problems in $\mathbb{R}$ to facilitate easy comparison with known theoretical results and easy visualization. We will also compare the same fitting problem with multi-layer perceptrons also known as fully connected feedforward neural networks.

---

## The Course
FRTN50 Optimization for Learning was given in Fall 2023 at the Department of Control, Faculty of Engineering, Lund University.

**Aim**
Learning from data is becoming increasingly important in many different engineering fields. Models for learning often rely heavily on optimization; training a machine is often equivalent to solving a specific optimization problem. These problems are typically large-scale. In this course, we will learn how to solve such problems efficiently. The large-scale nature of the problems renders traditional methods inapplicable. We will provide a unified view of algorithms for large-scale convex optimization and treat algorithms for the nonconvex problem of training deep neural networks.

**Learning outcomes**
Convexity, models for learning, unified convex optimization algorithm view, fixed-point iterations, monotone operators, nonexpansive mappings, stochastic methods, reduced variance methods, block-coordinate methods, nonconvex stochastic gradient descent and variations for deep learning training.


