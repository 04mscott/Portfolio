# Mason's Portfolio
Welcome to my portfolio! Here I track all of my completed and in-progress projects. Many of these projects span multiple domains, including web development, machine learning, and systems programming.

## Table of Contents
Projects are grouped by area of focus, but many combine multiple technologies. Some planned projects are listed as well.

- [Full Stack](#full-stack)
- [Python / ML](#pythonml)
- [Data Science](#data-science)
- [React](#react)
- [C](#c)

## Full Stack
| Project | Skills | Description |
| --- | --- | --- |
| [Impulse - Music Recommendation App](https://github.com/04mscott/Impulse-Music-Recs) | React, FastAPI, Spring Boot, REST API, OAuth2, Docker, Redis, Celery, PostgreSQL | Full-stack music recommendation app with a swipe-based UI, built but not released due to Spotify API access restrictions. Recommends songs based on Spotify listening history using backend vector embeddings and async featurization pipelines. Swiping right automatically adds a song to the user's Spotify liked tracks. |
| [EngageCS - Student Engagement Analytics Platform](https://github.com/04mscott) | Python, Dash, Flask, PostgreSQL, Plotly, Docker, Valkey | 6-person capstone commissioned by a UMD CS instructor and deployed to production for live classroom use with approximately 140 students per session. Served as data engineer and analytics lead: designed the PostgreSQL schema, built the Canvas LMS sync pipeline, led a V2 schema migration, and authored two internal Python libraries for data processing and visualization. Delivered instructor, TA, and student dashboards with risk scoring and topic engagement analytics. |

## Python / ML
| Project | Skills | Description |
| --- | --- | --- |
| [Recommendation API](https://github.com/04mscott/Recommendation-API) | Python, FastAPI, Scikit-learn, Celery, Redis, Vector Embeddings, MySQL, Docker | High-performance API that pulls Spotify listening data, generates vector embeddings, and serves cosine similarity-based song recommendations. Designed for async background processing and integrated with the Impulse full-stack app. |
| [Air Quality Prediction App](https://github.com/04mscott/Air-Quality-App) | Python, TensorFlow, LSTM, Time Series, AWS RDS, Streamlit, OpenWeatherMap API | Trained an LSTM model on historical air pollution data to forecast 8 pollutant concentrations using real-time API inputs, achieving a test RMSE of 0.1668. Built a Streamlit dashboard for real-time monitoring and deployed on Render with a MySQL data pipeline on AWS. |
| [Face Mask Image Classifier](https://github.com/04mscott/Face-Mask-Image-Classification) | Python, TensorFlow, CNN, Image Classification, TaiPy | CNN trained to classify proper face mask usage with a TaiPy GUI for real-time predictions and confidence display from uploaded images. |

## Data Science
| Project | Skills | Description |
| --- | --- | --- |
| [Reddit AITA Data Analysis](https://masonscott.net/static/media/HW%203%20Report%20-%20Mason%20Scott.bc9e7591820ff485558a.pdf) | Python, Pandas, Statistical Testing, Matplotlib | Applied chi-square tests and data wrangling to study moral judgment patterns across political affiliations using survey data modeled on AITA-style questions. |
| [Housing Price Predictor](https://github.com/04mscott/Housing-Price-Prediction-Model-) | Python, Pandas, Scikit-learn, Linear Regression | Built and tuned linear regression models on Kaggle housing data to predict sale prices, with feature engineering and cross-validated model evaluation. |

## React
| Project | Skills | Description |
| --- | --- | --- |
| [Personal Website](https://masonscott.net/) | JavaScript, React, HTML, CSS | Personal portfolio website with smooth animations, responsive layout, and project integration. |

## C
| Project | Skills | Description |
| --- | --- | --- |
| [Sorting Algorithm Benchmarks](https://github.com/04mscott/Sorting-Functions-C-) | C, Python, ctypes, Data Visualization | Implemented 8 sorting algorithms in C and benchmarked performance across various input sizes. Used `ctypes` to interface with Python and visualized results with Matplotlib. |
