# Deep Reinforcement Learning for playing Ping Pong
This code is written to teach an RL angent to play ping-pong with pictures of the game environment. (All the agent has as info is picture).

![image](https://github.com/kianfa/Deep-RL-Projects-/assets/108475427/23dea397-0f09-4f1b-977e-73ee6655a718)

## Action of Agent
Actions of agent are:


*   Up
*   Down
*   Stay

## Rewards for Agent
*   each time The agent returns the ball it will be rewarded +1
*   each time The agent can not the ball it will be rewarded -1 and the episode will be finished

by doing this The agent tries to increase the number of times it returns the ball succesfully.


# Deep learning
A CNN neural network is used for estimating each state of the game. For further information you can visit CNN with Duel Algo in https://arxiv.org/abs/1511.06581 

# train
For train you can simply click on run all sections in jupiter lab. Make sure you set the runtime type on "T4 GPU", otherwise training the agent would be so slow.

# test
rerun test section to set the parameters for showing the results.Then you can run Main section again and see how the agent reacts to the Ball.





## Some suggestions to improve the code


*   Adding a auto save of CNN parametes in Drive.
*   Making a simple GUI code which a human can play with the trained Agent.(You can remove red wall by editing Environment code a little bit)
*   Adding moving objects to the environment can increase the undeterministicity of the environmnet and this will make everything more challenging for the agent
*   Traing improvement is not illustrated by any charts. By doing this more info can be provided for users.
*   Training continues for a very long time now. I did't add any command to stop for some basic reasons... you can add a function for this 


 **Note : you can simply replace the environment part with open AI-gym ping pong environment, but by using the provide Environment code you can make desireed changes in the environment easily.**
