[![<CircleCI>](https://circleci.com/gh/omar-adel153/microservices-devops.svg?style=svg)](https://circleci.com/gh/omar-adel153/microservices-devops)

## Project Overview
This is a project contains a `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).


## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`
4. Test the predictions app: `./make_prediction.sh`
