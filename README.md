
# Quick Start

(for ubuntu)

source .venv/bin/activate 

gymnasium

Check Cuda Version:

nvidia-smi

then check the top right corner

# Version Control

pip3 freeze > requirements.txt


With standard supervised learning for Image Net,

You have 1 millon images, you randomly select a mini batch of 64, and you make prediction

The problem I am interested in solving is that of a baby, which is born and learns to make a helpful contribution to the world.

mini-batch = 1

Each data is time-series

How can we use this to our advnatage?

Problem Statement:

RL Problem

States, Rewards, Actions

I want a policy that goes from states to actions to maximise the reward.

Actions are muscle activations = [0,1] or [-1,1]

Idea 1.

Predictive learning. (see Yan Lecunn)

- quick feedback loop (t + 1)
- Rich feedback, 1000x1000 pixels vs 1 scalar value for RL
- No human labelers (Save on $$$)
- Requires understanding of structure of data. See LLMs - "And the murderer was ..."

Big Issue is that standard neuron has no sense of time/state. 100% a neuron that has a sense of state could do awesome things. In standard supervised learning not helpful, beacuse each sample time independent. For Situatiaed agent, temporal can be a huge boost.

I want to make a change to the fundamental unit of the nueral network (for modular effects like transitor, etc.)

Nueron = wx + b

P Nueron = wx + b - pid(e)

wx + b works as an integral term

I need to add a proptional term here for fast feedback.


 Time-series data.

 There is a strong coorelation between previous prediction error and current prediction

 We are trying to track reality.

 # Principles

 Just [0-1] inputs and [-1 to 1] outputs.

 Pretraining a model using next token prediction
 Conditioning model using RL