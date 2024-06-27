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

3D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/1939eda4-f0dd-401f-8976-46da8f6d745a)
![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/5075d4ba-8098-4f9e-8a02-1c25f5fac051)

Diversity Metric: A measure used to assess the variety or heterogeneity within a set of items, ensuring that outputs are varied and not redundant.

Mode Collapse Detection: The process of identifying when a Generative Adversarial Network (GAN) produces limited variations of outputs, ignoring other possible outputs.

2D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/46b36111-aa1f-456e-84bb-fc11b7243a6e)

3D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/6a8308ad-6b3a-452e-97d8-c8da976047f3)

Learning Rate Adjustment: The process of modifying the learning rate during training to improve model performance and convergence.

Convergence Metric: A measure used to determine whether a model has reached a point where further training will not significantly improve performance.

2D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/4c063cbe-f9e8-4346-9d0a-eace266b70ef)

3D FUNCTION GENERATION

![image](https://github.com/SakshiGoyal001/FunctionGeneration/assets/100338507/b6459400-8128-412b-8bcd-492c1d859e1b)




