Hi, Welcome to ABM4ALL!

ABM4ALL is a developing community among agent-based modelers for sharing ideas and resources. 
Currently, the projects are created and maintained by *Songmin Yu* and *Zhanyi Hou*. 

  * [Melodie](https://github.com/ABM4ALL/Melodie) - a general framework for developing agent-based models (ABMs) in Python. 
  * [MelodieStudio](https://github.com/ABM4ALL/MelodieStudio) - a package developed in parallel with **Melodie** which interacts with the `Melodie.Visualizer` module and visualizes the simulation results in the browser in real-time.
  * [tab2dict](https://github.com/ABM4ALL/tab2dict) - a detailed package for managing input data in ABMs.

To start, our [documentation](https://abm4all.github.io/Melodie/html/index.html) is the best option. The [tutorial](https://abm4all.github.io/Melodie/html/tutorial.html) section gives you a detailed explanation of the [covid_contagion](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion) model, which is a minimum example containing all the core modules provided by **Melodie** for developing agent-based models. 

* Then, for those who are familiar with Mesa or AgentPy, we also provide a [comparison](https://abm4all.github.io/Melodie/html/framework_comparison.html) between Melodie and the two packages. We prepared the code implementing the tutorial model with [Mesa](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_mesa) and [AgentPy](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_agentpy).
* Furthermore, starting from the tutorial model [covid_contagion](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion), following models are also provided with code and documentation to showcase the use of other optional modules in **Melodie**:
  * `Grid` [[code](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_grid), [doc](https://abm4all.github.io/Melodie/html/gallery/covid_contagion_grid.html)]: supports simulations where agents move and interact on a 2D discrete space. 
  * `Network` [[code](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_network), [doc](https://abm4all.github.io/Melodie/html/gallery/covid_contagion_network.html)]: supports simulations where agents interact based on a graph topology. 
  * `Visualizer` and `MelodieStudio`: visualizes the simulation results in the browser in real-time.
    * [covid_contagion_grid_visual](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_grid_visual) and [doc](https://abm4all.github.io/Melodie/html/gallery/covid_contagion_grid_visual.html)
    * [covid_contagion_network_visual](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_network_visual) and [doc](https://abm4all.github.io/Melodie/html/gallery/covid_contagion_network_visual.html)
  * `Calibrator` [[code](https://github.com/ABM4ALL/Melodie/tree/master/examples/covid_contagion_calibrator), [doc](https://abm4all.github.io/Melodie/html/gallery/covid_contagion_calibrator.html)]: auto-calibrates the model parameters to match the empirical data using Genetic Algorithm. 
  * `Trainer` [[code](https://github.com/ABM4ALL/Melodie/tree/master/examples/rock_paper_scissors_trainer), [doc](https://abm4all.github.io/Melodie/html/gallery/rock_paper_scissors_trainer.html)]: searches strategies for agents to maximize their utility using evolutionary reinforcement training.

Finally, apart from the [examples](https://github.com/ABM4ALL/Melodie/tree/master/examples) in the Melodie repo, we will also share other (probably more complicated) models developed with **Melodie**. At the moment, we have [DatingMarket](https://github.com/ABM4ALL/DatingMarket), which showcases how **tab2dict** can be used in **Melodie**. 

We really hope ABM4ALL is useful for you, and most importantly, inspires you to join the ABM community! 
