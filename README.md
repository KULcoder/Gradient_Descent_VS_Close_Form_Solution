# Gradient_Descent_VS_Close_Form_Solution

In a homework of DSC140A at UCSD. I find that the result of a theoretical closed form solution of a ridge regressor differ significantly from the result of `sklearn` implementation, therefore, I wish to implement such a gradient descent (even might try other method like `adam`) to investigate the updating rule clearer. 



### Main Goal

- Check how precise the solution can a gradient descent method provides 

### Secondary Goal

- figure out why `sklearn` provides such a solution, try to produce those results
- try `adam` optimizer and see how it works on simple tasks



## Conclusion

- The gradient descent method can lead to a very closed form of
- It is because that `sklearn` uses Sum Squared Error as loss function, which leads to differences in regularization strength compares to same solution optimizes for Mean Squared Error.



**Remark**: many of this work utilizes *chatGPT* and *GitHub copilot*
