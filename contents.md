### Abstract

1. Deep Neural Network is good
2. Training Deep Neural Network needs good performance and energy efficiency
3. Previous work focus on inference. We can take their ideas to training
4. But we are faced with challenges.
4. We propose a new training method and corresponding architecture

### Introduction

1. Deep Neural Network is good
2. Training Deep Neural Network needs good performance and energy efficiency
3. FPGA has been widely adopted in data center, we need to use them
4. Previous FPGA inference accelerators have adopted good SW-HW co-design ideas but not used in training yet
5. Using these ideas is challenging but we solve these challenges in this paper
6. The structure of this paper.

### Related Work

1. neural network, the power and time cost of training
2. Previous work on training, FPT, FCCM, ASAP
3. Previous work on inference

### Training Neural Network

1. Gradient descent
2. The operations in neural network training

### Training a Simplified Network

1. Quantization
2. Pruning

### Hardware Design

1. System structure
2. sparse kernel
3. compressed sparse block
4. Scheduling*

### Experiments

1. Training result
2. Hardware performance

### Conclusion