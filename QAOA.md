# QAOA Literature Manager


<details>
<summary><font color=DarkTurquoise>A Quantum Qpproximate Optimization Algorithm</font>

[arXiv: 1411.4028v1](https://arxiv.org/abs/1411.4028v1)   
**Author**: Edward Farhi and Jeffrey Goldstone  
**Date**: 14 Nov 2014 
</summary>
 
**Abustract**: 
We introduce a quantum algorithm that produces approximatesolutions for combinatorial op-timization problems. The algorithm depends on an integer $p\geq1$ and the quality of the approx-imation improves aspis increased. The quantum circuit that implements the algorithm consistsof unitary gates whose locality is at most the locality of theobjective function whose optimum issought. The depth of the circuit grows linearly withptimes (at worst) the number of constraints.Ifpis fixed, that is, independent of the input size, the algorithm makes use of efficient classical pre-processing. Ifpgrows with the input size a different strategy is proposed. We study the algorithmas applied to MaxCut on regular graphs and analyze its performance on $2$-regular and $3$-regulargraphs for fixedp. For $p=1$, on $3$-regular graphs the quantum algorithm always finds a cut thatis at least $0.6924$ times the size of the optimal cut.  

**Note**:   
[Combined optimization problem](https://en.wikipedia.org/wiki/Combinatorial_optimization)  

[Quantum optimization algorithm](https://en.wikipedia.org/wiki/Quantum_optimization_algorithms)

<font color=cornflowerblue> Some instance </font>

</details>  


<details>
<summary><font color=DarkTurquoise>A Quantum Approximate Optimization Algorithm Applied to a Bounded Occurrence Constraint Problem</font>  

[arXiv: 1412.6062v2](https://arxiv.org/abs/1412.6062v2)   
**Author**: Edward Farhi and Jeffrey Goldstone  
**Date**: 25 Jun 2015 
</summary>

**Abustract**: We apply our recent Quantum Approximate Optimization Algorithm to the combinatorialproblem of bounded occurrence Max E3LIN2. The input is a set of linear equations each of whichcontains exactly three boolean variables and each equationsays that the sum of the variables mod $2$ is $0$ or is $1$. Every variable is in no more thanDequations. A random string will satisfy 1/2of the equations. We show that the level one QAOA will efficiently produce a string that satisfies $\Big(\frac{1}{2}+\frac{1}{101 D^{1/2}ln D}\Big)$ times the number of equations.  A recent classical algorithm achieved $\Big(\frac{1}{2}+\frac{constant}{D^{1/2}}\Big)$ . We also show that in the typical case the quantum computer will output a stringthat satisfies $\Big(\frac{1}{2}+\frac{1}{2\sqrt{3e} D^{1/2}}\Big)$ times the number of equations.

**Note**:
</details> 

<details>
<summary><font color=DarkTurquoise>Performance of QAOA on Typical Instances of
Constraint Satisfaction Problems with Bounded Degree</font>

[arXiv: 1601.01744](https://arxiv.org/pdf/1601.01744.pdf)    
**Author**: Cedric Yen-Yu Lin and Yechao Zhu  
**Date**: 8 Jan 2016
</summary>

**Abstract**: We consider constraint satisfaction problems of bounded degree, with a good notion of "typicality", e.g. the negation of the variables in each constraint is taken independently at random. Using the quantum approximate optimization algorithm (QAOA), we show that $\mu+\Omega(1/\sqrt{D})$ fraction of the constraints can be satisﬁed for typical instances, with the assignment eﬃciently produced by QAOA. We do so by showing that the averaged fraction of constraints being satisﬁed is $\mu + \Omega(1/\sqrt{D})$, with small variance. Here $\mu$ is the fraction that would be satisﬁed by a uniformly random assignment, and D is the number of constraints that each variable can appear. CSPs with typicality include Max-kXOR and Max-$k$SAT. We point out how it can be applied to determine the typical ground-state energy of some local Hamiltonians. We also give a similar result for instances with "no overlapping constraints", using the quantum algorithm. We sketch how the classical algorithm might achieve some partial result.  
</details>

<deltails>
<summary><font color=DarkTurquoise>





