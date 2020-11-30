A [[Normed Vector Space]] $(X, \norm{\cdot})$ is a [[Metric Space]] with a [[Metric]] given by,

$$
d(x, y) = \norm{x - y}
$$

## Proof

Consider the defintion of a metric function given below

![[Metric]]

1. Point 1 is provided by the equivalent requirement of the norm.
2. Point 2 by 1.1.
3. Symmetry by:
     $$
	 \norm{x - y} = \norm{(-1)(y - x)} = |-1|\norm{y - x} = \norm{y - x}
  $$
4. Triangle inequality provided by the same on a norm.

## Properties of an induced metric

If a metric is induced by a norm it has the follow additional properties:

- **Translation invariance**: $d(x + c, y + c) = d(x, y)$.
- **Homogeneity order 1**: $d(\lambda x,\lambda y)=|\lambda|d(x,y)$.
