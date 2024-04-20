# First Karpathy Vid
The idea that you can implement the functions at whichever level of abstraction that you want is great. I think that's going to be the core in understanding tinygrad.

## Questions
```python
class Value:
    def __init__(self, data, _children=()):
        self.data = data
        self._prev = set(_children)
        
```

He suggests that using set of children is for efficiency. I'm not sure why that would be the case. I guess I would remove duplicate children if you had a*a? 


### Graphviz
Looks nice, may be able to do some cool stuff

### Topological Sort
What else is this used for? 

It grabs all leaf nodes and puts them first.


### Misc
How does backprop work in the human brain

### Backward of exp
Turns out I don't know derivative of e^x
