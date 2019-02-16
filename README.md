# Content: Deep Reinforcement Learning
## Project: Training a Quadcopter through DDPG Algorithm

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Keras](https://keras.io/)
- [Math](https://docs.python.org/3/library/math.html#module-math)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Quadcopter Project.ipynb
```  
or
```bash
jupyter notebook Quadcopter Project.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Project

Implement a Deep Deterministic Policy Gradients Algorithm to train a quadcopter (quadrotor helicopter) to land safely from an elevated starting position.  Utilizing Keras to build out an Actor-Critic Neural Network model to perform policy and value updates with experiences sampled form a replay buffer.
