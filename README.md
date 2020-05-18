# Goal 

Project is initiated as of May, 2020. 

wise.sim is in development stage.

wise.sim is a game simulation environment to: 
* develop and verifiy game design with simulation implementation 
* use reinforcement learning to enhance game mechanics 
* load-test server with protocol plugin 


## Architecture 

* use Unreal Engine 4 (UE4, here after) for visual rendering and processing
* use python for simulation and loadtest 


## Roadmap 

* research and integrate machine learning libraries 
  * RLLib 
* make python a script language for game play of UE4 
* build pipelines for :
  * simulation development 
  * RL 
  * loadtest


### Research: RLLib 

RLLib seems to be a good library to learn reinforcement learning with hands-on practicing. 
It is integrated with OpenAI Gym and has Ray and Tune for distributed learning and hyperparameter tuning. 

Experience and experiments are important to have concrete and actual skills to handle NN for RL to solve RL problems. 

The idea is to replace OpenAI Gym to UE4 as an environment to make the overall environment and visual effects be more like games or games. 

### python in UE4 

UE4 has python support as a scripting language, but in editor only. There are other efforts to bring python to UE4 for scripting game play. 

Research those ideas and build a full interface and environment to develop application and games in python. This is the first big step. 


