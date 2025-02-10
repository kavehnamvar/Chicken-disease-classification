# Chicken-disease-classification


## Workflows

1. Update config.yaml
2. Update secrets.yaml [optional]
3. Update parmas.yaml
4. Update the entity
5. Update the configuration manager in src config
6. update the components 
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


# How to run:

## Steps:

Clone the repository:

``` 
git@github.com:kavehnamvar/Chicken-disease-classification.git 
```

## STEP 01- Create a conda environment after opening the repository

```
conda create -n chicken_classification python=3.8 -y
```
```
conda activate chicken_classification
```

## STEP 02- install the requirements

```
pip install -r requirements.txt
```
```
# Now run the following command
python app.py
```

Now, open up your local host and port

## DVC cmd

1. dvc init 
2. dvc repro
3. dvc dag

# AWS-CICD-Deployment-with-Github-Actions

## 1. Login to AWS console.

## 2. Create IAM user for deployment

```
#with specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


#Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2 

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

#Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess
```

## 3. Create ECR repo to store/save docker image

