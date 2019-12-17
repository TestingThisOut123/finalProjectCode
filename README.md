
1. Project Type: C
2. Group Members Name:Humberto Garduno-Hernandez
3. Link to live Application: https://lkjklj.herokuapp.com/login?next=%2Findex
4. Link to Github Code Repository: https://github.com/TestingThisOut123/finalProjectCode
5. List of Technologies/API's Used: 
Flask, heroku, python
6. Detailed Description of the project (No more than 500 words):

Not needed for project C. Skipped. 


7. List of Controllers and their short description (No more than 50 words for each controller):
All Controllers: index,login,logout, register, user, before request, edit profile, follow, unfollow, explore. 

Index, is the controller handles the first thing the user will see. 

Login, is the controller that is used for login into the program. 

logout, is the controller that deals with logging out. 

Register, is the controller that deals with sign up users. 

User, is the controller that deals with showing user information. 

edit profile, is the controller that deals with editing a user profile. 

follow, is the controller that deals with following another user.

unfollow, is the controller that deals with unfollowing another user. 

Explore, is the controller that displays all the comments writing by users. 



8. List of Views and their short description (No more than 50 words for each view):

All views: _posts, 404,500, base, edit_profile, index,login, register, user,

_posts view handles posts on a page. 
404, handles 404 error on a page.
500, handles 500 error on a page. 
base, is base template for the project.
edit_profile view handles the editing of a profile on a page. 
index, is the view that handles the front view of the project.
login, is the view that handles logins.
register, is the view that displays the view for signup users. 
user, is the view that displays the view profile. 


9. List of Tables, their Structure and short description

Tables in the program: Post, User. 

User structure:
id, and primary key: an int.
username, a name of the user: a string. 
email, the email of the user: a string. 
password_hash, the password of user, that is hashed: a string.
about_me: short description of the user: a string.
last_seen: a time datetime field.
followed: A relationship field, that is used for followings. 

Description of User:
This is used by the database to store User's information. 

Post structure:
id, and primary key: an int. 
body, the post that was written, a string.
timestamp, a field that display when the post was written, a Datetime.
user_id, a foreignKey used for matching a user to their posts: an int. 

Description of Post:
This is used by the database to store Posts' information. 

10. References/Resources: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
