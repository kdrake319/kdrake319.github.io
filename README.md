<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
	<link rel="stylesheet" href="module2-solution.css">
  </head>
  <body>
  
    <h1>Our Menu</h1>
	
	<div class='row'>
	<div class='col-lg-4 col-md-6 sx-12'>
	<div class='section'>
	<span id='p1'>Chicken</span>
	<p>Chicken is the most common type of poultry in the world. Owing to the relative ease and low cost of raising chickens—in comparison to mammals such as cattle or hogs—chicken meat and chicken eggs have become prevalent in numerous cuisines. Let's eat some chicken! Yum it's so good. What's your favorite kind of chicken? </p>
	</div>
	</div>
	
	<div class='col-lg-4 col-md-6 sx-12'>
	<div class='section'>
	<span id='p2'>Beef</span>
	<p>Beef is the culinary name for meat from cattle. In prehistoric times, humans hunted aurochs and later domesticated them. Since then, numerous breeds of cattle have been bred specifically for the quality or quantity of their meat. Today, beef is the third most widely consumed meat in the world, after pork and poultry.</p>
	</div>
	</div>
	
	<div class='col-lg-4 col-md-12 sx-12'>
	<div class='section'>
	<span id='p3'>Sushi</span>
	<p>Sushi is a traditional Japanese dish of prepared vinegared rice, usually with some sugar and salt, accompanied by a variety of ingredients, such as seafood, often raw, and vegetables. Styles of sushi and its presentation vary widely, but the one key ingredient is "sushi rice", also referred to as shari, or sumeshi.</p>
	</div>
	</div>
    
  </body>
</html>
  
  
  {
	box-sizing: border-box;
}
body{
	background-color: white;
}

h1 {
	font-size: 30px;
	font-family: Helvetica;
	text-align: center;
	color: rgb(0,0,0);
	margin-bottom: 30px:
}
p {
	padding: 15px 10px 10px 5px;
	font-family: Helvetica;
	font-size: 15px;
	position: relative;
}
.section {
	background-color: rgb(150,150,150);
	border: 2px solid black;
	margin-right: 20px;
	padding: 3px;
	text-align: justify;
	position: relative;
}

span {
	font-size: 20px;
	width: 150px;
	border: 1px solid black;
	font-weight: bold;
	text-align: center;
	float: right;
	position: relative;
}
#p1 {
	background-color: rgb(250, 150, 150);
	color: rgb(0,0,0);
}
#p2 {
	background-color: rgb(250,0,0);
	color: rgb(0,0,0);
}
#p3 {
	
	background-color: rgb(200,200,100);
	color: rgb(0,0,0);
}
}

.row{
	width: 100%;
}


@media (min-width: 992px) {
	.col-lg-4 {
		width: 33.33%;
		float: left;
	}
}

@media (min-width: 768px) and (max-width: 991px) {
 .col-md-6{
	 width: 50%;
	 float: left;
		}
 .col-md-12{
	 width: 100%;
	 float: left; 
 } 
}

@media (max-width: 767px) {
 .col-sx-12{
	 float: left;
	 width: 100%;
 }
}
