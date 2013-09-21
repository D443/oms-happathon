Perguntus UI
================================

***What is the purpose of Perguntus? i.e., why does it exist?***

Perguntus is an example application that is built on top of OMS. It uses some Backend Components and some Frontend Components. It was created to show some of the abilities of OMS

***Is perguntus a Django app? If so, how does it differ from regular Django apps.***

Perguntus is a Django app. The main difference is that the Django settings and urls are going into the manifest file. Perguntus acts 100% as a django app.

***What is the purpose of each of the files in the repo?***

Perguntus is separated into 2 parts they exists in oms-experimental repo:
* perguntus_ui - the UI that users interact with (The Frontend)

***HTML Templates***

* perguntus_ui/templates/dashboard.html - the main dashboard UI page
* perguntus_ui/templates/edit.html - the edit questions UI page
* perguntus_ui/templates/mobile.html - the mobile answer page
* perguntus_ui/templates/questionform.html - the 'add a question’ form
* perguntus_ui/templates/settings.html - the settings page
* perguntus_ui/templates/sharing.html - the sharing page

***Static Files***

* perguntus_ui/static/css/* - all style sheets files related to the project
* perguntus_ui/static/img/* - all of the images related to the project
* perguntus_ui/static/js/* - all the javascript files related to the project

***Files that the user should notice:***

* perguntus_ui/static/js/PerguntusAnswer.js - the Javascript Backbone Answer Object
* perguntus_ui/static/js/PerguntusBackbone.js - Perguntus Backbone Javascript Implementation
* perguntus_ui/static/js/PerguntusDashboard.js - Perguntus Javascript Dashboard logics
* perguntus_ui/static/js/PerguntusEdit.js - Perguntus Javascript Edit Question Page logics
* perguntus_ui/static/js/PerguntusQuestion.js - the Javascript Backbone Question Object

* perguntus_backend - the django Models and server logics (The Backend)
* perguntus_backend/api.py - Django TastyPie Implementation 
* perguntus_backend/check_questions.py - function to check if questions need to be sent to the user
* perguntus_backend/models.py - Question/Answer data models
* perguntus_backend/send_question.py - function to manually send specific questions to the user
* perguntus_backend/tests.py - Simple UnitTest
* perguntus_backend/views.py - Provides a way to run send_question via an HTTP request

***Is there a working demo of stock perguntus I can see?***

https://kodkod.idhypercubed.org/PerguntusUI

***specific to the hackathon***

***What skills will I need to know to make changes?***

To make changes you will need to have the following skills:

HTML

Javascript

CSS

Python (Django)


***What are some examples of changes I might want to make?***

Changes to Perguntus can come in 2 ways:

As Perguntus is still a work in progress a developer may try to improve the followings:

Make Perguntus Templates extend from a base Template

Refactor UI to work with Backbone.js templates

Improve Javascript code

***Frontend changes*** - All of these changes will be made on perguntus_ui and will require HTML/Javascript/CSS skills.

These changes can include:

changing the graphs on the dashboard (using other graphs or displaying the data we already save in a different way)

changing the edit question page

changing the mobile answer page

***Backend changes*** - All of these changes will be made on perguntus_backend and will require Python (Django) skills

These changes can include:

Changing the way we save the data (changing the data models)

Changes that will require changes to both parts of Perguntus can include:
adding more data models.
This will require you to add a new data model to the backend models and then create the UI to interact with the new backend model.

***Where should I ask for help?***

IRC or kodkod