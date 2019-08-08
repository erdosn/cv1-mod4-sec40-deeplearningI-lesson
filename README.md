
### Questions
- The various formulas that are used
- Chain Rule

### Objectives
YWBAT
- identify the parts of a neural network and explain their values
- define forward propagation in your own words
- explain the issues of multicollinearity
- explain the pros and cons of using keras

### Outline
- Prior Knowlege (10 minutes)
    - Label a neural network diagram in a slideshow
- Discuss neural networks and their purpose
- Explain the pros and cons of using keras

### Output Equation

$$ O_1 = S(W^2 \circ H^1_1)$$

But ..........

$$ O_1 = S(W^2 \circ [H^1_1, H^1_2, H^1_3, H^1_4)$$

So.....

$$ O_1 = S(W^2 \circ [H^1_1(W^1_1), H^1_2(W^1_2), H^1_3(W^1_3), H^1_4(W^1_4)]$$

$$ O_1(W^1, W^2) \implies  C(W^1, W^3) \implies y - y^{\text{hat}}(W^1, W^2)$$
 


### What is stochastic Gradient Descent?
- It's like gradient descent, but finds the parameters that minimize the cost by using many starting points
- learning rate stays the same


### ADAM (ADAptive Momentum) optimization
- learning rate changes


```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
```

### Assessment
