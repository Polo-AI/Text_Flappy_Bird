# Text_Flappy_Bird
Individual Assignment in Reinforcement Learning Class at CentraleSupelec, MSc in Data Science & Business Analytics

# About the Project
For this assignment, the goal was to implement two agents to try to solve the Text Flappy Bird Environment provided at https://gitlab-research.centralesupelec.fr/stergios.christodoulidis/text-flappy-bird-gym/-/tree/master. I chose to implement a Q-Learning agent as well as a SARSA agent, and managed to train both of them to beat the game and yield potentially infinite scores. 

# Instructions
The goal of this assignment is to apply reinforcement learning methods to a simple game called Text Flappy Bird (TFB). The game is a variation to the well know Flappy Bird in which the player is made with a simple unit-element character as can be seen in Figure 1.

![image](https://user-images.githubusercontent.com/103437814/229241093-6bb8aacc-4e7b-493b-b419-d21d0dc82ad0.png)

The environment is already implemented and can be found at the Text Flappy Bird Gym Gitlab. Instructions on how to use it can also be found at the same repository. There are two available versions of the environment, one that returns as an observation the complete screen render of the game (TextFlappyBird-screen-v0 ) and another one that returns the distance of the player from the center of the closest upcoming pipe gap (TextFlappyBird-v0 ) along the two axes (x, y). Within the scope of this assignment you are asked to implement and compare two agents that can solve the TextFlappyBird-v0 environment. Feel free to use any algorithm that is presented in the book of Sutton and Barto 2.
