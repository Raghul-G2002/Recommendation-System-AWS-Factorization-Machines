# Recommendation-System-FM
This project aims to build a recommendation system using MXNet models and AWS SageMaker Factorization Machines Algorithm. We will be using the Movielens dataset, which is a popular movie rating dataset containing a large number of ratings from users for movies. We will build a model that predicts the rating a user would give a movie based on their past ratings and preferences.

## Prerequisites

To run this project, you will need the following:

- Python 3.6 or later
- AWS account
- AWS SageMaker instance
- Movielens dataset

## Installation

Clone this repository to your local machine.
```
git clone https://github.com/Raghul-G2002/Recommendation-System-FM.git
```

## Usage

- Download the Movielens dataset from [here](https://files.grouplens.org/datasets/movielens/ml-100k.zip).
- Upload the dataset to your AWS S3 bucket.
- Open the recommendation_system.ipynb notebook using Jupyter Notebook on your SageMaker instance.
- Update the BUCKET_NAME variable to your S3 bucket name.
- Follow the instructions in the notebook to train and deploy the recommendation model.

## Credits

This project is based on the work of AWS Samples and Apache MXNet.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
