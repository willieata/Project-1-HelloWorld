# Project 1 - Hello World

前言：才做Project 1就GG，先回去複習一下Javascript </br>
StartUp With NPM  </br>
npm install express  </br>
npm install nodemon (Update The File and Restart The Server Automatic) </br>
FileName : index.js </br> </br>
</br>
var express = require('express'); </br>
var app = express(); </br>
var port = 3000; </br>
  </br>
app.get('/' , function(req ,res){ </br>

  res.send('Hello World'); </br>

}); </br>

 
app.listen(port, function(){ </br>

  console.log('Server is Listening On port ' +port); </br>

}); </br>

</br>
Test Server With Node </br>
nodemon index.js </br>
Go To http://localhost:3000/ </br>
 

