# FOOD HALL

# User Story

- This is a food application; to access the content on the site, one must sign-up and then login. 
- The app offers various food recipes 
- A user can leave their reviews on the recipe

BONUS
- Order Feature
- Add to cart feature
- About and Contact us in the footer section

# Technologies Used

1. HTML5
2. CSS
3. Java Script
4. Node and it's packages
5. Mongoose/MongoDB
6. Express

# Layout

1. Home Page

![entityRelationshipDiagram](images/Home.png)

2. Signup/Login Page

![entityRelationshipDiagram](images/Login.png)

3. Food Collection Page

![entityRelationshipDiagram](images/Food.png)

#### URL GUIDE

#### Food

| **URL**          | **HTTP Verb**|**Action**|
|------------------|--------------|----------|
| /food/         | GET          | index  
| /food/:id      | GET          | show       
| /food/new      | GET          | new   
| /food          | POST         | create   
| /food/:id/edit | GET          | edit       
| /food/:id      | PATCH/PUT    | update    
| /food/:id      | DELETE       | destroy  

#### Comments

| **URL**          | **HTTP Verb**|**Action**|
|--------------------|--------------|----------|
| /comments/:foodId | POST         | create  
| /comments/delete/:foodId/:commentId      | DELETE          | destroy       


#### Users

| **URL**          | **HTTP Verb**|**Action**|
|------------------|--------------|----------|
| /users/signup    | GET         | new  
| /users/signup    | POST         | create  
| /users/login     | GET         | login       
| /users/login     | POST         | create       
| /users/logout    | DELETE       | destroy   