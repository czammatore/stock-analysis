# stock-analysis
Stock Analysis using Visual Basic

The goal of this analysis was to determine which stocks from a specific group to recommend/discourage a client from investing in. We compared the 2017 and 2018 returns using raw data that was then run through code in Visual Basic for Excel to produce clear results.

In 2017, stock performance for the selected group was generally good. Stock TERP was the only one to have a loss of 7.2%. Many others had significant returns, including DQ with a return of 199.4% and SEDG with a return of 184.5%. The market activity in 2018, however, tells a much different story. Only ENPH and RUN had any positive return. The previous market leader DQ had a return of -62.6%, while SEDG had a more modest loss of footing at a return of -7.8%.

From a code perspective, our original code looked at specific years and fixed variables, while our refactored code is more flexible and will allow us to look at different variables in the future with a minimum of changes. Possibly because of our use of variables and definitely because of the use of refactoring and simplifying, our code’s run time for 2017 data went from 0.4960938 seconds to 0.0849375 seconds. A similar benefit was seen for 2018’s data, with a reduction from 0.484375 seconds to 0.07421875 seconds.

*author’s note: thank you for taking the time to read this and I apologize for any incoherency or spelling mistakes I may not have caught. I currently have COVID-19 and do not recommend the experience. Be safe and well.
