
<h1 align="center">Course: Big Data Optimization </h1>
<p align="center"><a href="http://people.inf.ethz.ch/niaohe/teaching.html"><img alt="Big Data Optimization" src="./assets/img/" width="20%"></a></p>

## Course Information
Instructor: [Niao He](http://people.inf.ethz.ch/niaohe/index.html)

### Course Description
> Nearly every problem in machine learning and high-dimensional statistics can be formulated in terms of optimization of some function, possibly under some constraints. In the wake of Big Data era, there is an increasingly strong need to design efficient and scalable algorithms to address optimization problems in large scale - including problems exhibiting inherently high dimensions and problems involving truly massive data sets. The key aim of this course is to expose students to a wide range of modern algorithmic developments in optimization (mainly in convex optimization) and bring them near the frontier of research in large-scale optimization and machine learning. 
 
> *Courtesy warning*: The course will be theory-oriented and emphasize deep understanding of structures of optimization problems and computation complexity of numerical algorithms. The course will not cover any software or tools used for big data analytics and is not an application course.

### Prerequisite
Students are expected to have strong knowledge of linear algebra, real analysis, and probability theory. Some prior exposure to optimization at a graduate level is preferred.

### Textbook
No book is required, but you are highly recommended to read the following:

1. Ben-Tal & Nemirovski. [Lectures on Modern Convex Optimization](http://www2.isye.gatech.edu/~nemirovs/Lect_ModConvOpt.pdf), SIAM, 2011.
2. Nesterov. [Introductory Lectures on Convex Optimization: A Basic Course](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.693.855&rep=rep1&type=pdf), Kluwer-Academic, 2003.
3. Sra, Nowozin, Wright (eds). [Optimization for Machine Learning](https://mitpress.mit.edu/books/optimization-machine-learning). MIT Press, 2011.
4. Bubeck. [Convex Optimization: Algorithms and Complexity](http://research.microsoft.com/en-us/um/people/sebubeck/Bubeck15.pdf). In Foundations and Trends in Machine Learning, 2015.


### Topical Outlines

- **Part I: Introduction and Fundamentals** (3 weeks): basics of convex analyis, conic programming, machine learning under optimization lenses.
- **Part II: Smooth Convex Optimization** (4 weeks): gradient descent, acceleration, projection-gree methods, coordinate descent, etc. 
- **Part III: Nonsmooth Convex Optimization** (4 weeks): subgradient method, smoothing, Mirror Prox, primal-dual algorithms, proximal and splitting algorithms, etc. 
- **Part IV: Stochastic and Online Optimization** (3 weeks): sample average approximation, stochastic approximation, incremental gradient methods, online algorithms, etc. 
- **Part V: Optimization Perspectives for Selective Topics in Machine Learning** (2 weeks): sparsity learning, large-scale kernel machine, reinforcement learning, deep learning, etc. 


### Class Schedule

|: Module I :|||
| Lecture  | Topic | Resources |
| :-----:  | :-------: | :---------: |



| 1 |  Introduction | Introduction to course;  | [[Scribe](./lecture_slides/IE521-lecture-1-convex-sets.pdf)] |
| 2 | Convex Sets | Radons Theorem; Helleys Theorem and Applications; Separation Theorems | [[Scribe](./lecture_slides/IE521-lecture-2-convex-geometry.pdf)] |
| 3 | Separation Theorems | Separation Hyperplane Theorem; Strong Separation Hyperplane Theorem; Farkas Lemma; Duality of Linear Programming | [[Scribe](./lecture_slides/IE521-lecture-3-separation-theorems.pdf)] |
| 4 | Convex Functions | Convex Functions  | [[Scribe](./lecture_slides/IE521-lecture-4-convex-functions.pdf)] |
| 5 | Convex Functions II | Characterizations of Convex Functions; Continuity of Convex Functions; Closed Convex Functions | [[Scribe](./lecture_slides/IE521-lecture-5-convex-functions-II.pdf)] |
| 6 | Subgradient and Subdifferential | Subgradient; Directional Derivative and Subdifferential Set; Calculus of Subgradient | [[Scribe](./lecture_slides/IE521-lecture-6-subgradients.pdf)] |
| 7 | Convex Conjugate | Conjugate Function; Conjugate Theory; Minima of Convex Functions | [[Scribe](./lecture_slides/IE521-lecture-7-convex-conjuate.pdf)] |
| 8 | Convex Programs and Duality | Convex Programs; Convex Theorem on Alternatives; Lagrange Duality | [[Scribe](./lecture_slides/IE521-lecture-8-convex-programs-and-duality.pdf)] |
| 9 | Optimality Conditions | KKT Conditions; Saddle Point Perspective; Minimax Theorems | [[Scribe](./lecture_slides/IE521-lecture-9-optimality-conditions.pdf)] |
| 10 | Solving Convex Programs | Accuracy Measure, Oracles, Complexity; Cutting Plane Methods; Center of Gravity Algorithm | [[Scribe](./lecture_slides/IE521-lecture-10-solving-convex-programs.pdf)] |
| 11 | Polynomial Solvability of Convex Programs | Complexity vs Convergence; Center of Gravity; Ellipsoid Method | [[Scribe](./lecture_slides/IE521-lecture-11-ellipsoid-method.pdf)] |
| 12 | Conic Programming | Generalized Inequality; Conic Programs: LP, SOCP, SDP; Applications: norm minimization, sparse group lasso, robust linear program | [[Scribe](./lecture_slides/IE521-lecture-12-conic-programs.pdf)] |
| 13 | Dual Cone; Conic Duality; SOCP Duality; SDP Duality and Applications | [[Scribe](./lecture_slides/IE521-lecture-13-conic-duality.pdf)] |
| 14 | SDP Relaxation and Applications | SDP for Eigenvalue Optimization; SDP for Max Cut Problem; SDP for Nonconvex QCQP; SDP for Stability of Dynamical Systems | [[Scribe](./lecture_slides/IE521-lecture-14-SDP-relaxation.pdf)] |
| 15 | CVX Tutorial | CVX Tutorial; MATLAB Demonstration | [[Scribe](./lecture_slides/IE521-lecture-15-CVX-tutorial.pdf)] |
| 16 | Interior Point Method  Part I | Path Following Scheme; Self-concordant Functions;  | [[Scribe](./lecture_slides/IE521-lecture-16-IPM-self-concordance.pdf)] |
| 17 | Interior Point Method  Part II | Classical Newton Method and Analysis; Newton Method for Self-concordant Functions; Damped Newton Method and Global Convergence | [[Scribe](./lecture_slides/IE521-lecture-17-IPM-Newton-method.pdf)] |
| 18 | Interior Point Method  Part III | Self-concordant Barriers; Restate Path Following Scheme | [[Scribe](./lecture_slides/IE521-lecture-18-IPM-path-following-scheme.pdf)] |
| 19 | Interior Point Method  Part IV | Self-concordant Barriers for LP, SOCP, SDP; Complexity of Interior Point Method; Primal-Dual Path Following Scheme;  | [[Scribe](./lecture_slides/IE521-lecture-19-IPM-conic-programs.pdf)] |
| 20 | Subgradient Method | Subgradient Method; Choices of Stepsize; Convergence Analysis;  | [[Scribe](./lecture_slides/IE521-lecture-20-subgradient-method.pdf)] |
| 21 | Bundle Methods | Kelleys Method; Level Set Method;  | [[Scribe](./lecture_slides/IE521-lecture-21-bundle-methods.pdf)] |
| 22 | Constrained Subgradient Methods | Problems with Functional Constraints; Constrained Level Method | [[Scribe](./lecture_slides/IE521-lecture-22-constrained-subgradient-methods.pdf)] |
| 23 | Dual Methods | Augmented Lagrangian; ADMM | [[Scribe](./lecture_slides/IE521-lecture-23-dual-methods.pdf)] |

## License
