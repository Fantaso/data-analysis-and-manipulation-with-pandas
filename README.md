<!-- logo -->
<a href="https://www.fantaso.de">
<img src="/readme/fantaso.png" align="right" />
</a>

<!-- header -->
<h1 style="text-align: left; margin-top:0px;">
  Data Analysis & Manipulation With Pandas
</h1>

> Data analysis with Pandas, Numpy, Matplotlib & Seaborn.


<!-- build -->
<!-- [![Build Status][travis-image]][travis-link] -->


Project consists to analyse a publicly available movie dataset found in https://www.kaggle.com/beyjin/movies-1990-to-2017
and use Python tools like Pandas in order to get some initial insights about the dataset
and finally proceeding to clean, transform and save a new version of the dataset in a better structure
thinking about storing the data in a database.

<br><br>

---
## Index:
- #### Introduction
    1. `initial_insights.ipynb`
    2. `clean_datasets.ipynb`
    3. `cleaned_datasets_grouped.ipynb`
    4. Raw & Cleaned Datasets
    
- #### Information
- #### Maintainer

<br><br>


---
## Introduction
There are 3 files which you can look in this exact order
1. `initial_insights.ipynb`

    Taking a first look to the raw datasets and finding
    insights that help us understand the data we will be processing
    and also to get an overview on how we should structure the datasets
    as if we where going to store the data into a database
    
    _**Note:** insights and conclusions can be found in the jupyter file_
    
2. `clean_datasets.ipynb`

    We go here through the whole process standardizing the data types,
    extracting columns that should go in a different dataset
    and saving the and cleaned datasets.
    
    Note: Target Database Schema
    ![database-schema][db-schema] 
     
3. `cleaned_datasets_grouped.ipynb`
    
    Here we take the cleaned datasets and we just join them all together
    into a big and only one dataset

4. Raw & Cleaned Datasets
    
    - The original datasets (raw) are located in the folder `orignal_datasets/`
    - The output generated datasets (cleaned) will be located in the folder `output/`

<br>

## Information:
| Technology Stack |  |  |
| :- | :-: | :- |
| Python                    | ![language][python]                   | Language |
| Pandas                    | ![data-analysis][pandas]              | Data Analysis & Manipulation |
| Numpy                     | ![data-computing][numpy]              | Data Computing |
| Matplotlib                | ![data-visualization][matplotlib]     | Data Visualization |
| Seaborn                   | ![data-visualization][seaborn]        | Data Visualization |

<br><br>


## Maintainer
Get in touch -–> [fantaso][fantaso]



<!-- Links -->
<!-- Profiles -->
[github-profile]: https://github.com/fantaso/
[linkedin-profile]: https://www.linkedin.com/
[fantaso]: https://github.com/fantaso/
<!-- Extra -->

<!-- Repos -->
[github-repo]: https://github.com/Fantaso/data-analysis-and-manipulation-with-pandas

<!-- Builds -->
[travis-link]: https://travis-ci.org/
[travis-image]: https://travis-ci.org/

<!-- images -->
[python]: readme/python.png
[pandas]: readme/pandas.jpeg
[numpy]: readme/numpy.png
[matplotlib]: readme/matplotlib.png
[seaborn]: readme/seaborn.png

[db-schema]: readme/movies_database_diagram.jpg