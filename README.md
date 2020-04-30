# devops-challenge

## Welcome

Welcome to Audibene's DevOps challenge :)

Please try to complete the below requirements and send us a link to your public github repo containing the solution code!

## Requirements

Please create a Jenkins pipeline (using groovy) that achieves the following behaviors on the corresponding branches:

* **Pull Request Commits:** triggers tests
* **Commits/Merges into `develop`:** docker build, push built image to registry and deploy code to kubernetes 
* **Commits/Merges into `master`:** promotes code to master branch

Things to keep in mind:

* If any specific details are ommited from the requirements, feel free to make your own assumptions and detail them in the README.md of your repository
* Feel free to use any opensource code to illustrate the behavior of your pipeline

## Expectations
By the end of your task, we expect a link to your public github repo that contains:
* A `Jenkinsfile` containing your pipeline code
* A description of all the assumptions that you have made in building the pipeline in a README.md
