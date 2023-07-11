Practical Application 2: developing multiple multivariate regression models to understand the underlying factors that drive prices.

This repository is concerned with the pricing of cars. More specifically this repository attempts to make clear the underlying factors that drive the pricing of used cars. To do this a multitude of different regression based predictive models are created, trained, and tuned and the mechanics of said models examined to gain a higher level of understanding. 

Models with different aspects of regularization and feature selection are included as well as an in depth section dedicated to data cleaning and scaling, as well as feature encoding. The high cardinality of encoded features and large number of categorical values is tackled with Lasso regression. Ultimately XGBoostRegression performed the best, however the efficacy of the model is less of concern than the features it relied on to produce its results. 

The results found were largely intuitive; odometer reading and year of manufacture were the two most important drivers of price. However, it was additionally found that  cars being Toyotas or Mercedes Benzs was also a significant factor in price. The commonality of model of car was similarly important as well as the drive of a car. Additional research could be with polynomial features of the purely numeric features of odometer reading and year of manufacture to more accurately characterize their relationship to car price. 

The project in its entirety is found below:

- [https://github.com/alexanderomason/practical_app_II/blob/master/prompt_II.ipynb]