---
title: Analyze Popular Stocks with Power BI
description: Analyze Popular Stocks with Power BI
author: paulinbar
ms.author: painbar
ms.service: powerbi
ms.subservice: powerbi-template-apps
ms.topic: how-to
ms.date: 03/14/2021
LocalizationGroup: Connect to services
---
# Analyze popular stocks with Power BI

The stock market app shows you multiple KPIs to start your analytics journey in Power BI. You can use it to track end-of-day quotes as well as weekly, monthly, or yearly trends for popular stocks and ETFs. The app shows you Power BI in action, with tracking of stock highs and lows, moving averages, sector-wise distribution, Bollinger bands, and even performance comparisons for popular stocks over time.

The app features four dashboards:
* **My Dashboard**: Shows percent of change over time for companies you select. 
* **Stock Performance Analysis**: Enables detailed analysis of selected stocks with visuals for closing trends, volume, OHLC, and Bollinger bands.
* **Stocks and ETFs Comparison**: Provides a normalized chart to make it easily for you to compare stocks and EFTs.
* **Sector-wise distribution**: Allows you to break out stock performance by sector.

You can navigate between the dashboards using the navigation side pane or the buttons at the top the page.

![Screenshot of stocks app.](media/service-connect-to-analyze-stocks/stocks-app1.png)

## My Dashboard

My dashboard shows you the percent of change over time for companies you select. You can choose as many stocks and ETFs as you want.

![Screenshot of My Dashboard.](media/service-connect-to-analyze-stocks/stocks-app-my-dashboard.png)  

## Stock Performance Analysis

The Stock Performance Analysis dashboard shows you important KPI’s about selected stock, such as the previous day's close, close, open, high, and low. At the bottom of each chart is a slider you can use to zoom in for more granularity.

### Closing trend

You can see the closing trend for the selected stock. You can adjust the time period to help you see in which part of the selected time period the stock gained or lost value. Hover over the chart to see the closing value at that point. Use the slider at the bottom of the chart to zoom in for more granularity.

![Screenshot of closing trends of selected stocks](media/service-connect-to-analyze-stocks/stocks-performance-closing-trend.png)  

### Volume

You can look at the volume of selected stock by scrolling down to the next visual. You can hover at a time interval to see the volume of stock at that point. Use the slider at the bottom of the chart to zoom in for more granularity. 

![Screenshot of volume of selected stocks](media/service-connect-to-analyze-stocks/stocks-performance-volume.png)

### OHLC chart

OHLC Charts are highly useful since they show four major datapoints for a given stock at the same time. You can also look deeper into the data by changing the moving average using the slider above the chart. Use the slider at the bottom of the chart to zoom in for more granularity.

![Screenshot of OHLC](media/service-connect-to-analyze-stocks/stocks-performance-ohlc.png)

### Bollinger band

Bollinger bands use complex mathematics to show the trends. You can see a number of KPI’s which were in OHLC, and along with that you see another three lines. The middle line shows the moving average. The top line is shifted up by certain number of standard deviation and the bottom line is shifted down by a standard deviation. Use the slider at the bottom of the chart to zoom in for more granularity.

![Screenshot of bollinger band.](media/service-connect-to-analyze-stocks/stocks-performance-bollinger.png) 

## Stocks and ETFs Comparison

The Stocks and ETFs Comparison dashboard shows you a normalized chart that makes it easy to compare selected stocks and ETFs. You can choose as many stocks and ETFs to compare as you like. Use the slider at the bottom of the chart to zoom in for more granularity.

![Screenshot of Stocks and ETFs Comparison dashboard.](media/service-connect-to-analyze-stocks/stocks-comparison-dashboard.png) 

## Sector-wise distribution

On the sector-wise distribution page, you see the various stocks and the market they belong to. If you click on any of the sectors, the stocks get filtered out, and the stocks belonging to the selected sector will start appearing. 

![Screenshot of sector-wise distribution.](media/service-connect-to-analyze-stocks/sector-wise-distribution.png)
 
You can then hover over the stock to see the important KPI’s, such as previous close, close and the difference. The difference will help you understand how much the stock has gained or lost since yesterday.

![Screenshot of sector-wise distribution detail.](media/service-connect-to-analyze-stocks/sector-wise-distribution-detail.png)

You can scroll down to see all of the stocks in that category.
 
To see the distribution of market for different sectors we have the “Sector-wise distribution” visual which shows from top to bottom the sectors having the highest difference in their closing price from the previous day.

![Screenshot of distribution of market for different sectors](media/service-connect-to-analyze-stocks/stocks-comparison-based-on-sector.png)

## Next steps

* [What are Power BI template apps](service-template-apps-overview.md)
* [Create a template app in Power BI](service-template-apps-create.md)
* [Install and distribute template apps in your organization](service-template-apps-install-distribute.md)
* Questions? [Try asking the Power BI Community](https://community.powerbi.com/)