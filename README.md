# controls-project

### Study of PI based stochastic optimal control and Implementation of MPPI for Aggressive Driving

<div align='center'>
  <img src="https://raw.githubusercontent.com/vvrs/MPPIController/master/matlab_implementation/res/anim.gif"/>
</div>


This project was submitted as a course project for RBE502 - Robot Control  in Spring 2018 at Worcester Polytechnic Institute. 

Course page - [https://users.wpi.edu/~jfu2/rbe502/index.html](https://users.wpi.edu/~jfu2/rbe502/index.html)

The project is to conduct a study on Model Predictive Path Integral (MPPI) Control and implement the same for aggressive driving for a car-like robot. This is primarily based on work presented in 

- [Aggressive driving with model predictive path integral control](https://ieeexplore.ieee.org/document/7487277/)
- [Model Predictive Path Integral Control: From Theory to Parallel Computation](https://arc.aiaa.org/doi/abs/10.2514/1.G001921)
- [Information Theoretic Model Predictive Control: Theory and Applications to Autonomous Driving](https://arxiv.org/abs/1707.02342)

For more details on the work, check this [report](https://github.com/vvrs/MPPIController/tree/master/report/report_MPPI.pdf).
<br>

#### How to run
---------------

change directory to `matlab_implementations/` in MATLAB and execute `MPPI_Pendulum.m`

```matlab
MPPI_Pendulum.m
```

<br>

#### Result
-----------

<div align='center'>
  <img src="https://raw.githubusercontent.com/vvrs/MPPIController/master/matlab_implementation/res/states.png"/>
</div>


#### References
-----------
```
  @INPROCEEDINGS{7487277, 
                author={G. Williams and P. Drews and B. Goldfain and J. M. Rehg and E. A. Theodorou}, 
                booktitle={2016 IEEE International Conference on Robotics and Automation (ICRA)}, 
                title={Aggressive driving with model predictive path integral control}, 
                year={2016}, 
                volume={}, 
                number={}, 
                pages={1433-1440}, 
                keywords={control engineering computing;graphics processing units;importance sampling;nonlinear control systems;optimal control;predictive control;road traffic control;road vehicles;GPU;aggressive driving;cost criteria;fifth-scale auto-rally vehicle;free energy notion;graphics processing unit;importance sampling scheme;information theoretic notion;model predictive path integral control;nonlinear systems optimization;relative entropy notion;stochastic optimal control framework;Entropy;Optimal control;Prediction algorithms;Q measurement;Stochastic processes;Trajectory;Vehicles}, 
                doi={10.1109/ICRA.2016.7487277}, 
                ISSN={}, 
                month={May},
                }

  @article{    Williams2017a,
                author = {Williams, Grady and Aldrich, Andrew and Theodorou, Evangelos A.},
                doi = {10.2514/1.G001921},
                file = {Ltd./Mendeley Desktop/Downloaded/Williams, Aldrich, Theodorou - 2017 - Model Predictive Path Integral Control From Theory to Parallel Computation.pdf:pdf},
                issn = {0731-5090},
                journal = {Journal of Guidance, Control, and Dynamics},
                number = {2},
                pages = {344--357},
                title = {{Model Predictive Path Integral Control: From Theory to Parallel Computation}},
                url = {http://arc.aiaa.org/doi/10.2514/1.G001921},
                volume = {40},
                year = {2017}
                }

  @article{     DBLP:journals/corr/WilliamsDGRT17,
                author    = {Grady Williams and
                             Paul Drews and
                             Brian Goldfain and
                             James M. Rehg and
                             Evangelos A. Theodorou},
                title     = {Information Theoretic Model Predictive Control: Theory and Applications
                             to Autonomous Driving},
                journal   = {CoRR},
                volume    = {abs/1707.02342},
                year      = {2017},
                url       = {http://arxiv.org/abs/1707.02342},
                archivePrefix = {arXiv},
                eprint    = {1707.02342},
                timestamp = {Sat, 05 Aug 2017 14:56:10 +0200},
                biburl    = {https://dblp.org/rec/bib/journals/corr/WilliamsDGRT17},
                bibsource = {dblp computer science bibliography, https://dblp.org}
              }
```
