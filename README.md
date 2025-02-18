# Impact of recent US elections on the Indian Stock Market

### Objective: Analyze the impact of US presidential elections on the Indian stock market (e.g., Nifty 50, Sensex, or sectoral indices).

### Key Questions:
1) How do US election outcomes influence Indian stock market performance?
2) Are there specific sectors in India that are more sensitive to US elections?
3) What is the time lag between the election outcome and its impact on the Indian market?
4) Can machine learning models predict market movements based on US election data?

### Data will be divided into two areas:
1) Indian Stock Market data, a time series data of stocks: NSE Website
 	-NIFTY, BANKNIFTY, SENSEX
 	-Top 5 sectors
 	-Top 10 Indian Companies famous among the general population  
 
2) US Election Data
 	-Sentiment Data (News, Social Media, Public Opinion Polls) – Possible sources(GDELT, Twitter-API)
	-Election Day Data
	-US Election timeline and events data – Possible sources(GDELT, News Archve)
	-Geopolitical Events during election – Possible sources(GDELT)

### Possible Primary Data Sources:
1) NSE
2) GDELT Project
3) Twitter API (if needed in future)

### The NSE dataset :
The stock market data provided by the National Stock Exchange of India (NSE), one of the largest stock exchanges in India. This dataset includes extensive financial and stock-related information about companies listed on the NSE. The dataset can include:

1) Stock Prices: Historical and real-time data for stock prices (open, close, high, low, and adjusted close prices).
2) Volume Traded: Number of shares traded for each stock during a specified time period.
3) Indices: NSE indices such as Nifty 50, Nifty Bank, etc., along with their historical performance.
4) Corporate Actions: Dividends, stock splits, buybacks, and other corporate events.
5) Sectoral Data: Data segmented by industry sectors such as IT, Pharma, Energy, etc.
6) Financial Statements: Quarterly and yearly financial reports of companies (balance sheet, income statement, cash flows).

### The GDELT Project :
A comprehensive global dataset that monitors and analyzes world events, media coverage, and societal trends in real-time. It captures human society's behavior, sentiment, and events worldwide by analyzing news media from every corner of the globe. GDELT is unique because it processes massive streams of news and other sources to map human interaction, conflicts, natural disasters, protests, elections, and more.

Key Features of GDELT:
1) Real-Time Data: It continuously ingests information from thousands of news sources in over 100 languages and applies machine learning algorithms to extract structured event data.
2) Event Data: Tracks who did what to whom, when, and where (e.g., protests, conflicts, speeches, etc.). Events are coded using the CAMEO coding framework (Conflict and Mediation Event Observations).
3) Sentiment Analysis: GDELT performs sentiment analysis on articles to gauge public sentiment on global topics.
4) Global Scope: Covers over 197 countries and can analyze news reports in local languages, offering a broad, worldwide view.
5) Multimedia Analysis: Analyzes not only text data but also images and videos to provide insight into visual narratives.
6) Open and Free: The GDELT dataset is publicly accessible, allowing researchers to study global events and trends.
