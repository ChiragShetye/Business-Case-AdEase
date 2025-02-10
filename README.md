# Business-Case-AdEase

About AdEase 🌟
AdEase is an advertising and marketing company that empowers businesses to achieve
maximum clicks at minimum cost. It serves as a robust ad infrastructure designed to help
brands promote themselves easily, effectively, and economically.
At the heart of AdEase is an advanced AI-driven advertising system, powered by three core
modules:
● Design: Craft customized, high-performing ad creatives.
● Dispense: Efficiently distribute ads across relevant platforms.
● Decipher: Analyze ad performance to optimize campaigns and maximize ROI.
This end-to-end 3-step process makes AdEase the go-to digital advertising solution for
businesses aiming for optimal growth and visibility.
Project Objective & Problem Statement 📊
The goal of this project is to analyze and forecast daily page views for various Wikipedia
pages over 550 days to predict future trends and optimize ad placement strategies for
AdEase’s clients. With data for 145,000 Wikipedia pages, your task is to:
1. Understand the per-page view trends for different Wikipedia pages.
2. Forecast future page views to predict traffic spikes.
3. Provide region-specific insights on ad performance for pages in different languages,
enabling clients to target the right audience more effectively.
Key Deliverables 🚀
➔ Exploratory Data Analysis: Discover trends and patterns in page views.
➔ Time Series Forecasting: Build a model to predict future page views.
➔ Region & Language-Based Insights: Tailor recommendations for clients in different
regions and languages.
➔ Optimization Strategy: Suggest ad placement improvements based on forecasted
traffic.
Business Impact 💡
This project will help AdEase's clients:
● Maximize ad visibility by predicting high-traffic periods.
● Optimize marketing budgets through accurate forecasting.
● Increase engagement and conversion by targeting the right pages at the right time.
📃 Features of the Dataset
The dataset comprises two CSV files containing information about web traffic and external
campaign events that influence Wikipedia page views. Here’s a breakdown of the dataset:
1. train_1.csv
This file contains web traffic data for various Wikipedia pages. Each row represents a specific
page, and each column corresponds to a date. The values indicate the number of visits on that
particular date.
● Page Name: Contains information about the page in the format:
SPECIFIC_NAME_LANGUAGE.wikipedia.org_ACCESS_TYPE_ACCESS_ORIGIN.
This provides details about the page name, language, access type, and request origin.
○ SPECIFIC_NAME: The unique title of the Wikipedia page.
○ LANGUAGE: Language version of the page (e.g., en for English, fr for French).
○ ACCESS_TYPE: The type of access—desktop, mobile-web, or
mobile-app.
○ ACCESS_ORIGIN: Specifies whether the request is from all-agents (human
visitors) or spiders (bots/crawlers).
● Date Columns: Each column from 2015-07-01 to 2018-09-10 represents the
number of visits on the respective date.
2. Exog_Campaign_eng.csv
This file contains information about significant events or marketing campaigns that may have
influenced page views for English-language Wikipedia pages.
● Date: Indicates the specific date of an event or campaign.
● Campaign Indicator: A binary variable where 1 denotes the presence of a campaign on
that date, and 0 indicates no campaign. This serves as an exogenous variable for
forecasting models.
🔮 The Road Ahead:
📊 Exploratory Data Analysis: Analyzed web traffic trends, seasonality, and campaign
impact on page views.
⌛ Time Series Built predictive models using ARIMA, SARIMAX, and Prophet to
forecast future traffic.
🤝 Insights & Recommendations: Identified key patterns to optimize marketing
strategies and improve campaign planning
