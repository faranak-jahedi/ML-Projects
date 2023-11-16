# CryptoDataset
I am using this link as a good reference for using its API for my goals: 

"https://min-api.cryptocompare.com/documentation?api_key=e813f7f8324c46ff0a9630ee2312326ea492f32d9e2e734b0c0cb4f310825d76"

**Dataset Description:**

The dataset is obtained from the CryptoCompare API, which provides real-time and historical cryptocurrency pricing information.

The dataset size is dynamic, depending on the number of symbols requested. It is structured as a JSON response from the API, containing information about multiple cryptocurrencies and their prices.

The primary features include cryptocurrency symbols (fsyms), the target currency symbols (tsyms), and various pricing information such as current price, volume, and market cap.

The data types are typically in JSON format, and the values can be numeric (for prices, volume, market cap) or string (for symbols).

The API response may not contain missing values.

The target variable could be the cryptocurrency prices in the specified target currency (tsyms).

**Analysis plans I can make with this dataset**

Exploratory Data Analysis (EDA):

Explore the retrieved data to understand the distribution of cryptocurrency prices, identify trends, and detect outliers.

Descriptive Statistics:

Calculate basic statistics for key variables, such as mean, median, standard deviation, etc.

Visualization:

Create visualizations (e.g., line charts, bar charts) to represent trends in cryptocurrency prices over time or compare different cryptocurrencies. Also, I can explore possibilities for creating new features, such as daily price changes, relative performance, or moving averages.

Data Preprocessing:

Check for and handle any outliers or inconsistencies in the data.

Model Selection:

If the analysis involves predictive modeling, consider selecting appropriate models for predicting cryptocurrency prices.

Evaluation Metrics:

Define evaluation metrics relevant to modeling goals, such as mean absolute error or percentage error.
