<!DOCTYPE html>
<html>
<meta charset = "UTF-8">
<head>
<style>
body{
background-color:#0099ff;
overflow:hidden;
}
#loafy{
position:absolute;
width:50px;
height:20px;
background-color:grey;
z-index:-1;
}
#loafyjr{
position:absolute;
background-color:#2C3539;
width:200px;
height:50px;
z-index:-2;
}
#modifyCursor{
position:absolute;
width:100%;
height:100%;
cursor:crosshair;
z-index:100;
}
#honker{
position:absolute;
width:10px;
height:10px;
background-color:grey;
}
</style>
</head>
<body>
<div id = "modifyCursor" onclick="bullet()">
</div>
<div id = "loafy">
</div>
<div id = "loafyjr">
</div>
<div id = "honker"></div>
<script>
var newAngle;
var angle;
var newx = x;
var newy = y;
var upPressed = false;
var rightPressed = false;
var downPressed = false;
var leftPressed = false;
var mouseX;
var mouseY;
var x = 0;
var y = 0;
document.addEventListener("keydown",keyDownHandler,false);
document.addEventListener("keyup",keyUpHandler,false);
function keyDownHandler(e){
if(e.keyCode == 37||e.keyCode == 65){
leftPressed = true;
}
if(e.keyCode == 38||e.keyCode == 87){
upPressed = true;
}
if(e.keyCode == 39||e.keyCode == 68){
rightPressed = true;
}
if(e.keyCode == 40||e.keyCode == 83){
downPressed = true;
}
}
function keyUpHandler(e){
if(e.keyCode == 37||e.keyCode == 65){
leftPressed = false;
}
if(e.keyCode == 38||e.keyCode == 87){
upPressed = false;
}
if(e.keyCode == 39||e.keyCode == 68){
rightPressed = false;
}
if(e.keyCode == 40||e.keyCode == 83){
downPressed = false;
}
}
function bullet(){
newx = x;
newy = y;
newAngle = angle;
}
function loop(){
if(leftPressed){
x-=5;
}
if(upPressed){
y-=5;
}
if(rightPressed){
x+=5;
}
if(downPressed){
y+=5;
}
newx += 15 * Math.cos(newAngle * Math.PI / 180);
newy += 15 * Math.sin(newAngle * Math.PI / 180);
document.getElementById("honker").style.left = newx+"px";
document.getElementById("honker").style.top = newy+"px";
onmousemove = function(e){
mouseX = e.clientX;
mouseY = e.clientY;
}
angle = Math.atan2(mouseY - y, mouseX - x);
angle = angle * (180/Math.PI);
document.getElementById("loafy").style.left = x+"px";
document.getElementById("loafy").style.top = y+"px";
document.getElementById("loafy").style.transform = "rotate("+angle+"deg)";
document.getElementById("loafyjr").style.left = x+"px";
document.getElementById("loafyjr").style.top = y+"px";
}
setInterval(loop,10);
</script>
</body>
