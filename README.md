# Formula One Analytics
Jupyter notebooks with the automatized process to obtain the necessary data from F1 API, resulting in Looker interactive dashboards.
- Course: Web Analytics
- Final grade: 9.2/10

## Tools and covered topics
- Jupyter Notebook
- Google Looker Studio
- Python libraries: numpy, pandas, sqlearn, matplotlib, seaborn
- Manipulation of temporal series and prediction: AutoRegressive Integrated Moving Average (ARIMA)
- ML models to compare their feature importance: MLPs, Gradient Boosting, DTs, Random Forest, Linear Regression

## Objective
The primary goal is to work with Formula One API Ergast (see Documentation [here](https://ergast.com/mrd/)), as well as to perform Data Analytics and a comparison of Machine Learning techniques from the dataset extracted.

## Key Features

- **Driver Performance Analysis**: Explore how drivers perform across different races and seasons.
- **Race Strategy Optimization**: Analyze race data to optimize pit stop strategies and track performance.
- **Team Comparison**: Compare the performance of different F1 teams over time.
- **Data Visualization**: Visualize complex F1 data in intuitive and informative ways.

## Expected Results
The final result should represent accurately the statistics and outputs of the ML models for the Formula One drivers, cars and teams in a Looker Dashboard.

Some examples of the ML models to compare are:
- Random Forest
- Linear Regression
- MLP
- Gradient Boosting
- Decision Trees

Some examples of analytics metrics performed are: 
- Clustering of drives thourghout F1 history
- Lap times in each circuit along history
- Boxes and result per circuit and year
- Evolution of the champions' points per year

## Repository contents
- .ipynb notebook with the data extraction, cleaning and visualizations.
- PDF with the final dashboards (which can be found in the following [link](https://lookerstudio.google.com/reporting/003df30b-544c-43a5-99d8-fa5aab70ffff))

## Evaluation Criteria
The project will be evaluated based on the following criteria:
1. Code Execution: Your code must run without errors.
2. Scalability: Your implementation should be scalable, tested with datasets ten times larger on a cluster with 80 execution workers.
3. Documentation: Adequate code documentation is required.
4. Complexity of the Machine Learning techniques: Advanced techniques must be performed.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
Feel free to customize it further to match your repository's specific details and needs!
