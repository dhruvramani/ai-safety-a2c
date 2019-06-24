# A2C Implementation for AI Safety Gridworlds Environment

Just a basic implementation of A2C for AI-Safety-Gridworlds environment. Decided to make it public so that you don't have to go through the painful debugging that I had to go through. As obvious, this doesn't explicity consider any safety, and should be used as a base to improve upon. 

## Installation
Other than your standard ML/RL ammunition, you'll need to install a Gym wrapper for the original [environments](https://github.com/deepmind/ai-safety-gridworlds) by DeepMind. Thanks to [@david-lindner](https://github.com/david-lindner), 
```shell
git clone https://github.com/david-lindner/safe-grid-gym
python3 setup.py install
```
## Running
Run yo' standard old `main.py`. 

Heavily borrowed from [here](https://github.com/gitlimlab/i2a-tf).
