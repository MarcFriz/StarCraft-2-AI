# StarCraft-2-AI

## Overview 
This code will use the open Blizzard API, tensorflow and Baselines OpenAI for a reinforcement learning agend. The agend will rund some minigames in StarCraft 2.

## Dependencies
- pysc2 (Deepmind)
- baselines (OpenAI)
- s2client-proto (Blizzard)
- Tensirflow (Google)

Maybe you will need some other dependencies to run other minigames.

## Usage
#### Tensorflow
Bevor you can use the code you have to create a environment for tensorflow.
The Homepage from tensorflow will guide you through the installation:
[Tensorflow Homepage](https://www.tensorflow.org/install/)

#### Dependencies
The easiest way to get the dependencies is to use pip.
For example:
```
$ pip install pysc2
``` 

## Train
Train your model:
```
$ python train_mineral_shards.py
``` 

## Environment 
I used Visual Studio with python to get my code running.

## Credits
Credits for the basic of this code go to [chris-chris](https://github.com/chris-chris) and [Siraj](https://github.com/llSourcell).
I fixed the open Issues and make it running in Visual Studio.
Further minigames will be developed by me.
