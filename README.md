# Hi! I'm Kirill Rubashevskiy

## About Me

I'm currently pursuing a Master's degree in Artificial Intelligence at the Higher School of Economics.

## Skills
### Programming & Data Tools
<div>
  <img height="32" width="32" src="https://cdn.simpleicons.org/python" alt="Python" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/pandas" alt="Pandas" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/numpy" alt="NumPy" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/scipy" alt="SciPy" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/postgresql" alt="PostgreSQL" />
</div>

### Machine Learning & Deep Learning
<div>
  <img height="32" width="32" src="https://cdn.simpleicons.org/scikitlearn" alt="scikit-learn" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/pytorch" alt="PyTorch" />
</div>

### Web Scraping & Automation
<div>
  <img height="32" width="32" src="https://cdn.simpleicons.org/selenium" alt="Selenium" />
</div>

### MLOps & DevOps
<div>
  <img height="32" width="32" src="https://cdn.simpleicons.org/apacheairflow" alt="Apache Airflow" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/mlflow" alt="MLflow" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/weightsandbiases" alt="Weights & Biases" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/docker" alt="Docker" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/fastapi" alt="FastAPI" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/git" alt="Git" />
  <img height="32" width="32" src="https://cdn.simpleicons.org/amazons3" alt="Amazon S3" />
</div>

## Professional Goals

I am open for hire and internships in impactful projects.

## Interests

Besides studies, I enjoy hiking and cooking, both of which help me maintain a creative 
and fresh perspective in my professional work.

## Work in Progress

### [Graildient Descent](https://github.com/kirill-rubashevskiy/graildient-descent)

#### Project Overview

**Graildient Descent** is a machine learning project focused on predicting the sold 
prices of high-end fashion items listed on [Grailed](https://www.grailed.com/), an 
online marketplace. The project demonstrates end-to-end ML pipeline development, from 
data collection to model deployment, working with multimodal data:

- **Tabular features**: Item attributes like brand, category, and size
- **Text features**: Descriptions, titles, and hashtags
- **Images**: Cover images of items (future work in progress)

#### Main Goals

- **Data Collection**: Build a robust data pipeline for collecting Grailed listings data
- **ETL Pipeline**: Develop an Apache Airflow-based ETL pipeline for data collection and 
processing
- **Price Prediction**: Create ML models to predict sold prices using item features
- **Deployment**: Deploy results via FastAPI service and Streamlit app

#### Current Status

- **Data Pipeline**: Successfully implemented:
  - Web scraper for Grailed sold listings
  - ETL pipeline using Apache Airflow
- **Analysis & Modeling**:
  - Completed extensive EDA for tabular and text features
  - Conducted ML experiments achieving 37.1% improvement over baseline
  - Best model: CatBoost with combined tabular and text features (RMSLE: 0.64)
- **Deployment**:
  - Deployed interactive [Streamlit app](https://graildient-descent.streamlit.app) 
    showcasing:
    - Data collection process
    - EDA visualizations and insights
    - ML experiment methodology and results

Next steps include completing image feature analysis, implementing FastAPI service for 
predictions, and exploring deep learning approaches for potential improvements.

## Completed Projects

### [Authorship Identification ML Service](https://github.com/kirill-rubashevskiy/mlds23-authorship-identification)

#### Project Overview

This machine learning service was designed to identify the authorship of texts among ten 
prominent Russian 19th-century writers. Developed as part of my master’s degree 
coursework, the project focused on natural language processing and building a full ML 
pipeline from data collection to deployment.

#### Main Goals

- **Build an End-to-End ML Pipeline**: From data collection from open sources to 
monitoring the performance of a deployed service.
- **Apply ML Techniques in NLP**: Employ machine learning algorithms tailored for 
natural language processing (NLP).
- **Get Hands-On MLOps and DevOps Experience**: Practical experience in MLOps and DevOps 
principles, including cloud storage, microservice architecture, containerization, 
deployment, and performance monitoring.

#### Project Outcomes

- **Best Model Performance**: Developed a logistic regression model using text 
statistics and Bag-of-Words embeddings, achieving a weighted F1 score of 0.85 on test 
data.
- **Service Deployment**: Successfully built and deployed a FastAPI application to 
handle predictions and integrated a Telegram bot for user interaction.

> **Note**: This project is primarily in Russian.

---