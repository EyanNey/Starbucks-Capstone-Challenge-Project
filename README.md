# **Project :** ***Starbucks Capstone Challenge Project***

## Table of Contents
1. **Description**
2. **File Description**
3. **Executive Summary**
4. **Licensing, Authors, and Acknowledgements**


### 1. Description
This is a **"Starbucks Capstone Challenge Project"** under Udacity Data Scientist Nanodegree Program. 
We're given a dataset contains simulated data that mimics customers behavior on Starbucks rewards mobile app to complete the challenge.


### 2. File Description
The given dataset is contained in three files :
  1. **portfolio.json : This file containing offer ids and meta data about each offer (duration, type and etc)** 
     - *id (string) : offer id*
     - *offer_type (string) : type of offer i.e. BOGO, discount, informational*
     - *difficulty (int) : minimum required spend to complete an offer*
     - *reward (int) : reward given for completing an offer*
     - *duration (int) : time for offer to be open, in days*
     - *channels (list of strings)*
  2. **profile.json : This file containing demographic data for each customer**
     - *age (int) : age of the customer*
     - *became_member_on (int) : date when customer created an app account*
     - *gender (str) : gender of the customer (note some entries contain 'O' for other rather than M or F)*
     - *id (str) : customer id*
     - *income (float) : customer's income*
  3. **transcript.json : This file containing records for transactions, offers received, offers viewed, and offers completed**
     - *event (str) : record description (ie transaction, offer received, offer viewed, etc.)*
     - *person (str) : customer id*
     - *time (int) : time in hours since start of test. The data begins at time t=0*
     - *value (dict of strings) : either an offer id or transaction amount depending on the record*


### 3. Executive Summary
#### Problem Statements :
  - Question 1. Is there any different in customers' demographic that respond best to a specific type of offer ?
  - Question 2. Which offers should be recommended and sent to a particular customer to increase the sales ?
1. *"StarbucksCapstoneChallengeProject.ipynb"* is capturing the program scripting details especially on data understanding, exploration, cleaning and modeling (if relevant) part.
2. *Blog post [Now everyone can enjoy "Starbucks"…](https://medium.com/@eyanney.ang/now-everyone-can-enjoy-starbucks-14f00df74a72)* is mainly summarizing the business objective, methodology and its executive summary.

### 4. Licensing, Authors, Acknowledgements
1. Acknowledgements to 
   - Udacity Data Scientist Nano Degree courses for some of code ideas
   - Starbucks for providing real-life disaster events to train my model 
2. Otherwise, feel free to use the code here as you would like !
