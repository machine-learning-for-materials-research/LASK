# Low-Cost Autonomous Scientist Kit
Research into [robotic science labs](https://www.cell.com/matter/fulltext/S2590-2385%2821%2900306-4) (a.k.a. self-driving labs (SDL), autonomous research systems, etc.) involve equipment costing from tens of thousands to tens of millions of dollars. __This website is dedicated to the open-source development of the low-cost, minimum viable product for a robotic science kit.__ The kit has been published under the name [LEGO-based Low-cost Autonomous Science kit](https://link.springer.com/article/10.1557/s43577-022-00430-2) and has been used for 3 years in an annual course at UMD and is being introduced in JHU and Loyola University courses. Development is lead by a NIST-UMD collaboration.

<img src="https://github.com/machine-learning-for-materials-research/LASK/blob/main/images/Picture4.jpg?raw=true" width="500"> <br>
Left: Kit used in UMD, Right: Robotic scientist kit <br>

Robotic science places machine learning (ML) in control of automated scientific equipment, allowing ML to perform experiment design, execution, and analysis in a closed loop. The ML driving the robot must be capable of 1) analyzing data collected from past experiments, 2) predict the potential outcomes of future experiments, 3) determine the best set of experiments to perform next to hone-in on user goals. <br>

In the [publication](https://link.springer.com/article/10.1557/s43577-022-00430-2), the kit was used to learn the relationship between a mixture of acid and base (at strengths comparable to vinegar and milk of magnesium) and the resulting pH, as described by the [Henderson-Hasselbalch equation](https://en.wikipedia.org/wiki/Henderson%E2%80%93Hasselbalch_equation) (HH). [See video.](https://www.youtube.com/watch?v=TtPM7zXI5kQ) The ML tackled various separate tasks, performing the minimum number of experiements toward the following goals:
- Learn a surrogate model (Gaussian process) for the relationship between pH and acid/base ratio.
- Given the form of HH, identify the parameter values using Bayesian inference.
- Given a set of potential functions relating pH to acid/base ratio, hone-in on the correct function.
- Given no prior knowledge, discover the mechanstic model (HH eqn). Here using symbolic regression in a closed loop. <br>

The kit, as well as this website are under development. Links for the kit: <br>
[Construction](https://github.com/logansaar/LEGOLAS-Files/tree/main/Construction), including parts, sourcing, and assembly instructions. \
[Electronic setup and calibration files](https://github.com/logansaar/LEGOLAS-Files/tree/main/Setup) \
[Code](https://github.com/logansaar/LEGOLAS-Files/tree/main/Code) \
[Example course exercises](https://github.com/logansaar/LEGOLAS-Files/tree/main/Worksheets) 

For more information, please contact: A. Gilad Kusne, aaron.kusne@nist.gov
