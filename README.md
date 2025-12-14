# Ex04 Places Around Me
## Date: 14/12/2025
## Name : Adithya NM

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

map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Adithya NM (25011586)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="894,479,828,417" href="Science_Park.html" title="Science Park">
<area shape="circle" coords="887,357,810,291" href="Trichy_Birds_Park.html" title="Trichy Birds Park">
<area shape="circle" coords="988,698,1067,763" href="Tiruchirappalli_International_Airport.html" title="Trichirappalli International Airport">
<area shape="circle" coords="842,132,932,204" href="Sri_Ranganatha_Swamy_Temple.html" title="Sri Ranganatha Swamy Temple">
</map>
</center>
</body>
</html>

Science_Park.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Science Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Trichirappalli Science Park is an educational and recreational center designed to make science approachable, practical, and engaging for students and the general public. It features interactive exhibits, working models, and demonstrations that explain core concepts of physics, mathematics, astronomy, energy, and environmental science through hands-on learning rather than textbooks alone. The park encourages curiosity, logical thinking, and innovation by allowing visitors to experiment, observe cause-and-effect, and understand how science operates in everyday life. Widely used for school visits, workshops, and awareness programs, the Science Park plays an important role in nurturing scientific temper and promoting experiential learning in Tiruchirappalli and surrounding regions.
</p>
</body>
</html>

Trichy_Birds_Park.html
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Trichy Birds Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Trichy Birds Park is a well-developed, eco-friendly conservation and recreation destination near Tiruchirappalli that offers visitors an immersive experience with a wide variety of native and migratory bird species. Designed to replicate natural habitats, the park features spacious open aviaries, landscaped walkways, and water bodies that allow birds to move freely while visitors observe them at close range. Beyond recreation, the park plays an important role in environmental education by creating awareness about bird conservation, biodiversity, and the importance of protecting natural ecosystems. It is a popular spot for families, students, photographers, and nature lovers, providing a calm and informative escape from urban life while promoting respect for wildlife.
</p>
</body>
</html>

Trichirappalli_International_Airport.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Trichirappalli International Airport</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Tiruchirappalli International Airport (TRZ) is a major aviation hub for central Tamil Nadu, playing a crucial role in connecting the region with key domestic cities and important international destinations, particularly in Southeast Asia and the Middle East. Located about five kilometers south of Tiruchirappalli city, the airport supports tourism, religious travel to Srirangam and nearby heritage sites, and overseas employment-linked travel. With a modern passenger terminal, upgraded infrastructure, and growing flight operations, it handles a steady flow of passengers and cargo, contributing significantly to regional trade and economic development. As one of the few international airports in Tamil Nadu outside Chennai, Trichy Airport stands as a strategic gateway that strengthens connectivity, commerce, and cultural exchange for the region.
</p>
</body>
</html>

Sri_Ranganatha_Swamy_Temple.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Tiruchirappalli</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Ranganatha Swamy Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Sri Ranganathaswamy Temple at Srirangam is one of the most important and magnificent temples in India, dedicated to **Lord Ranganatha**, a reclining form of Lord Vishnu resting on the cosmic serpent **Adisesha**. Situated on Srirangam island between the rivers **Cauvery and Kollidam**, the temple’s geography adds to its sacred character and historical resilience. Spanning about **156 acres**, it is the **largest functioning Hindu temple complex in the world**, designed as a vast temple-city with **seven concentric enclosures**, massive walls, broad streets, and towering gopurams, the tallest rising over 70 meters. The temple is a central seat of **Sri Vaishnavism** and one of the **108 Divya Desams**, celebrated by the Alvar saints and shaped intellectually by Ramanujacharya. With its ancient inscriptions, intricate sculptures, grand halls, and uninterrupted traditions of worship and festivals, the Sri Ranganathaswamy Temple stands as a living symbol of South India’s spiritual depth, architectural brilliance, and cultural continuity across centuries.
</p>
</body>
</html>


## OUTPUT
![alt text](<Trichirappalli Map-1.png>)

## Science Park
![alt text](<Science Park.png>)

## Trichy Birds Park
![alt text](<Trichy Birds Park.png>)

## Trichirappalli International Airport
![alt text](<Tiruchirappalli International Airport.png>)

## Sri Ranganatha Swamy Temple
![alt text](<Sri Ranganatha Swamy Temple.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
