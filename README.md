# Ex04 Places Around Me
## Date: 

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

<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center"><font color="red"><b>TIRUVANNAMALAI</b></font></h1>

    <h3 align="center"><font color="blue"><b>Madhupriya R(212224040177)</b></font></h3>

    <img src="map.png" usemap="#MyCity" height="800" width="1550">

    <map name="MyCity">
        <area target="_blank" alt="hometown" title="hometown" href="home.html" coords="1128,637,906,561" shape="rect">
        <area target="_blank" alt="temple" title="temple" href="temple.html" coords="75,685,109" shape="circle">
    </map>
</body>
</html>


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
