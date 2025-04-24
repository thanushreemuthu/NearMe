# Ex04 Places Around Me
## Date: 24/04/2025

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
<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>KORATTUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>Thanushree</b></font>
  </h3>

  <center>
    <img src="map.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
        <area shape="rect" coords="900,150,850,650" href="home.html" title="Home">
        <area shape="circle" coords="570,230,45" href="road.html" title="TELEPHONE EXCHANGE">
        <area shape="circle" coords="640,200,30" href="place.html" title="KOCHAR">
        <area shape="circle" coords="1120,360,10" href="theater.html" title="SIVASHAKTHI CINEMAS">
        <area shape="rect" coords="950,120,1100,140" href="school.html" title="BHAKTAVATSALAM SCHOOL">
      </map>
  </center>
</body>
</html>
```
school.html
```
<html>
<head>
  <title>BHAKTAVATSALAM SCHOOL</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>KORATTUR</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>BHAKTAVATSALAM SCHOOL</b></font>
  </h3>

  <hr size="3" color="cyan">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        Bhaktavatsalam School is a prominent educational institution located in Korattur, Chennai.
        It is known for its commitment to academic excellence and holistic development of students.
        The school offers a well-rounded curriculum, including academics, sports, and extracurricular
        activities, fostering a nurturing environment for learning. With dedicated faculty and modern 
        facilities, Bhaktavatsalam School aims to prepare students for future challenges while instilling
        values and discipline.
  </p>
</body>
</html>
```
theater.html
```
<html>
<head>
  <title>CINEMAS</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>KORATTUR</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>SIVASHAKTHI CINEMAS</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        Sivasakthi Cinemas is a popular movie theater located in Korattur, Chennai.
        It is known for screening a variety of films, including Tamil blockbusters and regional cinema.
        The theater offers a comfortable viewing experience with modern amenities, making it a favorite
        spot for movie enthusiasts in the area. With its convenient location and diverse film selection,
        Sivasakthi Cinemas attracts a wide audience, contributing to the vibrant entertainment culture
        of Korattur.
</body>
</html>
```
place.html
```
<html>
<head>
  <title>KOCHAR</title>
</head>
<body bgcolor="blue">
  <h1 align="center">
    <font color="cyan"><b>KORATTUR</b></font>
  </h1>

  <h3 align="center">
    <font color="lime"><b>KOCHAR</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5" color="white">
        Kochar is a well-known area in Korattur, Chennai, famous for its vibrant community and local culture. 
        It features various shops, eateries, and parks that attract residents and visitors alike. The area is 
        characterized by its friendly atmosphere and accessibility, making it a popular destination for families
        and individuals seeking a lively neighborhood experience.
  </p>
</body>
</html>
```
road.html
```
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="green">
  <h1 align="center">
    <font color="gray"><b>KORATTUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>TELEPHONE EXCHANGE</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
        A telephone exchange is a central hub that connects phone calls by routing signals between users.
        It serves as the backbone of telecommunication, enabling seamless voice communication across distances.
        Early exchanges were manual, with operators connecting calls using switchboards.
        Today, modern digital exchanges handle millions of calls automatically with high speed and reliability.
    </font>
  </p>
</body>
</html>
```
## OUTPUT


![map](https://github.com/user-attachments/assets/31db6c17-b0fe-4eaa-b5d2-be5d8d135424)

![Screenshot 2025-04-23 230117](https://github.com/user-attachments/assets/2a1f7ee6-76e2-4863-bf17-88f898ab587d)
![Screenshot 2025-04-23 231827](https://github.com/user-attachments/assets/45d59649-f437-4ff2-88d1-be837cefe3c6)


![Screenshot 2025-04-23 231844](https://github.com/user-attachments/assets/3b682244-0516-4fbd-8410-1cc184c85051)

![Screenshot 2025-04-23 231907](https://github.com/user-attachments/assets/b9933b6f-7da0-46cf-a17a-124a82e94f36)

## RESULT
The program for implementing image maps using HTML is executed successfully.
