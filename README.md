<doctype! html>
<html>
<head>
<style>
li{

float:right;
display:block;
padding-right:10px;
font-size:20px;
}
ul
{
list-style-type: none;
    margin: 0;
    padding:0;
    overflow: hidden;
   background:orange;


}
li a {
    display: block;
    color: blue;
    text-align: center;
    padding: 15px;
    text-decoration: none;
}
#aa
{
float:left;
}


li a:hover {

    background-color:white;
}
.column {
	border:3px;
border-color:black;
	margin-left:0;
	height=100%;
    float: left;
    width: 60%;
}
#column1

{
background:orange;
height:100%;
padding-left:5;
margin-left:660;
font-color:white;

}
#column1 h1
{
color:white;
font-size:30px;
}
#column1 table td
{
color:white;
font-size:25px;
}
#column1 h2 input
{
color:black;
font-size: 40px;
}


/*
. Clear floats after the columns */
.row:after {
	height=80%;
    content: "";
    display: table;
    clear: both;
}
#vv ul
{
font-size:20px;
background:grey;
}
#vv bb  nn a
{
float:center;
}



</style>	
</head>
<body>
<div>
<ul>
<li id=aa> <img src="Ranger.jpg"style="height:55;width:85" border:"2px" ></li>
<li ><a href="" >Contact </a>  </li>
<li ><a href="" >Sign In  </a>  </li>
<li ><a href="" >About</a>  </li>
<li ><a href="" >Home </a>  </li>	
</ul>
<hr/>
</div>
<div class="row">
  <div class="column">
<img src="dice2.jpg" alt="gone!!" height=100% width=100%> 
</div>
 

 <div id="column1"  >
<div>
	<br/>
	<br/>
	<center><img src="Ranger.jpg" border="none" width=120 height="120" </center>
<h1 font-size="20px"><center>REGISTER</center></h1>
<center>

<form  style="height=100%">
<table calss="tables" style="font-color:white;">
    <tr>
      <td align="right"  >First Name:</td>
      <td align="left"><input type="text" name="first" /></td>
    </tr>
    <tr>
      <td  align="right" style="font-color:white;" >Last Name:</td>
      <td align="left"><input type="text" name="last" /></td>
    </tr>
    <tr>
      <td align="right" style="font-color:white;" >Email:</td>
      <td align="left"><input type="text" name="email" /></td>
    </tr>
 <tr>
      <td align="right" style="font-color:white;" >User Name:</td>
      <td align="left"><input type="text" name="text" /></td>
    </tr>
 <tr>
      <td align="right" font-color="white" >Password:</td>
      <td align="left"><input type="password" name="password" /></td>
    </tr>
 <tr>
 <tr>
      <td align="right" text-color="white;" > Confirm Password:</td>
      <td align="left"><input type="password" name="confirm password" /></td>
    </tr>
 <tr>
      <td align="right" style="font-color:white;" >Contact Number:</td>
      <td align="left"><input type="text" name="number" /></td>
    </tr>
 <tr>
      <td align="right" style="font-color:white;" >Locality:</td>
      <td align="left"><input type="text" name="text" /></td>
    </tr>

  </table>

</form>
</center>

<h2><input type="button" name="submit" width="100"font-size="50px" value="Submit"/></h2>
</div>
</div>
</div>

<div id="vv">
<ul id="bb">
<li id="nn"><a href =" ">Thankyou</a></li>


</ul>



</div>


</body>
</html>
</doctype!>
