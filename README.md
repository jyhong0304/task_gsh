# Task-specific Geometric Sensitive Hashing (T-GSH)

<p float="left">
  <img src="figures/generating_process.png" alt="generating_process" width="13%"/>
  <img src="figures/task_specific_geometric_hash.png" alt="task_specific_geometric_hash" width="85%" />
</p>

This repository is the official implementation of [task-specific geometric sensitive hashing](https://openreview.net/forum?id=EHvgtRcrix)

## Abstract
Geometric Sensitive Hashing functions, a family of Local Sensitive Hashing functions, are neural network models that
learn class-specific manifold geometry in supervised learning. However, given a set of supervised learning tasks,
understanding the manifold geometries that can represent each task and the kinds of relationships between the tasks
based on them has received little attention. We explore a formalization of this question by considering a generative
process where each task is associated with a high-dimensional manifold, which can be done in brain-like models with
neuromodulatory systems. Following this formulation, we define *Task-specific Geometric Sensitive Hashing* and show
that a randomly weighted neural network with a neuromodulation system can realize this function.

## Experiments
* **RotationMNIST**: See ```FlyNet - RotationMNIST.ipynb```
* **ShiftMNIST**: Code will be posted soon :)
* **AugmentMNIST**: Code will be posted soon :)

## Acknowledgement
Our work is based on:
* [For Manifold Learning, Deep Neural Networks can be Locality Sensitive Hash Functions](https://arxiv.org/abs/2103.06875)
* [Learning to Modulate Random Weights: Neuromodulation-inspired Neural Networks For Efficient Continual Learning](https://arxiv.org/abs/2204.04297)

## Reference
You can cite this:
```
@inproceedings{hong2023randomly,
 author = {Jinyung Hong and Theodore P. Pavlic},
 booktitle = {UniReps:  the First Workshop on Unifying Representations in Neural Models},
 title = {Randomly Weighted Neuromodulation in Neural Networks Facilitates Learning of Manifolds Common Across Tasks},
 url = {https://openreview.net/forum?id=EHvgtRcrix},
 year = {2023}
}
```
