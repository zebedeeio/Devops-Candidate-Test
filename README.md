**IMPORTANT Dislaimer** If you are unfamiliar with the material, you may spend more than 12 hours on Steps 1–6. There is no strict deadline, but please communicate your timeline and progress. Treat this as a learning opportunity, with no guarantee of compensation or a job upon completion.

There are 2 optional sections if you find yourself with more time or want more of a challenge.
- If doing the terraform optional section, please request credentials as early as possible.

# Task
### Step 1:
- PLEASE DO NOT FORK THIS PROJECT: Setup a github or a gitlab repo for your project. Use your repo for all code/config/scripts/documents for the project. Send us the link to view your personal repo.

### Step 2: 
- Create an application with an API. (Use any language you would like)

This API will have minimum 3 endpoints.
 - /health is a healthcheck which returns a 200 "OK" "I'm healthy"
 - /metrics is a prometheus exported metrics page used for scrapping stats from this application.
    - Have at least 1 metric exported, feel free to make other ones.
- A 3rd endpoint that will help trigger additional stats / usage in the application.

### Step 3: 
- Dockerize the application you created.
- Make sure while running the docker container you can still access the endpoints.

### Step 4: 
- Run prometheus and have it sucessfully scrape data from the /metrics endpoint.

### Step 5:
- Use Grafana to query prometheus, display the metric(s) in a dashboard panel.

### Step 6: 
Note: It is entirely up to you if you want to use docker-compose or other docker tooling. Make sure to have a clear and tested README.md on how one could host this locally with only docker installed.
_____________________________________________
_____________________________________________
_____________________________________________
# Optional 

## Hosting 
- Host this microservice with a public endpoint.
- Publish your docker image on dockerhub or AWS ECR.

## Terraform Automation:
- Terraformize this application and infrastructure with AWS. (We are happy to help provide an AWS environment for you if needed).

## CI/CD
- Be able to spin up and spin down this infrastructure with ease via a cicd pipeline.
