# Things-in-R
Different projects in R


Project 1
Voting behavior in the UK in 2016
What factors, values and beliefs influences a person to vote for a certain party?

Discrete Choice Modelling - UK_politics

Cointains a markdown script in R that can be knitted for a nice Latex-layout.
Multinomial logit regression models are used to study the voting choices.
Different tables for descriptive statistics and models.
Data wrangling using tidyverse.
Chunks in the code can be run individually or all at once.

This tables displays the two multinomial regression models, as seen in finished knitted Latex markdown-file.


Table 2 presents two multinomial regression models where the first model has the dependent variable of party of choice when voting and the independent variable of views on immigrations effect on the countrys economy. The second model has the same two variables and also adds the independent variables of age, gender and level of education attained. The reference category for the dependent variables in the model is the Labour Party, and for the independents of categorical nature it is their binary opposite. Female is reference category for male, low educated is reference category for high educated.

![Skärmavbild 2023-02-21 kl  09 56 38](https://user-images.githubusercontent.com/120380560/220296608-dabaaa00-28c0-436f-ad09-576f46c69329.png)







Figure 1 displays the odds-ratios of the two models previously presented in table 2, but is visualized in the form of a graph. Outcome from model 1 is displayed as dot or circle, whereas model 2 is displayed as a triangle. The different political parties are presented in the graph by four colors. Conservative is presented in red, Liberal Democrat in yellow, other parties in green, and UKIP in blue. The red line indicates the reference category of the Labour Party and in what position the circles or triangles are displayed in relation to the line determines the odds-ratio of that outcome compared to the reference category.
![Skärmavbild 2023-02-21 kl  09 58 17](https://user-images.githubusercontent.com/120380560/220297037-20791797-e6ae-499a-a1a6-ded53723ddc5.png)

In figure 2 the predicted probabilities of voting for a certain party given the attitudes on immigration is displayed in two panels in one graph. The first panel shows the predicted probabilities of people with low educational attainment, and the second panel displays the predicted probabilities for individuals with high educational attainment. The distinction between the two educational categories are divided according to the parameters of any higher education attained. This dichotomous separation represents traditional class lines in society. The colored lines represents the different parties. Conservative displayed in red, Labour in yellow, Liberal Democrat in green, UK Independence Party in purple, and Other in blue. The bottom of each panel shows the ten-step scale of a persons attitude towards immigrations positive or negative effect on the countrys economy, where the operationalization is done so 0 is immigration is bad for the economy and 10 good for the economy.

![Skärmavbild 2023-02-21 kl  10 08 42](https://user-images.githubusercontent.com/120380560/220299764-46cb2d2c-7889-468e-bb63-5bc50cd48b1d.png)



