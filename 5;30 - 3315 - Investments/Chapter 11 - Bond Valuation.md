# Behavior of Market Interest Rates
- Bond market is not a single market, but consists of many different sectors
	- US Treasury Issues
	- Municipal bond issues
	- Corporate bond issues
- There is not single interest rate that applies to all the segments of the bond market
- ==Yield spreads==: differences in interest rates between various market sectors
# What Causes Interest Rates to Move
1. Inflation rate:
	- When investors expect inflation to slow down, interest rates generally fall as well
2. Changes in the money supply
	- Increase in money supply pushes rates down
3. Federal budget deficit
	- When US treasury has to borrow to cover deficit, increased demand for funds exerts upward pressure on interest rates
4. Level of economic activitiy
	- Businesses need more capital when economy expands
5. Policies of the federal reserve
	- Actions of the Federal Reserve to control inflation
6. Level of interest rates in major foreign markets
# Inflation and Interest Rates
![[screen-2024-10-28-17-47-09.png]]
# Term Structure and Yield curve
- Bonds having different maturities typically have different interest rates
- Term strucutrue of interest rates
	- Relationship between interest rates and time to maturitiy for any class of similar-risk securities
- Yield curve: graph that depicts this relationship
# Why Yield Curve Shape Changes
## Expectations Hypothesis
- Investors will ask for a higher price if interst rate is expected to go up, since stock prices will go down
- 
## Liquidity Preference Theory
- Investors associate longer term with higher risk, and ask for a higher payout
## Market Segmentation Theory
- Bond market is segmented on the basis of the maturity preferences of different investors
# Pricing of Bonds
## Concept
- Bondholders receive two distinct types of cash flow
	- Periodic interest income
	- Principal at maturity
- Bonds are priced according to the present value of their future cash flow streams
Bond price = Present value of coupon payments + Present value of bond's par value
BP = SUM((CPN / (1 + r)^t) + (FV/(1+r)^N))
FV = Face Value
# Yield to Maturity
- Most important and widely used measure of a bond's return
	- Also known as promised yield
	- Rate of return earned by an investor who holds a bond to maturity and receives all principal and interest payments when promised
	- Used not only to gauge return on a single issue, but also to measure required returns for bread classes on bonds
	- Basically, internal rate of return on a bond
YTM = (FV / PV) ^(1/N) - 1
## Example 3
- 15-year, zero coupon bond
- Price = 315
- If held to maturity, what is YTM?
= (1000/315)^1/15 - 1 = 0.080055227076252
## Example 4
- YTM?
- Rate = 7.5%
- $1000 Par value
- 15 years to maturity
- Currently $809.50 in market
# Accrued Interest
- Most bonds pay interest every 6 months, but trade any time
- Interest accrues on bonds between coupon payments
	- Selling the bond prior to payment does not mean bondholders sacrifice any interest that they earned
- Accrued interest is the amount earned since the last coupon payment
# Yield to Call (YTC)
Shows the yield on a bond assuming that the bond is called on its first call date
- YTC is commonly used with bonds that carry deferred-call provisions
- Finding YTC requires making two modifications to standard YTM equation
	- Length of investment is number of years to the first call date
	- Use the bond's call price insteat of par value
# Expected Return
- Some investors prefer to actively trade in and out of bonds securities over short investment horizons
- Measures such as YTM and YTC have relatively little meaning
	- Other than as indicators of the rate of return
- These investors need an alterative measure of return that they can use
![[screen-2024-10-30-17-39-37.png]]
# Duration
## Concept
- Bond investors face many types of risk
	- Even for bonds like Treasures, there is still risk that interest rates will move and cause bond prices to move in the opposite direction
	- Investors who use coupon-paying bonds, there is uncertainty about the rate at which payments can be reinvested because interest rates do not stay the same
- The longer it takes to get money back, due to interest, there is more risk
- To find a less sensative one, you want to find a shorter length bond
## Equation
Duration = SUM((PV(Ct)/BP) x t)
- Duration is the average amount of time it takes to recieve the ineterst and the principal
## Steps in Calculating Duration
1. Find present value of each coupon or principal payment
2. Divide this present value by the current market price of a bond
3. Multiply this weight by the year in which the cashflow is recieved
4. Repeat 1-3 for each year in the life of the bond, then add
## Other Notes
- In general, bond duration possesses the following properties
	- Higher coupons result in shorter durations
	- Longer maturities mean longer durations
	- Higher yields lead to shorter durations
- Shorter the duration, less volatile
# Modified Duration
- There is no exact relationship between bond maturities and bon price volatiltieis with respect to interest rate changes
	- There is a relationship between bond duration and price volatility
- Bond's duration can be used as a viable predictor of price volatility as long as yield swings are relatively small
- Mathmatical link between changes in interest rates and changes in bond prices involves modified duration
## Equations
Percent change in bond price =
-1 x Modified Duration x Change in interest rates
Modified Duration = 
Macaulay Duration in years / 1 + YTM
# Bond Immunization
Allows you to derive a specified rate of return from bond investments over a given investment interval regardless of what happens to market interest rates
- Happens when average duration of the bond portfolio equals the investment time horizion
- Maintaining a fully immunized portfolio requires continual portfolio rebalancing