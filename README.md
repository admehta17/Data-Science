# Data-Science
# Project Writeup

### Project Problem and Hypothesis
The purpose of this experiment is to explore the relationship of commonly viewed technical indicators and their relative ability to predict short term price movements in financial products.  I will look across a range of differing financial instruments (hopefully at least five) in order to test if any potential findings are consistent with or tied to their respective market. 

The outcome being predicted on is future price movement in a given time period.  This a continuous value therefore this experiment will rely heavily on linear regression.  There is the potential to utilize logistic regression if this experiment is converted into a trade simulation/backtesting experiment where risk/reward as well as an entry and exit strategy is defined so that the outcome would be determining the probability of success of a given trade.

The impact I hope to achieve is to reduce “noise” as it relates to technical analysis in trading.  By identifying which indicators (predictors) are more effective in certain market environments we can eliminate false signals and bring clarity by narrowing the focus to make sound short term trading and investing decisions.

I think longer term price directions, measured by tangents to moving averages, will be the most impactful on future price movement.  I foresee sideways range-bound longer term price movement producing more effective signals and more predictable future price movement while trending long-term price movement producing false or unclear signals which hopefully will provide a profitable “counter” signal.


### Datasets
The datasets for which this I will be analyzing in this experiment have been pulled from Quandl.com as CSVs.  They have come with the following fields: 'Date', 'Open', 'High', 'Low', 'Settle', 'Volume' and 'Prev. Day Open Interest.' Besides the ‘Date’ field, these are all continuous values in float format.  From these I will create more features that will be predictor variables.

### Domain knowledge
I was previously a Trader at two proprietary trading firms over an eight year span.  I have used technical analysis on a daily basis throughout.  However, my exploration into the math and statistics behind technical analysis, in particular, outside of an intraday timeframe has not been very deep.  My familiarity helps in that I have some basic preconceived notions of how certain indicators behave in certain environments, which may lead to surprising findings to the contrary or strengthen my stance on certain indicators.

### Project Concerns
I’m concerned that the predictors will be too closely related.  I’m also concerned that there won’t actually be a real conclusion and that this will lead to just a broad analysis and less a predictive model.  Also, I’m worried that the analysis I’m applying is too simplistic.  Additionally, one of the predictors I planned on analyzing will be much tougher to examine than I thought due to the nature of continuous financial products like futures and the extreme drop-offs at quarter roll periods.

Another concern is whether a handful of products enough to draw any conclusions.  It may take dozens or more to draw any meaning conclusions.

The cost of the model being wrong can be quite severe if any financial decisions were made from it.  The opposite is true if the model is meaningful and applied appropriately.  That said, without proper risk/reward, the downside is much greater regardless of how well a model is built. 


### Outcomes
I expect that the output won’t reveal anything profound as most of as the variables are pretty closely related.  However, I do expect that there will be a clear difference in efficacy of indicator signal based on market environments which will serve as the most valuable feature.  That said, I will have to identify and categorize market environments appropriately to get quality results.  

I’m not quite sure how complicated the project will have to get.  I believe I will have a better understanding once I have a chance to explore the data.

If the project is a bust, I will likely find another subject to explore because there are so many tools that have been discussed for which I would like to apply in an experiment.



