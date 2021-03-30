# Events_WebApp

Web App final for CS97

Description of App

Our web application would ideally be a site where students could both find events happening on campus as well post new events to share with other students. Hopefully students would be able to go on on the website and find new things to do things to do around campus.

App Features

Our app features a list of current events, a section to add events, and a search bar. Firstly, we have a section on the right hand side of the page that displays all the current events in a list format. Then we have a section in the upper right side where users can input new events with details such as the name, date, time, etc. Then in the bottom right side we have a section where we can search for an event by name and then the event(s) with that name will be displayed under the Events section.

How to Run Web App

In order to be able to run the webapp, we will

  1. need to have node installed
  2. be working in the command line

First we need to clone the repository

 ```git clone https://github.com/Striker528/CS97-WebApp.git```
 
The repository will be named CS97-WebApp and this holds everything we did with the webproject. The actual webapp is in a directory named FinalProject within the main repository.

We can navigate to the correct directory using

 ```cd CS97-WebApp/FinalProject/```
 
and we will be initializing and installing libraries in this directory.

Next we need to initalize the file by running the line

 ```npm init``` 
A concern to note with the npm init command is that at the bottom we will see a line saying

 Is this OK? (yes)
Be careful not to just to click past this part. However, if you happen to click past this, just run npm init and go down to the line again. With this we have to make sure we type yes to initalize the line so the should look like this after we input yes and press enter.

 Is this OK? (yes) yes
Next we need to install some libraries using

 ```npm install express --save```
 ```npm install nodemon --save-dev```
 ```npm install body-parser --save```
 ```npm install mongodb --save```
 ```npm install ejs --save```
 ```npm install locus --save```
 
Everything should be installed now and we should be able to run the application using

 ```npm start ```

The application should be running on localhost:3000 and we will see in the command line

 ```listening on 3000```
which means the application is running!!!
