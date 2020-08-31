AI Learns To Walk
Introduction-
	This document is the report of small project " Al learns how to walk" .The project is an attempt to design a training game through neat algorithm .NEAT (NeuroEvolution of Augmenting Topologies) is an evolutionary algorithm that creates artificial neural networks.We had used OpenAl gym environment "Bipedalwalker-V3" .OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like pong or pinball. Gym provides an environment and its is upto us to implement any learning algorithms.

Knowledge Needed-
•	Python
•	NEAT(Neuroevolution of Augmenting Topologies)
•	OpenAIGym
•	Box2D
•	Deep Neural Networks


What we did for implementing- 
We learned NEAT(NEAT: An Awesome Approach to NeuroEvolution) and other technologies. We then found the best way to test our NEAT module will be on OpenAiGym Box2D environments(https://gym.openai.com/envs/#box2d). We tried our module on the "Bipedalwalker-v3" Environment of Box2D and optimize it and train it until we got the reward of +300 points. We trained the bipedal walker such that if it falls it dies and for every positive step forward we give reward and negative points for moving backward. We synced the parameters that we obtain from the BipedalWalker-v3 environment and achieved it.

 



How’s it going?
The gym bipedal walker completed its track with a reward of 300 in 35 seconds.

Source to your code-
https://drive.google.com/drive/folders/1QGDI3Qf8sWXRwTuwxy9IIjM5dG1ksV3w?usp=sharing

References
•	https://github.com/sroj/neat-openai-gym
•	http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf
