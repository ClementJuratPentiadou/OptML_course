# EPFL Course - Optimization for Machine Learning - CS-439

[Official coursebook information](http://edu.epfl.ch/coursebook/en/optimization-for-machine-learning-CS-439)

`Lectures:` Fri 13:15-15:00 in [CO2](https://plan.epfl.ch/?room==CO%202)

`Exercises:` Fri 15:15-17:00 in [BC01](https://plan.epfl.ch/?room==BC%2001)

This course teaches an overview of modern mathematical optimization methods, for applications in machine learning and data science. In particular, scalability of algorithms to large datasets will be discussed in theory and in implementation.

### Team
 - Instructors: 
   - Martin Jaggi [martin.jaggi@epfl.ch](mailto:martin.jaggi@epfl.ch)
   - Nicolas Flammarion [nicolas.flammarion@epfl.ch](mailto:nicolas.flammarion@epfl.ch)
 - Assistants:
   - Aditya Varre [aditya.varre@epfl.ch](mailto:aditya.varre@epfl.ch)
   - Amirkeivan Mohtashami [amirkeivan.mohtashami@epfl.ch](mailto:amirkeivan.mohtashami@epfl.ch)
   - Matteo Pagliardini [matteo.pagliardini@epfl.ch](mailto:matteo.pagliardini@epfl.ch)
   - Scott Pesme [scott.pesme@epfl.ch](mailto:scott.pesme@epfl.ch)

`Contents:`

Convexity, Gradient Methods, Proximal algorithms, Subgradient Methods, Stochastic and Online Variants of mentioned methods, Coordinate Descent, Frank-Wolfe, Accelerated Methods, Primal-Dual context and certificates, Lagrange and Fenchel Duality, Second-Order Methods including Quasi-Newton Methods, Derivative-Free Optimization.

*Advanced Contents:*

Parallel and Distributed Optimization Algorithms

Computational Trade-Offs (Time vs Data vs Accuracy), Lower Bounds

Non-Convex Optimization: Convergence to Critical Points, Alternating minimization, Neural network training

### Program:
| Nr  | Date  | Topic                                                 | Materials                                                                                                  | Exercises                             |
| --- | ----- | ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| #1  | 25.2. | Introduction, Convexity                               | [notes](../../raw/master/lecture_notes/lecture-notes.pdf), [slides](../../raw/master/slides/lecture01.pdf) | [lab01](../../tree/master/labs/ex01/) |
| #2  | 4.3.  | Gradient Descent                                      | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #3  | 11.3. | Projected Gradient Descent                            | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #4  | 18.3. | Proximal and Subgradient Descent                      | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #5  | 25.3. | Stochastic Gradient Descent, Non-Convex Optimization  | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #6  | 1.4.  | Non-Convex Optimization, Accelerated Gradient Descent | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #7  | 8.4.  | Newton's Method & Quasi-Newton                        | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| .   | 15.4. | `easter vacation`                                     |                                                                                                            | -                                     |
| .   | 22.4. | `easter vacation`                                     |                                                                                                            | -                                     |
| #8  | 29.4. | Frank-Wolfe                                           | notes,                                                                                                     |                                       |
| #9  | 6.5.  | Coordinate Descent                                    | [notes](../../raw/master/lecture_notes/lecture-notes.pdf),                                                 |                                       |
| #10 | 13.5. | Duality, Gradient-free, adaptive methods              | notes,                                                                                                     |                                       |
| #11 | 27.5. | Opt for ML in Practice                                | notes,                                                                                                     | Q&A                                   |
| #12 | 3.6.  | Opt for ML in Practice                                | notes,                                                                                                     | Q&A Projects                          |
| #13 | 10.6. | `Mini-Project week`                                   |                                                                                                            |

### Videos:
[Playlist on youtube of last year's videos](https://www.youtube.com/playlist?list=PL4O4bXkI-fAeYrsBqTUYn2xMjJAqlFQzX)

### Exercises:
The [weekly exercises](../../tree/master/labs/) consist of a mix of theoretical and practical `Python` exercises for the corresponding topic each week (starting week 2). Solutions to theory exercises are available [here](../../tree/master/lecture_notes), and for practicals in the lab folder.

### Project:
A `mini-project` will focus on the practical implementation: Here we encourage students to investigate the real-world performance of one of the studied optimization algorithms or variants, helping to provide solid empirical evidence for some behaviour aspects on a real machine-learning task. The project is mandatory and done in groups of 3 students. It will count 25% to the final grade. Project reports (3 page PDF) are due June 17th. Here is a [detailed project description](../../raw/master/labs/mini-project/miniproject_description.pdf).

### Assessment:
Final written exam in exam session on T.B.D.. _Format: Closed book. Theoretical questions similar to exercises. You are allowed to bring one cheat sheet (A4 size paper, both sides can be used), either handwritten or 11 point minimum font size._
For practice: [exam 2020](../../raw/master/exams/exam2020.pdf), [solutions 2020](../../raw/master/exams/exam2020solutions.pdf), [exam 2019](../../raw/master/exams/exam2019.pdf), [solutions 2019](../../raw/master/exams/exam2019solutions.pdf), [exam 2018](../../raw/master/exams/exam2018.pdf), [solutions 2018](../../raw/master/exams/exam2018solutions.pdf).

### Links to related courses and materials 
 - [CMU 10-725](https://www.stat.cmu.edu/~ryantibs/convexopt-F18/)
 - [Berkeley EE-227C](https://ee227c.github.io/)
 
### Recommended Books
 - [Convex Optimization: Algorithms and Complexity](https://arxiv.org/pdf/1405.4980.pdf), by Sébastien Bubeck (free online)
 - [Convex Optimization](http://stanford.edu/~boyd/cvxbook/), Stephen Boyd and Lieven Vandenberghe (free online)
 - [Introductory Lectures on Convex Optimization](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.693.855&rep=rep1&type=pdf), Yurii Nesterov (free online)
