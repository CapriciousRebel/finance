# Finance with the Rebel!

## Stock Market

### Fundamental analysis:

#### Market Cap:
It is the total amount needed to buy all the stocks of a company, 'the cost of a company'. 
Shows us the "size" of the company.
```
MarketCap / TotalNumberOfShares = Price of one Share
```

---
#### Enterprise Value:
It is the actual value of a company. It can be negetive as well, it is negetive when a compnay has more cash than its marketcap and debt combined, now this means that people are not giving enough value to this company(since `MarketCap = SharePrice * NoOfShares`). A research on such companies must be done to find out why it's shares dont have the value.
```
EnterpriseValue = MarketCap + Debt - Cash
```

---
#### Standalone vs Consodilated:
Standalone price of a company is the price of that company itself, it does not include the financial details of the company's subsidiaries or acquisitions.
Eg. Tata owns Jaguar and LandRover, so if we look at Tata as a standalone company vs as a considilated, we se two different pictures.
It is important to see the full picture, and one must look at the consodilated price of a stock.
sometimes a company's standalone enterpirse value is -ve but it's consodilated value is +ve.

---
#### SP (Share Price):
- LTP (last traded price): The price paid for a the last share that was traded.
- Opening price: The cost of one share when the stock market opened today
- Closing price: The cost one one share when the stock market closed today

---
#### EPS (Earning Per Share):
It is the net profit divided by number of shares
```
EarningPerShare = NetProfit/NumberOfShares
```

--- 
### Limited Companies:
A company is said to be "limited" when all of it's debts and cash are belonging to the company as a seperate entity, and not to it's shareholders.
So it's the company who pays it's loans, not it's shareholders.

---
#### P/E (Price over earnings) ratio:
It is the ratio of the price of a share divided by the earnings made from the share
It is a measure of how much value people give to this share
- High P/E ratio means that the share is overvalued
- Low P/E ratio means that the share is undervalued
```
PERatio = SharePrice/EarningPerShare
if(PERatio == 0):
    Company.Profit < 0
```

---
#### Valuation chart:
A plot of the PERatio vs time.
- If the current PERatio is at a maxima, that may mean that the share is being given too much value, so we may want to ask why that is, is it because of something good being done by the company? Will this value increase in the future? What happended in the past when the share was given a high value? Of course the value will fall, but when will it fall? We need some reading here to judge the comapany.
- If the current PERatio is at a minima, that means that the share is being given a lower value, again the same question arises, "why?". Look at the history a bit, see if the company has recovered such drops well in the past. If it was able to recover well, then maybe that stock should be bought, it has a good chance of giving you better return value.

But that is not enough to judge a company, it should be coupled with Profit Growth.

---
#### Profit growth chart:
A plot of the growth in profit over a time (generally 1yr, 3yr, 5yr)
- This chart tells us how the company's profit has grown over the years. Hence we get an idea of the EPS as well, which in turn gives us an idea of the PERatio and the valuation chart of the company.

As the company keeps giving better and better profit growth, it increases the investors' confidence in the share and they give more value to it, in such a case, we see that `ProfitGrowth↑ -> EarningPerShare↑ -> SharePrice↑ -> Valuation↑ -> PERatio?` Because SP↑ and EPS↑ hence if PERatio increases in such a case, it means people believe in the share more, but if it doesn't, it may mean that people dont trust that share too much

If the  Profit growth of a company is increasing, but the P/E is not increasing then it means that the stock is not getting enough value as much as it deserves

---
#### Book Value:
Book value is the value of all the assets owned by a company per share.
It is important to not judge every company using BookValue itself, since book value only includes physical assets, like factory, cars, land, etc. only tangible assets are included. Employees are NOT included
So a company who is a physical asset intensive company, like say a Cement, Power, Steel, Textile company or a Bank must be judged using it's book value.
A company in, say, the tech sector is more employee intensive so their book value doesn't matter much. 
```
BookValue = NetPriceOfAllAssets/NumberOfShares
```

---
#### P/B (Price over BookValue) ratio:
It is the ratio of the price of the stock over the bookvalue of the stock.
It is a measure of how much value a specific type of share get's based on it's total asset costs
- High P/B ratio means that the share is overvalued
- Low  P/B ratio means that the share is undervalued
```
PBRatio = StockPrice/BookValue
```

---
#### Dividend Yield:
It is the amount of cash a company gives back to it's shareholders per year.
- If a company gives a high dividend yield, it means that such a company has a confidence on it's stability, and it doesn't have a lot of ways to spend it's profits, say, in marketing or new aquisitions od companies or assets. Such companies might include Mining companies who have more or less monopoly over their mines. It's important to note that such companies might not show a good growth of share price over the years, in fact the share price might go down as well.
Such companies might be PSUs with a lot of cash. They must be bought only in the bad times, when market is in a bad state. Because one gets good cash appreciation on their income.
- On the other hand, the companies who face huge competition, have to spend their profits on advertisements, aqusitions, assets, technology, workforce, etc... Such companies give minimal dividend yield, but they might have a good growth of share price over time as well.
- There are also some companies who have a high sales growth, as well as a high dividend yield. Such companies **dont require** a lot of `IncrementalInvestments(Investing back the profits to get more profits)`. Given other factors are not bad, such companies are good companies to invest into.

When deciding if a dividend yield should be given on a particular year, a company might consider thinking about better ways in which this money could have been used. Maybe investing it to start a new project, maybe to onvest in some other company, etc. A company wouldn't give dividend yield if they have better ways to earn returns on their profits (good returns = 10 - 12%)
```
DividendYield% = (Dividend/SharePrice)*100
```

---
#### Face Value:
It is the price of the share written on the physical form of the share. Ignore this value, it has nothing to do with investing.

---
### share holding patterns:
---
#### Promoter Holding:
It is the percentage of equity, the original owners of the company hold in it. Promoter holding in any private sector company must be high (`PromoterHolding% > 40%`). It shows the confidence of the owner of the company in the company.
Exceptions:
1. Professionally Managed Comapanies: Companies like ITC(`PromoterHolding = 0%`) are managed by many comapanies, so they dont have a single owner, but many owners, hence their promoter holding will be low.
2. Banks: There is a limit on how much power a single person can have over a bank which is set by the RBI(regulating body for banks in India). So banks will have a lower promoter holding.

---
#### Promoter Pledging:
It is the percent of shares kept mortgage by the promoter. A promoter might have a shortage of money, and can keep thier shares of the company as mortgage with a bank who can give them a loan. More Promoter Pledging is a very bad sign

---
#### Promoter Holding Pattern and Promoter Pledging Pattern:
It is the trend over the years of a the said values
- If the promoter holding is reducing and/or pledging is increasing, then it is a very very bad sign.

---
#### DII(Domestic Institutional Investors) and FII(Foreign Institutional Investors) Holdings:
This category includes banks, insurance companies, mutual fund houses, etc. Basically experienced investors who manage pooled money for people.
Clearly, a higher % of Dll Holding is a good sign since it shows that experienced people are trusting this company
FII Play a huge role in the trend in which the company's stock prices and the overall indian market/economy will go towards.

If the DII and FII Trends are increasing, such companies are the safest to invest into.

--- 
#### Public Holdings:
This is simply the normal public's investement in the company

--- 
---
#### PAT margin (net margin) and Profit Markup:
It is the net profit margin calculated on the `Selling Price`.
For example, I buy a pen for $10 and sell it for $15, then my PAT Margin will be ((15-10)/15) * 100
```
PATMargin = ((SellingPrice - CostPrice - Expenses - Taxes)/SellingPrice)*100
```
It's important to note that Profit Margin and Profit Markup are two different things. 
Profit Markup is calculated on `Cost Price`:
```
ProfitMarkup = ((SellingPrice - CostPrice - Expenses - Taxes)/CostPrice)*100
```

**Profit margin is not enough to judge a company:**
Say I have a profit margin of 50% on my products but I sell 10 products
Meanwhile my competition has a 20% margin but they sell 100 products, so clearly they have a better bussiness model

---
#### ROE(Return on equity):
It is the total return the company gave on the initial investment. Say I start a company, with a total investemnt of $100 (say I got all this in form of equity from self, friends, family), Then I did bussiness, and my company value became $120 by the end of the year. So my return on equity is 20%
```
ROE = ((CurrentEquityValue - InvestedEquityValue)/InvestedequityValue)*100
```

ROE is one of the most important ratios to consider in finance. it is literally the % gain one got on their initial investments.

**Important:** ROE only considers initial invested equity value, hence it is possible to increase the ROE simply by taking Debt (a debt twice of the equity is often taken by the company). It might be good for the company, but it is a bad idea to invest in companies with debt. As an investor, one must not buy shares in a debt ridden company. It's important to see the debt/equity ratio of a company when buying into it.

#### Debt/Equity Ratio:
It is the ratio of the current debt and current shareholder equity.
```
DebtEquityRatio = (Debt/equity)*100
```
This ratio should be as small as possible when buying a safe stock

**Note:** This ratio is irrelevant for Banks, finance companies, lenders, etc. because it is their job to take money from people and give debt to people.

---
#### Asset turnover:
It is the efficiency of a company essentially, basically it measures the total profit a company got out it's assets. For example, if I have a car company, then muy asset turnover will be more if I use my car more to gain money.
```
AssetTurnover = ProfitsFromAnAsset/CostOfTheAsset
```
Asset turnover must be high.

---
#### Cash Cycle:
It is basically a measure of the effectiveness of a company. It tells us about the number of days a company needs to convert it's investments into profits. So if I want to sell a product, I will give the product today, but take the payment tomorrow, then my Cash Cycle will be 1 day.
```
CashCycle = DayOnWhichIAmPaid - DayOnWhichIDevliveredMyProduct
```
Cash Cycle must be as small as possible (-ve is preffered)
Cash cycle tells us about the reputation of a company

---
### Corporate Actions:

#### 1. Stock Split:
A stock split is when a company multiplies the number of it's shares and divides the cost of it's shares.
So if a company has 1Cr shares, and $100 per share, if it does a 1:2 split, the number of shares will become 2Cr and cost of each share will be $50 per share.
```
- Face Value   /= 2
- NoOfShares   *= 2
- CostPerShare /= 2
- ShareCapital = ShareCapital
- TotalReserve = TotalReserve
- TotalShareholdersFund = TotalShareholdersFund
```

Now this can have different effcts. It is possible that since the price is reduced, the demand may increase and also the price

#### 2. Bonus:
A company gives bonus shares to it's shareholders, say a company does a 1:1 bonus then it's stockholders will get 1 share

```
- Face Value   = FaceValue
- Book Value   /= 2
- NoOfShares   *= 2
- CostPerShare /= 2
- ShareCapital *= ShareCapital
- TotalReserve /= 2
- TotalShareholdersFund = TotalShareholdersFund
```

#### 3. Rights issue:




#### Profit and Loss statements vs Cash Flows:
Profit and loss statements are not 100% accurate when it comes to the real picture. Say a company makes a sale today for $1000, then it is recorded by the accounting section, even though the actual money is yet to be received 

--- 
### Technical Analysis:


#### Percentage Change
It is the percent change in the price of a share from it's previous day's closing price
```
PercentageChange = 100 * (LTP - PrevDayClosingPrice) / PrevDayClosingPrice
```

#### Asset
Something that we can own which can be converted into cash
Eg: A house worth rupees 1Cr, Gold worth rupees 50Lac, Stocks worth rupees 1Cr, etc.

#### Liability
Something that we can own which will can be converted into negetive cash
Eg: Home loan worth rupees 50Lac, Short sold stock worth rupees 20Lac, etc.


#### Net Worth
It is the total amount of cash a person can have
```
NetWorth = TotalAssets - TotalLiabilities
```

#### Equity and Debt 
**Equity** is the amount of ownership of an an asset
Eg: Say I buy a car worth rupees 10Lac and I pay 3Lac myself, but take 7Lac loan. In such a case, I own 30% of the car, or my equity is of 30% in that car which is 3Lac rupees.
```
Equity = Asset - Debt
```

**Debt** is the amount of money that I have to *pay back* to someone.
In the above example, we can see that my debt is 70% which is 7Lac rupees.

--- 

**Example of a company**:
- Say me and my two friends open a Tech company (we are the `promoters`)
- Each of us put 20Lac rupees in it, which means we have 20x3 = 60Lac rupees 
- We take a loan of 40Lac rupees from a bank => company's `debt`
- Now we have 1Cr rupees for the company
- We hire people, we generate ideas, we make websites, we buy computers, we already invested 60Lac rupees, etc => The company's `assets`

State:
    - Assets = 100Lac
    - Debt   = 40Lac
    - Equity = 100Lac - 40Lac = 60Lac
    - Shareholding = 100% by promoters
    
At this point each of me and my friends own equal ownership of the company (1/3 each)

- Now the company grows, we make good profits, we want to now expand the company to more locations, serve more customers, etc
- Thus we need more assets, so we find the valuation of our company, we find the valuation is 10Cr
- Say, we need 2Cr of total investment now to grow the bussiness
- We take a loan of 1Cr from the bank => more `debt` for the company
- For the other 1Cr, we open up our company for equity investments, which means we diluted the shares(ownership) of our company by 10%.
- Investors will now invest their money into our company and we will get the 1Cr rupees from them.

State:
    - Funds Raised = 2Cr
    - Equity       = 1Cr (Investors) => Will not have to be paid back 
    - Debt         = 1Cr (Lenders = Bank Loan) => Will have to be paid back, with interest
    - Shareholding = 10% by Investors and 90% by promoters

- Basically, there are some investors who hold 10% ownership of our company, they can be fetched via public(share-market0 or private(friends/family) investestments
- Me and my friends now hold 30% ownership of the company each and will own 30% of whatever value the company grows to.
- The bank doesn't get ownership of the company, they only get their money back with interest, irrespective of the company's growth
- The investors will get 10% of whatever value the company grows to.

Risk: 
  - Investors have a high risk where their returns vary from 0% to infinity.
  - The Lenders have a lower risk since they will keep getting their interest back per year, and in a case that the company goes bankrupt (debt > assets) (equity < 0) the lenders have the first right to auction the assets off to get their money back

Types of Investors:
- public(stock market)
- private (Private equity(PE), venture capitalists, angels, self)

Types of Lenders:
- Banks
- Financial Instituitions (FIs)
- Corporate Bonds
- Government Bonds (TBD)

Types of equity investments;
- Stocks
- Mutual funds (TBD)
- SIPs (TBD)
- ULIPs (unit link insurance plans, TBD)
- ELSS (equity linked saving services, TBD)
- Private equity firms
- Startups
- Bussiness
- Franchise

Types of debts:
- Loans
- Debt Products
- Bonds

---

#### Liquidity
It is essentially how easily an asset can be exchanged, a measure of the current market activity
(If many people are trading a stock, you can easily sell that stock at any time you want)
Liquidity can be thought of as the rate of conversion of an asset into cash
Liquidity considers short term assets and liabilities
`Short term means under one year`

- Cash/Stocks are generally of high liquidity
- Real Estate is low liquidity, harder to sell generally
More liquidity is important

#### liquidity ratios:
These tell us about short term financial position of a company
1. Current Ratio
2. Quick Ratio
3. Cash Ratio

#### solvency ratios:
These tell us about long term financial position of a company
1. Debt ratio
2. Debt to equity ratio
3. Interest coverage ratio
4. Debt service coverage ratio


#### Solvency and Insolvency
`If Net-Worth > 0 the solvency = true`
`If NetWorth < 0 then Insolvency = true`

#### Market depth
It shows the last 5 or 20 trades that happened on the stock, more the bids/offers, more is the liquidity

#### Product Type
- CNC (Cash and Carry):  Buy a stock for long term investment, will be held
- MIS

#### Stock Status

T   Day: The day of trading a stock (first day) => Stock shows up on Positions (Intraday trading allowed)
T+1 Day: The first day after trading a stock (second day) => Stock shows up in Holdings (Now Intraday is over)
T+2 Day: The second day after trading a stock (third day) => Stock is now settled and will be delivered to the demat account.


#### Patterns, Bearish, Bullish
**Bullish**: A bull is powerful animal, and hence Bullish means that the stock is going up.
**Bearish**: A bear is a weak animal, and hence Bearish means that the stock is going down.

A buyer, when buys a stock, believes that the stock is bullish, that it's price will go up, hence buyers are said to be bullish.
A seller, when sells a stock believes that the stock is bearish, that it's price will go down, hence sellers are said to be bearish.

When people think a stock is bullish, they buy the stock, and are willing to pay a higher price for it, which in turn causes the stock to rise, but then people see the stock being very powerful, and they start reaping their profits, and start selling the stock, at there is a general vibe that the stock is bearish, so people start selling the stock. And then the cycle repeats itself, hence there is always a pattern of maxima and minima in the price of a stock


#### Types of orders:
**CNC**: Cash And Carry -> Buys a stock that can not be sold on the same day, it will send delivery of the stock in your demat account after T+2 days.
**MIS**: Margin Intraday Squareoff -> Buys/Sells a stock which has to be sold/bought on the same day, if not sold/bought till 15:10 hrs, then the broker will do it for you (square off) at the current trading price.

