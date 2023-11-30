# MarchMadnessMania
March Madness Mania (kaggle competition) on only men's tournaments

Participated in the March Madness Machine Learning Competition (2023) provided by Kaggle. Here is the link to the competition: https://www.kaggle.com/competitions/march-machine-learning-mania-2023/overview .

There are several notebooks that I have to show my work. The main notebook where all the work that I have finalized / am confident in is in the "data-integration" notebook. The other notebooks were done in september and october when this project was in "amateur" phase. The "data-integration" notebook is cleaner, commented, and has better logic, design, practice, methods and structure. The goal of this notebook is to model professional work. I want it to be known that this whole project has been a very big learning project for myself where I am not confident in the model and it's predictions, however I continue to research ways to improve it and overall am trying to do industry-standard work. 

Goals for the future include:
  1. Turning the notebook in .py files so I can apply this model to each new years tournmanent data.
  2. Creating new features to help the model predict better (examples: ELO rating, coaching strength, strength on the road, more categorical features)
  3. More hyper-parameter tuning, the main work I have done is feature engineering / data integration, EDA and testing/comparing models to eachother to find the best grouping of features to be used.

Below is a description of each of the other notebooks that I wrote in September and October of 2023:

The first notebook (ML WORK) is where I did all my data aggregating and pandas work to create my final dataset that has all of the tournament games with each team's individual features side by side. Instead of using the same feature twice (i.e. points per game for team A and team B, I did teamAPPG-teamBPPG). There's a bunch more logic I did here to make sure that it would be compatible for modelling. I also did a lot of feature engineering in this notebook. 

The second notebook I worked on is the EDA notebook where I made a bunch of plots and looked for and stories in the data. Finally made some heatmaps to see which features correlate with the target variable. 

Lastly the third notebook is called modelling. Where I am working on the pipeline for modelling the data and getting the best predictions possible without overfitting. 
