**Stock-Market-Forecasting1
LSTM is very powerful in solving sequence prediction problems because it can store previous information, which is essential to predict the future record and trend of daily QC items. Through the standard recurrent layer, self-loops, and the internal unique gate structure, the LSTM network effectively improves the forgetting and gradient vanishing problem existing in the traditional RNN Besides, LSTM can learn to make a one-shot multi-step prediction useful for predicting the time series. 
An LSTM neural network unit combines four gates: an input gate, a cell state, a forgotten gate, and an output gate.
The forget gate is used to determine which messages pass through the cell, then enter the input gate, which decides how many new messages to add to the cell state, and finally decide the output message through the output gate.

![acm213558-fig-0001-m](https://github.com/markquestion32/Stock-Market-Forecasting1/assets/40835903/8787a411-f7d1-4e3b-9d48-f4691b24db4e)


** PAndas data reader
https://pandas-datareader.readthedocs.io/en/latest/

**TIIngo
Tiingo is a financial data platform that makes high quality financial tools available to all. Tiingo has a REST and Real-Time Data API, which this library helps you to access. Presently, the API includes support for the following endpoints: Stock Market Ticker Closing Prices + Metadata.
