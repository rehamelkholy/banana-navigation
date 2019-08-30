# Project 1: Navigation
--------------------------------------------------------------------------------------------------------------------------------------------
## The Environment
This project trains an agent to navigate (and collect yellow bananas, while avoiding blue ones!) in a large, square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:
- `0`: move forward.
- `1`: move backward.
- `2`: turn left.
- `3`: turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Installing Dependencies
1. Clone the repository:
`
git clone https://github.com/rehamelkholy/banana-navigation.git
`

2. Follow the instructions at [this link](https://github.com/udacity/deep-reinforcement-learning#dependencies) to install dependencies. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

__*(For Windows users)*__ The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels. 

## Downloading the Unity Environment
1. For this project, you will **not** need to install Unity - this is because the environment is already built for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


2. Then, place the file in the `p1_navigation/` folder in the DRLND GitHub repository, and unzip (or decompress) the file.


_**(For Windows users)**_ Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

## Running the Code

1. Open the Python notebook `Navigation.ipynb`.
2. Run the first cell to install dependencies for the notebook.
3. You can explore the environement in the rest of section 1, and sections 2 and 3. If you do, be sure to restart the kernel before continuing.
4. To train and evaluate an agent, just run the rest of the script (_starting from section 4_) in sequential order.
