# Criteria A- Planning

## Definition of the problem
The client of this project is ISAK'S climbing club leader Sara Goh. As the leader of climbing club, Sara's responsibility includes taking attendance and making sure equipment and budget are set right, it is important to her that she gets this information right. Sara would like to be able to take attendance faster, and keep track of her inventory of climbing equipment. Using google sheets to take attendance and stock means that she has to go in and edit things column by column, which takes time and can be confusing, especially for week by week attendance. 

## Solution to problem
Develop a website for client that will fufill multiple purposes. The website has a form functionality that can take attendance on the given day, attendance will be stored in a database organized by date and member. At any time the database can be accessed through the website, and be edited. A similar database will be created for gym equipment, possibly budget. The website should be an easy to navigate central hub of information for the client to keep track of the club. Python Flask will be used to code the website. 

## Solution justification
-Website was chosen as it will be easy to access- There is no installation process like with applications, and can be accessed on both computer and phone. Versatility is important for usability. Ontop of this, the client is familiar with technology, and so will have no problems working with a website style database, and can be taught quickkly on how to use the website.

-A database style form of data-storing was chosen, as it can be organized and as such specific information can be quickly found. 

-Editing of the equipment database will be direct, as there isn't a large amount of constantly changing information needed, and as such the editing of information can be efficient even if done directly.

-Storing of the attendance will go through a form, as it will provide a quick way for the client to take attendance without taking time to directly edit database.

-In terms of coding language, Python and Flask were chosen for the website structure, SQL for database and HTML+CSS for website styling.Python was chosen because it is a widely used, versatile language with much documentation and many libraries in which functions can be drawn from, this will make processes efficient and prevent myself from having to code every function, improving time efficiency on the project. Python is also an object-oriented language, which will provide more efficiency in the code through reusability of objects, aswell as modularity. Flask is a web-design framework which allows for creating organized databases, and is coded and used with python. Flask was chosen for its compatability with python, as well as its versatility due to its usage of libraries to guide programming. HTML and CSS will be used in conjuction with flask to provide the design of the website itself. HTML and CSS are the most commonly used languages for the layout and styling of a website, they are a simple language to use and provide the results needed in the scope of the project, thus are viable for the website. HTML and CSS also work in conjuction with flask, which adds more viability. Because flask does not support databases natively, MySQL will be used for coding the databse. MySQL was chosen as the complexity provided by SQL Alchemy is not needed for this project, and SQL lite is less optimized for website-based databases, as well as being less capable of storing larger databases. MySQL also works in conjunction with Flask, which will make integration simple. 


## Success Criteria

1.) User data- login and password should be secured.

2.) The client finds the website easy to navigate and use, and website provides client efficiency.

3.) The website has a form to record attendance on any given day, the members of the club will be logged so that they may be selected.

4.)The website stores all attendance on a database. 

5.)All climbing equipment will also be stored on a seperate database

6.)Both databases have edit and search functions.

7.)The website is usable on both phone and computer

8.)The client finds the website  

# Critereon B- Design

## Concept Sketches of various website interfaces
Below are first-prototype illustrations for the various pages/interfaces the website wil have, and how they will work.

### Login Menu Interface
The first menu that will appear on visit to the website is the login, here the client can either choose to login or create a new account.



