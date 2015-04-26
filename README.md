Expectation Maximization: 
When to use: 
1. Data is only partially observable
2. Unsupervised Clustering(target value unobservable)
3. Surpervised learning(some instance attributes unobservable)

1. Expectation Step:
2. Maximization Step

# EM-Shift-Invariant-models
Drawing procedure: At each draw the drawing process performs the following operations.

It first randomly selects one of the larger urns according to a probability distribution P(Z). Here Z represents the urn selected.
Then it selects one ball each from each of the sub-urns in the selected urn.The probability of balls in the (X,Y) sub-urn of the Zth urn is P(X,Y|Z). The probability of balls in the (X) sub-urn of the Zth urn is P(X|Z). The probability of balls in the (Y) sub-urn of the Zth urn is P(Y|Z).
Let (X1,Y1) be the numbers on the ball drawn from the (X,Y) sub-urn. Let X2 be the number on the ball drawn from the (X) sub-urn. Let Y2 be the number on the ball drawn from the (Y) sub-urn. The process finally outputs (X1+X2,Y1+Y2).
(X,Y) = (X1+X2,Y1+Y2).
Problem 1: 
P(X,Y)=P(Z)*P(X,Y|Z)


1. Fragement the probility
2. according to the probability to updata the corresponding probability
