# Project swergio

The goal of this project is to automate the process and production of analytics for small data sets. These are the key ideas to achieve this ambitious target:

### We want more....
It is very difficult for one person to know everything and be able to produce all possible analysis. But in teams, people can complement each other strength to master obstacles easier. swergio is built on the concept of the collaboration of separate AI agents. Therefore not every agent needs to be perfectly trained to know all the answers, but can rather be specialized for a few manageable tasks.

### Communication is key
Solving problems in a team without communication isn't possible. swergio AI agents need a clear communication protocol to work efficiently together.
To make the communication in the network easy to access and ready to receive human input and feedback, we want our AI agents to understand and use natural language.  

### Never stop learning
Is it really possible to standardize analytics? Can a solution be defined in a static way? Expectations are changing, components are heavily influenced by outside factor and there isn't always just the one "right" answer. We want our agents to be flexible and adaptable in various situation. Rather find a new way and approach than a standardized solution.
To achieve this goal the swergio AI agents must be able to learn continually and optimize their strategies. Our approach is to use reinforcement learning methods and immediate feedback from clients and other agents in the network. 

### "Questions?!"
Asking questions is essential for learning new things or working in uncertain areas. It is often easier to ask an expert then try and fail on your own. 
Using natural language as communication protocol should enable AI agents to ask experts (humans or other AIs) to clarify uncertainties and improve the learning curve.

###  Easy like Sunday morning
The swergio network should be easy to use and flexible enough for multiple problems and settings.
As each component can be started in a separate docker container, the network itself is just a docker swarm. This approach allows a quick setup as well as possible extensions of a running network at any time. 
To start a simple example network look at this docker-compose file.

## Current progress and outlook
[x] Communication Protocol for separate components
[x] Simple example implementation for possible client and worker
[x] Example agent using A2C reinforcement learning and VAE-GAN approach
[] Fully trained example swergio network
[] Easier way to implement expert trajectories

## References
This project is influenced by several code snippets, libraries, publications and blog posts.
These sources and ideas we've been using for code snippets, implementation, and inspiration.

Tensorflow  - https://www.tensorflow.org/
Flask-SocketIO - https://github.com/miguelgrinberg/Flask-SocketIO

###### A2C Model
Publication - https://arxiv.org/abs/1602.01783
Example implementation in Open AI's  baselines library - https://github.com/openai/baselines

###### Least Squares GAN (LSGAN)
Publication - https://arxiv.org/abs/1611.04076v2
Blog Post with explanation and implementation  from Augustin Kristiadi - https://wiseodd.github.io/techblog/2017/03/02/least-squares-gan/

###### MemN2N Model
Publication - https://arxiv.org/abs/1503.08895v4
Example implementation -https://github.com/carpedm20/MemN2N-tensorflow

###### VAE-GAN
Publication - https://arxiv.org/pdf/1512.09300.pdf
Example implentation - https://github.com/timsainb/Tensorflow-MultiGPU-VAE-GAN 

###### Seq2Seq Model 
Explanation and example implementation in tutorial for  tensorflow - https://github.com/tensorflow/nmt
