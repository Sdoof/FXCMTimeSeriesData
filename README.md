# FXCMTimeSeriesData

Enjoy free access to our historical Time Series or Candle Data.

Our repository contains Candle Data from 1 January 2012. The data is compiled by trading instrument for that trading week for m1 & H1, and trading year for D1. The files are stored in our public directory and is updated every Monday for minute (m1) and hour (H1) data only.

https://candledata.fxcorporate.com/{periodicity}/{instrument}/{year}/{int of week of year}.csv.gz

Periodicity	: m1, H1, D1

Instrument	: AUDCAD, AUDCHF, AUDJPY, AUDNZD, CADCHF, EURAUD,
EURCHF, EURGBP, EURJPY, EURUSD, GBPCHF, GBPJPY,
GBPNZD, GBPUSD, NZDCAD, NZDCHF, NZDJPY, NZDUSD,
USDCAD, USDCHF, USDJPY

Year		: 2012, 2013, 2014, 2015, 2016, 2017, 2018

Week		: 1 to 53 (only applicable to m1 and H1)

To give an example, the path for extracting EURUSD minute-data for the 1st week of 2012 would be
https://candledata.fxcorporate.com/m1/EURUSD/2012/1.csv.gz

To give an example, the path for extracting EURUSD hourly-data for the 1st week of 2012 would be
https://candledata.fxcorporate.com/H1/EURUSD/2012/1.csv.gz

To give an example, the path for extracting EURUSD daily-data for 2012 would be
https://candledata.fxcorporate.com/D1/EURUSD/2012.csv.gz



Note:
•	For personal use only
•	Timestamps are in UTC
•	Data points are indicative and based on the our lowest spreads available exclusively on Active Trade accounts
•	Daily data is only updated yearly
