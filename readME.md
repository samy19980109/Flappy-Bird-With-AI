# AI Playing Flappy Bird

## Using reinforcement learning (Neat_Python)
An AI that plays flappy bird! Using the NEAT python module. The NEAT python module uses deep reinforcement learning to find the optimal configuration of neural net (number and type of hidden layers) so that the birds with the best fitness continue on to the next generation. 

## Instructions
Simply run flappy_bird.py and watch an AI start training itself to play the game of flappy bird!

## How it works
the algorithm finds the best from each generation and slightly changes the values for the weights and bias. This results in similar birds to the best of the previous generation. NEAT finds for us the best neural network that will solve this problem, we just specify the number and type of input neurons and number and type of output neurons. In out case, the input neurons are:
 * Birds Y position
 * the y positionn of the top pipe
 * the y position of the bottom pipe 
and the output neurons is:
 * probability that we should jump

Our activation function is tanh, so we get a value between -1 and 1. 

