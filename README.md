# Analysing News Articles


![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white) [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](URL_TO_YOUR_APP)

<div id="main image" align="center">
  <img src="https://github.com/ereshia/2401FTDS_Classification_Project/blob/main/announcement-article-articles-copy-coverage.jpg" width="550" height="300" alt=""/>
</div>

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. MLFlow](#mlflow)
* [6. Streamlit](#streamlit)
* [7. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

In today’s digital age, efficiently managing the vast amount of news content is a significant challenge for news outlets. Our team at DataInsight Solutions has been brought on board as data science consultants to develop a sophisticated news classification system. This project will use machine learning and natural language processing (NLP) to improve content categorization and enhance the reader experience.

We will build an end-to-end system that includes data loading, preprocessing, model training, evaluation and deployment through a user-friendly Streamlit interface. This will ensure accurate classification of news articles, optimizing content management for the outlet and providing a more personalized experience for readers.

The key stakeholders who will benefit from our solution are:

- Editorial Team: Simplified workflows and better article organization.
- IT/Tech Support: Easy integration and deployment of advanced models.
- Management: Increased operational efficiency and valuable strategic insights.
- Readers: More personalized and engaging news content.

DataInsight Solutions aims to showcase the practical application of data science in solving real-world problems. Our project will emphasize the importance of thorough data preprocessing, selecting appropriate models, and rigorous performance evaluation. Deploying our solution with Streamlit ensures accessibility and usability for non-technical stakeholders. 

The aim of this study is to develop a machine learning-based news classification system that accurately categorizes news articles, improving content management for the news outlet and enhancing the reader experience. This system will streamline workflows for the editorial team, simplify integration and deployment for IT/tech support, increase operational efficiency for management and provide more personalized and engaging content for readers. The project will encompass the entire workflow from data loading and preprocessing to model training, evaluation and deployment using Streamlit for a user-friendly interface.

Ours objectives are as follows:
- Data Preprocessing the text data
- Generate insights that will inform model selection and feature engineering
- Evaluate 5 different models suitable for text classification
- Develop a web application using Streamlit to provide an interface for the classification model.


## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset is comprised of news articles that need to be classified into categories based on their content, including `Business`, `Technology`, `Sports`, `Education`, and `Entertainment`. You can find both the `train.csv` and `test.csv` datasets [here](https://github.com/ereshia/2401FTDS_Classification_Project/tree/main/Data/processed).

**Dataset Features:**
| **Column**                                                                                  | **Description**              
|---------------------------------------------------------------------------------------------|--------------------   
| Headlines   | 	The headline or title of the news article.
| Description | A brief summary or description of the news article.
| Content | The full text content of the news article.
| URL | The URL link to the original source of the news article.
| Category | The category or topic of the news article (e.g., business, education, entertainment, sports, technology).

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
+ `Seaborn 0.12.2`
+ `nltk 3.8.1`
+ `mlflow 2.4.1`
+ `re 2.2.1`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
## 5. MLFlow<a class="anchor" id="mlflow"></a>

MLOps, which stands for Machine Learning Operations, is a practice focused on managing and streamlining the lifecycle of machine learning models. The modern MLOps tool, MLflow is designed to facilitate collaboration on data projects, enabling teams to track experiments, manage models, and streamline deployment processes. For experimentation, testing, and reproducibility of the machine learning models in this project, you will use MLflow. MLflow will help track hyperparameter tuning by logging and comparing different model configurations. This allows you to easily identify and select the best-performing model based on the logged metrics.

- Please have a look here and follow the instructions: https://www.mlflow.org/docs/2.7.1/quickstart.html#quickstart

## 6. Streamlit<a class="anchor" id="streamlit"></a>

### What is Streamlit?

[Streamlit](https://www.streamlit.io/)  is a framework that acts as a web server with dynamic visuals, multiple responsive pages, and robust deployment of your models.

In its own words:
> Streamlit ... is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

> It’s a simple and powerful app model that lets you build rich UIs incredibly quickly.

[Streamlit](https://www.streamlit.io/)  takes away much of the background work needed in order to get a platform which can deploy your models to clients and end users. Meaning that you get to focus on the important stuff (related to the data), and can largely ignore the rest. This will allow you to become a lot more productive.  

## 7. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Clement Mphethi](https://github.com/HoOdpHarMxcisT)                                        | clementmphethi@gmail.com
| [Koena Mahladisa](https://github.com/koenaMahladisa)                                        | kmahladisa9@gmail.com
| [Naledi Mogale](https://github.com/Andriena)                                                | nalediandriena@gmail.com
| [Neo Radebe](https://github.com/umkhulubhungane)                                            | radebeneo17@gmail.com
| [Nolwazi Mndebele](https://github.com/NolwaziMND)                                           | mndebelenf@gmail.com
| [Tshepiso Mudau](https://github.com/tshepisoMudau)                                          | mudaureneilwe@gmail.com
