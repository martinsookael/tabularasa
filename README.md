Blank Famo.us-Angular + Express + Gulp (livereload) + Heroku + Bower + Moment + jQuery + Bootstrap
===================


This is a boilerplate for beginning a new Single Page Application with the components listed in the header.


INSTALLATION AND STARTING UP
===================  

(Assuming you have everything else until nodemon/node installed)  

```
npm install  
cd public  
bower install  
```  

Select any 1.3.0 option:  
angular#~1.3.0 which resolved to 1.3.0 and is required"
```
gulp  
```  
(other terminal)  
```
nodemon app.js
```  

Go to: http://localhost:5000/


ABOUT  
 ===================  


EXPRESS:  
Sets up a basic http server that serves the index.html file from public folder.  

GULP:  
Refreshes the browser every time something is edited in public folder.  

HEROKU:  
There is a Heroku specific Procfile present, that starts app.js if uploaded to Heroku.  

BOWSER  
is configured to install everything into folder "b"  

RESPONDJS  
brings media queries to IE 6-8  

HTML5SHIV  
brings HTML5 to IE  

JQUERY + BOOTSTRAP + ANGULAR + ANGULAR ROUTE  
These guys do what they've always done.  
As a side note - Bootstrap also does a CSS reset.  

FAMO.US + ANGULAR
Promises to bring animations at the level of native apps to webapps.
