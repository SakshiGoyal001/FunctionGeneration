# Function Generation Using GAN 

In the ever-evolving landscape of artificial intelligence and machine learning, the demand for
large, labeled datasets for training models has become a significant bottleneck. The project at
hand addresses this challenge by harnessing the power of Generative Adversarial Networks
(GANs) to synthesize realistic data points. The specific focus is on generating synthetic data in
both 2D and 3D spaces, paving the way for innovative solutions to data scarcity issues.

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/79a0c891-a87b-4905-8aff-1bb6128a5518)

Proposed Model

Generative Adversarial Networks (GANs) represent a powerful class of machine learning
models consisting of a generator and a discriminator. The generator aims to create data
indistinguishable from real data, while the discriminator attempts to differentiate between real
and generated samples. This adversarial training process results in a generator capable of
producing high-quality synthetic data.



Model Architecture:

In the 2D case, the discriminator comprises a neural network with one input layer (2 nodes for
X and Y coordinates), a hidden layer with 25 nodes using ReLU activation, and an output layer
with a sigmoid activation for binary classification. The 2D generator includes one hidden layer
with 15 nodes using ReLU activation and an output layer with 2 nodes for X and Y coordinates.
For the 3D case, the architecture is extended to accommodate three-dimensional data, with
adjustments made to both discriminator and generator structures.


Training Procedure:

The training process spans a defined number of epochs with dynamic adjustments to the
learning rate. Discriminator and generator losses are monitored throughout the training phase.

Results and Comparison

2D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/764b8a3d-1f6b-4241-ac59-2d3e383f988d)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/12d39c0b-a4ac-4ee8-b267-800b8332da25)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/46b36111-aa1f-456e-84bb-fc11b7243a6e)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/4c063cbe-f9e8-4346-9d0a-eace266b70ef)


3D FUNCTION GENERATION


![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/1939eda4-f0dd-401f-8976-46da8f6d745a)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/2c261ad5-6305-449f-8b60-f8fbf0a6d8e6)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/5075d4ba-8098-4f9e-8a02-1c25f5fac051)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/6a8308ad-6b3a-452e-97d8-c8da976047f3)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/b6459400-8128-412b-8bcd-492c1d859e1b)
