# Lecture slides

* Lecture 1 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Introduction
* Lecture 2 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Stability
* Lecture 3 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Laplace
* Lecture 4, 5 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Control
* Lecture 5 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Discrete
* Lecture 6 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/NullRow
* Lecture 7 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/ColumnLeftNull
* Lecture 8 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/LyapunovTheory
* Lecture 9 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/HJB_LQR
* Lecture 10 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/tree/main/Slides/Observer

# Lecture videos 

([playlist](https://www.youtube.com/watch?v=x2cYtqJR-qg&list=PLlxR_sEKjSpTyteBJYJR6WBuAlPineEwz))

* Lecture 2 - https://youtu.be/x2cYtqJR-qg
* Lecture 4 - https://youtu.be/geeaciySBHY
* Lecture 5 - https://youtu.be/c9yNjq2vtpw
* Lecture 6 - https://youtu.be/qTIOv82XAQE
* Lecture 7 - https://youtu.be/VS0NC_a8kQY
* Lecture 8 - https://youtu.be/FIGE0Cyi55g

# Labs

* Assignment / lab / submission / gradable item \# 2 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/blob/main/ColabNotebooks/Lab2_Control2021.pdf

# Self-study with Colab

* Lecture 1 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/blob/main/ColabNotebooks/practice1_StateSpace_transformation_simulation.ipynb
* Lecture 2 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/blob/main/ColabNotebooks/practice2_LTI_Stability.ipynb
* Lecture 3 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/blob/main/ColabNotebooks/practice3_transfer_functions.ipynb

...

* Lecture 8 - https://github.com/SergeiSa/Control-Theory-Slides-Spring-2021/blob/main/ColabNotebooks/lecture8_LyapunovEq.ipynb

# For contributors

Pull requests with suggestions and improvements, however small or big, are welcome!

The changes in lecture slides are going through an automated check.

The PDFs are compiled and updated automatically when PR is merged (thanks to k1rill-fedoseev from the 2020 Linear Control class!). You don't need to update them manually. They are also uploaded as workflow artifacts for every new commit pushed into this repository. You can use them to see your changes.
 
Consider adding \*.pdf to the .git/info/exclude file on your local repo. Here is the ~~overy long but helpful~~ [description why it works](https://medium.com/@dave_lunny/exclude-files-from-git-without-committing-changes-to-gitignore-986fa712e78d)

# Book suggestions


## Lecture 1. State-Space, ODE

* Control Systems Engineering Norman S. Nise 
  * Chapter 3.3: The General State-Space Representation 
  * Chapter 3.4: Applying the State-Space Representation
* Systems of First Order Linear Differential Equations. 
[Download](http://www.personal.psu.edu/sxt104/class/Math251/Notes-LinearSystems.pdf)
* Control theory by S. Simrock - sections 1, 3:
https://cds.cern.ch/record/1100534/files/p73.pdf


## Lecture 2. Stability

* State Space Stability (Linear Systems Theory EECS 221a, Berkeley) - https://youtu.be/7GarcEQ0uk8
* Control Systems Engineering Norman S. Nise (chapters 3.3, 3.4)
* Paul's Online Notes (systems of linear ODE, solutions for them):
http://tutorial.math.lamar.edu/Classes/DE/SystemsDE.aspx
http://tutorial.math.lamar.edu/Classes/DE/SolutionsToSystems.aspx
* Astolfi, A., 2006. Systems and Control Theory: An Introduction. Imperial College London lecture notes. - 2.3.1 Linear systems (on equilibrioum of linear systems):
http://www3.imperial.ac.uk/pls/portallive/docs/1/31851696.PDF


## Lecture 3. Transfer functions

* Control Systems Engineering, by Norman S. Nise 
  * chapter 2.2 Laplace Transform Review
  * chapter 2.3 The Transfer Function (for self-study, in case of interest)
* Cho W. S. To, Introduction to Dynamics and Control in Mechanical Engineering Systems. 
  * 2 Review of Laplace Transforms 
  * 8.3 Transfer Functions
* Control theory by S. Simrock - sections 2, 3 and 4:
https://cds.cern.ch/record/1100534/files/p73.pdf


## Lecture 4, 5. Stabilizing control
* Control theory by S. Simrock - sections 5, 6 (stability discussed in terms of TF):
https://cds.cern.ch/record/1100534/files/p73.pdf
* Module 9: State Feedback Control Design, Lecture Note 1:
https://nptel.ac.in/content/storage2/courses/108103008/PDF/module9/m9_lec1.pdf
* 16.31 Feedback Control Systems
https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-30-feedback-control-systems-fall-2010/lecture-notes/MIT16_30F10_lec11.pdf
* Chapter 6 State Feedback - http://www.cds.caltech.edu/~murray/books/AM05/pdf/am06-statefbk_16Sep06.pdf

## Lecture 6. Discrete Systems
  * Control theory by S. Simrock - section 7 (goes to z-transform, which is outside the scope of our course)
https://cds.cern.ch/record/1100534/files/p73.pdf
* Astolfi, A., 2006. Systems and Control Theory: An Introduction. Imperial College London lecture notes:
  * 1.2.9 Approximate discrete-time models;
  * Proposition 2.3 (Trajectories of linear, discrete-time, systems) - on Controllability:
http://www3.imperial.ac.uk/pls/portallive/docs/1/31851696.PDF
* Dahleh, M., Dahleh, M.A. and Verghese, G., 2004. Lectures on dynamic systems and control. A+ A, 4(100), pp.1-100. (goes to z-transform, which is outside the scope of our course):
https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-241j-dynamic-systems-and-control-spring-2011/readings/MIT6_241JS11_chap10.pdf

## Lecture 8 Lyapunov Theory 
* 3.9 Liapunov’s direct method - https://folk.uib.no/nmagb/m2142002l3.pdf
* Universita degli studi di Padova Dipartimento di Ingegneria dell'Informazione, Nicoletta Bof, Ruggero Carli, Luca Schenato, Technical Report, Lyapunov Theory for Discrete Time Systems - https://arxiv.org/abs/1809.05289

## Other

### MIMO, LTI, LTV
  * Equilibrium Points of Linear Autonomous Systems. 
  [Link](https://www.math24.net/linear-autonomous-systems-equilibrium-points/)

### Optimal Control of LTI systems
 * Underactuated Robotics. Continuous dynamic programming.
   [Link](http://underactuated.csail.mit.edu/dp.html#section3)
 * Underactuated Robotics. Linear Quadratic Regulators
   [Link](http://underactuated.csail.mit.edu/lqr.html)
 * Control theory by S. Simrock - section 8:
https://cds.cern.ch/record/1100534/files/p73.pdf

### Noise, Information, Observation
  * For statistical prerequisites, see Mathematics for Machine Learning: PCA, Week 1: https://www.coursera.org/learn/pca-machine-learning.

### Observer Design, Kalman Filter
  * Control theory by S. Simrock - section 8.1:
https://cds.cern.ch/record/1100534/files/p73.pdf

### Parameter estimation
  * Control theory by S. Simrock - section 9:
https://cds.cern.ch/record/1100534/files/p73.pdf
