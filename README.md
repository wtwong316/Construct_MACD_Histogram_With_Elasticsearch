# Construct_MACD_Histogram_With_Elasticsearch
Materials for the article "Construct MACD Histogram with Elasticsearch" in Medium

The following steps have been tested with Elasticsearch Server v7.10.1

1. Create an index, fidelity28_fund and the corresponding data are populated. The data for the index, fidelity28_fund, is coming from IEX (Investors Exchange) with the 28 Fidelity commission-free ETFs selected for demo purpose. The time range picked is between 2020-12-15 and 2021-05-31.

./fidelity28_index.sh

2. After the indices are created and the data are populated, MACD Histogram of "Fidelity Low Volatility Factor ETF" (FDLO) is calculated.

./fdlo_macd_histo.sh
