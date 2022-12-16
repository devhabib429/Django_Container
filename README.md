# Django_Container

# STEP 1

Create a server Ubuntu/Windows or some

# STEP 2

Install Docker as per Requirement 

# STEP 3

Create a Folder and inside install Virtual envorment and ACTIVATE

# STEP 4

Install All depenedency such as python , Django and pip as well

# STEP 5

Create a folder inside this have to create a DJANGO PROJECT as per command (Make Run as server )

# STEP 6

Now lets start Docker Container Process :

Create a Dockerfile inside root folder of project and also Create a file requirements.txt in which all dependency name would be listed.
Put all content of Dockerfile in your as per modification.

# STEP 7 

Now Build your docker file by using `docker build -t name:tag .` then image is created.
Its time to run your image of project -
`docker run -p port:port -d container_id`



Ref - https://blog.logrocket.com/dockerizing-django-app/

Thats it.

Thank you !

