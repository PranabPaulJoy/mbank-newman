# MBank-Rest-API-Newman

## Project Summary:
- This project has automated user API from Postman using Newman
- In this project, we can see a few basic mobile banking operations like Depositing, Send Money, Payment, Withdrawing, and Balance Check.
## Technology used:
- Postman
- Newman
## Editor:
- VS Code
## Pre Requisites:
- NodeJS
- Git
## How to run this project
- clone this project
- Open with any code editor / Command Shell
- ## Give this following command :
- ``` npm init -y ```
-  ``` npm i newman ```
-  ``` npx newman run .\collection\mbank.js ```
-  ``` npm i newman-reporter-htmlextra ```
-  ``` node .\report.js ```



## API Documentation:
- https://documenter.getpostman.com/view/27452892/2s93m7WMLp

## Test Cases for this project (Link is given below): 
- https://docs.google.com/spreadsheets/d/1yLzROG3W5J4HhHzH8wULBNJQUC2DoAm3/edit?usp=sharing&ouid=102526777056504026911&rtpof=true&sd=true

## Bug report for this project (Link is given below):
- https://docs.google.com/spreadsheets/d/1XXIdrY2fAczTM0hihcEzJuUqz6_0RjKN/edit?usp=sharing&ouid=102526777056504026911&rtpof=true&sd=true

## Newman Report:

![Newman Report Summary](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/17016445-78ed-45aa-adc7-50663e5326d5)

![Newman Report Summary](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/0529965f-da8a-4f97-b7ba-f33b925ba2e2)

![Newman Report Request](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/8ad70fa2-2954-4a8f-8663-c184a72cc68d)

## Positive and Negative case are Created for Follwing Scenraio

1. Admin creates an agent and random 2 customers
2. Deposit some money from SYSTEM account to the agent
3. Agent deposit to any of 1 customer
4. The customer checks balance
5. Then withdraw any amount from the agent
6. And send money to the other customer
7. Then the customer will check statement
8. For each transaction, assert expected balance
