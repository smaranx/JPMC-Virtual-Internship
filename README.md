# JPMC-Virtual-Internship
This is a repository that contains the tasks for the JP Morgan &amp; Chase Software Engineering Virtual Internship offered by Forage.
The goal was to visualize stock price data using JPMC's own visualization tool named 'Perspective' to help traders by giving insights on trading stratergies.

## Task 1 - Interface with a stock price data feed
We’ve been asked to assist with some development to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks.

The trader would like to be able to monitor two historically correlated stocks and be able to visualize when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

Before implementing this request using perspective, first we’ll need to interface with the relevant financial data feed and make the necessary adjustments to facilitate the monitoring of potential trade opportunities.

## Task 2 - Use JPMorgan Chase frameworks and tools
Implement the Perspective open source code in preparation for data visualization.

Typically, traders monitor stock prices and trading strategies by having data displayed visually on their screens in chart form. Often these charts will be accompanied by alerts that notify users when certain events occur or when preset price thresholds are hit.

Perspective provides a set of flexible data transforms, such as pivots, filters, and aggregations. It utilizes bleeding-edge browser technology such as Web Assembly and Apache Arrow and is unmatched in browser performance. It is engineered for reliability and production-vetted on the JPMorgan Chase trading floor and is now available to the development community as Open Source.

## Task 3 - Display data visually for traders
Use Perspective to create the chart for the trader’s dashboard

Being able to access and  adjust data feeds is critical to any trading analysis and stock price monitoring. From the previous tasks, we now have the adjusted data set up on your systems and being piped into Perspective.

For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstation.

Given there is a lot of information and data being produced at once, visualizing data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

### Task 4 is entirely optional and pertains to contribution to the open-source community.
