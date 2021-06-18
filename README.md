# 20195034--MinwooKim
This is a repository for implementing multi-agent deep reinforcement learning task.
The training environment originally belongs to [here](https://github.com/Bigpig4396/Multi-Agent-Reinforcement-Learning-Environment.git). 
### OS
- Ubuntu 18.04
- pytorch version over 1.2.0
- matplotlib

### Training Environment
The default number of agents and targets are **5** and **20**.
Note that if there are too little targets, the algorithm has difficulty in finding a proper policy.
Too frequent `model evaluation check` can increase the learning time.
You could change the learning parameters in `arguments.py`. For example,
- You could change the number of agents from using the command `--num-drones`
- You could change the view range using the command `--view-range`

### Implementation
For implementation of each code, go to the directory of the algorithm.
Run the code through `python3 main.py`.

### Log history
You could check the history of the learning algorithm in the `log` directory.
Type the command `tensorboard --logdir={name of the log directory}`.

### Saving models
The default location of the saved model is not speficifed. 
You could change the saved_model directory using the arguments `--model-dir={Location where you want}`.
