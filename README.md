# Blog-Post-Website-Using-Node-js

This Blog Post Website made following Udemy Courses

# I have Learn
* how to use express module
* use of EJS
* Templete in EJS
* express routing parameter
* Dinamic web page creation using Templating
* Also Connected to a mongo database

## project overview

### Home :

- All the post Data will be fetched from the MongoDb Database name blogPostDB and rendered into the Home page.  

- The website will be **dinamiclly** updated whenever a new post will be added to the Database.  

- All the post-Content will be truncated max upto 100 charecters only and there will be a [Read more] link to view the full post.  

- There is also Contact and About page with Random shit with EJS content .

![Home page](images/home.png?raw=true "Title")

  
  
  
### Compose :

This is hidden page to publish a new posts into the website.  
To access it we have to go to the **"/compose"** route.  
If the app is listening to **"localhost:3000"** then the compose route will be **"localhost:3000/compose"**

![Compose page](images/compose.png?raw=true "Title")

  
    
 ### Post :
 
- Using **EJS** and **Express routing parameter** a new page will be dinamically render into the screen with corresponding post content.
- It will be fetch by the Id of the post from the Database
  
  
![Post page](images/post.png?raw=true "Title")
