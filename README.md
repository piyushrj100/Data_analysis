# Data_analysis

This a beginner level analysis  on  the latest Stackoverflow developers Survey 2022  



The dataset can be downloaded from https://insights.stackoverflow.com/survey    
After downloading the dataset, unzip it and save the extracted files in a directory  

In my case, I saved the files in a folder called StackOverflow_2022. The tree structure looks like this :


.   
├── StackOverflow2022_EDA  
|   ├── .gitignore  
│   ├── StackOverflow_2022  
│   │   ├── README_2022.txt  
│   │   ├── so_survey_2022.pdf  
│   │   ├── survey_results_public.csv  
│   │   └── survey_results_schema.csv  
│   └── Survey_2022.ipynb  



Survey_2022.pynb is the notebook where all the analysis has been performed.   
As the dataset is large in size(>100MB), you might get issues to push it to github. 


Make a .gitignore file and add the below to this :  
survey_results_public.csv  
survey_results_schema.csv  


This gitignore will make sure that these 2 large files are not pushed to github repo.   
 
