# CoasterRacer-Bot
With the release of OpenAI Universe, a large number of environments are available to test new Reinforcement Learning algorithms. In this, I coded a bot for the famous Flashgame CoasterRacer provided by the Universe.

# Working
The whole problem is divided into two parts:
1. Whether to turn or not?
This is answered by evaluating the reward function collected in a specified interval. In case the bot is colliding (lesser rewards), it will turn.
2. Where to turn?
The choice of the direction of the turn is made randomly between left or right. 

# Dependency
* Universe - install instructions [here](https://github.com/openai/universe)
* random -  `pip install random`

# Usage
Run `python Bot.py` in terminal to run this code <br /> <br />
`OR`


1. Run `docker run -p 5900:5900 -p 15900:15900 --cap-add SYS_ADMIN --ipc host --privileged quay.io/openai/universe.flashgames:0.20.28`  (This is the image file for CoasterRacer-v0)

2. Then run `python Bot.py`

# Credit
This work was learnt from and based on the [OpenAI's official Tweet](https://twitter.com/openai/status/805843673208393728?lang=en) and [Siral Raval](https://github.com/llSourcell)

