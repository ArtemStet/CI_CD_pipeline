# Overview

In this project, we will build a Github repository from scratch and create a scaffolding that will assist you in performing both Continuous Integration and Continuous Delivery. We'll use Github Actions along with a Makefile, requirements.txt and application code to perform an initial lint, test, and install cycle. Next, we'll integrate this project with Azure Pipelines to enable Continuous Delivery to Azure App Service.

## Project Plan

* A link to a Trello board for the project: https://trello.com/b/IO6wfqrI/project-ci-cd
* A link to a spreadsheet: https://docs.google.com/spreadsheets/d/1lQva3W4fR6LvbDaEz3O3PD10gi5qVnGgqO-b0LISt9I/edit#gid=1348135932 

## Instructions

* Architectural Diagram 
![image](https://user-images.githubusercontent.com/83006335/180063741-06d147bd-8c45-4072-a2da-3875560bc672.png)

Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project cloned into Azure Cloud Shell

<img width="1422" alt="Screenshot 2022-07-18 at 15 04 28" src="https://user-images.githubusercontent.com/83006335/180242457-50b0de1d-ea05-449f-9559-d670b9f4fe96.png">

* Passing tests that are displayed after running the `make all` command from the `Makefile`
<img width="1423" alt="Screenshot 2022-07-18 at 16 09 19" src="https://user-images.githubusercontent.com/83006335/180242335-5c22283b-9903-4414-99a7-728af606e2e7.png">

* Output of a test run
<img width="1428" alt="Screenshot 2022-07-18 at 16 16 13" src="https://user-images.githubusercontent.com/83006335/180241064-47cb1e1a-acfb-4a7c-b4cf-1ff6d8284ad4.png">

* Running Azure App Service from Azure Pipelines automatic deployment

<img width="1428" alt="Screenshot 2022-07-21 at 13 50 46" src="https://user-images.githubusercontent.com/83006335/180240839-a43df2e1-1526-403b-948c-29f558b78657.png">


<img width="1427" alt="Screenshot 2022-07-21 at 16 18 34" src="https://user-images.githubusercontent.com/83006335/180240676-48405f47-9862-48e6-9b0a-dd2f10f94299.png">


The output of make_predict_azure_app.sh:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```
<img width="1415" alt="Screenshot 2022-07-21 at 16 19 10" src="https://user-images.githubusercontent.com/83006335/180240239-f0d91cd4-bdc7-40c1-a972-cecc98d8cc1a.png">



* Output of streamed log files from deployed application
<img width="1428" alt="Screenshot 2022-07-21 at 16 29 41" src="https://user-images.githubusercontent.com/83006335/180240062-7b193784-1fc9-45ff-903b-116f22b48207.png">

> 

## Enhancements

* Adding more test cases to improve the app
* Creating a UI for making predictions with different variables
* Using Github Actions 

## Demo 

<TODO: Add link Screencast on YouTube>


