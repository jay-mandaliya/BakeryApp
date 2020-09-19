# BakeryApp

### Project Overview
-----
As restaurants and bakery shops become more and more digitally driven, they’re turning to next-generation order management solutions to help them bridge the gap between their physical and online operations. We have designed an order application where users are able to add or view an order, for three companies to manage their own resources and interact with other companies. If an authenticated user makes an effective order online, the order system should then send the order to both the bakery and the warehouse to prepare for the order. 

UI for the order website should be user-friendly so that our customers can easily make an order on the platform. For our company, the security of user identity is also important, we must ensure the one who make operations on websites are real customers, we will verify users by sending an account activation link through an email. 

The frontend of the Bakery Company website will be used by the staff of the bakery company, so the UI is simple and straightforward. All the operations to manage dishes and orders can be easily reached through the navigation bar and buttons on homepage. 

The frontend of the Ingredients Company will be used by the staff of the ingredients supply company, so the UI is simple and straightforward. All the operations to manage ingredients and orders can be easily accessed through the navigation bar and buttons on homepage.

### Software Overview
-----
1. **Bakery Company**

The basic function of Bakery Company is to manage available products and also accept orders from the Order App. The operations on the website are listed as below: 
* List products
* Add product
* Edit product
* Accept Order

2. **Ingredients Company**

The basic function of Ingredients Company is to manage available ingredients which can be supplied for Bakery Company, and also accept orders from the Order App. The operations on the website are listed as below: 
* List ingredients
* Add ingredients
* Edit ingredient
* Accept Order

3. **Order App**

The basic function of Order Company is to manage orders from users, send the corresponding requests for Bakery and Ingredients Companies. The operations on the website are listed as below:
* Login/logout
* Register and verify user status
* Add Order
* View Orders

### User Interface
-----
#### *Ingredients management home page*
![alt text](/images/1.png)
#### *Adding ingredient information*
![alt text](/images/2.png)
#### *Bakery management home page*
![alt text](/images/3.png)
#### *Configure product information*
![alt text](/images/4.png)
#### *Order app home page*
![alt text](/images/5.png)
#### *Confirming order information*
![alt text](/images/6.png)


### Software Frameworks
-----
Bakery Company uses AWS serverless computing platform, while OrderApp and Ingredients Company are deployed on cloud (Azure and Heroku respectively) using Containerization. All the three companies use SailsJS as a real-time MVC Framework for Node.js. The serverless flow chart and the MVC software framework are shown below. 

#### *Flow chart of AWS Serverless Computing drawn using draw.io*
![alt text](/images/7.png)
#### *Software Architecture of SailsJS MVC Framework drawn using draw.io*
![alt text](/images/8.png)

### Tasks achieved
* Our scenario includes three independent companies organized together through orders.
* Data are stored on three different DBs on clouds.
* ORM is used to access information in two of the databases.
* Deployed Bakery Company on AWS with serverless computing.
* Containers are used for the deployment of Supply and Order Companies.
* Used XA transactions to achieve functional requirements across all companies.
* Tested every endpoint with Postman.
* Used the agile software development method based on Sprints and Scrum.
