# 2024 United States presidential election research

## Goal :heavy_check_mark:

- To identify trends and key topics in online discussions during 2024 United States presidential election using Topic Modeling

## Source of data :microscope:

- Reddit, r/politics
- All data was collected by me personally

## Web version of the research notebook :computer:

- Deployments - github-pages
- Link: <https://leobellap.github.io/2024-US-presidential-election-research/>

## Main packages :wrench:

- PRAW: to load data from Reddit
- re: to clean data from noise using regular expressions
- scikit-learn: to remove stopwords from a dataset
- pandas: to convert the dataset to a dataframe
- SentenceTransformers: to create text embeddings
- cuML: to reduce dimensions and cluster embeddings with the power of GPU
- seaborn: to visualise data distribution
- BERTopic: to extract topics from the data

## Repository structure :gear:

- Research notebooks can be found in a folder 'notebooks'
- Gathered data can be found in a folder 'notebooks/original_data'
- 'load_data.ipynb' file is used to gather data from Reddit
- 'hot_topics_research.ipynb' and 'top_topics_research.ipynb' files are part of the previous research project. They were used to do a topic modelling of online discussions on Reddit during the last 24 hours.
- 'dynamic_topics.ipynb' file containes the current research project. It uses data gathered during previous research projects to provide comprehensive view on online discussions on r/politics subreddit during 2024 US Elections.
