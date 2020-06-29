# Deep Reinforcement Learning Nanodegree

My solutions to the projects (and mini-projects) of Udacity's <a href="https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893">Deep Reinforcement Learning Nanodegree</a> program.

<img src="./gif/trained.gif">

## Chapters

🧪 Chapter 1: Introduction to Deep Reinforcement Learning<br />
Notes of Chapter 1 - <a href="#">**'Chapter1.MD'**</a>

🧪 Chapter 2: Value-Based Methods<br />
Notes of Chapter 2 - <a href="#">**'Chapter2.MD'**</a>

🧪 Chapter 3: Policy-Based Methods<br />
Notes of Chapter 3 - <a href="#">**'Chapter3.MD'**</a>

🧪 Chapter 4: Multi-Agent Reinforcement<br />
Notes of Chapter 4 - <a href="#">**'Chapter4.MD'**</a>

<hr />

## Projects


📥 <b>Project 1: Navigation</b> - <a href="#">Project 1 directory</a>

<b>Goal:</b> train an agent to navigate (and collect bananas!)<br />
<b>Reward:</b> +1 (Yellow banana) and -1 (Blue banana)<br />
<b>Actions:</b> <br />
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

<b>Environment:</b> <a href="https://github.com/udacity/deep-reinforcement-learning#dependencies">dependencies</a>, <a href="./proj1_navigation/Banana_Windows_x86_64.zip">unity banana </a><a href="https://github.com/Unity-Technologies/ml-agents">(unity-ml-agent)</a>

<img src="gif/banana.gif" height=20% >

<br /><p align="justify">The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.</p>

<b> Getting Started </b>

1. Download the environment from one of the links below.  You need to select only the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the <a href="https://github.com/udacity/deep-reinforcement-learning/">DRLND GitHub repository</a>, in the `p1_navigation/` folder, and unzip (or decompress) the file.

<b>Requirements for Udacity:</b>
- Training Code **[Navigation.ipynb]**, Framework use - PyTorch and Python 3, Saved Model Weights **[model.pt]**
- **[Report.pdf]** with Learning Algorithm, Plot of Rewards and Ideas for future Algorithm
- [Extra] Implement a double DQN, a dueling DQN, and/or prioritized experience replay!

Follow the instructions in <a href="#">Navigation.ipynb</a> to get started with training the agent! Here's my <a href="#">report</a> and here's the <a href="#">YouTube video</a> of my trained agent!

(Optional) Challenge: Learning from Pixels

<br />

📥 <b>Project 2: Continuous Control</b>

📥 <b>Project 3: Collaboration and Competition</b>
