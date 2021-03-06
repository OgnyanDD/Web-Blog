# :triangular_ruler: Exercise: Javascript BLOG basic functionality

Problem for exercises and homework from the [Software Technologies](https://github.com/OgnyanDD/Software-Technologies) course @ [SoftUni](https://softuni.bg/).<br/>
Creating a **Blog** application with the **Express.js Framework**, from setting up the framework through ***authentication module***, ending up with creating a **CRUD** around **MySQL** entities using **Sequelize** object-document model module.<br/>
**I have implemented changes to the functionality of the BLOG and its design, which differ from its default idea in the task!**<br/>

**Sumary of my project:**
* Created a database with Heidi SQL;
* Defined users authentication parameters;
* Created new controllers;
* Created new models;
* New design of all pages;
* New functions and improvements:
  - new parameters have been added to register a new user;
  - the users can attache web images to the articles;
  - the users can get information about their profiles;
  - the users can edit and delete articles;
  - etc.<br/>
  
**Follow these steps to run the application:**
- Install node.js (if you not have it);
- Start MySQL server to listen;
- Create data base with name "blog";
- Open CMD terminal in project folder;
- Write *"npm install --save sequelize mysql2 passport"* to take the dependecies;<br/>
- Initialize Sequelize with the following command:<br/>
*"sequelize init"*<br/>
There is a chance you hit on an error. You are missing another module that you need to install globally – sequelize-cli. Just run the following command:<br/>
*"npm install -g sequelize-cli"*<br/>

**Other variations of the blog:**
* [**PHP Blog with Symfony Framework**](https://github.com/OgnyanDD/Software-Technologies/tree/master/TF19.%20PHP%20BLOG%20BASIC%20FUNCTIONALITY%20-%20EX%20(BLOG))
* [**JAVA Blog with Spring Framework**](https://github.com/OgnyanDD/Software-Technologies/tree/master/TF25.%20JAVA%20BLOG%20BASIC%20FUNCTIONALITY%20-%20EX%20(BLOG))
* [**C# Blog in ASP.NET MVC using Entity Framework and MVC**](https://github.com/OgnyanDD/Software-Technologies/tree/master/TF29.%20CSHARP%20BLOG%20BASIC%20FUNCTIONALITY%20-%20EX%20(BLOG))

## Screen previews of my design in 768px mode:
![My Design](https://github.com/OgnyanDD/Web-Blog/blob/master/pic's/MyDesign.png)
<br/>
## Screen previews of default design in 768px mode:
![Default Design](https://github.com/OgnyanDD/Web-Blog/blob/master/pic's/DefaultDesign.png)
