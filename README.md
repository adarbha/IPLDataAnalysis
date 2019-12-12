## Table of Contents
1. ### Installation
    This code is run on Python 3.6 in conda virtual environment. Please install all the python dependencies using **requirements.txt** 
2. ### Project Motivation
    My goal is to perform descriptive analysis on data from one of the most popular sport leagues in India called the Indian Premier League. This is a Cricket League that is played every summer in India and one of the most watched sporting leagues in the world. League data is collected for the year range 2008-2019. This is a descriptive analysis of the league data which aims to introduce the league to the unintiated. Questions addressed are
     - How many teams participated in the league every season? How many seasons each team participated in and who won the championship most number of times
     - Who is the better team in terms of winning percentages and captain smartness - an inhouse metric of captain intelligence!? 
     - Check the trends of the two metrics above based on season
     - There is a hypothesis that teams to tend accelerate - score at a higher average - post 15 overs. Perform a statistical test to check the validity of this claim 
3. ### Files and their description
    * README.md - This file 
    * ipldata - Directory with all the data used for this analysis. Includes two csv files 
        - matches.csv - match level results and metadata
        - deliveries.csv - delivery(ball) level results
    *  images - Directory of all images used in compiling the blog. All the images are generated in the notebook
    *  DataExploration.ipynb - The master notebook where analysis is performed. A medium article is written based on the analysis done in this notebook
    *  requirements.txt - Python dependencies text file
4. ### Results
   - Team participation summarized through bar charts
   - Winning percentages and captain smartness metric plotted as trend lines
   - One-tailed t-test is performed on pre and post 15 over data to reject Null Hypothesis in favour of alt. hypothesis that post 15 over run rate is greater</b>
    The results of this analysis have been communicated in a carefully curated article in Medium [here](https://medium.com/@arjunsdarbha/ipl-descriptive-analysis-d142ae11d5f2).
5. ### Acknowledgements
    Credit to Kaggle user **Navaneesh Kumar** for providing the datasets. Licensing for the data can be found in the Kaggle page [here](https://www.kaggle.com/nowke9/ipldata/). Please feel free to use other parts of the code.