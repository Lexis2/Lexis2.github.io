# Lexis2.github.io
LTM high school has been participating in the CRC robotics competition for many years now, where they can show off many different skills. These include but aren't limited to artistic, technological, acting and video-making skills. In this website, you will be able to learn more about this year's team.
  
<!doctype html>
<html lang="en">
<head>
    <style>
        .header {
            background-image: url("header nice10.jpg");
            background-size: 100% 100%;
            text-align: left;
            padding: 7%;
            resize: horizontal;
            overflow: auto;
            text-indent: 2%;
            text-shadow: 3px 2px 2px white;
            color: #702121;
            z-index: 1;
            max-width: 100%;
        }
        .header{
            box-shadow: 0 2.5px 9px white;
            border-bottom: 0.5px #6d6d6d;
        }
         body{
           background-color: white;
               font-size-adjust: 0.58;
float: middle;
             margin:0;
             padding: 0;
             Background-size: cover;
             background-repeat: no-repeat;
             width:100%;
             transition: background-color 500ms ease-in;
        }
   
        .hidden {display: none;}

        .button{
            background-color: black;
            border: none;
            color: white;
            padding: -3px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: auto;
            cursor: pointer;
            transition-duration: 0.4s;
            transition-duration: 0.4s;
            box-shadow: 1px 1px 5px black;
            position: absolute;
            right: 10px;
            top: 1%;
            width: 5%;
            height: 6%;
            border-radius: 20px;
            display: inline-block;
            resize: both;
            font-family: cursive;
            animation-name: slide;
            animation-duration: 2s;
        }
        @keyframes slide{
            0%{right: -130px;}
            50%{right: 50px;}
            100%{right: 10px;}
            
        }
        .button1{
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
            box-shadow: -3px 1px 10px white;
        }
        .button:hover{
            box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
            box-shadow: -3px 1px 10px grey;
            background-color: #302E30;
            color: white;
        }
        .button span{
            cursor: pointer;
            display: inline-block;
            position: relative;
            transition: 0.4s;
        }
        .button span: after{
            content: '\00bb';
            position: absolute;
            opacity: 0;
            transition: 0.4s;
            color: #FFFFFF;
            top: 0;
            right: -20px;
        }
        .button: hover span{
            padding-right: 5%;
            color: white;
        }
        .button: hover span :after{
            opacity: 0;
            right: 1;
            color: white;
        }
          .button2{
            background-color: #ffb347;
            border: solid black 3px;
            color: black;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: auto;
            cursor: pointer;
            transition-duration: 0.4s;
            transition-duration: 0.4s;
            box-shadow: 1px 1px 5px black;
            position: absolute;
              margin-top: 18%;
            margin-left: 40%;
            margin-bottom:0;
            width: 9%;
            height: 8%;
            border-radius: 20px;
              display: inline-block;
            resize: both;
            font-family: cursive;
        }
          .button1{
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
           
        }
        .button2:hover{
            box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
            box-shadow: -3px 1px 10px grey;
            background-color: #302E30;
            color: white;
        }
        .button2 span{
            cursor: pointer;
            display: inline-block;
            position: relative;
            transition: 0.4s;
        }
        .button2 span: after{
            content: '\00bb';
            position: absolute;
            opacity: 0;
            transition: 0.4s;
            color: #FFFFFF;
            top: -70%;
            right: 30px;
        }
        .button2: hover span{
            padding-right: 5%;
            color: white;
        }
        .button2: hover span :after{
            opacity: 0;
            right: 1;
            color: white;
        }
          .button3{
            background-color: #ffb347;
            border: solid black 3px;
            color: black;
            padding: -3px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: auto;
            cursor: pointer;
            transition-duration: 0.4s;
            transition-duration: 0.4s;
            box-shadow: 1px 1px 5px black;
            position: absolute;
margin-top: 2%;            
              margin-left: 40%;
            margin-bottom:0;
            width: 5%;
            height: 8%;
            border-radius: 20px;
              display: inline-block;
            resize: both;
            font-family: cursive;
        }
          .button1{
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
           
        }
        .button3:hover{
            box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
            box-shadow: -3px 1px 10px grey;
            background-color: #302E30;
            color: white;
        }
        .button3 span{
            cursor: pointer;
            display: inline-block;
            position: relative;
            transition: 0.4s;
        }
        .button3 span: after{
            content: '\00bb';
            position: absolute;
            opacity: 0;
            transition: 0.4s;
            color: #FFFFFF;
            top: -70%;
            right: 30px;
        }
        .button3: hover span{
            padding-right: 5%;
            color: white;
        }
        .button3: hover span :after{
            opacity: 0;
            right: 1;
            color: white;
        }
        .button4{
            background-color: #ffb347;
            border: solid black 3px;
            color: black;
            padding: -3px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: auto;
            cursor: pointer;
            transition-duration: 0.4s;
            transition-duration: 0.4s;
            box-shadow: 1px 1px 5px black;
            position: absolute;
              top: 368%;
            margin-left: 41%;
            margin-bottom:0;
            width: 5%;
            height: 8%;
            border-radius: 20px;
              display: inline-block;
            resize: both;
            font-family: cursive;
        }
          .button1{
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
           
        }
        .button4:hover{
            box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
            box-shadow: -3px 1px 10px grey;
            background-color: #302E30;
            color: white;
        }
        .button4 span{
            cursor: pointer;
            display: inline-block;
            position: relative;
            transition: 0.4s;
        }
        .button4 span: after{
            content: '\00bb';
            position: absolute;
            opacity: 0;
            transition: 0.4s;
            color: #FFFFFF;
            top: -70%;
            right: 30px;
        }
        .button4: hover span{
            padding-right: 5%;
            color: white;
        }
        .button4: hover span :after{
            opacity: 0;
            right: 1;
            color: white;
        }
        .topnav{
          
           display: block;
            background-color: black;
            overflow: hidden;
            z-index: 500;
            box-shadow: 5px 10px 25px #1D1D1D;
        }
        .topnav a{
            float: left;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
            font-family: cursive;
        }
        topnav a:hover{
            background-color: white;
            color: black;
        }
        .topnav a.active{
            background-color: #FF6D00;
            color: black;
            font-weight: bold;
            font-family: cursive;
            border-style: solid;
            border-radius: 10px;
        }
        .col-1{width:8.33%}
        .col-2{width: 16.66%}
        .col-3{width: 25%}
        .col-4{width: 33.33%}
        .col-5{width: 41.66%}
        .col-6{width: 50%}
        .col-7{width: 58.33%}
        .col-8{width: 66.66%}
        .col-9{width: 75%}
        .col-s-10 {width: 83.33%;}
        .col-s-11 {width: 91.66%;}
        .col-s-12 {width: 100%;}
         .hometitle {
           text-shadow: 2px 3px 2px grey;
             text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 3px 1px 0 #000;
           font-family: cursive;
           font-size: 220%;
           color: #FC69A8;
           margin-top: 11%;
           font-weight:bold;
                     }
        .homesubtitle {
            margin-top: -1%;
            text-shadow: 2px 3px 2px grey;
            font-family: cursive;
            font-size: 160%;
            color: black;
            font-weight: bold;
        }
        .home_intro_paragraph {
            margin-top: -256.5vh;
            font-family: cursive;
            font-size: 120%;
            color: black;
            max-width: 50vw;
            height: auto;
            text-align: justify;
        }
            hr {
        width:45%; 
        height:2.5px; 
        background: black;
        margin-top:1%;
        }
        .image {
  box-sizing: border-box;
}
   .image1{
            height: auto;
            width: 35%;
            top:-16%;
          margin-bottom: 5%;
          display:block;
          margin-left: 10%;
        }
            .image2{
            height: auto;
            width: 35%;
            margin-top: -16%;
          margin-bottom: 5%;
          display:block;
          margin-right: 30%;
                box-shadow: -2px 9px 10px black;
        }
  .column1 {
      box-sizing: border-box; 
        }
   .row{
       display: flex;
        }
    .column {
        flex: 50%;
        padding: auto;
        }
        .direction{
 -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg);
}
        .sticky {
  position: fixed;
  top: 0;
  width: 100%;
}
        .box{
            color: black;
        }
   
            .div1 {
width: 100%;
height: 100%;
min-width: 1150px;
min-height: 760px;
}
        .rectangle{
            margin-top: 7%;
        height:270px;
        width:99.55%;
        background-color:#ffec73;
         border: solid black 3px;        }
        .triangle-right {
	width: 40px;
	height: 50px;
	border-left: 70px solid #555;
	border-bottom: 45px solid transparent;
            transform: rotatex(180deg);
            transform: rotatey(180deg);
            margin-top: 0%;
            margin-left: -3.7%;
            border-color: transparent transparent transparent #d4c253;
} 
        .triangle-right2 {
	width: 0;
	height: 50px;
	border-bottom: 45px solid #555; 
            border-left: 70px solid transparent;
            margin-left: 94.85%;
            margin-top: -7%;
            margin-right: auto;
            border-color: transparent #d4c253 transparent;
}
          .rectangle2{
        margin-top: 7%;
        height:270px;
        width:99.55%;
        background-color:#ffec73;
        border: solid black 3px;
        box-shadow: 5px 3px 10px;
        }
        .rectangle3{
        margin-left: 13.5%;
        margin-top: 5%;
        height:255px;
        width:72.7%;
        background-color:#ffec73;
            border: solid black 3px;
                    box-shadow: 5px 3px 10px;

        }
          .fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: 0.15} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: 0.2} 
  to {opacity: 1}
}
        
    .flip-card {
        position: absolute;
margin-top:2.7%;
        margin-left: 5%;
  background-color: transparent;
  width: 15%;
  height: 29%;
  perspective: 1000px;

}
        .flip-card2 {
        position: absolute;
margin-top:2.7%;
    margin-left: 23%;
  background-color: transparent;
  width: 15%;
  height: 29%;
  perspective: 1000px;
       
}
        .flip-card3 {
        position: absolute;
margin-top:2.7%;
    margin-left: 59%;
  background-color: transparent;
  width: 15%;
  height: 20%;
  perspective: 1000px;
}
        .flip-card4 {
        position: absolute;
margin-top:2.7%;
    margin-left: 77%;
  background-color: transparent;
  width: 15%;
  height: 20%;
  perspective: 1000px;
}
        .flip-card5 {
        position: absolute;
margin-top: 2.5%;
            margin-left: 6%;
  background-color: transparent;
  width: 25%;
  height: 30%;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
   background-color: transparent;
  width: 100%;
  height: 190px;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
    border-radius: 9px;
} 

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}
        .flip-card2:hover .flip-card-inner {
  transform: rotateY(180deg);
}
  .flip-card3:hover .flip-card-inner {
  transform: rotateY(180deg);
}  .flip-card4:hover .flip-card-inner {
  transform: rotateY(180deg);
}
.flip-card5:hover .flip-card-inner {
  transform: rotateY(180deg);
}
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: auto;
  backface-visibility: hidden;
}
.flip-card-front, .flip-card-back-2 {
  position: absolute;
  width: 100%;
  height: auto;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: black;
  color: transparent;
}

.flip-card-back {
    font-family: cursive;
    font-size:92%;
    border-radius: 9px;
color: white;
    background-color: rgba(0,0,0,0.7);
    transform: rotateY(180deg);
    width: 102.5%;
    height: 100%;
} 
        .flip-card-back-2 {
    font-family: cursive;
    font-size:92%;
    border-radius: 9px;
     border: solid black 3px;
color: white;
    background-image: url("Screenshot 2020-01-05 at 1.16.24 AM.png ");
    transform: rotateY(180deg);
    width: 102.5%;
    height: 100%;
} 
        @media screen and (max-width: 1060px) {
    #primary { width:67%; }
    #secondary { width:30%; margin-left:3%;}  
}

@media screen and (max-width: 768px) {
    #primary { width:100%; }
    #secondary { width:100%; margin:0; border:none; }
}
        html { font-size:100%; }
@media (min-width: 640px) { body {font-size:0.8rem;} } 
@media (min-width:960px) { body {font-size:1rem;} } 
@media (min-width:1100px) { body {font-size:1.1rem;} } 
        
     #wrapper {
    margin-left:auto;
    margin-right:auto;
    width:960px;
}   
    </style>
        <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>LTM Robotics 2020</title>
 <div class="header" style="font=size: 140%"><b></b></div>
  </head>
    <body  class="fade">
<a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Menu.html"><button  class="button button1 col-2" style="vertical-allign:middle"><span>Fran&ccedil;ais</span>
    </button></a>
      <div class="topnav" class="fade" id="myHeader">
        <a class="active" href="file:///F:/RoboticsLorax/index.html">Home</a>
        <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Our_School.html">Our School</a>
        <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Flip.html">The Flip Game</a>
        <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Our_Robot.html">Our Robot</a>
          
        <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Team.html">Our Team</a></div>
       
        <fieldset style="background-color:white; width:70vw;
height: 300vh;
margin-left:14%;
border-color:black;
       margin-bottom: 5%;
border-width: 4px;
box-shadow: 0px 4px 10px;">
        <div class="fade" style="background-color: #ffd154; height: 23vh auto auto; border-radius:15px; box-shadow: 3px 5px 10px; width: 90%; margin-left:5%; line-height:70px; text-overflow: ellipsis;
 ">     <center class="hometitle">Sciencia Vincit Omnia</center>
        <hr>
            <center class="homesubtitle">Science Conquers All</center></div>
     

        </fieldset> 
        <center><div class="home_intro_paragraph" class="fade"style="background-color: rgba(222, 222, 222, 0.65); box-shadow: 25px 25px 50px 0 white inset, -25px -25px 50px 0 white inset; float: middle; text-indent: 7%;">Every year, there's a robotics competition that is held for students in high school and in cegep. This competition is known as the CRC Robotics competition. With this, students are able to develop team building and technological abilities. LTM's robotics team started participating in this yearly competition in 2011, with its first competition being the Mill-Bornes game.
          
          <p>Throughout this website, you will be able to discover more about this year's competition and our robotics team even further. From its school to its team members.</p></div></center>
     <div>   
        <div class="rectangle">
        <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Flip.html"><button class="button2 button1 col-2" style="vertical-allign:middle;"><span>Learn About This Year's Game</span>
             </button></a>
<div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="Screenshot 2020-01-05 at 1.14.44 AM.png" alt="convertogame" style="border: solid black;top:141%;
          width:100%; height: auto;
          margin-bottom: 5%;
          display:block;
           box-shadow: -2px 9px 10px black; position: absolute;border-radius: 9px;">
    </div>
    <div class="flip-card-back">
        <h1><center>The 2018-2019 Vertigoal Game</center></h1>
    </div>
  </div>
</div>
        
<div class="flip-card2">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="Screenshot 2020-01-05 at 1.17.27 AM.png" alt="pythagoreangame" style="border: solid black;top:141%;
          width:100%; height: 186px;
          margin-bottom: 5%;
          display:block;
           box-shadow: -2px 9px 10px black; position: absolute;border-radius: 9px;">
    </div>
    <div class="flip-card-back">
        <h1><center>The 2015-2016 Pythagorium Game</center></h1>
    </div>
  </div>
</div>
        
        <img src="Screenshot 2019-12-13 at 5.45.38 PM.png" alt="crc" border="4" style="border-color: solid black; width: 15%; height: auto; margin-top:2%;
          margin-bottom: 5%;
          display:block;
          margin-left: 40.5%; box-shadow: -2px 9px 10px black; position: absolute;border-radius: 9px;">
        
        <div class="flip-card3">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="Screenshot 2020-01-05 at 1.15.17 AM.png" alt="convertogame" style="border: solid black;top:141%;
          width:100%; height: 186px;
          margin-bottom: 5%;
          display:block;
           box-shadow: -2px 9px 10px black; position: absolute;border-radius: 9px;">
    </div>
    <div class="flip-card-back">
        <h1><center>The 2015-2016 Pythagorium Game</center></h1>
    </div>
  </div>
</div>
        <div class="flip-card4">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="Screenshot 2020-01-05 at 1.15.52 AM.png" alt="convertogame" style="border: solid black;top:141%;
          width:100%; height: 186px;
          margin-bottom: 5%;
          display:block;
           box-shadow: -2px 9px 10px black; position: absolute;border-radius: 9px;">
    </div>
    <div class="flip-card-back">
        <h1><center>The 2017-2018 Converto Game</center></h1>
    </div>
  </div>
</div>
        
                </div>
            </div>
         <div class="triangle-right"></div>
 <div class="triangle-right2"></div>
        <div style="margin-top: 5%;
                    margin-left:25%;
            font-family: cursive;
            font-size: 120%;
            color: black;
            max-width: 50%;
            text-align: justify;
                    background-color: rgba(222, 222, 222, 0.65);
                    box-shadow: 25px 25px 50px 0 white inset, -25px -25px 50px 0 white inset;">
                As mentionned before, our robotics club started participating in the CRC competiton in 2011. At that time, there were only three members to the team. But, over the years, this number has grown. It has now reached nineteen. Every member tries to help with their abilities or abilities that they can learn. We all try our best and do what we can.</div>
            <div>
        <div class="rectangle2">
        <div class="flip-card5">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="Screenshot 2020-01-05 at 1.21.13 AM.png" alt="our_club" border="4" style="border-color: solid black; width: 100%; height: 180px; top:240%;
          margin-bottom: 5%;
          display:block;
           box-shadow: -2px 9px 10px black; position: absolute; border-radius: 9px;">
    </div>
    <div class="flip-card-back-2">
    </div>
  </div>
</div>
        <div style="Margin-top: 3%;      margin-left:35%;
            font-family: cursive;
            font-size: 105%;
            color: black;
            max-width: 50%;
            text-align: justify;">It started with only three members, but now we're twenty. In 2010, three students decided to start a club where they could build robots, and they decided to participate in a competition. The next year, they changed the competition they were participating in for the CRC competition. At first, we could only build a tiny robot made with VEX parts. There were wheels and a claw. That was all. But, we did come a long way since then. I mean, if we think about it, that small kid to the left in the picture is now a giant, right!</div>
          <a href="file:///home/chronos/u-592d3ffee1b6e2a08fd84d8acacc5cd6fcf25e8e/MyFiles/Robotics%20Website/Team.html"><button class="button3 button1 col-2" style="vertical-allign:middle;"><span>Learn About This Year's Team</span>
             </button></a>
                </div>
</div>
    <script>
window.onscroll = function() {myFunction()};

var header = document.getElementById("myHeader");
var sticky = header.offsetTop;

function myFunction() {
  if (window.pageYOffset > sticky) {
    header.classList.add("sticky");
  } else {
    header.classList.remove("sticky");
  }
}
   window.onload = function() {
        document.body.style.backgroundColor = '#FDD8AB';
    }
      
</script>
                <div style="text-align: right;font-family: cursive; color: black; margin-right:3%; margin-bottom:1%;margin-top: 25%;"> Inspired by Dr.Seuss' "<i>The Lorax</i>"</div>
    </body>
</html>       
