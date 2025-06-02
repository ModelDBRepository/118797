### Note from the ModelDB Administrator: the below is a snapshot of the
[authors web site](http://web.njit.edu/~matveev/calc/BCMscripts.html) on April 10th, 2009.

---

| Calcium Calculator Simulation Script Files                                                                                                 |
|--------------------------------------------------------------------------------------------------------------------------------------------|
| [CalC Download](http://web.njit.edu/%7Ematveev/calc.html) | [CalC Manual](http://web.njit.edu/%7Ematveev/calc/manual.html) | [CalC Scripts](http://web.njit.edu/%7Ematveev/calc/scripts.html) | [CalC Publications](http://web.njit.edu/%7Ematveev/calc/calc_pub.html) | [Victor's Homepage](http://web.njit.edu/%7Ematveev/) |



The scripts following below reproduce the simulation results presented
in the manuscript:

| <a href="http://web.njit.edu/%7Ematveev/" target="_top">V. Matveev</a>, <a href="http://www.math.fsu.edu/%7Ebertram/" target="_top">R. Bertram</a>, <a href="http://mrb.niddk.nih.gov/sherman/" target="_top">A. Sherman</a> (2006)
**Residual Bound Ca<sup>2+</sup> Can Account for the Effects of Ca<sup>2+</sup> Buffers on Synaptic Facilitation**
*Journal of Neurophysiology*, **96**: 3389-3397.
[ Abstract ](http://jn.physiology.org/cgi/content/abstract/00101.2006v1) [ Full Text ](http://jn.physiology.org/cgi/reprint/00101.2006v1) [ PDF ](http://web.njit.edu/%7Ematveev/documents/MatveevBertramSherman.pdf) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|


The comments in these script files
provide a detailed step-by-step
description of the simulations.

---

| File                                                                                     | Description                                                                                                                |
|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| ♦ [ode.BCM.par](http://web.njit.edu/%7Ematveev/calc/examples/Bound_Calcium_Model/ode.BCM.par) | This script file contains all ODE definitions (implementation of Eqs. 6-9). Place it in the same directory with the files below before running the infividual figure scripts. |
| ♦ [pde.BCM.par](http://web.njit.edu/%7Ematveev/calc/examples/Bound_Calcium_Model/pde.BCM.par) | This script file contains all PDE definitions (implementation of Eqs. 2-5). Place it in the same directory with the files below before running the infividual figure scripts. |
| ♦ [demo.BCM.par](http://web.njit.edu/%7Ematveev/calc/examples/Bound_Calcium_Model/demo.BCM.par) | reproduces Figures 2 and 3 of the manuscript. Use fura-2 concentration as command-line parameter. Execute `calc demo.BCM.par 0` to reproduce Fig. 2 and control data in Fig. 3. Execute `calc demo.BCM.par 400` to reproduce fura-2 data in Fig. 3. |


---

Victor Matveev
This server is running a
[Redhat](http://www.redhat.com/) distribution of
[Linux](http://www.linux.org/).

Last modified: Oct 14, 2006


---

2025-06-02: Converted README to Markdown.