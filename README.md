GENERAL DESCRIPTION

This repository hosts a project developed for the 'Collective Intelligence' course, focusing on the application of Multi-Agent Reinforcement Learning. The core objective of this project is to simulate a simplified version of a warehouse packing operation. It involves two agents whose tasks are to locate a box and then determine the most efficient route to the delivery area. To achieve this, the project incorporates two key reinforcement learning algorithms: Proximal Policy Optimization (PPO) and Linear Q-learning. These methods have been implemented to enable the agents to make intelligent decisions and improve their performance over time. This project serves as an educational exploration into the capabilities and practical applications of Multi-Agent Reinforcement Learning in a controlled environment.


INSTALLATION 

1. Clone the Repository
    Begin by clonning the repository to your local machine. Open your terminal and execute the following command: 
    git clone https://github.comHeqiqetEhmedMARL_collective_intelligence.git
 
2. Create an Anaconda ENvironment
    Using Anaconda, create a new environment named pygame_env. This can be accomplished by executing the command below in your Anaconda terminal:
    "conda create --name pygame_env" 

3. Activate the Environment
    Once the environment is created, activate it using 
    "conda activate pygame_env"
4. Navigate to the Installation Folder
    Change your current directory to the RLsnake Installation folder within the cloned repository.

5.  Install Dependencies
    Install the required dependencies by running the following command in the terminal. This will install all the necessary packages as specified in the requirements.txt file located in the root folder of the project:
     pip install -r requirements.txt

6. Run the Learning Program using the "python agent.py" command in the root folder


Known Issues
Agent Navigation Post-Target Acquisition: Agents currently struggle with efficiently navigating to the drop zone after picking up the target.

Proposed Enhancements
Multi-Box Environment: Introducing an environment with multiple targets to enhance complexity and learning opportunities for the agents.
