# EYEO Case Study

Adtech for the topics API  

## Question 1  

Q: Please provide us with a work sample of yours that you are proud of (at least 100 lines of code, preferably in Python), written during the past year.  

The notebooks below sorts images using the Clip VitL14 model. For more impressive pure coding skills, look at the TOPICS notebooks from technical analysis.  

### Sorting Macron "you dont say" memes

https://github.com/louispaulet/docker_stable_diffusion_v2/blob/master/project/clip_compare_macron_caricatures.ipynb  

### Sorting paintings between "framed" and "unframed"  

https://github.com/louispaulet/sort_framed_and_unframed_paintings  
https://github.com/louispaulet/ai_art_ressources/blob/main/clip_interrogation/separate_framed_and_unframed_paintings_using_CLIP.ipynb  

## Question 2  

Q: How would you design an adtech service that would leverage Chrome’s Privacy Sandbox Topics API proposal in the most optimized way?

### Notebooks used to create and analyze the 2Topics x 1M domains dataset

First notebook performs simple dataset exploration and initial test of Google Topics classifier.  
https://github.com/louispaulet/eyeo_case_study/blob/main/EYEO_1_Exploration_TopicsModelExecution.ipynb  

Second notebook infers 2 topics for all domain names (split into 2 and 2b versions for parallel computing).  
https://github.com/louispaulet/eyeo_case_study/blob/main/EYEO_2_Compute_TopicsModelExecution.ipynb  

The first visualisation notebook also creates a clean dataset (Kaggle Version).  
https://github.com/louispaulet/eyeo_case_study/blob/main/EYEO_3_Visualisation_TopicsModelExecution.ipynb 

More visualisations related to the dataset.  
https://github.com/louispaulet/eyeo_case_study/blob/main/EYEO_4_Visualisation2_TopicsModelExecution.ipynb

# The dataset is on Kaggle

The latest dataset is available here:  
https://www.kaggle.com/datasets/thefrenchguy/2-google-topics-for-top-1-million-domain-names  