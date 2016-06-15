# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
The backend stores data coming from the front end. If u have a website that needs an email, the backend keeps the email data so it can be used later.```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model```

Which layer in the MVC pattern communicates with the model?

```bash
Das kontroller.```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We don't use views because views return source code or html elements to the viewer. As developers, we are already familiar with what the html or css will look like.```

What does C.R.U.D stand for?

```bash
Create Read Update Destroy```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Controller gives these to the model.```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Update, create, show, destroy, edit```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
server gives a route to controller via dispatcher
controller sends Read to model
model process read, validates data, and pulls from server
model gives it back to controller
controller to view
view back to controller
controller to server
server to client```

What is the command to generate a new rails-api app?

```bash
// your response here
```

What is the command to start an instance of a rails server?

```bash
rails s```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
*drop - dropdb
*create - createdb
*migrate - generate migration```

What is the command to scaffold a pet with a name and an age?

```bash
generate scaffold Pet name:string age:numerable```

List two advantages of using serializers? (2 bullet points)

```bash
*it helps test the backend status
*it has a wide compatabilty```
