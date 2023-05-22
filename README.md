# IS-211-Final-Project-David-Maldonado

David Maldonado
Professor Ledon
IS 211
5/21/2023

Git Hub Repository: https://github.com/dmaldon8186/IS-211-Final-Project-David-Maldonado.git

Final Project Description

I developed a blog site using the Flask web framework in Python in this project. The blog allows users to create, edit, and delete posts, including authentication functionality using the flask_login and werkzeug.security libraries. To begin with, I set up a Flask project by creating the necessary directory structure and initializing a Flask application. I leveraged the flask_login extension for user authentication, which provides a user session management system. It allows users to register, log in, and log out of the blog site. User passwords were securely hashed using the werkzeug.security module, which implements robust password hashing algorithms. I designed a database model to implement the post functionality using Flask-SQLAlchemy. 
The model included a Post class representing a blog post, with attributes such as the post title, content, author, and timestamps. I defined routes and corresponding view functions for handling different actions within the blog site in the Flask routes. For example, I created a route to display all blog posts, another route to handle creating new posts, and additional routes to edit and delete existing posts. Each route was mapped to a specific URL and associated view function, which implemented the required logic. I created templates for various pages, such as the dashboard page, post creation/editing page, and login/register page. With the implementation complete, users can now visit the blog site, register for an account, and log in. Once logged in, they can create new posts, edit them, and delete them if desired. All posts are displayed on the dashboard page, allowing users to browse and read through the blog content easily. Overall, this Flask blog site provides a user-friendly interface for managing blog posts with essential features such as post creation, editing, liking, and deletion. The authentication functionality uses flask_login and werkzeug.security ensures that user accounts and passwords are securely handled.
