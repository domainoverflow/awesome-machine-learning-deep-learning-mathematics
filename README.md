# awesome machine learning and deep learning mathematics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome machine learning and deep learning mathematics and advanced mathematics descriptions,documents,concepts,study materials,videos,libraries and software (by language).

[![Main Architecture 1](https://image.slidesharecdn.com/machinelearningwithapachemahout-120216160514-phpapp02/95/machine-learning-with-apache-mahout-15-728.jpg?cb=1329409119)](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/)
[![Main Architecture 2](https://whatsthebigdata.files.wordpress.com/2017/03/machinelearning_mathtopics.png?w=640)](https://ocw.mit.edu/courses/mathematics/18-657-mathematics-of-machine-learning-fall-2015/)                        

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [INTRODUCTION](#introduction)
    - [Why Maths Important for Machine Learning?](#introduction-why-maths)
- [BASICS](#basics)
    - [What is Machine Learning?](#basics-what-machinelearning)
    - [What is Deep Learning?](#basics-what-deeplearning)
    - [Applications of Mathematics in Machine and Deep Learning?](#basics-what-topological-quantum-computing)
    - [Machine and Deep Learning with Mathematics vs without Mathematics](#basics-mathematics-nonmathematics-vs) 
- [MATHEMATICAL TOPICS FOR MACHINE AND DEEP LEARNING](#mathematicaltopics)
    - [Linear Algebra](#mathematicaltopics-linear-algebra)
    - [Probability and Statistics](#mathematicaltopics-probability-statistics)
    - [Linear Calculus](#mathematicaltopics-linear-calculus)
    - [Vector Calculus](#mathematicaltopics-vector-calculus)
    - [Tensor Calculus](#mathematicaltopics-tensor-calculus)
    - [Other Calculus Topics](#mathematicaltopics-other-calculus)
    - [Graphs Theory](#mathematicaltopics-graphs-theory)
    - [Complexity Theorems](#mathematicaltopics-complexity-theorems)
    - [Number Theory](#mathematicaltopics-number-theory)
    - [Optimization Theorems](#mathematicaltopics-optimizationtheorems)
    - [Topology](#mathematicaltopics-topology)
- [ADVANCED MATHEMATICAL TOPICS FOR MACHINE AND DEEP LEARNING](#mathematicaladvancedtopics)
    - [Hamiltonian Calculus](#mathematicaladvancedtopics-hamiltoniancalculus)
    - [Halleys Calculus](#mathematicaladvancedtopics-halleyscalculus) 
    - [Complex Numbers](#mathematicaladvancedtopics-complexnumbers)
    - [Quaterinions](#mathematicaladvancedtopics-quaterinions)
    - [Sedenions](#mathematicaladvancedtopics-sedenions)
    - [Qudratic Function](#mathematicaladvancedtopics-quadraticfunction)
    - [Advanced Probability and Statistics](#mathematicaladvancedtopics-advanced-probability-statistics)
    - [NP Problem](#mathematicaladvancedtopics-npproblem)
- [LINEAR ALGEBRA](#mathematicallinearalgebra)
    - [Linear Equations](#mathematicallinearalgebra-linearequations)
    - [Polynomial Equations](#mathematicallinearalgebra-polynomialequations)
    - [Vectors](#mathematicallinearalgebra-vectors)             
    - [Matrices](#mathematicallinearalgebra-matrices)
    - [Tensors](#mathematicallinearalgebra-tensors)
    - [Vector Space](#mathematicallinearalgebra-vectorspace)
    - [eigenvalues and eigenvectors](#mathematicallinearalgebra-eigen)
    - [Cartesian Coordinate System](#mathematicallinearalgebra-cartesian)
    - [Matrix Decomposition](#mathematicallinearalgebra-matrixdecomposition)
    - [Tensor Decomposition](#mathematicallinearalgebra-tensordecomposition)
    - [Structural Geometry](#mathematicallinearalgebra-structural-geometry)
    - [Factorial](#mathematicallinearalgebra-factorial)
- [PROBABILITY AND STATISTICS](#mathematicalprobabilitystatistics)
    - [Probability](#mathematicalprobabilitystatistics-probability)
    - [Rules of probability](#mathematicalprobabilitystatistics-rulesprobability)
    - [Mean](#mathematicalprobabilitystatistics-mean)
    - [Median](#mathematicalprobabilitystatistics-median)
    - [Mode](#mathematicalprobabilitystatistics-mode)                 
    - [Variance](#mathematicalprobabilitystatistics-variance)
    - [Standard Deviation](#mathematicalprobabilitystatistics-standarddeviation)
    - [Random Variables](#mathematicalprobabilitystatistics-randomvariables)
    - [Probability Distribution](#mathematicalprobabilitystatistics-probabilitydistribution)
    - [Conditional Probability](#mathematicalprobabilitystatistics-conditionalprobability)
    - [Probability Density Function](#mathematicalprobabilitystatistics-probabilitydensityfunction)
    - [Cumulative Probability Distribution](#mathematicalprobabilitystatistics-cumulativeprobabilitydistribution)
    - [Sample or Sampling](#mathematicalprobabilitystatistics-sampling)
    - [Population](#mathematicalprobabilitystatistics-population)
    - [Statistical Inference](#mathematicalprobabilitystatistics-statisticalinference)
    - [Maximum likelihood](#mathematicalprobabilitystatistics-maximumlikelihood)
    - [Binomial Distribution](#mathematicalprobabilitystatistics-binomial)
    - [Normal Distribution](#mathematicalprobabilitystatistics-normal)
    - [Gaussian Distribution](#mathematicalprobabilitystatistics-gaussian)
    - [Statistical Models](#mathematicalprobabilitystatistics-statisticalmodels)
    - [Expectation Maximization](#mathematicalprobabilitystatistics-expectationmaximization)
    - [Central Limit Theorem](#mathematicalprobabilitystatistics-centrallimittheorem)
    - [Adequality](#mathematicalprobabilitystatistics-adequality)
    - [Local Minima and Maxima](#mathematicalprobabilitystatistics-localminimamaxima)                    
    - [Regression](#mathematicalprobabilitystatistics-regression)
    - [Linear Regression](#mathematicalprobabilitystatistics-linearregression)
    - [Stochastic Process](#mathematicalprobabilitystatistics-stochasticprocess)
    - [Hypothesis](#mathematicalprobabilitystatistics-hypothesis)
    - [Bayesian Probability](#mathematicalprobabilitystatistics-bayesian)
    - [Null Hypothesis](#mathematicalprobabilitystatistics-nullhypothesis)
    - [Confidence Interval](#mathematicalprobabilitystatistics-confidenceinterval)
    - [Correlation](#mathematicalprobabilitystatistics-correlation)
    - [Correlation Coefficient](#mathematicalprobabilitystatistics-correlationcoefficient)
    - [Histogram](#mathematicalprobabilitystatistics-histogram)
    - [Z-Score](#mathematicalprobabilitystatistics-zscore)
    - [Covariance](#mathematicalprobabilitystatistics-covariance)
    - [Least Square Fitting](#mathematicalprobabilitystatistics-leastsquarefitting)
    - [Posterior Probability](#mathematicalprobabilitystatistics-posteriorprobability)
    - [Bootstrapping](#mathematicalprobabilitystatistics-bootstrapping)
    - [Cross Validation](#mathematicalprobabilitystatistics-crossvalidation)
    - [Muller Theorem](#mathematicalprobabilitystatistics-mullertheorem)
- [ADVANCED PROBABILITY AND STATISTICS](#mathematicaladvancedprobabilitystatistics)
    - [Linear Regression](#mathematicaladvancedprobabilitystatistics-linearregression)
    - [Tangent](#mathematicaladvancedprobabilitystatistics-tangent)
    - [Hyperbolic Tangent](#mathematicaladvancedprobabilitystatistics-hyperbolictangent)
    - [Gompertz curve](#mathematicaladvancedprobabilitystatistics-gompertzcurve)
    - [ogee curve](#mathematicaladvancedprobabilitystatistics-ogeecurve)
    - [Sigmoid function](#mathematicaladvancedprobabilitystatistics-sigmoidfunction)
    - [Activation function](#mathematicaladvancedprobabilitystatistics-activationfunction)
    - [Generalized logistic curve](#mathematicaladvancedprobabilitystatistics-generalizedlogisticcurve)
    - [Gompertz function](#mathematicaladvancedprobabilitystatistics-gompertzfunction)
    - [Heaviside step function](#mathematicaladvancedprobabilitystatistics-heavisdestepfunction)
    - [Hyperbolic function](#mathematicaladvancedprobabilitystatistics-hyperbolicfunction)                 
    - [Logistic distribution](#mathematicaladvancedprobabilitystatistics-logisticdistribution)
    - [Logistic function](#mathematicaladvancedprobabilitystatistics-logisticfunction)
    - [Logistic regression](#mathematicaladvancedprobabilitystatistics-logisticregression)
    - [Logit](#mathematicaladvancedprobabilitystatistics-logit)
    - [Modified hyperbolic tangent](#mathematicaladvancedprobabilitystatistics-modifiedhyperbolictangent)
    - [Softplus function](#mathematicaladvancedprobabilitystatistics-softplusfunction)
    - [Smoothstep](#mathematicaladvancedprobabilitystatistics-smoothstep)
    - [Softmax function](#mathematicaladvancedprobabilitystatistics-softmaxfunction)
    - [Weibull distribution](#mathematicaladvancedprobabilitystatistics-weibulldistribution)
    - [Netoid function](#mathematicaladvancedprobabilitystatistics-netoidfunction)
    - [Monte Carlo Method](#mathematicaladvancedprobabilitystatistics-mcmc)
    - [Empirical Mean](#mathematicaladvancedprobabilitystatistics-empiricalmean)
    - [Stationary Probability Distribution](#mathematicaladvancedprobabilitystatistics-stationaryprobabilitydistribution)
    - [Empirical Measures](#mathematicaladvancedprobabilitystatistics-empiricalmeasures)
    - [McKean-Vlasov Processes](#mathematicaladvancedprobabilitystatistics-mcKeanvlasovprocesses)
    - [Nonlinear Filtering Equation](#mathematicaladvancedprobabilitystatistics-nonlinearfilteringequation)
    - [Hessian Matrix](#mathematicaladvancedprobabilitystatistics-hessianmatrix)
    - [Ising Model](#mathematicaladvancedprobabilitystatistics-isingmodel)
- [APPROXIMATION TECHNIQUE or OPTIMIZATION THEOREMS](#mathematicalapproximation)
    - [Taylor Series](#mathematicalapproximation-taylorseries)
    - [Gradient Descent](#mathematicalapproximation-gradientdescent)
    - [Newtons Theorem](#mathematicalapproximation-newtonstheorem)
    - [Newtons Law of Approximation](#mathematicalapproximation-newtonslawofapproximation)
    - [Root Finding Algorithms](#mathematicalapproximation-rootfindingalgorithms)
    - [Householder's Method](#mathematicalapproximation-householdersmethod)
    - [Rational Approximation](#mathematicalapproximation-rationalapproximation)
    - [Halleys Approximation](#mathematicalapproximation-halleysapproximation)
    - [Padé Approximation](#mathematicalapproximation-padeapproximation)
    - [Diophantine Approximation](#mathematicalapproximation-diophantineapproximation)
    - [Transcendental Number Theory](#mathematicalapproximation-transcendentalnumbertheory)
    - [Simulated Annealing](#mathematicalapproximation-simulatedannealing)
    - [Steepest Descent](#mathematicalapproximation-steepestdescent)
- [OTHER CALCULUS TOPICS](#mathematicalothercalculus)
    - [Differential Calculus](#mathematicalothercalculus-differential)
    - [Integral Calculus](#mathematicalothercalculus-integral)
    - [Propositional calculus](#mathematicalothercalculus-propositional)             
    - [Ricci Calculus](#mathematicalothercalculus-matrices)
    - [Lambda Calculus](#mathematicalothercalculus-tensors)
    - [Stochastic Calculus](#mathematicalothercalculus-stochastic)
    - [Hamiltonian Calculus](#mathematicalothercalculus-hamiltonian)
    - [Taylor's Theorem](#mathematicalothercalculus-Taylors)
	- [L'Hôpital's rule](#mathematicalothercalculus-LHopital)
- [TOPOLOGY](#mathematicaltopology)
    - [Set Theory](#mathematicaltopology-settheory)
    - [Axioms](#mathematicaltopology-axioms)
    - [General Topology](#mathematicaltopology-generaltopology)
    - [Topological Space Theory](#mathematicaltopology-topologicalspacetheory)
    - [Algebraic Topology](#mathematicaltopology-algebraictopology)
    - [Differential Topology](#mathematicaltopology-differentialtopology)
    - [Tensor Space Theory](#mathematicaltopology-tensorspacetheory)
    - [Low Dimensional Space Theory](#mathematicaltopology-lowdimensionalspacetheory)
    - [Knot Theory](#mathematicaltopology-knottheory)
    - [Continuous Functions](#mathematicaltopology-continuousfunctions)
    - [Homeomorphisms](#mathematicaltopology-homeomorphisms)
    - [Klein Bottle](#mathematicaltopology-kleinbottle)
    - [Topological Invariants](#mathematicaltopology-topologicalinvariants)
    - [Topological Data Analysis](#mathematicaltopology-topologicaldataanalysis)
    - [Proximity Parameters](#mathematicaltopology-proximityparameters)
    - [Betti Number](#mathematicaltopology-bettinumber)
    - [Persistent Homology](#mathematicaltopology-persistenthomology)
    - [Klein bottle](#mathematicaltopology-kleinbottle)
- [TYPES OF MECHANICS FOR MATHEMATICS AND MACHINE LEARNING](#mathematicalmechanics)
    - [Analytical mechanics](#mathematicalmechanics-analyticalmechanics)
    - [Lagrangian mechanics](#mathematicalmechanics-lagrangianmechanics)
    - [Hamiltonian mechanics](#mathematicalmechanics-hamiltonianmechanics)
    - [Routhian mechanics](#mathematicalmechanics-routhianmechanics)
    - [Koopman–von Neumann mechanics](#mathematicalmechanics-koopmanvonneumannmechanics)
- [FACTORIAL](#mathematicalfactorial)
    - [Gamma Function](#mathematicalfactorial-gammafunction)
- [MEETUPS](#mathematicalmeetups)
- [GOOGLE GROUPS](#mathematicalgroups)
- [COMPANIES DOING PRODUCTS](#mathematicalcompanies)
- [LINKEDLIN GROUPS](#mathematicallinkedlin)
- [DEGREES](#mathematicaldegrees)
- [CONSOLIDATED BOOKS](#mathematicalconsolidatedbooks)
- [CONSOLIDATED VIDEOS](#mathematicalconsolidatedvideos)
- [CONSOLIDATED Reserach Papers](#mathematicalconsolidatedresearchpapers)
- [CONSOLIDATED Reserach Scientist](#mathematicalconsolidatedresearchscientist)
                                                                   

<!-- /MarkdownTOC -->

### License

[![License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/LICENCE)

### Dedicated Opensources

[![Dedicated Opensources](http://livingintown.com/wp-content/uploads/sites/1112/2015/03/coming-soon-small.jpg)]()
                                                                  
* Source code of plenty of Algortihms in Image Processing , Data Mining ,etc in Matlab, Python ,Java and VC++ Scripts
* Good Explanations of Plenty of algorithms with flow chart etc
* Comparison Matrix of plenty of algorithms

### Contribution

<a href="https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/contribution.md"><img src="http://comps.canstockphoto.com/can-stock-photo_csp23653568.jpg" align="left" height="200" width="200"></a>
