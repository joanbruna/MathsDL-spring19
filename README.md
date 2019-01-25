# MathsDL-spring19
Topics course Mathematics of Deep Learning, NYU, Spring 19. CSCI-GA 3033. 

## Logistics

* Mondays from 7.10pm-9pm. CIWW 102

* Tutoring Session with Parallel Curricula (**optional**): Fridays 11am-12:15pm CIWW 101. 

* Piazza: [sign-up here](https://piazza.com/nyu/spring2019/csciga3033)

* Office Hours: Tuesdays 9:30am-11:00am

## Instructors

__Lecture Instructor__: Joan Bruna (bruna@cims.nyu.edu)

__Tutor (Parallel Curricula)__: Luca Venturi (lv800@nyu.edu)


## Syllabus

This Graduate-level topics course aims at offering a glimpse into the emerging mathematical questions around Deep Learning. In particular, we will focus on the different geometrical aspects surounding these models, from input geometric stability priors to the geometry of optimization, generalisation and learning. We will cover both the background and the current open problems. 

Besides the lectures, we will also run a parallel curricula (optional), following the [Depth First Learning](www.depthfirstlearning.com) methodology. We will start with an inverse curriculum on the [Neural ODE paper](https://arxiv.org/abs/1806.07366) by Chen et al.

### Detailed Syllabus 

*  Introduction: the Curse of Dimensionality

* Part I: Geometry of Data
  * Euclidean Geometry: transportation metrics, CNNs , scattering. 
  * Non-Euclidean Geometry: Graph Neural Networks. 
  * Unsupervised Learning under Geometric Priors (Implicit vs explicit models, microcanonical, transportation metrics).
  * Applications and Open Problems: adversarial examples, graph inference, inverse problems.

* Part II: Geometry of Optimization and Generalization
  * Stochastic Optimization (Robbins & Munro, Convergence of SGD) 
  * Stochastic Differential Equations (Fokker-Plank, Gradient Flow, Langevin Dynamics, links with SGD; open problems) 
  * Dynamics of Neural Network Optimization (Mean Field Models using Optimal Transport, Kernel Methods) 
  * Landscape of Deep Learning Optimization (Tensor/Matrix factorization, Deep Nets; open problems). 
  * Generalization in Deep Learning. 
  
* Part III (time permitting): Open qustions on Reinforcement Learning


## Pre-requisites

Multivariate Calculus, Linear Algebra, Probability and Statistics at solid undergraduate level.

Notions of Harmonic Analysis, Differential Geometry and Stochastic Calculus are nice-to-have, but not essential.

## Grading

The course will be graded with a final project -- consisting in an in-depth survey of a topic related to the syllabus,
plus a participation grade. The detailed abstract of the project will be graded at the mid-term. 

**Final Project is due May 1st by email to the instructors**

## Lectures

| Week        | Lecture Date           | Topic       |  References                     |
| ---------------|----------------| ------------|---------------------------|
| 1 | 1/23  | **Guest Lecture: Arthur Szlam (Facebook)**  |  [References](doc/refs.md#lec1)  |
| 2 | 1/30  | **Lec2** Euclidean Geometric Stability. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture2.pdf) |  [References](doc/refs.md#lec2)  |
| 3 | 2/6  | **Guest Lecture: Leon Bottou (Facebook/NYU)** [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/bottou-02.06.2018.pdf)  |  [References](doc/refs.md#lec3)  |
| 4 | 2/13  | **Lec3** Scattering Transforms and CNNs [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture3.pdf) |  [References](doc/refs.md#lec3)  |
| 5 | 2/20  | **Lec4** Non-Euclidean Geometric Stability. Gromov-Hausdorff distances. Graph Neural Nets [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture4.pdf)|  [References](doc/refs.md#lec4)  |
| 6 | 2/27  | **Lec5** Graph Neural Network Applications [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture5.pdf) |  [References](doc/refs.md#lec5)  |
| 7 | 3/6  | **Lec6** Unsupervised Learning under Geometric Priors. Implicit vs Explicit models. Optimal Transport models. Microcanonical Models. Open Problems [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture6.pdf)  |  [References](doc/refs.md#lec6)  |
| 8 | 3/13  | **Spring Break**  |  [References](doc/refs.md#lec8)  |
| 9 | 3/20  | **Lec7** Discrete vs Continuous Time Optimization. The Convex Case. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture7.pdf)   |  [References](doc/refs.md#lec7)  |
| 10 | 3/27  | **Lec8** Discrete vs Continuous Time Optimization. Stochastic and Non-convex case [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture8.pdf) |  [References](doc/refs.md#lec8)  |
| 11 | 4/3  | **Lec9** Gradient Descent on Non-convex Optimization. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture9.pdf) |  [References](doc/refs.md#lec9)  |
| 12 | 4/10  | **Lec10** Gradient Descent on Non-convex Optimization. Escaping Saddle Points efficiently. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture10.pdf) |  [References](doc/refs.md#lec10)  |
| 13 | 4/17  | **Lec11** Landscape of Deep Learning Optimization. Spin Glasses, Kac-Rice, RKHS, Topology. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture11.pdf) |  [References](doc/refs.md#lec11)  |
| 14 | 4/24  | **Lec12** **Guest Lecture: Behnam Neyshabur (IAS/NYU): Generalization in Deep Learning** [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture12_behnamneyshabur.pdf) |  [References](doc/refs.md#lec12)  |
| 15 | 5/1  | **Lec13** Stability. Open Problems. |  [References](doc/refs.md#lec13)  |



### Lab sessions / Parallel Curricula

## [NeuralODE living document](https://docs.google.com/document/d/1GHvyCCZ3Ep-IWa5QSQ6NMtPsCJry9h0jOPues5iEIus/edit?usp=sharing)

* Class 1: Numerical solution of ODEs I
  * Motivation: ODEs are used to mathematically model a number of natural processes and phenomena. The study of their numerical 
    simulations is one of the main topics in numerical analysis and of fundamental importance in applied sciences. 
  * Required Reading: 
    * Sections 12.1-4 from An Introduction to Numerical Analysis (‘INA’)
    * Sections 11.1-3 from Numerical Mathematics (‘NM’)
