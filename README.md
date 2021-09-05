# My Blog

Taken from my [100 Days of Code](https://github.com/SimonMably/100_Days_of_Code) repository.
I created this blog as my project for [day 69](https://github.com/SimonMably/100_Days_of_Code/tree/main/day_69).
I will be using the same blog in this repository to deploy on Heroku as part of my project for day 70 of 100 Days of Code.

---

Features:
* **User Registration / login / logout**

    Users can register and subsequently login and logout. Register with a username, email and password. It doesn't matter
    if the email is real or fake, as long as it's in a typical email format. The password is hashed and salted.
  
* **Blog Posts**

    Currently, only the user with admin status (me) can create, edit and delete blog posts. Posts have been 
    paginated to 5 posts per page as not to bog down the site.
  
* **Comments**

    All registered users can post comments on blog posts. Comments can be deleted by the user who created them
    and the admin user (me).
  
This blog is hosted on Heroku. It uses a Postgres database on Heroku or SQLite locally. 


See my blog [here](https://simons-blog.herokuapp.com/).