**Check out the live version of my sample blog site, hosted by Heroku and served by gunicorn:**       
https://olivers-blog.herokuapp.com

**Project Credits:**   
Basic blog template - [startbootstrap.com](https://startbootstrap.com/theme/clean-blog)   
Project idea and reference - Dr. Angela Yu from [100 Days of Code: The Complete Python Pro Bootcamp for 2022](https://bit.ly/3S3ihuC)   

**Site Functionality:**   
-> New users can register an account with the site, and existing users can login to their account at any time   
-> The first registered account, by default, is considered the admin account, and has special admin-only privileges   
-> The admin is able to edit and delete any blog post, as well as delete any comment on the page   
-> Other (non-admin) users are only able to remove their own comments, if they wish to do so   
-> User account credentials are securely stored in a PostgreSQL database (passwords are salted and hashed)

**This application utilizes:**   
-> Flask, Flask-Login, Flask-WTF, Flask-Bootstrap, Flask-SQLAlchemy, Flask-CKeditor, Flask-Gravatar   
-> Werkzeug, Twilio API, smtplib
