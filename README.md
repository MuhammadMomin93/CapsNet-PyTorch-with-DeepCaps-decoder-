# Details
PyTorch implementation of CapsNet but using the class independent decoder from DeepCaps.
We have used this implementation in generating results for the unpublished paper "Do Capsule Networks need Routing?" which can be accessed here: https://drive.google.com/file/d/1UUw3BhJrKGyXeAPd3rYGUR79rBqI8kiA/view?usp=sharing
# Experiements
This implementation is used to explore the effect of dynamic routing in the original CapsNet paper [1]. Experiments include:
1. How does training effect the distribution of routing weights?
2. How does sparsity of the routing weights evolve with training?
3. Does training a network with equal routing weights (no routing) result in object capsules that agree with the predictions made by part capsules?

# Results
Our results have shown that if we assign equal routes

# References
[1] Sabour, Sara, Nicholas Frosst, and Geoffrey E. Hinton. "Dynamic routing between capsules." Advances in neural information processing systems. 2017.
