<!DOCTYPE html>
<html dir="Ariel" >
   <head>
      <title>
	  Ariel Page
	  </title>
   </head>
   <center>
   <body style="background-image: url(c2.jpg)">
    <h3 style="color:antiquewhite">Ariel Kravizki ID 039678024</h3>
   
<script>
 
 function isChecked(){
 if ( document.getElementById('Argentina').checked)
 {
   window.open("https://he.wikipedia.org/wiki/%D7%93%D7%92%D7%9C_%D7%90%D7%A8%D7%92%D7%A0%D7%98%D7%99%D7%A0%D7%94");
 }
 if (document.getElementById('France').checked)
 {
   window.open("https://he.wikipedia.org/wiki/%D7%93%D7%92%D7%9C_%D7%A6%D7%A8%D7%A4%D7%AA");
 }
 if (document.getElementById('germany').checked)
 {
   window.open("https://he.wikipedia.org/wiki/%D7%93%D7%92%D7%9C_%D7%92%D7%A8%D7%9E%D7%A0%D7%99%D7%94");
 }
 if (document.getElementById('israel').checked)
 {
   window.open("https://he.wikipedia.org/wiki/%D7%93%D7%92%D7%9C_%D7%99%D7%A9%D7%A8%D7%90%D7%9C");
 }
 if(Agentina==false && France == false && germany==false && israel==false){
 
 return alert('please select The Country : ');
 }
 else{
 return true;
 }
 }
 
 </script>
 
</head>
<body>
<form  method="get" onsubmit="return isChecked();">
 <h1 class="a"><u>Mark the flag on the cube and click below to learn : </u></h1>
 <h3 class="a">Argentina</h3><input type="checkbox" name="countries" value="Argentina" id="Argentina"><br/><br/><br/>
 <h3 class="a">France</h3><input type="checkbox" name="countries" value="France" id="France"/><br/><br/><br/>
 <h3 class="a">germany</h3><input type="checkbox" name="countries" value="germany" id="germany"/><br/><br/><br/>
 <h3 class="a">israel</h3><input type="checkbox" name="countries" value="israel" id="israel"/><br/><br/><br/>
 <button class="b"  onclick="isChecked()">Click here to go to the flag study!</button>
</form>


<script>
function clean(){
        document.form.str1.value = ""

    }
function mypicture()
{
var i;
var str1;
var flag=false;
str1=document.getElementById("str1").value;

var flag = ["argentina", "france", "germany","israel","italy","rasha","spain"];
for(i=0;i<flag.length;i++)
if(flag[i]==str1)
{
 document.getElementById('myImage').src=flag[i] + ".jpg";
  document.getElementById("demo").innerHTML = flag[i];
flag=true;
break;
 }
 if(flag==false)
 document.getElementById('myImage').src="notanimals.jpg";

 }
 
 
 
 
 var i=0;
 function mycountry()
{


i++;


var flag = ["argentina", "france", "germany","israel","italy","rasha","spain"];
     var flag2 = [" Contry : Argentina ", " Contry : Franch", " Contry : Germany", "Contry : Israel", "Contry : Italy","Contry : רוסיה","Contry :Spain"];
     var flag3 = ["capital : Buenos Aires", "capital : Paris", "capital : Berlin", "capital : Jerusalem", "capital : Rome", "capital : מוסקבה","Capital : Madrid"];
 document.getElementById('myflag').src=flag[i] + ".jpg";
  document.getElementById("demo1").innerHTML = flag2[i];
  document.getElementById("demo2").innerHTML = flag3[i];
if(i==6)
i=-1;

}

</script>
<style>
   button.b {
       background-color: black; 
       color: red;
       font-size: 30px;
      padding: 20px 20px;
     
       
   }
   
   button.b:hover {
       box-shadow: 2px 12px 16px 2px rgba(0,0,0,0.4);
   }
   h1.a{
  color: blanchedalmond;
    text-align: center;
    font-size: 40px;
    font-style: initial;
    text-shadow: 2px 2px 40px red;
   }
   h3.a{
  color: blanchedalmond;
    text-align: center;
    font-size: 30px;
    font-style: initial;
    text-shadow: 2px 2px 40px rgb(255, 230, 0);
   }
    .screen {
        width: 300px;
        height: 40px;
        font-size: 30px;
        background: blanchedalmond;
        border-radius: 6px;
        box-shadow: inset 0px 4px rgba(0, 0, 0, 0.2);
        font-size: 21px;
        line-height: 60px;
        color: black;
        font-style: initial;
        border-style: solid;
        text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        text-align: right;
        letter-spacing: 1px;
        border-radius: 10px;
    }
</style>
<hr>
<br>
<br>
<h1 class="a"><u> Click the button below and learn about capital cities : </u></h1>
<h3 class="a" id="demo1"> Country : Argentina </h3>
<h3 class="a" id="demo2">Capital : Buenos Aires </h3>
<img id="myflag" src="argentina.jpg" style="width:150px height:150px">
<br>
<br>
<button class="b" onclick="mycountry()">To learn capital cities click here!</button>
<br>
<hr>
<h1 class="a"><u>(Type one of the countries and the flag will be displayed - the participating flags are : argentina, france, germany, israel, italy, rasha, spain</u></h1>

<button class="b" type="button" onclick="clean()">Content cleaning</button>
<button class="b" onclick="mypicture()">Click here to display the flag</button> 
<br>
<br>
<img id="myImage" src="" style="width:150px height:150px">
<form name="form">
    <h3 class="a">Type the country name here</h1><input class="screen" type="text" id="str1" name="str1">
</center>
</html>
   </body>
</html>
