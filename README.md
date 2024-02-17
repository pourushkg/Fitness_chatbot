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


```bash
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

### For fine tuning I use these pdf's
```bash
1. Atomic_Habits.pdf
2. Bigger_Leaner_Stronger.pdf
3. Complete_Guide_to_Food_for_Sports.pdf
4. contribution_of_physical_activity_in_fitness.pdf
5. How_Not_to_Die.pdf
6. You_Are_Your_Own_Gym_pdf.pdf
```
## Run app.py file
## Go to the url given to get the fitness chatbot interface 


