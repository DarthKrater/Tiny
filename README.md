# Tiny
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>New webpage</title>
    </head>
       <canvas id="mycanvas"></canvas> 
  <script src="https://cdn.jsdelivr.net/processing.js/1.4.8/processing.min.js"></script> 
<body>
<script>
var programCode=function(proccessingInstance){
with(proccessingInstance){
    size(400,400);
    frameRate(50);
var Time2=100;
var Health2=100;
var Grow=0;
var Time=100;
var monkey= {
    x:2,
    y:2};
 var KingRobot={
     x:2,
     y:2};
  var Boss={
      x:2,
      y:2};
  var Xpos=200;  
var Xneg = 0;
    var Health=100;
var drawMonkey=function(Monkey){
   fill(105, 89, 89);
    ellipse(340,340,100,100);
   fill(20, 18, 18);
   arc(280,310,300,300,300,320); 
fill(105,89,89);
rect(280,280,20,50);
fill(255, 0, 0);
ellipse(360,330,30,30);
ellipse(315,330,30,30);
};
var drawMini=function(Mini){
 fill(15, 14, 14);
 ellipse(150,250,107,100);
 fill(255, 0, 0);
 ellipse(125,250,30,30);
 ellipse(175,250,30,30);
 fill(23, 22, 22);
 rect(200,245,40,25);
fill(255, 0, 0);
 rect(240,100,20,150);
 fill(18, 17, 17);
 rect(240,230,20,40);
fill(235, 221, 221);
textSize(16);
 
};
var drawRobot2= function(King2) {
    background(255, 0, 0);
    fill(120, 111, 111);
    rect(100,75,200,250);
   fill(255, 0, 0);
    ellipse(150,150,30,30);
        ellipse(250,150,30,30);
rect(110,275,175,25);
fill(130, 120, 120);
rect(300,200,80,40);
fill(255, 0, 0);
rect(360,140,20,100);
fill(23, 21, 21);
rect(+340,+130,55,40);
fill(255, 0, 0);
triangle(340,130,360,150,340,170);
triangle(395,130,375,150,395,170);
fill(41, 37, 37);
rect(120,325,40,10);
rect(120,335,40,10);
rect(120,345,40,10);
rect(120,355,40,10);
rect(120,365,40,10);
rect(120,375,40,10);
rect(120,385,40,10);
rect(225,325,40,10);
rect(225,335,40,10);
rect(225,345,40,10);
rect(225,355,40,10);
rect(225,365,40,10);
rect(225,375,40,10);
rect(225,385,40,10);
fill(122, 112, 112);
rect(100,390,70,20);
rect(220,390,70,20);
fill(227, 211, 211);
fill(41, 38, 38);
textSize(10);
};

draw = function() {

background(255, 0, 0);
drawMonkey();
Xpos+=1;
Xneg+=-1;

fill(26, 24, 24);
text("The Tales of Tiny Robot",10,50,200,150);
  fill(135, 121, 121);
   rect(Xneg,0,200,400);
    rect(Xpos,0,200,400);
    textSize(40);

};
mouseClicked=function(){
draw= function() {
background(255, 0, 0);
drawMonkey();
fill(227, 209, 209);
ellipse(270,270,30,30);   
ellipse(250,250,30,30);
ellipse(200,200,150,100);
fill(33, 28, 28);
textSize(12);
text("Hello Adventurer! Welcome to the apocalypse!",160,180,100,60);
};
mouseClicked=function(){
draw= function() {
fill(227, 209,209);
ellipse(200,200,150,100);
fill(15, 13, 13);
text("Your task is to save us from this monster!",160,180,100,60);    
};

mouseClicked=function(){
draw= function() {
fill(227, 209,209);
ellipse(200,200,150,100);
fill(15, 13, 13);
text("good luck!",160,180,100,60);    
};
mouseClicked=function(){
draw= function() {
    background(255, 0, 0);
   fill(133, 123, 123);
    rect(150,150,100,50);
fill(31, 29, 29);
textSize(35);
text("PLAY",160,170,100,100);
};    
if(mouseX>=150&&mouseX<=250&&mouseY>=150&&mouseY<=200){
var drawRobot= function(King) {
    background(255, 0, 0);
    fill(120, 111, 111);
    rect(100,75,200,250);
   fill(255, 0, 0);
    ellipse(150,150,30,30);
        ellipse(250,150,30,30);
rect(110,275,175,25);
fill(130, 120, 120);
rect(300,200,80,40);
fill(255, 0, 0);
rect(360,140,20,100);
fill(23, 21, 21);
rect(340,130,55,40);
fill(255, 0, 0);
triangle(340,130,360,150,340,170);
triangle(395,130,375,150,395,170);
fill(41, 37, 37);
rect(120,325,40,10);
rect(120,335,40,10);
rect(120,345,40,10);
rect(120,355,40,10);
rect(120,365,40,10);
rect(120,375,40,10);
rect(120,385,40,10);
rect(225,325,40,10);
rect(225,335,40,10);
rect(225,345,40,10);
rect(225,355,40,10);
rect(225,365,40,10);
rect(225,375,40,10);
rect(225,385,40,10);
fill(122, 112, 112);
rect(100,390,70,20);
rect(220,390,70,20);
fill(227, 211, 211);
fill(41, 38, 38);
textSize(10);
};
draw= function() {
drawRobot();    
};

mouseClicked=function(){
draw= function() {
fill(232, 223, 223);
ellipse(75,70,15,15);
ellipse(85,80,15,15);
ellipse(70,40,115,50);
fill(41, 36, 36);
textSize(9);
text("I am the robot king! You can not defeat me!",15,35,100,100);    
};
mouseClicked=function(){
    draw= function() {
      
        background(255, 0, 0);
      drawRobot2();  
    textSize(14);
    fill(237, 223, 223);
    rect(150,20,100,50);
fill(33, 29, 29);
    text("Start Boss Battle",175,40,100,100);
    };

  if(mouseX<=250&&mouseX>=150&&mouseY<=70&&mouseY>=20){
draw= function() {
background(255,0,0);
Time+=-0.3;
fill(240, 221, 221);

if(Time<=0){
draw= function() {
 Grow+=2;   
fill(217, 174, 87);
ellipse(200,200, Grow+20, Grow+20);
fill(255, 119, 0);
ellipse(200,200,Grow,Grow);
fill(255, 0, 0);
ellipse(200,200,Grow-20,Grow-20);
fill(23, 20, 20);
textSize(25);
text("you lost! Try again next time!",50,200,400,200);
};

}
fill(255, 0, 0);
rect(150,20,100,50);

drawRobot2();
    fill(23, 21, 21);
    rect(125,25,150,33);
    rect(125,375,150,33);
    fill(227, 211, 211);
    rect(150,30,Health,28);
    rect(150,380,Time,28);
    if(Health<=0){
draw= function() {
background(255,0,0);
textSize(20);
fill(201, 197, 197);
ellipse(200,200,150,100);
ellipse(255,255,30,30);
ellipse(275,275,30,30);
drawMonkey();
fill(33, 32, 29);
text("very good!",150,200,300,200);

};    
}
if(Health<=0){
mouseClicked=function(){
draw= function() {
background(255,0,0);
fill(133,123,123);
rect(150,150,100,50);
fill(0, 0, 0);
text("Next battle",150,175,100,100);
mouseClicked=function(){
if(mouseX>150&&mouseX<250&&mouseY>150&&mouseY<200){
draw= function() {
background(255,0,0);
drawMini();
};}
mouseClicked=function(){
draw= function() {
background(255,0,0);
drawMini();
};    
mouseClicked=function(){
draw= function() {
background(255, 0, 0);
drawMini();
fill(23, 21, 21);
ellipse(100,130,280,100);
fill(232, 227, 227);
textSize(16);
 text("I am Darth Vadur your nephew's father's roomate's cousin's son. Die!",1,103,250,100);

};
mouseClicked=function(){
draw= function() {
background(255, 0, 0);
drawMini();
fill(133, 126, 126);
rect(150,50,100,40);
fill(5, 5, 5);
text("Start Next Battle",155,55,100,100);
};
mouseClicked=function(){
if(mouseX>=150&&mouseX<=250&&mouseY>=50&&mouseY<=90){
draw= function() {
background(255, 0, 0);
drawMini();
Time2+=-0.3;
fill(26, 24, 24);
rect(125,5,150,33);
rect(125,362,150,33);
fill(255, 0, 0);
rect(150,7.5,Health2,28);
rect(150,364.5,Time2,28);
if(Health2<=0){
draw= function() {
background(255, 0, 0);
drawMonkey();
fill(252, 252, 252);
ellipse(220,220,150,125);
fill(13, 12, 12);
text("Amazing! Only two more before the final boss!",167,180,100,100);
};    
}
if(Time2<=0){
draw= function() {
background(255, 0, 0);
drawMini();
Grow+=1;
fill(251, 255, 0);
ellipse(200,200,Grow+20,Grow+20);
fill(255, 119, 0);
ellipse(200,200,Grow,Grow);
fill(255, 0, 0);
ellipse(200,200,Grow-20,Grow-20);
fill(41, 38, 38);
text("You died due to emotional damage after you learned the evilest person to ever live is your nephew's father's roomate's cousin's son.Try again next time! (with some psychiatric support)",100,150,200,200);

};    
}
};

 mouseClicked=function(){
 Health2+=-5;
 };

}    
    
};

};

};
};

};
};


};
}
  
};
mouseClicked=function(){
Health+=-5;
};
  }
};};
}
};
};
};
};




}    
}

var canvas = document.getElementById("mycanvas"); 
  var processingInstance = new Processing(canvas, programCode); 
 
    </script>
        </body>

</html>
