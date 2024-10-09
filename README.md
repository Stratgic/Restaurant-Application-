# Restaurant-Application-
Build a CRUD application using Django and React # python # javascript # django # react
Requirements
For this tutorial, you’ll need to have a basics understanding of Django models, Django Rest serializers, and ViewSets.
Project Setup

First of all, we must set up the development environment. Pick up your favorite terminal and make sure you have virtualenv installed.
Once it’s done, create an environment and install Django and Django rest framework.
Note: Don’t forget the dot at the end of this command. It will generate the directories and files in the current directory instead of generating them in a new directory restaurant.
To make sure that the project has been well initiated, try python manage.py runserver. And hit 127.0.0.1:8000.
Now let’s create a Django app.

So make sure to add the menu app and rest_framework in the INSTALLED_APPS in settings.py file.
Good. We can start working on the logic we want to achieve in this tutorial. So, we’ll write Menu :

*Model  *
Serializer
ViewSet
And finally, configure routes.
Model
The Menu model will only contain 5 fields.

React.js CRUD REST API Consumption
Make sure you have the latest version of create-react-app installed.With this line of command, we installed :

axios : a promised based HTTP client
bootstrap: a library to quickly prototype an app without writing too much CSS
react-router-dom : a React library for routes in our application.
Inside the src/ folder, make sure you have the following files and directories.

In the src/components/ directory, we have three components :

AddMenu.js
UpdateMenu.js
MenuList.js
And in src/services/ directory, create menu.service.js and the following lines :
