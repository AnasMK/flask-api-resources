# Flask Api Resources

## JWT Authentication 

### Tutorials. 
1. [Real Python tutorial using PyJWT package](https://realpython.com/token-based-authentication-with-flask). 
2. [JWT authorization in Flask using ](https://codeburst.io/jwt-authorization-in-flask-c63c1acf4eeb)
- [github project](https://github.com/oleg-agapov/flask-jwt-auth) more than 130 star 

### Packages
1. [PyJWT package](https://pyjwt.readthedocs.io/en/latest/index.html)
- JWT basic low level features (encode, decode, claims, etc..)
- can be used to implement your own JWT auth system or package
2. [Flask Praetorian](https://flask-praetorian.readthedocs.io/en/latest/)
- pretty neat package
- role based access (authorization)
- does not support all JWT features, like refresh tokens
3. [Flask-JWT](https://pythonhosted.org/Flask-JWT/)
- Abandoned package - not maintained since Nov - 2015
4. [Flask-JWT-Extended]()
- most mature JWT package
- support refresh tokens. fresh/non-fresh tokens
- does not support role based authoriztion
5. [Flask-HTTPAuth](https://flask-httpauth.readthedocs.io/en/latest/) 
- login using username and password
- role based authorization
- token support
- does not support JWT
### Some Comments About Available Packages for JWT
There is no available package that is full-featured flask authentication & authorization extinsion, I will discuss the available packages


References for the comments:  
[compersion between available pachkages](https://flask-praetorian.readthedocs.io/en/latest/comparison.html)
- flask-jwt
- flask-jwt-extended
- flask-jwt-simple
- flask-security

[REDDIT - Introducing Flask-JWT-Extended](https://www.reddit.com/r/Python/comments/53uorh/introducing_flaskjwtextended/).   
[REDDIT - Which way of login is better? Flask-login or flask-jwt?](https://www.reddit.com/r/flask/comments/eh5i69/which_way_of_login_is_better_flasklogin_or/).   
[REDDIT - Flask JWT](https://www.reddit.com/r/flask/comments/40xw9v/flask_jwt/).   
[REDDIT - Full-featured Flask authentication extension using JWT?](https://www.reddit.com/r/flask/comments/7w1tu6/fullfeatured_flask_authentication_extension_using/).   

## Organizing Flask Project - Blueprints
1. [Flask Blueprints](https://flask.palletsprojects.com/en/1.1.x/blueprints/)
2. [Explore Flask - best practices for flask apps](https://exploreflask.com/en/latest/organizing.html)
3. [Flask blueprint tutorial](https://hackersandslackers.com/flask-blueprints/)
- [Github project](https://github.com/hackersandslackers/flask-blueprint-tutorial) - 62 star
4. [Real Python - Use a Flask Blueprint to Architect Your Applications](https://realpython.com/flask-blueprint/)
5. [Real Python project for JWT](https://github.com/realpython/flask-jwt-auth)
- Good project sturcure

## Security
[Flask Security](https://flask.palletsprojects.com/en/master/security/).   
[Flask-SeaSurf](https://flask-seasurf.readthedocs.io/en/latest/).   
[flask-talisman](https://github.com/GoogleCloudPlatform/flask-talisman).   
[Flask SSL with Lets Encrypt](https://blog.miguelgrinberg.com/post/running-your-flask-application-over-https)

## Flask Courses
1. [REST APIs with Flask and Python](https://www.udemy.com/course/rest-api-flask-and-python/)
- most popular Flask REST API course on Udemy.  
- BESTSELLER Udemy tag on the course. 
- ![image](https://user-images.githubusercontent.com/13350394/83796656-0f537400-a6aa-11ea-8dc3-acf3a6a5faa0.png)
