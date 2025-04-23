# Ex04 Places Around Me

## Name: P KEVIN

## Register No: 212224040159

## Date: 23/04/2025

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
```
<!DOCTYPE html>
<html>
<head>
    <title>My City - Avadi</title>
</head>
<body>
    <h1 align="center"><font color="red"><b>AVADI</b></font></h1>
    <h3 align="center"><font color="blue"><b>P KEVIN (212224040159)</b></font></h3>
<center>
    <img src="map.png" usemap="#MyMap" height="768" width="1458">
</center>
    <map name="MyMap">
        <area target="_blank" alt="Avadi" title="Avadi" href="avadi.html" coords="780,530,900,580" shape="rect">
        <area target="_blank" alt="Veppampattu" title="Veppampattu" href="veppampattu.html" coords="470,410,550,460" shape="rect">
        <area target="_blank" alt="Murugappa Polytechnic College" title="Murugappa Polytechnic College" href="murugappa.html" coords="970,360,1050,410" shape="rect">
        <area target="_blank" alt="Poonamallee" title="Poonamallee" href="poonamallee.html" coords="820,700,930,750" shape="rect">
    </map>
</body>
</html>
```
avadi.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Avadi</title>
</head>
<body bgcolor="lightblue">
    <h1 align="center"><font color="red"><b>AVADI</b></font></h1>
    <h3 align="center"><font color="blue"><b>P KEVIN (212224040159)</b></font></h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Avadi is a prominent residential and military area in western Chennai, Tamil Nadu. It is known for its defense establishments, educational institutions, and excellent connectivity. Avadi is also home to the Ordnance Factory and the Heavy Vehicle Factory.
            <br><br>
            <b>Strategic Importance:</b> Avadi's military significance stems from its major defense factories and Indian Army presence. This has greatly influenced its growth into a residential hub for working professionals and families.
            <br><br>
            <b>Development:</b> Over the years, Avadi has seen rapid urbanization with modern infrastructure, shopping complexes, and residential projects. The area remains a top choice for those seeking connectivity to Chennai's industrial zones.
            <br><br>
            <b>Key Landmarks:</b> Some of Avadi's important landmarks include the Ordnance Factory, Heavy Vehicle Factory, and Avadi Lake, which are not only vital to the region's economy but also provide recreational spaces for the residents.
            <br><br>
            
        </font>
    </p>
</body>
</html>
```
poonamalle.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Poonamallee</title>
</head>
<body bgcolor="lightgreen">
    <h1 align="center"><font color="red"><b>POONAMALLEE</b></font></h1>
    <h3 align="center"><font color="blue"><b>P KEVIN (212224040159)</b></font></h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Poonamallee is a vibrant town located in the western part of Chennai, known for its historical significance and modern development. The town serves as an important transit hub connecting various parts of Chennai.
            <br><br>
            <b>Historical Significance:</b> Poonamallee has been a key area since ancient times, serving as a strategic point for trade and administration. It was once a thriving settlement during the British colonial era.
            <br><br>
            <b>Modern Development:</b> Today, Poonamallee is known for its rapidly developing infrastructure, with numerous shopping complexes, schools, and residential areas. The presence of major roads like the Chennai Bypass makes it a bustling urban center.
            <br><br>
            <b>Key Attractions:</b> Poonamallee is home to several notable landmarks including the Poonamallee Bazaar, Arulmigu Sri Vadapalani Andavar Temple, and the famous Koyambedu wholesale market.
        </font>
    </p>
</body>
</html>
```
veppampattu.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Veppampattu</title>
</head>
<body bgcolor="lightyellow">
    <h1 align="center"><font color="red"><b>VEPPAMPATTU</b></font></h1>
    <h3 align="center"><font color="blue"><b>P KEVIN (212224040159)</b></font></h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Veppampattu is a suburban area in the outskirts of Chennai. It is well-connected by the Chennai Suburban Railway Network and is a growing residential locality due to its proximity to industries and commercial hubs.
            <br><br>
            <b>Transport Connectivity:</b> Veppampattu enjoys excellent transport facilities with the presence of the Veppampattu Railway Station, which is part of the Chennai Suburban Railway Network. This makes commuting to the city center quick and convenient.
            <br><br>
            <b>Residential Growth:</b> Over the years, Veppampattu has witnessed rapid residential development. Many new apartment complexes, gated communities, and residential projects have made this area an attractive destination for people working in the nearby industrial areas.
            <br><br>
            <b>Proximity to Key Locations:</b> The locality is situated close to other important areas like Avadi, Red Hills, and Poonamallee, with easy access to arterial roads like the Chennai Bypass and the NH4 (National Highway 4).
        </font>
    </p>
</body>
</html>
```
murugappa.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Murugappa Polytechnic College</title>
</head>
<body bgcolor="lightcoral">
    <h1 align="center"><font color="red"><b>MURUGAPPA POLYTECHNIC COLLEGE</b></font></h1>
    <h3 align="center"><font color="blue"><b>P KEVIN (212224040159)</b></font></h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Murugappa Polytechnic College is a renowned technical institution in the region, providing diploma-level education in engineering and technology. The college has a strong reputation for quality education and infrastructure.
            <br><br>
            <b>Established in:</b> The college was established in 1957 under the guidance of the Murugappa Group. It aims to provide high-quality technical education to students from diverse backgrounds.
            <br><br>
            <b>Programs Offered:</b> Murugappa Polytechnic College offers a wide range of diploma programs in fields such as Civil Engineering, Mechanical Engineering, Electrical and Electronics Engineering, and Computer Engineering.
            <br><br>
            <b>Facilities:</b> The college is equipped with state-of-the-art laboratories, a library with a wide range of technical books, modern classrooms, and a sports complex to promote physical and mental well-being.
            <br><br>
            <b>Placement Record:</b> The college has a strong placement record with many of its students securing jobs in reputed organizations across various sectors. The placement cell ensures that students are well-prepared for the industry.
        </font>
    </p>
</body>
</html>
```

## OUTPUT

![Screenshot 2025-04-23 230953](https://github.com/user-attachments/assets/148835b8-71a4-46c8-9904-c3ed17afa4f2)

![Screenshot 2025-04-23 231441](https://github.com/user-attachments/assets/490f833d-8085-4611-ae1f-49d0c67e8bd3)

![Screenshot 2025-04-23 231509](https://github.com/user-attachments/assets/59ae59a3-c9f9-47d1-8d16-2829fb11ac56)

![Screenshot 2025-04-23 231536](https://github.com/user-attachments/assets/3780d749-4ec1-4ee5-ad05-98496fd6ee2f)

![Screenshot 2025-04-23 231559](https://github.com/user-attachments/assets/0c509beb-d730-44dc-825f-478eadcbe540)


## RESULT
The program for implementing image maps using HTML is executed successfully.
