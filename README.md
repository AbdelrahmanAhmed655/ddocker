
![Untitled Diagram (3)](https://github.com/user-attachments/assets/6b216870-719f-4472-865a-afb74c90c04d)


The demo app runs across three containers:

1- api - a Java REST API which serves words read from the database


2- web - a Go web application that calls the API and builds words into sentences



3- db - a Postgres database that stores words



Build and run in Docker Compose



`docker compose up --build`



