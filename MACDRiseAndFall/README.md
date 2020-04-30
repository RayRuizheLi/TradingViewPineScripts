# MACD Rise and Fall

## Summary

For a typical MACD trading script, the script enters when histogram crosses from negative to positive 
and exists when histogram crosses from positive to negative. This is not optimal since it buys in late and
sells late. 

Instead, this script counts the consecurtive rising bars for buy in signal and conscutive falling bars for selling signal.
This way, buy in price is closer to the lowest point of the dip, and selling price is closer to the peak, thus optimizing 
amount of earnings per trade. 

## Sample Profitable Setup

* Ticket Symbol: K
* TradingView Chart Period: 3m

### Strategy Script

#### More profit 

* Inputs Setting
![Strategy Setting](https://github.com/RayRuizheLi/TradingViewPineScripts/blob/master/Noro'sDIStrategyRayVersion/Images/StrategySetting.png)
* How it looks
![Strategy Proof](https://github.com/RayRuizheLi/TradingViewPineScripts/blob/master/Noro'sDIStrategyRayVersion/Images/StrategyProof.png)

#### Better Accuracy 

* Inputs Setting
![Strategy Setting](https://github.com/RayRuizheLi/TradingViewPineScripts/blob/master/Noro'sDIStrategyRayVersion/Images/StrategySetting.png)
* How it looks
![Strategy Proof](https://github.com/RayRuizheLi/TradingViewPineScripts/blob/master/Noro'sDIStrategyRayVersion/Images/StrategyProof.png)



## Trading Advice 

Buy in when histogram bars starts to trend up. Sell when histogram bars starts to trend down. 


Profitable? Yes
