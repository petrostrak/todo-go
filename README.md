# A classic and simple Golang API server that connects to a Frontend page. Our Golang API server will use

-MySQL as our database
-GORM as ORM to interacting with our database
-Request router using gorilla/mux
-Logrus for logging

## How our entire app will work

![Diagram](https://fadhil-blog.dev/blog/7/architecture.png)

The specifications for our API Server are:

-It listens to port 8000 on localhost
-It has 5 endpoints: healthz, createItem, getCompletedItems, getIncompleteItems, updateItemand deleteItem
-TodoItem model consists of Id, Description and Completed status attributes.
