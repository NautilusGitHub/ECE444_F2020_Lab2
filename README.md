# ECE444_F2020_Lab2
Name: Jason Shang
Note: this repo contains some files from https://github.com/miguelgrinberg/flasky

Activity 1:
![Screenshot 1](https://github.com/NautilusGitHub/ECE444_F2020_Lab2/blob/master/image_2_1.png)

Activity 2:
![Screenshot 2](https://github.com/NautilusGitHub/ECE444_F2020_Lab2/blob/master/image_2_2.png)

Activity 3:
Flask context globals are variables exposed and temporarily made global when their respective contexts are activated.
These include:
current_app - exposed by application context. It is the application instance fo the active application
g - exposed by application context. It is an object the application can use for temporary storage during request handling, and is reset with each request.
request - exposed by request context. Represents the request object, and holds the contents of the HHTP request
session - exposed by request context. Represents the user session, and is a dictionary that can store values between requests

