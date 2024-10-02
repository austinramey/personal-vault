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
	- Allows for variable rates of growth in idvidends over time
	- Calculates a stock price in two stages
	- Value of a share = PV of future during initial - growth period + PV of price at end of variable-growth period
![[Pasted image 20240930182032.png]]

### Example 4
- annual dividend of $4.50 a share
- Dividends are expected to grow at a rate of 8% a year for next 5
- Then to level out at 3% a year
- Stock has beta of 1.5, risk-free of 2%, and expected return is 10%
- Use CAPM to find required rate of return (r)
What is v0?

CAPM: r = rf + p0(E(rm)-rf)
2% + 1.5(10-2) = 14%
d0=4.5 | d1    | d2       |  d3       |  d4     | d5
\----------------------------------------------------
t=0       t=1      t=2        t=3        t=4        t=5

d1 = d0(1+g) = 4.5(1+0.08) = 4.17
d2 = d1(1+g) = 4.17(1.08) = 4.5
d3 = d2(1+g) = 4.5(1.08) = 4.86
d4 = d3(1+g) = 4.86(1.08) = 5.2

## How to Estimate Growth Rate?
- Dividend distributions depend on a firm's earnings
	- Firms, however, can retain part of earnings to reinvest in new projects
	- Thus, they can choose not to distribute all earnings
- Withholding earnings and investing them in new projects can lead to higher chance of growth
![[screen-2024-10-02-17-35-41.png]]
or 
g = (reinvested earnings / total earnings) \* (earnings/book value)
first part = retention rate                          second part = Return on Equity

dividends per share = (1- retention ratio) * earnings per share
## Example 5
- RoE = 12%
- Payout ratio = 20%
- EpS = $86.67
- 1-0.12 * 86.67 = 10.40

# P/E Ratio
- Builds the stock valuation process around the stock's price-to-earning ratio
	- Simple appraoch
	- Favorite professional security analysts and widely used in practice
Stock price = EPS * P/E ratio
## Step 1: Forecasted Sales and Profits
- Assumes that the company will continue to perform as it has