# Maze 3D Collaborative Learning on shared task

Maze 3D game from: https://github.com/amengede/Marble-Maze
Reinforcement Learning (RL) Agent: Soft Actor Critic (SAC)

(work still in progress)

### Learn the task collaboratively with the **RL agent**:

* (Recommended) create a python virtual environment
    
        python3 -m venv env
        source venv/bin/activate
        pip install -r requirements.txt
    
* Adjust the hyperparameters in the `config.yaml` file
    * Note: Discrete SAC is only compatible with the game so far
* Run 
        
        python sac_maze3d.py

* Use left and right arrows to control the tilt of the tray around its vertical(y) axis

* The goal can be set in the maze3D/utils.py file
    e.g. 
  
        #################
        goal = left_down
        ################


