# Applied Data Science Capstone - IBM Data Science Coursera
In this capstone, we aim to predict the success of Falcon 9 first stage landings. SpaceX's unique ability to reuse the first stage significantly reduces launch costs compared to other providers, making it a crucial factor in determining the overall cost of a launch. By accurately predicting the first stage's landing outcome, we can estimate the cost of a launch, which can be valuable information for companies considering bidding against SpaceX for rocket launches. Throughout this module, we will gain necessary tools and knowledge to tackle this problem effectively.

1. [Complete the Data Collection API Lab](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/jupyter-labs-spacex-data-collection-api.ipynb)
- Make a ```GET``` request to the SpaceX API. Do some basic data wrangling and formating:
  - Request to the SpaceX API and clean the requested data
2. [Complete the Data Collection with Web Scraping lab](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/jupyter-labs-webscraping.ipynb)
- Web scraping Falcon 9 launch records with ```BeautifulSoup```:
  - Extract a Falcon 9 launch records HTML table from [Wikipedia](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)
  - Parse the table and convert it into a Pandas data frame
3. [Data Wrangling](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/labs-jupyter-spacex-Data%20wrangling.ipynb)
- Perform exploratory data analysis and determine training labels:
  - Exploratory data analysis
  - Determine training labels
  
4. [Complete the EDA with SQL](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/jupyter-labs-eda-sql-coursera_sqllite%20(2).ipynb)
- Load the dataset into the corresponding table in a Db2 database.
- Create and execute SQL queries to select and sort data to answer assignment questions.

5. [EDA with Visualization Lab](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/jupyter-labs-eda-dataviz.ipynb.jupyterlite%20(1)(1).ipynb)
- Perform exploratory data analysis and feature engineering using ```Pandas``` and ```Matplotlib```:
  - Create scatter plots and bar charts to analyze data in a ```Pandas DataFrame```.
  - Write Python code to conduct exploratory data analysis by manipulating data in a ```Pandas DataFrame```.

6. [Interactive Visual Analytics with Folium lab](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/lab_jupyter_launch_site_location.jupyterlite%20(1)(1).ipynb)
- Perform more interactive visual analytics using ```Folium```:
  - Mark all launch sites on a map.
  - Mark the success/failed launches for each site on the map.
  - Calculate the distances between a launch site and its proximities.

7. [Build an Interactive Dashboard with Ploty Dash](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/spacex_dash_app.py)
- Build a ```Plotly Dash``` application for users to perform interactive visual analytics on SpaceX launch data in real-time.
- This dashboard application contains input components such as a dropdown list and a range slider to interact with a pie chart and a scatter point chart.
8. [Complete the Machine Learning Prediction lab](https://github.com/lamtran13/Data-Science-Capstone/blob/bd94decccba8b40ceccf8285dae721c03e481609/SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite(2).ipynb)
- Perform exploratory data analysis and determine training labels:
  - Create a column for the class.
  - Standardize the data.
  - Split into training data and test data.
  - Find the best hyperparameters for SVM, Classification Trees, and Logistic Regression.
  - Determine the method that performs best using test data.

## Sources: 
All sources are from the Applied Data Science Capstone course on Coursera, provided by IBM Data Science.
