In this project, we will learn about how a neural network can benefit from predicting a sequence data set like time series or sentence formation. To initiate with this, we will use the Infosys Equities data set from January 1st, 2000 till December 31st, 2009 giving us a total of 10 years of data. The National Stock Exchange market opens only on Weekdays excluding weekends and national holidays, therefore, you can't except data for all 365/366 days a year.

The ![dataset](/Forecasting%20Stocks/INFY20002008.csv) includes the following features:

```
    Symbol:                     INFOSYSTCH throughout the dataset.
    Series:                     EQ (Equity) throughout the dataset.
    Date:                       Date corresponding to the data.
    Prev Close:                 Previous closing price.
    Open Price:                 Corresponding date's open price.
    High Price:                 Corresponding date's high price.
    Low Price:                  Corresponding date's low price.
    Last Price:                 Corresponding date's last price.
    Close Price:                Corresponding date's closing price.
    Average Price:              Corresponding date's average price.
    Total Traded Quantity:      Number of quantity traded.
    Turnover:                   Corresponding date's turnover.
    No. of Trades:              Total number of trades.
    Deliverable Qty:            Deliverable stock volume
    % Dly Qt to Traded Qty:     Ratio of deliverable volume to traded volume.
```

For our time series, we will be considering only 2 features:
- Date
- Average Price.