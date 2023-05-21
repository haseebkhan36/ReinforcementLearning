# ReinforcementLearning
We used to train an agent in highway environment for Merge , roundabout and parking agent . we can train the agent for more actions from https://github.com/Farama-Foundation/HighwayEnv 

### Car RL : 
A collection of environments for autonomous driving and tactical decision-making tasks
![highway-env1](https://github.com/haseebkhan36/ReinforcementLearning/assets/43695086/5cb5981f-8099-4874-8b13-3a3d1ad8633e)

## Highway Environment 
use pip install highway-env to install this environment 
### Highway 
environment = gymnasium.make("highway-v0")

The vehicle is operating in this task on a multilane roadway that is congested with other cars. The agent's goal is to accelerate quickly while avoiding collisions with other nearby cars. Additionally advantageous is driving on the right side of the road.

![highway-env1](https://github.com/haseebkhan36/ReinforcementLearning/assets/43695086/f8a5e979-acb6-4788-86d9-5390152040cf)

### Merge 
Use  environment = gymnasium.make("merge-v0")
The vehicle begins on a major thoroughfare but soon reaches a road intersection with approaching automobiles on the access ramp. The agent must now maintain a fast speed while leaving space for the cars so that they may integrate into the traffic in a secure manner.

![merge-env 1](https://github.com/haseebkhan36/ReinforcementLearning/assets/43695086/32656276-5fce-4c1c-bb2d-4bb6bfd18777)

### Roundabout 
use environment = gymnasium.make("roundabout-v0")
vehicle is moving towards a roundabout where traffic is moving. It will automatically follow its intended course, but it must manage lane changes and longitudinal control to go through the roundabout as quickly as possible without hitting anything.
![roundabout-env 1](https://github.com/haseebkhan36/ReinforcementLearning/assets/43695086/6cc6ffe9-4208-462a-860c-52bba33267e7)

### parking Agent 
use environment = gymnasium.make("parking-v0")
a continuous control job with an objective that requires the ego-vehicle to park in the designated spot under the correct heading.
![parking-env 1](https://github.com/haseebkhan36/ReinforcementLearning/assets/43695086/21627d7c-5c5f-4104-b8a3-673fbb3a2cff)

