# udacity-unsupervised-learning
Implementation of the Project 3 of the "Machine Learning - Introduction Nanodegree by Udacity". Using proprietary data on a company's customers and demographics of Germany, a clustering model was trained to describe customers characteristics.

## Context

This project is part of the "Machine Learning Introduction" Nanodegree by Udacity, as part of the requriements to graduate. Its objective is to develop a clustering model that is able to describe customers characteristics, taking demographics of Germany as a base for classification.

It was necessary to employ data engineering techniques, as well as a PCA analysis and finally a clustering model.

## Construction

The analysis started witht the demographics data of Germany.

The data had to go throught several engineering phases. The main issue to resolve was the **large amount of missing information**.

Then, a PCA analysis was done to summarize the **+70 features into 8 main components**. To the PCA transformed data, a clustering model was applyed to outline **18 clusters**.

The clustering model was applyed to the customers' data. The proportions of each cluster were compared between the demographics data and the customers data. The most discrepant proportions indicated the most proeminant features of the customers.

## Result

The analysis showed that the company's customers tend to have better life conditions, be less open-minded and live in less crowded areas.
