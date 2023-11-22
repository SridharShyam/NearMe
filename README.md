# Ex04 Places Around Me
## Date: 20.11.2023

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```

map.html

<html>
	<head>
		<title> My City </title>
	</head>
	<body bgcolor="aliceblue">
		<h1 align="center">
		<font color="teal"><b> KOLATHUR </b></font>
		</h1>
		<h3 align="center">
		<font color="LightSeaGreen"><b> SHYAM S (23012478) </b></font>
		</h3>
		<center>
		<img src="/static/map.png" usemap="#MyCity" height="605" width="1450">
		<map name="MyCity">
			<area shape="circle" coords="725,340,75" href="hometown.html" title="MY HOME CITY">
            <area shape="rect" coords="1175,425,1325,750" href="pizza.html" title="DOMINO'S PIZZA">
            <area shape="rect" coords="825,200,1025,275" href="school.html" title="EVERWIN SCHOOL">
            <area shape="rect" coords="600,150,800,200" href="fish.html" title="FISH MARKET">
            <area shape="rect" coords="675,200,775,300" href="lake.html" title="RETTERI LAKE">
		</map>
		</center>
	</body>
</html>

hometown.html

<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown"><b>KOLATHUR</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>KOLATHUR - My Home City</b></font>
		</h2>
		<hr size="3" color="sienna">
			<p align="justify">
				<font face="Georgia" size="4">
				Kolathur is my home town located in the northern part of Chennai, the capital city of the Indian state of Tamil Nadu. It is situated approximately 12 kilometers away from the city center. Over the years, Chennai has expanded, and Kolathur is now considered a part of the Greater Chennai Corporation with futuristic development.
				</font>
			</p>
	</body>
</html>

pizza.html

<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="bisque">
		<h1 align="center">
		<font color="saddlebrown"><b>PIZZA</b></font>
		</h1>
		<h2 align="center">
		<font color="darkgoldenrod"><b>DOMINO'S PIZZA</b></font>
		</h2>
		<hr size="3" color="sienna">
			<p align="justify">
				<font face="Georgia" size="4">
				Domino's Pizza has a presence in Chennai, and several Domino's outlets operate in the city and one such outlet is present in Kolathur, Chennai.  Domino's is known for its wide range of pizza offerings, including a variety of crusts, sauces, and toppings. In addition to pizza, the menu typically includes other items such as pasta, chicken wings, sandwiches, salads, and desserts.
				</font>
			</p>
	</body>
</html>

school.html

<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lightpink">
		<h1 align="center">
		<font color="deeppink"><b>SCHOOL</b></font>
		</h1>
		<h2 align="center">
		<font color="mediumvioletred"><b>EVERWIN GROUP OF SCHOOLS - Kolathur </b></font>
		</h2>
		<hr size="3" color="#800000">
			<p align="justify">
				<font face="Georgia" size="4">
				 Everwin Schools is a group of educational institutions with multiple branches in and around Chennai, Tamil Nadu, India. The Everwin Group of Schools aims to provide quality education from kindergarten to higher secondary levels. The schools often follow a curriculum based on educational boards such as the Tamil Nadu State Board of Secondary Education and the Central Board of Secondary Education (CBSE). Everwin Schools usually provide modern infrastructure and facilities, including classrooms, laboratories, libraries more.
				</font>
			</p>
	</body>
</html>

fish.html

<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="ivory">
		<h1 align="center">
		<font color="black"><b>FISH MARKET</b></font>
		</h1>
		<h2 align="center">
		<font color="slategray"><b> KOLATHUR FISH MARKET </b></font>
		</h2>
		<hr size="3" color="darkslategray">
			<p align="justify">
				<font face="Georgia" size="4">
				Professional Aquatics Store. Here you can find Saltwater fishes, Freshwater fishes, Fish tanks, Fish foods, Tank filters, Decor & Plants, etc.Contains wide varieties fishes such as Shark, Koi Fishes, Betta Fishes, Barb Fish, Gold Fish, AngelFish, etc.
				</font>
			</p>
	</body>
</html>

lake.html

<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lightcyan">
		<h1 align="center">
		<font color="darkturquoise"><b>LAKE</b></font>
		</h1>
		<h2 align="center">
		<font color="cadetblue"><b>RETTERI LAKE</b></font>
		</h2>
		<hr size="3" color="steelblue">
			<p align="justify">
				<font face="Georgia" size="4">
				 Retteri Lake is a man-made lake located in the northern part of Chennai, Tamil Nadu, India. The lake serves both as a water storage facility and a recreational area for the local residents. Lakes often contribute to local biodiversity. They can attract various bird species and aquatic life, enhancing the ecological balance in the area. The lake is primarily a water storage facility that helps in rainwater harvesting and groundwater recharge. It plays a role in managing water resources in the region.
				</font>
			</p>
	</body>
</html>
```

## OUTPUT

![1](https://github.com/SridharShyam/NearMe/assets/144871368/59260efe-bc77-4d4c-ad67-2473e39ee376)

![2](https://github.com/SridharShyam/NearMe/assets/144871368/5de7b8b4-8f83-47b2-9c09-17178be2774d)

![3](https://github.com/SridharShyam/NearMe/assets/144871368/5739f56e-e13a-4999-ad8a-1f03502f11b0)

![4](https://github.com/SridharShyam/NearMe/assets/144871368/695daa63-6bda-493e-908c-ccff809b1646)

![5](https://github.com/SridharShyam/NearMe/assets/144871368/7ff14730-e9bf-4567-ba11-20959c617b53)

![6](https://github.com/SridharShyam/NearMe/assets/144871368/ca97e39d-6ad7-41fd-aac9-09c778ec6ee9)

## RESULT
The program for implementing image maps using HTML is executed successfully.
