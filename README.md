<h2> Overview of the Project </h2>

A simple Django application that uses Models, View and Template design pattern in Django which is similar to Model View Controller in other programming languages. However in Django the View acts as a controller, routing the requests to database to fetch the data and then the url mapping sends the data to templates which then displays data to the user whereas in other frameworks controller is the one that routes the incoming HTTP requests. 


Model | View | Template   
------ | ---- | -----------
Model classes maps data to data base tables | Python functions that are mapped to url | Presentation layer (generates HTML)


<h2>Some of the commands </h2>

* django-admin startproject ${name_of_the_project} -->  starts a new django project
* python manage.py startapp ${name_of_website} --> creates a folder with model, view and template
* python manage.py run server -> starts the server
* python manage.py make migrations --> updates the database with the data form changes made as admin
* python manage.py show migrations --> shows the changes that were made

