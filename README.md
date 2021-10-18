# Go_WEB_APP
Go Getting Started from PluralSight. Simple webapp in golang

## This is simple Webapp in GO, which has users api to interact with backend 

This hosts the app in **3000** port, (please change in main.go if the port is not available)

### To run the App (from source directory): 
`go run main.go`

This will start the server and then you can use localhost for requests. 

Added postman collections to help you test the CRUD calls since there is no UI Form.

## To run Postman collections 
1. Create the environment variable `userId` 
2. Import collections from JSON file
3. It will import all tests and you can use it to run the REST APIs


## TO run Docker image  
1.  Builds the local docker image : `docker build --tag docker-go-webapp .`
2.  Runs the container on 3000 port : `docker run -p 3000:3000 docker-go-webapp`

