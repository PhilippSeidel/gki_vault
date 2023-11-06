The summed (or mean) squared error is a value aimed to be minimized by [[Linear Regression]].

## $SSE = \sum_{i = 1}^{N}(y_i - f(x_i))^2$ 

#### Why is this used?
- It is fully differentiable
- Easy to optimize
- You can easily show that:
	$f^*(x) = argmin_{f(x)}SSE \Rightarrow f^*(x) = E[y|x]$ 
	

