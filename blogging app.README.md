### difference

The idea of the applicationa I am proposing is a bogging app that allows users to create accounts and post posts
and comments on them. It will also support like and other types of reactions. This project will definitly benefit
from OOP.

### Description of the application flow from the user's point of view

A user first enter the mainpage of the application to find two buttons "Sign in" and "Sign up". Supppose that the user is still
new to the website, so he will click sign up to be redirected to a page when he will enter the following information: first name, 
last name, user name, user email, password. As you can see, at this point we can create an object called user, and this object will hold 
the values entered by the user plus the user id (unique), and then it will be stored in the local storage (for example). After creating 
an account successfuly, the user can post posts to be registerd in his profile. these posts can also be stored as objects with the following 
keys: post id, post editor name, post editor id, post title, post body, post likes numbers, post number of comments. Also, users can comment on posts.
the comments can also be represented as objects with the following keys: comment id, post id, comment editor, comment body. Finally the likes
object will have the following keys: post id, number of likes.