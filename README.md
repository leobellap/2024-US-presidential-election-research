# 2024 United States presidential election research

## Goal :heavy_check_mark:

- To identify and analyze trends in online discussions during 2024 United States presidential election using topic modeling

## Source of data :microscope:

- Reddit, r/politics

## Web version of the research notebook :computer:

- Deployments - github-pages
- Link: <https://leobellap.github.io/2024-US-presidential-election-research/>

## Main packages :wrench:

- PRAW: to load data from Reddit
- re: to clean data from noise using regular expressions
- spaCy: to remove stopwords from a dataset
- pandas: to convert the dataset to a dataframe
- SentenceTransformers: to create text embeddings
- cuML: to reduce dimensions and cluster embeddings with the power of GPU
- seaborn: to visualise data distribution
- BERTopic: to extract topics from the data
