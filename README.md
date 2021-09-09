# Financial Analytics with Python

### Credit Risk Modelling on the Loan Dataset
```The dataset has four features namely default(our target feature), student, balance and income. An extensive EDA was performed and financial insights were derived. Modelling was done implementing Logistic Regression after balancing the dataset using SMOTE(Imblearn Oversampler). Performance metrices like Confusion matrix, classification report were considerd for validating the model. Dataset used- "Default.csv"```

### Simple Portfolio using Python
```The Goal was creating a sample portfolio and finding out portfolio simple returns, get daily returns, volatility, etc. The data was extracted from Yahoo Finance using Pandas Data Reader. Stocks for "FB", "AMZN", "AAPL", "NFLX", "GOOG" were considered. Data used- Yahoo Finance with Pandas Datareader for extracting FAANG stock prices. NOTE: I took 2013-01-01 as the starting date because Facebook did not have an Initial Public Offering (IPL) prior mid 2012.```

### ETH Price Prediction using SVR
```A simple Support Vector Machine Regressor was implemented for predicting the next 5 days price of Ethereum based on historical data. Actual price vs Predicted price was then compared and plotted. Data was gathered from Yahoo Finance from 01/01/2021 till 08/09/2021.(ETH-USD.csv)```

### Investment Strategy Using Python
```Here, I have assumeed that the individual retires in 10 years and the expenses of that individual is fixed. There is a saying that "If you invest 50% of your income for 10 years then after 10 years you will be able to support yourself." I have considered the annual income to be $ 35000(it can be changed to any number), interest rate to be 8%(it can be also changed) and the individual spends 50% of his income into expenses and the remaining 50% into investments(this proportion can also be changed and a savigs factor can be added). Then, I have calculate the Yearly Income,	Yearly Expenses, Yearly Investments and	Annual Returns for the next 20 years and I have tried to validate the above saying. We can see that by 2030 the indivial's investments will be able to sustain him/her financially.```

### Bitcoin Price Movement Classifier
```The Data set was collected from Yahoo finance and contains the historical price of Bitcoins from 01/01/2021 till 09/09/2021. "BTH-USD.csv" is the data set file. I have calculated the Exponential Moving Average Indicator (EMA) to get more importance on the recent price data. Then Relative Strength Index (RSI) was calculated which hepls in understanding how quickly people bid the price of Bitcoin up or Down. Then the target column was created to determine if tomorrows price will be greater than todays price,then it will be considerd 1, else 0. RSI7, RSI14,	RSI20,	EMA15,	EMA20, EMA50 were considerd as independent features, where RSI signifies the Relative Strength Indexes for the respective time periods and EMAs the respective Exponential Moving Average Indicators. Model wa sbuilt using Rando Forest Classifier and predicted on the test data set. However, the model was not at all promising. A Lot of testing is needed and a large dataset is required. I have not performed Hyperparameter optimization because it wont make a significant impact as the dataset is very small. For getting better accuracy, other models of ML and DL might work better and we need a huge dataset as the price of Bitcoin is very volatile.```

