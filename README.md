# STAT-450-Lab-3-Test-Repo

To determine whether there is a relationship between bill length and bill depth of penguins, we will first consider a linear regression model (lm() in R):  Bill Depth = <math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>&#x03B2;<!-- β --></mi>
    <mn>0</mn>
  </msub>
  <mo>+</mo>
  <msub>
    <mi>&#x03B2;<!-- β --></mi>
    <mn>1</mn>
  </msub>
  <mo>&#x00D7;<!-- × --></mo>
  <mtext>Bill Length</mtext>
  <mo>+</mo>
  <msub>
    <mi>&#x03B2;<!-- β --></mi>
    <mn>2</mn>
  </msub>
  <mo>&#x00D7;<!-- × --></mo>
  <mtext>Species</mtext>
  <mo>+</mo>
  <mi>&#x03F5;<!-- ϵ --></mi>
</math>
(Mathematically, we will have two dummy variables for the "Species" variable). After fitting the model, we need to verify a couple of assumptions of a linear model. For example, we need to check whether the residuals have the same variance along different observations of penguins (constant variance of residuals) by plotting the residuals vs fitted values plot. We should also check the normality of residuals by plotting a Q-Q normal plot of residuals. 
