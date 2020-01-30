# Udacity-Starbuck-Capstone-Project
This project is a part of the Machine Learning NanoDegree Project

# Domain Background
Starbucks Corporation is an American coffee company and ​coffeehouse chain​. Starbucks was founded in Seattle, Washington, in 1971. As of early 2019, the company operates over 30,000 locations worldwide. Due to the tech boom, a lot of companies have divided their businesses into online and offline segments. The online segment will handle online operations like digital marketing, online promotions like ads or offers, the offline segment will manage operations like stock and inventory, offline promotions like banners. A proper sync between these two has helped companies grow a lot faster. Speaking of online. In July 2013, over 10% of in-store purchases were made on customer's mobile devices using the Starbucks app. The company once again utilized the mobile platform when it launched the "Tweet-a-Coffee" promotion in October 2013. On this occasion, the promotion also involved Twitter and customers were able to purchase a US$5 gift card for a friend by entering both "@tweetacoffee" and the friend's handle in a tweet. Research firm Keyhole monitored the progress of the campaign and a December 6, 2013, media article reported that the firm had found that 27,000 people had participated and US$180,000 of purchases were made to date. As we can see there is a lot of business potential through online promotions and we need to optimize it so that we can reap maximum benefits.

# Problem Statement
In this project, I will determine which demographic group is likely to respond to an offer which will help in predicting what offer can be sent to a certain individual.



### Datasets & Inputs
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


### Files
1. *"Nanodegree Project.ipynb"* The Notebook contains the entire Data Stages from preprocessing to the final output
2. *Blog post: check out my findings [here](https://lokeshlalwani07.blogspot.com/2020/01/using-machine-learning-to-determine.html)* 

### Libraries 
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Sklearn
6. Python Libraries

### Licensing, Authors, Acknowledgements
1. Acknowledgements to 
   - Udacity Machine Learning NanoDegree course
   - Starbucks for providing real-life disaster events to train my model 
