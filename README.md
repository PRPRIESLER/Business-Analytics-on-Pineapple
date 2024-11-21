# Business-Analytics-on-Pineapple
The project aims to outline the comprehensive scope of our collaboration with Pineapple, aiming to expand its operations in North America within the resold electronic products market. We specialize in enabling seamless Customer Relationship Management (CRM) through Salesforce and enhancing data visualization capabilities using Power BI.

The analytical solution for Pineapple encompasses the entire programming infrastructure designed to analyze customer data and present insights to facilitate more informed decision-making in business operations. With the advent of new and quicker methods for engaging with customers, the significance of transforming the data gathered about customers into actionable information has become increasingly vital for businesses. 

### Customer Account Management: 
The resolution necessitates overseeing accounts, starting from generating leads and identifying opportunities, all the way through to completing sales. 

 

### Profitability analysis and Customer value: 
Analyzing customer relationship management (CRM) data can offer a perspective on Pineapple’s customers who consistently yield the greatest profits. This entails not only evaluating a customer’s expenditure but also considering the resources allocated to serve that customer.  

 

### Personalization: 
CRM platform would be effective in documenting and monitoring customer analytics, encompassing purchase records, demographic information, and interactions with customer service. This functionality empowers Pineapple to provide personalized services to both individual customers and specific customer segments via focused advertising efforts, resulting in increased levels of customer satisfaction. 

# Database Design
The database schema for the entire project is shown below.
![image]([extended_database.png](https://github.com/PRPRIESLER/Business-Analytics-on-Pineapple/blob/main/extended_database.png))

The central focus of this design revolves around two pivotal tangible entities:  

1. Item  

2. Customer  

The 'Item' entity represents a table embodying the array of products that the electronic reseller company, Pineapple, engages with. In contrast, the other entities portrayed, such as 'Sales Order,' 'Item Depreciation’, ’Vendor’, 'Purchase Order,' and 'Feedback,' are abstract entities. These abstract entities encapsulate crucial aspects of Pineapple's operations, providing a conceptual framework for understanding key processes and interactions within the business. 

## Item: 
The ‘Item’ entity represents the products list that Pineapple deals with, that helps them generate revenue. 

## Customer: 

The ‘Customer’ entity represents the Customer base of the company. 

## Vendor: 

The ‘Vendor’ entity helps the service team to grab the information such as stock, and prices of the products upon enquiry raised by the customers. 

## Sales Order: 

The ‘Sales Order’ entity allows to get the information regarding all the sales orders that have been raised by the customer for the year 2023.  

## Item Depreciation: 

The ‘Item Depreciation’ entity helps to get the calculated deprecated prices for every item in the item list generated as per their age. 

## Purchase Order: 

The ‘Purchase Order’ entity helps to get the information regarding all the purchases that have been made from the vendors upon confirmed Sales Order. 

## Feedback: 

The ‘Feedback’ entity helps to grab the information regarding the feedback provided by the customers as well as also helps to calculate the Net Promoter Score (NPS) for Pineapple. 


