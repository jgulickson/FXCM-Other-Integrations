#FX-Other-Integrations

## Overview
#### Summary
Repository contains a Excel (*.xlsx) spreadsheet which sources select trading related data points from a financial trading platform written for Windows called [MetaTrader 4 (MT4)](https://www.metatrader4.com/en).  Additional data points are calculated within Excel to reach an end objective of a market dashboard for common FX products.

This integration is accomplished via [Dynamic Data Exchange (DDE)](https://en.wikipedia.org/wiki/Dynamic_Data_Exchange); see MetaQuotes' [documentation](https://www.metatrader4.com/en/trading-platform/help/service/dde) for further reading.

![MT4 DDE Integration](/README-Images/MT4-DDE-Integration.png)

#### Requirements
1. MT4 client terminal must be installed.

2. MT4 client terminal must have 'Tools' > 'Options' > 'Server Tab' > 'Enable DDE server' enabled

1. When using the Excel spreadsheet, MT4 client terminal must active and logged into an account.

##**Installation**
1. Clone or download desired MT4-DDE-Integration.xlsx file from this repository.

2. Launch MT4-DDE-Integration.xlsx after completed the steps outlined in 'Requirements' section above.

4. When asked, select 'Update' external links.

##Version History

####MT4 DDE Integration
######1.0.mmdd2012
- ***Initial release***
- Created circa 2012