
# Polar Ice Melting & Sea Level Rise Analysis App

## Introduction

Climate change presents one of the greatest challenges of our time, impacting ecosystems and human populations worldwide. A significant consequence of this phenomenon is the accelerated melting of polar ice caps, which directly contributes to rising sea levels. The Polar Ice Melting & Sea Level Rise Analysis app aims to provide insights into these critical issues through data analysis and visualization.

## Purpose

This app serves several key purposes:

- **Historical Data Analysis**: Explore historical data on polar ice melting trends (Arctic and Antarctic) and sea level rise.
  
- **Future Predictions**: Provide predictions for the next decade regarding polar ice extent and projected sea level rise.

- **City Flooding Risk**: Utilize an interactive map highlighting cities at risk of flooding due to rising sea levels, including population data.

- **Real-Time Webcams**: View real-time webcams from Antarctica and Greenland to observe current ice conditions.

- **Chatbot Integration**: Includes a chatbot for easier navigation and interpretation of data.

## Data Sources

The app utilizes datasets sourced from Kaggle:

- Sea level rise from 1993 to present
- Sea level rise data from 1880
- Polar ice extent data (Arctic and Antarctic)
- Dataset of cities susceptible to flooding

## Stack

- **Frameworks/Libraries**: Streamlit, Pandas, Numpy, Plotly Express, Matplotlib, Seaborn, Prophet, OpenAI.

## How to Use

To run the app locally:

1. **Clone the repository**
2. **Run the app**: streamlit run main.py

-Alternatively, you can access the app directly via Streamlit site.

## Pain Points

- Limited data for robust machine learning models; Prophet used for forecasting with available data.
- Initial visualization challenges addressed by adding a clearer graph representation.
- Chatbot integration enhances user experience by providing detailed data insights.

## Next Steps

- Improve chatbot functionality by training on more specific prompts.
- Integrate machine learning predictions with city data for accurate flood risk estimations.
- Expand data sources to enhance analysis and prediction accuracy.




