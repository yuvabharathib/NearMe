# Ex04 Places Around Me
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
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="green"><b>Zamin Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>yuvabharathi B</b></font>
</h3>
<center>
<img src="/static/images/new.png" usemap="#MyCity" >
<map name="MyCity">
<area shape="rectangle" coords="1154,213,1204,263" href="/static/html/poo.html"  title="poonamallee">
<area shape="rectangle" coords="749,153,848,192" href="/static/html/thiru.html" title="thiru">
<area shape="rectangle" coords="568,643,744,698" href="/static/html/lake.html" title="lake">
<area shape="rectangle" coords="231,489,333,526" href="/static/html/sec.html" title="saveetha">
<area shape="rectangle" coords="1063,949,1165,986" href="/static/html/kundrathur.html" title="kundrathur">
</map>
</center>
</body>
</html>

poo.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Poonamallee</title>
    </head>
    <body bgcolor="lime">
    <h1 align="center">
    <font color="green"><b>Zamin Thandalam</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>Poonamallee</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
    1)The name "Poonamallee" might have been derived from "Poovirundavalli", meaning "the place where jasmine is cultivated".<br>
    2)Poonamallee is a relatively peaceful and quiet residential area.<br>
    3)There is well-connected to other parts of Chennai, making it easy to commute to work or school. </font>
    </p>
    </body>
</html>

thiru.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Thirumalizhai</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="green"><b>Zamin Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Thirumalizhai</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
1)Thirumazhisai is a western suburb of Chennai, India.<br>2)It is located in Thiruvallur district of Tamil Nadu.<br>
3)Located on the way to Thiruvallur, the neighbourhood is situated at a distance of 28 km from the city's kilometer zero.<br>
4) The nearest railway station is at Thiruninravur, which is 13 km away.</font>
</p>
</body>
</html>

lake.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Chembarabakkam lake</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="green"><b>Zamin Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Chembarabakkam lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
   1)Chembarambakkam lake is a lake located in Chennai, Tamil Nadu, India, about 25 km from Chennai.<br>
   2) It is one of the two rain-fed reservoirs from where water is drawn for supply to Chennai City, the other one being the Puzhal Lake.<br>
   3)The Adyar River originates from this lake.A part of water supply of the metropolis of Chennai is drawn from this lake.<br>
   4)This was the first Artificial lake built by Rajendra Chola I the son of Rajaraja Chola and Thiripuvana Madeviyar, prince of Kodumbalur. </font>
</p>
</body>
</html>

sec.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Saveetha University</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>Zamin Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Saveetha University</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
1)SEC is a leading Engineering College located in Chennai, India.which offers a global approach to education and research, with a focus on global perspectives and expertise.<br>
2)SEC offers a wide range of undergraduate, postgraduate and doctoral programs in Engineering.<br>
3)Some of its Academic Highlights are, Only Engineering College in India to have 30 students per class. 91% results in University exam. 173 University Ranks. Compulsory internship every year.</font>
 </p>
</body>
</html>

kundrathur.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Kundrathur</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="green"><b>Zamin Thandalam</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Kundrathur</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
    1)Kundrathur is a south western suburb of the city of Chennai, India and it comes under Kanchipuram District limits.<br>
    2)It is the birthplace of Sekkizhar, a well-known poet-saint who authored the Periyapuranam.<br>
    3)The locality is known for the Kundrathur Murugan Temple, one of the most popular temples in Chennai. </font>
</p>
</body>
</html> 
```


## OUTPUT:
![love jpg](https://github.com/yuvabharathib/NearMe/assets/113497404/1d1d06f8-b644-4827-a28f-6f7ccc71dd66)

![2 jpg](https://github.com/yuvabharathib/NearMe/assets/113497404/3a8f0c4e-2c6a-4a47-9dfb-0ba3843aa0c2)
![nxt jpg](https://github.com/yuvabharathib/NearMe/assets/113497404/d6f2c0a4-946a-4596-82ea-12e3d1455b8c)
![3 jpg](https://github.com/yuvabharathib/NearMe/assets/113497404/5373d7b0-16fd-470c-98d5-ead9632ff32b)
![Screenshot (29)](https://github.com/yuvabharathib/NearMe/assets/113497404/4c07f990-c2b4-4847-8ff0-38621c202e58)
![Screenshot (26)](https://github.com/yuvabharathib/NearMe/assets/113497404/0965fbf1-820d-4c60-a7f9-e716efdf8024)






## HTML VALIDATOR
![Screenshot (31)](https://github.com/yuvabharathib/NearMe/assets/113497404/3c48d1b8-8398-4b15-bf74-9262bc611241)





## RESULT
The program for implementing image maps using HTML is executed successfully.
