# Stock Valuation Models
## Intuition
- Traditional asset pricing models focus exclusively on understanding expected returns
	- Expected returns are not observed
- Even if expected returns could be observed, we would not be able to answer questions such as:
	- Is stock price too high?
## Intrinsic Value
- Intrinsic value of firm can help identify under-valued and over-valued securities by comparing intrinsic value (V) with market price that the stock is traded at (P)
	- P > V -> firm is over-valued: do not buy or sell if you own
	- P \< V -> firm is under-valued : buy or hold
	- P = V -> firm is fairly priced
## Dividend-Discount Model (DDM)
### Setup
- Suppose we planned to hold a stock for 2 years
- Then we would recieve dividends in both year 1 and year two before selling the stock
- ![[screen-2024-09-30-17-53-10.png]]
### Required Rate of Return
- We can use CAPM to obtain the discount rates r
![[screen-2024-09-30-17-58-35.png]]
- What is themost uncertain part in the CAPM equation?
	- Expected market return
### Example 1
- p0 = 48
- O1 = 4
- p1 = 52
- r = 12%
HPR = CG + income / initial
(p1-p0) + 01 / p0
= 52-48+4/48
= 16.67%
Outperforming, so positive alpha value

v0 = D1 + P1 / 1+r
= 4+52 / 1.12
v0 = 50 > p0
Buy signal, undervalued stock

## Model 2: Constant- and Zero-Growth DDM
### Equation
- We have to make some strong and simple assumptions
- We will assume that dividends grow at a constant rate
- Works well with firms that will almost always give constant dividends
![[Pasted image 20240930181120.png]]
### Example 2
- d1 = 2.3
- r = 7%
- g = 2%
- v0 = D1/r-g = 2.3/7-2 = $46
	- Amount taht you are willing to pay, but any more and you lose money
## Variable-Growth DDM
- Also known as multi-stage DDM
	- Allows for variab