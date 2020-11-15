# Product-Recommendation-System

Amazon Product Recommendation
Online E-commerce websites like Amazon, Filpkart uses different recommendation models to provide different suggestions to different users. Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real time. This type of filtering matches each of the user's purchased and rated items to similar items, then combines those similar items into a recommendation list for the user. In this project we are going to build recommendation model for the electronics products of Amazon.

### Attribute Information:
● overall: Rating of the corresponding product by the corresponding user

● verified: Every user is either reviewed or not

● reviewTime: Time when review is provide

● reviewerID: Every user identified with a unique id

● asin: Every product identified with a unique id(Second Column)

● reviewerName: Name of the user

● timestamp: Time of the rating ( Fourth Column)

### Problem Statement:
Our objective is to build a recommendation system to recommend products to customers based on the their previous ratings for other products. For this purpose, first we will perform exploratory data analysis and then implement recommendation algorithms including Popularity-Based, Collaborative filtering.

Both these recommendation systems can be defined as below:

● Popularity based systems: It works by recommeding items viewed and purchased by most people and are rated high.It is not a personalized recommendation and is mostly useful for the test case of recommending products to new customers.

● Collaborative Filtering: It is based on assumption that people like things similar to other things they like, and things that are liked by other people with similar taste. There are two ways of doing this. One is user based and second is item based collaborative filtering.
