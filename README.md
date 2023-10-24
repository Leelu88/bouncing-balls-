# bouncing-balls-
My first repository on Github
I love 🍜 🍣 and 🎨.
<!DOCTYPE html>
<html>
<head>
  <meta charset= "UTF-8">
  <title>Bouncing Ball</title>
  <link rel="stylesheet" type+"text/css" href="style.css">
  </head>
  <body>
    <div id="ball"></div>

    <script src="ball.js"></script>
    </body>
    <html>

    #ball {
      z-index: 5;
      position: absolute;
      left: 0px;
      top: 200px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background: black;
    }


//Set global variable that would contain the position, velocity and the html element "ball"
var ball = document.getElementById("ball");
//write a function that can change the position of the html element "ball"
function moveBall() {
  // two fixed x-axis coordinates (you will use these variable in step 3)
  var Xmin = 0;
  var Xmax = 300;
}

// This call the moveBall function every 100ms
setInterval(moveBall, 100);
