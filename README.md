# pyspark-ml-mongodb-segmentation

This project demonstrates how to implement customer segmentation using PySpark MLlib and MongoDB. It focuses on clustering customers into distinct groups based on their attributes, such as age, gender, spending score, etc., using the K-Means clustering algorithm.

## 📌 Features:

    -   MongoDB setup using Docker and docker-compose
    -   JDBC connection for PySpark
    -   Customer Data load from Kaggle site
    -   Data insertion and retrieval using PySpark
    -   Data transformation using PySpark
    -   K-Means Clustering ML Algorithm using PySpark ML Library
    -   Steps to install dependencies and configure the setup

## 🛠️ Tech Stack

    -   **ETL Tools** : PySpark
    -   **Database** : MongoDB
    -   **Language** : Python
    -   **Container** : Docker

## Prerequisites

Ensure you have the following installed on your system:

    -   Docker
    -   Python (Recommended: Python 3.13.1)
    -   Jupyter Notebook (Optional, if running manually)
    -   PySpark

## 🚀 Setup Instructions

1) Clone the repository

``` bash
    git clone https://github.com/ItisVenkatesh/pyspark-ml-mongodb-segmentation.git
    cd pyspark-ml-mongodb-segmentation
```
2) Run Docker and start containers

After starting Docker engine,

``` bash
    docker-compose up --build -d
```
This will,

    -   Start MongoDB on port 27017
    -   Start Mongo Express on port 8081

3) Mongo Express

Open the URL [http://localhost:8081](http://localhost:8081) in your browser.

Log in using below credentials.
username: admin
password: pass

Explore the created mongodb using mongo express UI.

4) Install dependencies

``` bash
    pip install -r requirements.txt
```

5) Explore the Notebook

    -   Open notebook file "ml_mongodb_pyspark.ipynb" under "notebooks" folder.
    -   Explore the notebook by running the cells from beginning.
    -   It demonstrates K-Means clustering for customer segmentation.
    -   Feel free to modify the cells and explore.

6) Stop docker container

Once done, use below command to stop docker container

``` bash
    docker-compose down
```    

## License

This project is licensed under the MIT License - see the LICENSE file for details.
