# stock-analysis

## Overview of Project
This project refactors VBA code that analyzes and formats stock ticker data, including total volume traded and the yearly return.  The goal is to gauge process time improvements, if any, versus the prior itteration of code written through Module 2.  

## Results
![2017_Performance](https://user-images.githubusercontent.com/88443672/130889923-97671e86-4da5-412b-ab89-a67cacc48d6f.png)
![2018_Performance](https://user-images.githubusercontent.com/88443672/130889927-52a8770b-8402-4d28-9471-0db2d3ea98ed.png)
![17_18Comp](https://user-images.githubusercontent.com/88443672/130890901-0fc190f8-24c5-49cf-b136-ddeedc7b77ef.png)

2017 was a far better year for returns than 2018 was, as 2017 showed average returns of 67.32% across all stocks analyzed, versus -8.51% returns for 2018.

Trading volumes were marginally higher, up 4.4%, in 2018 vs 2017.  Although long investors were not reaping rewards, exchanges and clearing houses faired far better with higher trading volumes.

Two of the bottom three tickers for trading volume remained the same in both years, DQ and HASI.  One ticker, SPWR, displayed top three trading volumes for the stocks in both years for the stocks analyzed.

One stock, TERP, posted negative returns in both 2017 and 2018, while two stocks, ENPH and RUN, posted poitive returns for both years.

![green_stocks_2017](https://user-images.githubusercontent.com/88443672/130889473-a24a5bdf-abc3-4631-8854-e9108ac353fd.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/88443672/130889494-bd600328-1039-44b3-8ffd-7567b262816f.png)

After refactoring the code, analysis on 2017 stock data improved from 1.461 seconds to 0.156 seconds.

![green_stocks_2018](https://user-images.githubusercontent.com/88443672/130889506-39d81985-d457-4255-8786-8b17148fad6f.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/88443672/130889510-c8a66513-71e2-435d-aee0-c3224fdf03c5.png)

Similarly, refactoring the code decreased data processing times by nearly 90%, from 1.461 seconds to 0.148

![Mod2_Challenge_Comp](https://user-images.githubusercontent.com/88443672/130892149-52f55b8b-89b0-4b6b-8650-53b7779bcc22.png)

### Module 2 VBA Code for Refactoring
![Module2Code](https://user-images.githubusercontent.com/88443672/130895145-7c4d2090-a046-4c2b-bafc-0f72ecb3f6da.png)

### Challenge VBA Code Refactored W/ Arrays and Tickerindex
![ChallengeCode](https://user-images.githubusercontent.com/88443672/130895433-81fa3fb2-9f28-4066-8ad1-8929bb069984.png)


## Summary
- What are the advantages or disadvantages of refactoring code?
  The advantages of refactoring code include clearner/more-compact code, faster run-times, less processing capacity utilization, and the benefit of learning via solving the same problem a different way.  Additionally, if you end up with different results, it may help identify errors in the initial code.  Disadvantages of refactoring code come via adding complexity to the code via the increased room for error and the time involved to solve problems along the way.  You already had code that worked.  Is the extra time and effort spent refactoring the code worth the benefits gained?  
 - How do these pros and cons apply to refactoring the original VBA script?
  We ended up with code that is much more flexible and far more powerful, with faster run times to boot!  As more data is added to the database, the code is capable of adapting to the larger set of data.  If the code is used to take advantage of the added funcitonality, power, etc, then the pros outweigh the cons by far.  The code can be quickly adapted to adopt the larger set of data.  Additionally, as the database size grows, the time difference in run times between the old and new code would become an increasingly wide gap.     
