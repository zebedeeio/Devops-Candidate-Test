**IMPORTANT** DO NOT spend more than **12 hours** on Steps 1-6. Try to make it to the end of step 6 and if you find yourself with extra time *somehow*, there are plenty of bonus options for you to tackle. You are expected to run out of time and not complete all the sections. 

There are 2 optional sections if you find yourself with more time or want more of a challenge.
- If doing the terraform optional section, please request credentials as early as possible.

# Task
### Step 1:
- PLEASE DO NOT FORK THIS PROJECT: Setup a github or a gitlab repo for this project. Use this repo for all code/config/scripts/documents for the project. Send us the link to view the repo.

### Step 2: 
- Create an application with an API. (Use any language you would like)

This API will have 2-3 endpoints.
 - /health is a healthcheck which returns a 200 "OK" "I'm healthy"
 - /metrics is a prometheus exported metrics page used for scrapping stats from this application.
    - Have at least 1 metric exported, feel free to make other ones.
- (optional) - a 3rd endpoint that may help trigger stats / usage in the application.

### Step 3: 
- Dockerize the application you created.
- Make sure while running the docker container you can still access the endpoints.

### Step 4: 
- Run prometheus and have it sucessfully scrape data from the /metrics endpoint.

### Step 5:
- Use Grafana to query prometheus, display the metric(s) in a dashboard panel. (Your choice).

### Step 6: 
Note: It is entirely up to you if you want to use docker-compose or other docker tooling. Make sure to have a clear and tested README.md on how one could host this locally with only docker installed.
_____________________________________________
# Hosting (This is Optional)
- Request an AWS IAM user from Zebedee via email. *if needed
### Publish Docker Image
- Publish your docker image on dockerhub or AWS ECR.

### Public Endpoint: 
- Host this microservice with a public endpoint.
    - For instance, you can use Heroku or AWS ECS/EC2

### CI/CD
- Setup a ci/cd workflow through github/gitlab that updates your live service upon code changes to the application.

# Terraform Automation (This is Optional)
- Terraformize this application and infrastructure with AWS.
- Request an AWS IAM user from Zebedee via email. *if needed
- We will give you an IAM user with access to spin up resources in your own AWS account.
- Use Terraform to spin up this infrastructure with the idea of automation and zero/minimal manual configuration.
    - (100% up to you on how you want to host these resources)
    - If you need access to an AWS service/resources that is prohibitted, let us know, and we will give you access.
