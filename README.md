# Lecture slides

* [Lecture 1](./Slides/Introduction/main.pdf)
* [Lecture 2](./Slides/Stability/main.pdf)
* [Lecture 3](./Slides/Laplace/main.pdf)
* [Lecture 4, 5](./Slides/Control/main.pdf)
* [Lecture 5](./Slides/Discrete/main.pdf)
* [Lecture 6](./Slides/NullRow/main.pdf)
* [Lecture 7](./Slides/ColumnLeftNull/main.pdf)
* [Lecture 8](./Slides/LyapunovTheory/main.pdf)
* [Lecture 9](./Slides/HJB_LQR/main.pdf)
* [Lecture 10](./Slides/Observer/main.pdf)
* [Lecture 11](./Slides/ControllabilityObservability/main.pdf)
* [Lecture 12](./Slides/Linearization/main.pdf)
* [Lecture 13](./Slides/Constrained/main.pdf)

# Lecture videos 

* [**Full playlist**](https://www.youtube.com/watch?v=x2cYtqJR-qg&list=PLlxR_sEKjSpTyteBJYJR6WBuAlPineEwz)
* [Lecture 2 ](https://youtu.be/x2cYtqJR-qg)
* [Lecture 4 ](https://youtu.be/geeaciySBHY)
* [Lecture 5 ](https://youtu.be/c9yNjq2vtpw)
* [Lecture 6 ](https://youtu.be/qTIOv82XAQE)
* [Lecture 7 ](https://youtu.be/VS0NC_a8kQY)
* [Lecture 8 ](https://youtu.be/FIGE0Cyi55g)
* [Lecture 10](https://youtu.be/BhcDmOQjdGo)
* [Lecture 11](https://youtu.be/bpNQWrEUZY0)
* [Lecture 12 - version 1](https://youtu.be/q_WRiwkgnGU) 
* [Lecture 12 - version 2](https://youtu.be/6K9B8EWCIzw)
* [Lecture 13](https://youtu.be/UGLLSpwozTE)
* [Lecture 14](https://youtu.be/D-8M8XEygeg)

# Labs

* Assignment / lab / submission / gradable item \# 1: 
* * [colab](./ColabNotebooks/Lab1_Control2021.ipynb)
* Assignment / lab / submission / gradable item \# 2:
* * [colab](./ColabNotebooks/Lab2_Control2021.ipynb)
* * [PDF](./ColabNotebooks/Lab2_Control2021.pdf)
* Assignment / lab / submission / gradable item \# 3:
* * [colab](./ColabNotebooks/Lab_3.ipynb)

# Self-study with Colab

* [Practice 1 ](./ColabNotebooks/practice_01_StateSpace_transformation_simulation.ipynb)
* [Practice 2 ](./ColabNotebooks/practice_02_LTI_Stability.ipynb)
* [Practice 3 ](./ColabNotebooks/practice_03_transfer_functions.ipynb)
* [Practice 4 ](./ColabNotebooks/practice_04_basics_of_control.ipynb)
* [Practice 5 ](./ColabNotebooks/practice_05_reg_tracking.ipynb)
* [Practice 6 ](./ColabNotebooks/practice_06_discrete_systems.ipynb)
* [Practice 7 ](./ColabNotebooks/practice_07_ffs_svd.ipynb)
* [Practice 8 ](./ColabNotebooks/practice_08_la_applications.ipynb)
* [Practice 9 ](./ColabNotebooks/practice_09_lyapunov_functions.ipynb)
* [Practice 10](./ColabNotebooks/practice_10_observers.ipynb)
* [Practice 11](./ColabNotebooks/practice_11_controllability_observability.ipynb)
* [Practice 12](./ColabNotebooks/practice_12_design_example.ipynb)


# For contributors

Pull requests with suggestions and improvements, however small or big, are welcome!

The changes in lecture slides are going through an automated check.

The PDFs are compiled and updated automatically when PR is merged (thanks to k1rill-fedoseev from the 2020 Linear Control class!). You don't need to update them manually. They are also uploaded as workflow artifacts for every new commit pushed into this repository. You can use them to see your changes.
 
Consider adding \*.pdf to the .git/info/exclude file on your local repo. Here is the ~~overy long but helpful~~ [description why it works](https://medium.com/@dave_lunny/exclude-files-from-git-without-committing-changes-to-gitignore-986fa712e78d).

# Book suggestions


## Lecture 1. State-Space, ODE
* Control Systems Engineering Norman S. Nise 
  * Chapter 3.3: The General State-Space Representation 
  * Chapter 3.4: Applying the State-Space Representation
* Systems of First Order Linear Differential Equations. 
  * [Download](http://www.personal.psu.edu/sxt104/class/Math251/Notes-LinearSystems.pdf)
* [Control theory by S. Simrock]
  * [Sections 1, 3](https://cds.cern.ch/record/1100534/files/p73.pdf)


## Lecture 2. Stability
* [State Space Stability (Linear Systems Theory EECS 221a, Berkeley)](https://youtu.be/7GarcEQ0uk8)
* Control Systems Engineering Norman S. Nise (chapters 3.3, 3.4)
* Paul's Online Notes 
  * [Systems of linear ODE](http://tutorial.math.lamar.edu/Classes/DE/SystemsDE.aspx)
  * [Solutions for them](http://tutorial.math.lamar.edu/Classes/DE/SolutionsToSystems.aspx)
* Astolfi, A., 2006. Systems and Control Theory: An Introduction. Imperial College London lecture notes.
  * [2.3.1 Linear systems (on equilibrioum of linear systems)](http://www3.imperial.ac.uk/pls/portallive/docs/1/31851696.PDF)
* Stability for LTI via Jordan block representation (MAE598, LMIs in Control, Stability and Eigenvalues)
  * [Video](https://youtu.be/8zYOJbpiT38)


## Lecture 3. Transfer functions
* Control Systems Engineering, by Norman S. Nise 
  * chapter 2.2 Laplace Transform Review
  * chapter 2.3 The Transfer Function (for self-study, in case of interest)
* Cho W. S. To, Introduction to Dynamics and Control in Mechanical Engineering Systems. 
  * 2 Review of Laplace Transforms 
  * 8.3 Transfer Functions
* Control theory by S. Simrock
  * [Sections 2, 3 and 4](https://cds.cern.ch/record/1100534/files/p73.pdf)
* [(Advanced) Systems and signals Background information for block diagrams (MAE598, LMIs in Control)](https://youtu.be/PM5tDcWEZgk)
* [(Advanced) Laplace transform and H-norms (MAE598, LMIs in Control)](https://youtu.be/aL8PG8H1dp8)
* [(Advanced) Proper transfer functions, KYP Lemma (MAE598, LMIs in Control)](https://youtu.be/H-673uXX9FI)


## Lecture 4. Stabilizing control
* Control theory by S. Simrock
  * [Sections 5, 6 (stability discussed in terms of TF)](https://cds.cern.ch/record/1100534/files/p73.pdf)
* Module 9: State Feedback Control Design
  * [Lecture Note 1](https://nptel.ac.in/content/storage2/courses/108103008/PDF/module9/m9_lec1.pdf)
* [16.31 Feedback Control Systems](https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-30-feedback-control-systems-fall-2010/lecture-notes/MIT16_30F10_lec11.pdf)
* [Chapter 6 State Feedback](http://www.cds.caltech.edu/~murray/books/AM05/pdf/am06-statefbk_16Sep06.pdf)

## Lecture 5. Discrete Systems
* Control theory by S. Simrock
  * [Section 7 (goes to z-transform, which is outside the scope of our course)](https://cds.cern.ch/record/1100534/files/p73.pdf)
* Astolfi, A., 2006. Systems and Control Theory: An Introduction. Imperial College London lecture notes:
  * 1.2.9 Approximate discrete-time models;
  * [Proposition 2.3 (Trajectories of linear, discrete-time, systems) - on Controllability](http://www3.imperial.ac.uk/pls/portallive/docs/1/31851696.PDF)
* Dahleh, M., Dahleh, M.A. and Verghese, G., 2004. Lectures on dynamic systems and control. A+ A, 4(100), pp.1-100. (goes to z-transform, which is outside the scope of our course):
  * [Lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-241j-dynamic-systems-and-control-spring-2011/readings/MIT6_241JS11_chap10.pdf)

## Lecture 6, 7 - Fundamental subspaces, Projectors.
* [Subspaces (MAE598, LMIs in Control)](https://youtu.be/eAHq4bTiMnA?t=34m00s)

## Lecture 8 Lyapunov Theory 
* [3.9 Liapunov’s direct method](https://folk.uib.no/nmagb/m2142002l3.pdf)
* [Universita degli studi di Padova Dipartimento di Ingegneria dell'Informazione, Nicoletta Bof, Ruggero Carli, Luca Schenato, Technical Report, Lyapunov Theory for Discrete Time Systems](https://arxiv.org/abs/1809.05289)
* [Lyapunov Theory (MAE598, LMIs in Control)](https://youtu.be/cB_1_eIdqqM)

## Lecture 9 LQR
* [(Underactuated Robotics) Linear Quadratic Regulators](http://underactuated.mit.edu/lqr.html)
* [(CS 287: Advanced Robotics, Fall 2015) infinite horizon discrete LQR as an interative procedure, linear and affine cases, LTI and LTV cases](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa15/slides/lecture5-LQR.pdf)
* [(advanced) connection between LQR and Kalman Filter (MAE598, LMIs in Control)](https://youtu.be/Ahzg-Tj7aEU?t=1490)

## Lecture 10 Observers
* [Observers and the Separation Principle](https://www.dynsyslab.org/archive/RecEst2011/www.idsc.ethz.ch/Courses/Archives/Recursive_Estimation/recursive_estimation_2011/LectureNotes/RE_Lecture11_v1.pdf)
* [The Luenberger Observer Framework (MAE598, LMIs in Control)](https://youtu.be/eSY8Fwp2dQo)

## Lecture 11 Controllability, Observability

* [Invariant subspaces, Sylvester equation, PBH](https://stanford.edu/class/ee363/sessions/s2notes.pdf)
* [EE363 Winter 2008-09 Lecture 6 Invariant subspaces](https://web.stanford.edu/class/ee363/lectures/inv-sub.pdf)
* [Controllability (MAE598, LMIs in Control)](https://youtu.be/eAHq4bTiMnA?t=25m00s)

## Other

### MIMO, LTI, LTV
* [Equilibrium Points of Linear Autonomous Systems](https://math24.net/linear-autonomous-systems-equilibrium-points.html)

### Optimal Control of LTI systems
* (Underactuated Robotics) Continuous dynamic programming.
  * [Link](http://underactuated.csail.mit.edu/dp.html#section3)
* Control theory by S. Simrock
  * [Section 8](https://cds.cern.ch/record/1100534/files/p73.pdf)

### Noise, Information, Observation
* For statistical prerequisites, see Mathematics for Machine Learning
  * [PCA, Week 1](https://www.coursera.org/learn/pca-machine-learning)

### Observer Design, Kalman Filter
* Control theory by S. Simrock
  * [Section 8.1](https://cds.cern.ch/record/1100534/files/p73.pdf)
* [Kalman Filters, discrete and contininous (MAE598, LMIs in Control)](https://youtu.be/Ahzg-Tj7aEU)
* [An LMI for the Kalman Filter](https://en.wikibooks.org/wiki/LMIs_in_Control/Applications/An_LMI_for_the_Kalman_Filter)

### Parameter estimation
* Control theory by S. Simrock
  * [Section 9](https://cds.cern.ch/record/1100534/files/p73.pdf)

### Difference between linear and non-linear dynamics
* [Intro to Nonlinear Systems, Existence and Uniqueness (MAE598, LMIs in Control)](https://youtu.be/oXFPeP-1F0g)
