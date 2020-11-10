## sigmoid

```
import numpy as np

def sigmoid(x)
  return 1/(1+np.exp(-x))

def sigmoid_derivative(a):
  return a*(1-a)
  
def sigmoid_derivative(z):
  a = sigmoid(z)
  return a*(1-a)
```


## softmax


## ref
- https://themaverickmeerkat.com/2019-10-23-Softmax/
