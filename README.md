# Project 1 - Hello World
HackPad： Link to HackPad
前言：才做Project 1就GG，先回去複習一下Javascript
StartUp With NPM 
npm install express 
npm install nodemon (Update The File and Restart The Server Automatic)
FileName : index.js
<CODE>
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
 

