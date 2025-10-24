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
```
map.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Thirunelveli 
                Kallikuzham
            </b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b> C Annie Saron (212224040026)</b></font>
        </h3>
        <center>
            <img src="map2.png" usemap="#MyCity" height="610" widh="1450">
            <map name="MyCity">
                <area shape="rect" coords="500,500,900,900" href="home.html" title="My Home Town">
                <area shape="rect" coords= "640,200,900,900" href="Temple.html" title="Sri Sudalai Muthu Swamy Temple">
                <area shape="rect" coords="700,250,850,400" href="college.html" title="TDMNS College" >
                <area shape="circle" coords="640,200,300,650" href="garden.html" title="GM Garden">

            </map>
        </center>
        </body>
</html>

Temple.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b> Thirunelveli kallikuzham </b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Sri Sudalai Muthu Swamy Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                This is a local village deity shrine dedicated to Lord Sudalai
                 (also known as Sudalai Madan), a protective folk god common in 
                 many rural areas in Tamil Nadu. 
                The temple lies near Kallikuzham in the Thirunelveli district.
            </font>
        </p>
    </body>
</html>


college.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="Yellow">
        <h1 align="center">
            <font color="red"><b> Thirunelveli kallikuzham </b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>TDMNS College</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                T.D.M.N.S. College is located in T. Kallikulam – 627113,
                 in the Tirunelveli district of Tamil Nadu. 
                 Founded in July 1971, the college was established under
                the management of the Dakshina Mara Nadar Sangam with a 
                view to bring higher education to rural areas. 
                It is affiliated to Manonmaniam Sundaranar University, Tirunelveli. 
            </font>
        </p>
    </body>
</html>

garden.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="cyan"><b> Thirunelveli kallikuzham</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"><b>GM Garden</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" >
                Nestled just on the outskirts of T. Kallikulam, GM Garden is a serene 
                open-lawn venue framed by swaying palms and soft ambient lighting. 
                The grounds span a gently undulating green carpet, ideal for evening functions 
                and small celebrations under the stars. A shaded pergola on one side serves 
                as a cosy outdoor lounge for guests, while the adjoining enclosed hall 
                features floor-to-ceiling glass doors that open directly onto the lawn, 
                connecting indoor comfort with outdoor charm 
            </font>
        </p>
    </body>
</html>
```


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
