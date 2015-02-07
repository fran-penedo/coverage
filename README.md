# K-Lookahead CRH controller demo

To start the demo, go to http://fran-penedo.github.io/coverage/. Source code can be found at http://github.com/fran-penedo/coverage-control-sim/. Don't report bugs, suggestions or feature requests in this repository, do so in the coverage-control-sim one.

## User Guide

- To add targets and agents, select the corresponding button and click on the canvas.
- To add obstacles, select *Add obstacles* button and click on the canvas. Each click adds a vertex (first one is not shown), close the obstacle by double clicking the canvas (which will add a last vertex).
- To select an actor, click on it while the *Select* button is active. While selected, you can remove then by clicking on the *Remove* button.
- To change actor parameters, select them, modify the parameters in the right side panel and click the *Set* button. You can also drag actors in the canvas. The right side panel for an obstacle will show a table with all vertexes. You can modify, add or remove points from the table (it will update the obstacle instantly, there's no *Set* button). Controller parameters are always shown in the right side panel and can be modified.
- To start the simulation, click the *Start* button. To toggle pause, click the *Pause* button. Clicking the *Restart* button will reset the simulation to the state right before starting it. The *Reset* button will erase the canvas.
- Hide/show the trajectories of the actors using the *Trajectories* check box. Restarting the simulation will erase the trajectories.
- To save the scenario, click the *Save* button. If the simulation has been started, the scenario will be saved in the state it had before starting the current simulation.
- To load a scenario from a file, click the *Load* button.


