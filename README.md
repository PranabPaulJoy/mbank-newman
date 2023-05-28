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
- https://docs.google.com/spreadsheets/d/1Xk7c1t757wVcOpx7k-bGOiI9SSah3W6G/edit?usp=sharing&ouid=110143819451733453606&rtpof=true&sd=true

## Bug report for this project (Link is given below):
- https://docs.google.com/spreadsheets/d/1QA997U19yanklwkRpzpI6txA9pVKa04F/edit?usp=sharing&ouid=110143819451733453606&rtpof=true&sd=true

## Based on following Scenario this Positive and Negative case has been Created

1. At first Admin creates an agent and random 2 customers
2. SYSTEM account Deposit some money to the agent
3. Agent Deposit some money to the customer 1
4. The Customer Withdraw some amount from agent
5. The Customer Send money to another customer
6. The Customer Payment to the merchant
7. The Agent check balance & statment
8. The Customers check balance & statement

## Newman Report:

![Newman Report Summary](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/17016445-78ed-45aa-adc7-50663e5326d5)

![Newman Report Summary](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/0529965f-da8a-4f97-b7ba-f33b925ba2e2)

![Newman Report Request](https://github.com/PranabPaulJoy/mbank-newman/assets/127541697/8ad70fa2-2954-4a8f-8663-c184a72cc68d)

