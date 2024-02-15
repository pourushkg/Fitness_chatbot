# Fitness_chatbot

## 1. create a new environment name fitness_chatbot by using python=3.8

```bash
conda create -n fitness_chatbot python=3.8 -y
```

### 2. Activate the new repository

```bash
conda activate fitness_chatbot
```

### 3. visit the pine cone website and create a api key for creating clusters
```bash 
https://app.pinecone.io/organizations/-NmpTE4VYpR96DKF71NT/projects/gcp-starter:69uqnaz/keys
```
## To create pine cone index with vector dimension 384


### 4. Create a .env file in the root directory and add your Pinecone credentials as follows:

```bash 
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```



