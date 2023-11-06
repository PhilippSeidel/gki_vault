#### Goal:
Predict the value of a continuous variable based on the values of other variables assuming a linear or nonlinear model of dependency.

$y = f(x) + \epsilon$    :   We assume that the outputs are affected by (typically) Gaussian noise: $\epsilon \sim N(0,1)$ 

###### Examples:
- Weather forecasting
- Gasoline Consumption
- House Market
- Stock Market
**Q:** What are the dependent and independent variables in this example?



In linear regression, the output $y$ is modelled as linear function of the input $x_i$.
$y = f(x) + \epsilon = \omega_0 + \omega_1 x + \epsilon$ 

![[linear_regression_weight_effects.png]]


###### Objectiveof linear Regression:
Minimize the [[SSE|summed square error]].

##### Bringing it into matrix form
**Equation of the i-th sample**:
### $\hat{y} = \omega_0 + \sum_{j = 1}^{D}\omega_j x_{i,j} = \tilde{x}_i^T \omega$   

with
![[linear_regression_matrix_form1.png]]
![[linear_regression_matrix_form2.png]]
![[sse_matrix form.png]]
