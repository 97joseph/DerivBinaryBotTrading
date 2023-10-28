# DerivBinaryBotTrading
 # Tested Binary Bots

Once you log in to your Deriv account and select Deriv Bot from the platform dropdown in the top left corner, you will see the Deriv Bot’s workspace with 4 pre-set blocks in it – 3 mandatory (trade parameters, purchase condition and trade again) and 1 optional (sell condition). The mandatory blocks are essential to have your trading bot running, and the optional one gives you an opportunity to upgrade your automated trading strategy.

As discussed in our previous blog post, the pre-set parameters in these blocks let you start trading right away. But you also have the freedom to adjust these parameters to your personal trading strategy. In this blog post, we will review each pre-set block and explain how you can customise them to place your first personalised trade on Deriv Bot.

# Set your mandatory blocks

The mandatory blocks contain the crucial elements for trading information, like the market you prefer to trade on and when exactly to execute your trade.

# Trade parameters

Trade parameters is the first mandatory block, and you can find it under the ‘Trade parameters’ tab. In this block, you can set the following information: 



# Market

Select the market and asset you want to trade on – derived indices, forex, stock indices, and commodities. 

# Trade type
Choose your desired trade type – from Up/Down to Only ups/Only downs if you want to trade options. Alternatively, select multipliers.
Some trade types are offered in a few variations. For example, the Digits has Matches/Differs, Even/Odd, or Over/Under.
Make sure to check this section too, and select your preferred variation.

# Contract type
Your next step is to decide which contract type you want. You can leave this as ‘Both’ as later on you’re able to select the direction under ‘Purchase conditions’.

# Default candle interval
This section is important for setting up indicators for technical analysis. We cover technical analysis on Deriv Bot in another blog post, so we’ll leave this as it is for now.

Other parameters you can also set:
Restart buy/sell on error – let your bot know whether you want it to buy or sell a contract if this action was interrupted due to some error. This is disabled by default.
Restart last trade on error – let your bot know whether you want it to restart your last trade if it was interrupted due to some error. This is enabled by default.
Run once at start
The instructions set in this section are only executed one time — when you start your bot — and are not repeated every time the new trade is executed. 

Here you can set some additional parameters like custom text notification, but it’s optional and requires a little more technical understanding. 

We’ll cover more details in our ‘How to set up advanced parameters for Deriv’s trading bot’ blog post. For the time being, you can leave it blank.

# Trade options 
In this block, you need to add the essential parameters of your trade, such as the desired trade duration and stake amount when you trade options. Take note that some Digits options have an additional input field called ‘Prediction’. With this, you’ll need to enter a number from 0–9. This is your prediction of the last digit of the asset’s price when the contract closes.
For the multipliers trade type, you’ll need to add a multiplier value and stake amount, along with take profit and stop loss amounts. Take profit and stop loss are the conditions to close the open positions.



# Determine your purchase conditions

Purchase conditions is the most important block as it tells your bot what trade to execute. You can also select additional parameters to specify certain conditions to be met before executing a trade.

# Set restart trading conditions

Using this block, you can tell your bot to continue or stop trading. You can also adjust the parameters for your next trade and implement stop loss or take profit. For now, you can leave it as is.

Once you set these 3 mandatory blocks, your trading bot is ready to run trades for you. You can activate it by clicking the green ‘Run’ button, located at the top right side of your screen, right under your balance indicator. 

Bear in mind that once you run your bot, the trade you have set will be repeated indefinitely until you stop it manually by clicking the ‘Stop’ button. If you stop your bot before the current trade is closed, the bot will wait until its duration is over and won’t execute a new trade. 

Add an optional block to refine your strategy
The optional block can be used to potentially improve your trading strategy and add additional parameters.

# Sell conditions


With the sell conditions block, you can sell your trades at the market price before their duration is over. This block can’t be used with tick contracts, and selling availability also depends on the duration of the contract and current market conditions. In general, the sell conditions block is more applicable for trading multipliers.

If you are just setting up a simple strategy, you can leave the optional block blank or remove it from your workspace. Your bot is good to go with just the 3 mandatory blocks.

In our “How to set up advanced parameters for Deriv’s trading bot” blog post, we’ll go over all the details on how to add some additional instructions to your trading bot and how to set the optional block to make the most out of the automated trading!

You can also head over to Deriv Bot and practise setting up mandatory blocks on your risk-free demo account, preloaded with a 10,000 USD of virtual currency.
