# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a Django admin interface.
### Step 2:
Download your city map from Google.
### Step 3:
Using <map> tag name the map.
### Step 4:
take the screenshot and uploaded it
### Step 5:
write the html code and run server

## Code:
```py
### Jolen Hospital:
<!DOCTYPE html>

<html lang="en">

<head>

<title>jolen Hospital</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>geethalaya apartment</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>sembakkam</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Arial" size="5">

<b>

    jolen Hospital is a prominent healthcare hospital located in Chennai, Tamil Nadu, India.

    </b>

</font>

</p>

</body>

</html>

### map.html:
<!DOCTYPE html>

<html lang="en">

<head>

<title>My City</title>

</head>

<body>

<body bgcolor="cyan">

<h1 align="center">

<font color="red"><b>geethalaya apartment</b></font>

<font color="red"><b>Sembakkam

</h1>

<h3 align="center">

<font color="blue"><b>Yuvan (2300213)</b></font>

</h3>

<center>

<img src="/static/html/Screenshot (32).png" usemap="#MyCity" height="420" width="1100">

<map name="MyCity">

<area shape="rectangle" coords="190,50,20" href="/static/html/sec.html" title="geethalaya apartment"

<area shape="rectangle" coords="230,30,260,60" href="/static/html/hospital.html" title="tea talkies"> <area shape="circle" coords="400,350,50" href="/static/html/boyshostel.html" title="SEC Boys Hostel"> <area shape="circle" sords="400,200,75" href="/static/html/ground.html" title="Cricket Ground"> <area shape="rectangle" coords="490,150,870,320" href="/static/html/sembakkam.html" title="sembakkam"> </map>

</center>

</body>

</html>

### daisy aquarium.html:
!DOCTYPE html>

<html lang="en">

<head>

<title>daisy aquarium</title>

</head>

<body bgcolor="cyan">

<h1 align="center">

<font color="red"><b>daisy aquarium</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>sembakkam</b></font>

</h3>

<hr size="3" color="red">

t="420" width="1100">

<p align="justify">

<font face="Courier New" size="5">

<b>

   In sembakkam the aquarium named Daisy aquarium contains lots of fishes

</b>

</font>

</p>

</body>

</html>

### tea talkies:
<!DOCTYPE html>

<html lang="en">

<head>

<title>SEC</title>

</head>

<body bgcolor="lime">

<h1 align="center">

<font color="red"><b>tea talkies</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>tea talkies</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">

The main objectives of tea talkies are

<ul>

<li>To taste the every cup of tea and snack</li>

</ul>

</font>

</p>

</body>

</html>
```

## Output:
![Untitled](https://github.com/Yuvan291205/places-around-me/assets/138849170/b0f13a9b-8ec5-4f5c-b330-0420d72eb2fc)
![Untitled](https://github.com/Yuvan291205/places-around-me/assets/138849170/d1dd075f-7aa8-4718-a0f6-c5d6ff0fbed1)
![Untitled](https://github.com/Yuvan291205/places-around-me/assets/138849170/9257c4d5-4fb0-4ff2-b4e9-30db62e47b29)

the output is executed successfully
