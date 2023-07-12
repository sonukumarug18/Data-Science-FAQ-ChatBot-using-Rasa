# Data Science FAQ ChatBot #

## 🏄 Introduction ##
The purpose of this repo is to showcase a contextual AI assistant built with the open source Rasa framework.

It is a bot made as a project by me during internship at SmartBridge. It supports the following user goals:

- It helps new students to get familiar about the Data Science.
- Helps with getting familiar with new environment.
- Solves the most frequent issues for the student.
- Solves the issues regarding the fees, education type, admission process etc.
- Easy Interraction.

## 👷‍ Installation ##
To install please clone the repo and do follow the link:

 https://rasa.com/docs/rasa/user-guide/installation/
 
 ## 🤖 To run bot : ##
 
 Use `rasa train` to train a model.
 
 ## to test a bot ##
 After doing a `rasa train`, run the command:

`rasa shell`

## 👩‍💻 Overview of the files ##

`data/core/` - contains stories

`data/nlu` - contains NLU training data

`domain.yml` - the domain file, including bot response templates

`config.yml` - training configurations for the NLU pipeline and policy ensemble
 
 ## Output ##
![Screenshot 1](https://github.com/sonukumarug18/Data-Science-FAQ-ChatBot-using-Rasa/blob/master/screenshots/screenshot1.png)
