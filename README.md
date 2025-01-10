# ABCDEats Inc: Marketing Analytics Interface (Extra Work)

App: https://dminterfacedesigngit-idfghuzzv3vpdnnvvyp4as.streamlit.app/


**Group 90**  
Catarina Gonçalves Nunes, 20230083  
Fall/Spring Semester 2024-2025


## Motivation

This project introduces an interactive application aimed at helping the ABCDEats Marketing Team explore and interact with customer segmentation results from previous exploratory data analysis (EDA). The tool allows users to visualize cluster data, predict cluster assignments, and suggest strategies tailored to specific customer groups. By enabling real-time collaboration and documentation of ideas, the application supports team discussions and improves the efficiency of brainstorming during meetings.

## The Interface

The application is built using Streamlit and consists of four main pages:

1. **Home Page**: The entry point where users are introduced to the platform.
2. **Cluster Analysis Page**: This page visualizes and analyzes customer clusters using a variety of tools.
3. **Cluster Prediction Page**: Users can input data to predict which cluster a new customer belongs to.
4. **Suggestions Page**: A place for users to submit their strategy ideas or feedback, which are saved for later review.

### Key Features:

- **Cluster Analysis**: Users can compare clusters using histograms, violin plots, radar plots, and t-SNE visualizations. They can also analyze individual clusters through RFM (Recency, Frequency, Monetary) analysis and Market Basket Analysis (MBA) to uncover customer behavior patterns.
  
- **Cluster Prediction**: The app allows users to input customer data and predict their cluster assignment using a squared Euclidean distance method. If data contains outliers, a Decision Tree Classifier is used to classify them appropriately.

- **Suggestions Page**: Users can submit their ideas for visualizations or marketing strategies. These suggestions are stored in a CSV file for team review.

## Conclusion

This interactive application significantly enhances the ABCDEats Marketing Team's ability to explore customer segmentation results. It offers intuitive visualizations, predictive capabilities, and a system for capturing and organizing strategic ideas. By facilitating better data exploration and collaboration, the tool helps the team develop more effective, targeted marketing strategies.

## Bibliographical References

- IUYasik. (2023, October 4). Market basket analysis & Apriori algorithm using Zhang’s metric. Medium. [Link](https://medium.com/@iuyasik/market-basket-analysis-apriori-algorithm-using-zhangs-metric-708406fc5dfc)
- Kimnaruk, Y. (2022, September 18). What are market basket analysis and the Apriori algorithm? Medium. [Link](https://yannawut.medium.com/what-are-market-basket-analysis-and-the-apriori-algorithm-fe0e8e6e34d)
- Maaten, L. v. d., & Hinton, G. E. (2008). Visualizing data using t-SNE. Journal of Machine Learning Research, 9, 2579–2605. [Link](https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf)
- Noualibechir. (n.d.). Adapted t-SNE code. GitHub. [Link](https://github.com/noualibechir)
- Sant'Anna, L. (2023, November 22). Segmentação de clientes com RFM em Python. Medium. [Link](https://medium.com/@larixgomex/segmenta%C3%A7%C3%A3o-de-clientes-com-rfm-em-python-3a97e534ffa1)
- Soni, P. (2020, March 9). Do decision trees need feature scaling? Towards Data Science. [Link](https://towardsdatascience.com/do-decision-trees-need-feature-scaling-97809eaa60c6)
