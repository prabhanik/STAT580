# Project Template

Template adapted from [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)


Following this directory structure
```
|--template             <- Project root level, rename accordingly
README.md
  |--Scripts            <- Folder with all your R scripts
    |--FeatureEnginnering    <- Feature engineering scripts
    |--Modeling              <- Modeling scripts
    |--Requirements  
        |--requirements.r   <- The required libraries for reproducing 
  |--Volume             <- Folder with data and R objects 
    |--Data
        |--External      <- Any external data that you might have used 
        |--Modified      <- Pre-processed data  
        |--Raw           <- Raw client data
        |--Results       <- Any data sets with results you want client to have
    |--Workspaces    <- Any R objects used in the scripts
|--.getignore       <- List of files not to sync with github
```
