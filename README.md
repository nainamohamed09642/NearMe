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

## CODES
## MAP CODE:
```
<html>
    <head>
        <title>RAMANATHAPURAM</title>
        <style>
            h1{
                font-family: Algerian;
                color: rgb(19, 221, 8);
                font-size: large;
            }
        </style>
    </head>
    <body>
        <h1 align="center">welcome to RAMANATHAPURAM</h1>
        
        <center>
            <img src="ramnadmap.png"usemap="#mapnew">
            
            <map name="mapnew">
                <area target="" alt="Dr APJ Abdul Kalam's Memorial" title="DR.APJ ABDUL KALAM MEMORIAL" href="DR.APJ Abdul kalam.html" coords="296,253,596,337" shape="rect">
                <area target="" alt="DHANUSHKODI" title="DHANUSHKODI" href="Dhanushkodi.html" coords="310,210,50" shape="circle">
                <area target="" alt="PAMBAN BRIDGE" title="PAMBAN BRIDGE" href="pamban bridge.html" coords="520,487,667,569" shape="rect">
                <area target="" alt="ERWADI" title="ERWADI" href="Erwadi.html" coords="355,417,39" shape="circle">                
            </map> 
        </center> 
    </body>
</html>
```
## DR APJ
```
<head>
    <title>DR.APJ ABDUL KALAM MEMORIAL</title>
</head>
<body bgcolor="green">
    <h1 align="center">DR.APJ ABDUL KALAM MEMORIAL</h1>
    <p>
        The memorial consists of four halls that reflect various facets of Dr Kalam's life, including the Pokhran atomic test. There are replicas of rockets, missiles and paintings all of which highlight his association with the Defence Research and Development Organization (DRDO) and Indian Space Research Organization (ISRO).Dr. A.P.J. Abdul Kalam National Memorial is a memorial dedicated to the former president of the Republic of India A. P. J. Abdul Kalam located in Peikarumbu, Rameswaram, Tamil Nadu, India.
    </p>
    <img src="https://www.tamilnadutourism.tn.gov.in/img/pages/medium-desktop/dr-a-p-j-abdul-kalam-memorial-1656167865_24ede8a78a15bb4ba6f8.webp"width="450" lenght="450"  alt="Centered Image" style="display: block; margin: auto;">

</body>
```
## PAMBAN BRIDGE
```
<head>
    <title>PAMBAN BRIGE</title>
</head>
<body bgcolor="lavender">
    <h1 align="center">PAMBAN BRIDGE</h1>
    <P>Pamban Bridge is a railway bridge that connects the town of Rameswaram on Pamban Island with Mandapam in mainland India. Opened on 24 February 1914, it was India's first sea bridge, and was the longest sea bridge in India until the opening of the Bandra–Worli Sea Link in 2010.
        It is the second-longest sea bridge in India after Mumbai's Bandra-Worli Sea Link
    </P>
    <img src="https://www.tamilnadutourism.tn.gov.in/img/pages/medium-desktop/pamban-bridge-1656501956_3b08aac6f552f615ae4e.webp" width="450" lenght="450"  alt="Centered Image" style="display: block; margin: auto;">
</body>

```
## DHANUSHKODI
```
<head>
    <title>DHANUSHKODI</title>
</head>
<body bgcolor="grey">
    <h1 align="center">DHANUSHKODI</h1>
    <P>
        Dhanushkodi is a small, abandoned town located at the southeastern tip of Pamban Island in the state of Tamil Nadu, India. It holds both historical significance and a sense of mystery due to its tragic past and unique geographical location,Dhanushkodi lies on the southeastern end of Pamban Island, which is part of the Rameswaram Island in Tamil Nadu. It is located just 18 miles (29 km) away from Talaimannar in Sri Lanka, making it the closest point between India and Sri Lanka.
    </P>
    <img src="dhanushkodi.png"width="450" lenght="450"  alt="Centered Image" style="display: block; margin: auto;">
</body>>
</body>
```
## ERWADI
```
<head>
    <title>ERWADI</title>
</head>
<body>
    <h1 align="center">ERWADI</h1>
    <P>
        Erwadi is a village in Ramanathapuram District, Tamil Nadu. It belongs to Kilakarai Taluk and town panchayat. The village is the location of the grave and shrine of Qutb-us-Sultan Syed Ibrahim Badshah Shaheed, a ruler of Medina. Erwadi also belongs to Kadaladi assembly constituency, which is a part of Ramanathapuram.
    </P>
    <img src="http://rameswaramtourism.com/wp-content/uploads/2015/06/Ervadidargah-ramanathapuram-rameswaram.jpg" alt="Centered Image" style="display: block; margin: auto;"
</body>
```
## OUTPUT
DR APJ:
![Screenshot 2024-10-19 091129](https://github.com/user-attachments/assets/d1c949d8-584d-48c5-b344-eec1026c6451)
PAMBAN BRIDGE:
![image](https://github.com/user-attachments/assets/65faa65e-7547-46d2-a02c-956228f85ee3)
DHANUSHKODI:
![Screenshot 2024-10-19 091123](https://github.com/user-attachments/assets/edb3eea6-2bf8-42b5-b4ea-43f6baacb70c)
ERWADI:
![Screenshot 2024-10-19 091136](https://github.com/user-attachments/assets/2d739300-5a1c-4c18-96f5-a4a58932b2d8)

## RESULT
The program for implementing image maps using HTML is executed successfully.
