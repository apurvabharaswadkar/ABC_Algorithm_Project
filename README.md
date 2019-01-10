# ABC_Algorithm_Project
Heuristic algorithms have been developed to solve numerical optimization problems for multivariable and multimodal functions. In artificial intelligence and computer science, heuristic algorithms are the techniques to find out approximate solution when classic methods fail to find exact solutions. These algorithms can be classified into population based, stochastic, iterative based, deterministic. 
Artificial Bee Colony (ABC) is one of the most recently defined algorithms by Dervis Karaboga in 2005, motivated by the intelligent behavior of honey bees. The model consists of three essential components: employed and unemployed foraging bees, and food sources. The first two components, employed and unemployed foraging bees, search for rich food sources, which is the third component, close to their hive. The model also defines two leading modes of behavior which are necessary for self-organizing and collective intelligence: recruitment of foragers to rich food sources resulting in positive feedback and abandonment of poor sources by foragers causing negative feedback.

Motivation for the project
ABC as an optimization tool provides a population-based search procedure in which individuals called foods positions are modified by the artificial bees with time and the bee’s aim is to discover the places of food sources with high nectar amount and finally the one with the highest nectar. 
The purpose of the Project is to check the effects of control parameters of artificial bee colony algorithm (ABC) on the performance of ABC algorithm. There are different control parameters that define if the artificial bee colony algorithm will find optimized solutions for multivariable and multimodal functions. Therefore, it is necessary to study the effects of control parameter change on the performance of ABC algorithm. The performance of ABC algorithm can be compared by allowing the user to easily change the control parameters like the MCN (Maximum cycle number), the initial randomly distributed population solutions (SN) and the limit. Also, the algorithm should be tested using some benchmark functions that check the exploring and exploiting capabilities of the algorithm. There are various benchmark functions available that can check whether the algorithm gets trapped in local minima or if dimensions of the benchmark function affects its performance.

Test functions are important to validate and compare the performance of optimization algorithms. Ideally, test functions should have diverse properties so that these functions can be truly useful to test new algorithms in an unbiased way. The three benchmark functions used to test the ABC algorithm are unconstrained optimization problems with diverse properties in terms of modality, separability, and valley landscape.
 A function with more than one local optimum is called multimodal. These functions are used to test the ability of an algorithm to escape from any local minimum. If the exploration process of an algorithm is poorly designed, then it cannot search the function landscape effectively. This, in turn, leads to an algorithm getting stuck at a local minimum. 
Another group of test problems is formulated by separable and non-separable functions. A function of p variables is called separable, if it can be written as a sum of p functions of just one variable. On the other hand, a function is called non-separable, if its variables show inter-relation among them or are not independent.  The aim is to check if the algorithm can find optimum solutions for the non-separable functions.
The dimensionality of the search space is an important issue with the problem. As the number of parameters or dimension increases, the search space also increases exponentially. For highly nonlinear problems, this dimensionality may be a significant barrier for almost all optimization algorithms. Another problem that algorithms may suffer is the scaling problem with many orders of magnitude differences between the domain and the function hyper-surface. The global optimization problems are often defined as minimization problems; however, these problems can be easily converted to maximization problems.
 	The three test benchmark functions used in implementation are:

Alpine 1 Function: Continuous, Non-Differentiable, Separable, Non-Scalable, Multimodal.
The global minimum is located at origin x = (0, · · · , 0),  f(x) = 0.
	f(x) =          

Sphere Function: Continuous, Differentiable, Separable, Scalable, Multimodal
The global minima is located x = f(0, · · · , 0), f(x ) = 0.
	f(x) = 

Styblinski-Tang Function:  Continuous, Differentiable, Non-Separable, Non-Scalable, Multimodal.
The global minimum is located x = f(−2.903534, −2.903534), f(x) = −78.332                                               
f(x) = 

The control parameters for ABC algorithm are NP (total population), limit and MCN (maximum cycle number). The performance of the ABC algorithm was checked for the three benchmark functions using four control parameter sets.
Set 1: NP =50, limit =100, MCN =3000
Set 2: NP =50, limit =100, MCN =100
Set 3: NP =200, limit =100, MCN =100
Set 4: NP =200, limit =10, MCN =1000

From the graph plotted, it is clear that the performance of ABC algorithm mainly depends on the value of MCN. The higher the value of MCN, the better is the performance of ABC Algorithm. If the MCN value is set higher, then the ABC algorithm discovers the global minimum of the objective function used for optimization problem.

The code is in python and written in jupyter notebook

