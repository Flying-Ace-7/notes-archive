
Part Of: [[Math MOC]]



### Example:
John has 2 apples, labeled A and B and three oranges, labeled 1,2,3. How many different ways in which can he can eat  1 apple and then  1 Orange?

-> **Lets Break down the question**:
- John can choose one apple, and orange
- There are 2 ways to choose an apple.
- There are 3 ways to choose an Orange.
-> Lets draw a diagram, shall we?


```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.9.5 - 14.57pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
There are 2 different ways of performing the first actions $m$, and 3 ways of performing the second actions $n$ . We see that in total, there are 6 different ways in which we can perform these actions in succession.

These actions are **Independant**, choosing an apple does not choose how you choose the orange.

The Total number of ways to perform $n$ number of independant actions, where $n_i$ is the number of ways to perform the ith action is:
$$
n_{1} \times n_{2}\dots \times n_{i}
$$


OR Defined as probability.

$$
P( A / B)=\frac{P(A\cap B)}{P(B)}
$$
Where $P(A/B)$ is the probability of A occuring after B
If Events A and B are independant, 
$$
P(A \cap B)= P(A) \times P(B)

$$
SO, $P(A/B)= P(A)$, seeing that B doesn't affect A




