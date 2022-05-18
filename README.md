# Housing Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. 
> The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
> The company is looking at prospective properties to buy to enter the market. 
> The company wants to know:
	> Which variables are significant in predicting the price of a house, and
	> How well those variables describe the price of a house.
> Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Technologies Used
- Python 3
- Pandas
- Numpy
- Seaborn
- matplotlib.Pyplot
- sklearn

## Conclusions
A. Value of Alpha for ridge: 20
B. Value of Alpha for Lasso: 0.0005
C. Changes in model in Alpha for ridge is doubled:
	a. Mean Square error changed to 0.016203 from 0.016024
D. Changes in model in Alpha for lasso is doubled:
	a. Mean Square error changed to 0.01607 from 0.01580
E. Most important predictor variables after change:

Ridge:
5	GrLivArea		True	1	0.0940
1	OverallQual		True	1	0.0764
4	TotalBsmtSF		True	1	0.0527
2	OverallCond		True	1	0.0421
12	MSZoning_RL		True	1	0.0418
14	Foundation_PConc	True	1	0.0355
6	GarageCars		True	1	0.0326
10	MSZoning_FV		True	1	0.0326
3	BsmtFinSF1		True	1	0.0232
0	LotArea			True	1	0.0210

Lasso:
5	GrLivArea		True	1	0.103166
1	OverallQual		True	1	0.080508
12	MSZoning_RL		True	1	0.075934
4	TotalBsmtSF		True	1	0.052781
10	MSZoning_FV		True	1	0.051236
2	OverallCond		True	1	0.043043
14	Foundation_PConc	True	1	0.040828
13	MSZoning_RM		True	1	0.036561
6	GarageCars		True	1	0.033949
11	MSZoning_RH		True	1	0.023886

## Acknowledgements
- This project was inspired by upGrad


## Contact
Created by @heman2402 - feel free to contact me!