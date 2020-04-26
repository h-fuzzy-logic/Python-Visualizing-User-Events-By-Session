# Python-Visualizing-User-Events-By-Session
 Event data is often created as users navigate from screen to screen while using websites and other software. Engineering features for this type of data can be tricky. There can be lots of data and it may first seem unpredictable and hard to wrangle. Kaggle’s 2019 Data Science Bowl offers a wonderful opportunity to practice wrangling this type of data. The goal of the competition is to determine how different media types can improve performance on in-game assessments.  And the goal of this repo is to do some Exploratory Data Analysis to try to understand the gameplay events of a "typical" user.

# Related Blog Post
https://h-fuzzy-logic.github.io/blog/intuition-user-events/

# Tools Used
* Jupyter Notebook
* Python, Pandas, Seaborn

# Technical Highlights
* Used read_csv from pandas to read a CSV file from the competition.
* Used group_by and agg from pandas to get summaries by user, by session.
* Used cumcount() from pandas to generate an "index" by user/session group.  
* Used merge from pandas to combine a summary dataframe with the events dataframe (because calculating everything at once seemed overly complicated).
* Plotted events using Seaborn scatterplot.  
* Visualizations provide a quick summary of copious user event data.  

# Getting Started
* The data (CSV file) is not included in the repo and can be obtained from Kaggle's site. 
* All required imports are in one cell at the top of the notebook.
