# Project 1 - Hello World

前言：才做Project 1就GG，先回去複習一下Javascript </br>
StartUp With NPM  </br>
npm install express  </br>
npm install nodemon (Update The File and Restart The Server Automatic) </br>
FileName : index.js </br>
<CODE> </br>
var express = require('express');

var app = express();

var port = 3000;

 
app.get('/' , function(req ,res){

  res.send('Hello World');

});

 
app.listen(port, function(){

  console.log('Server is Listening On port ' +port);

});

</CODE>
Test Server With Node
nodemon index.js
Go To http://localhost:3000/
 

