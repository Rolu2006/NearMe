# Ex04 Places Around Me
## Date: 25.10.2025

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
MAP.HTML
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Rayachoty</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SOMALARAJU ROHINI (212224240156)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
            <area shape="rect" coords="100,100,900,900" href="home.html" title="My Home Town">
            <img src="Screenshot 2025-04-29 203945.png" usemap="#image-map">
            <area target="" alt="Vijaya Durga Temple" title="Vijaya Durga Temple" href="Temple.html" coords="699,172,867,219" shape="rect">
            <area target="" alt="Vishal Mega Mart" title="Vishal Mega Mart" href="Mart.html" coords="814,228,999,267" shape="rect">
            <area target="" alt="Ajay Residency" title="Ajay Residency" href="Residency.html" coords="652,296,898,354" shape="rect">
            <area target="" alt="SR Events" title="SR Events" href="Events.html" coords="706,589,871,644" shape="rect">
            <area target="" alt="SunGod PVT" title="SunGod PVT" href="pvt.html" coords="1526,558,1757,644" shape="rect">
</map>
            </map>
        </center>
    </body>
</html>

PVT.HTML
<html>
<body bgcolor="orange">
    <h1 align="center">
        <font  size="10" color="red">
            Rayachoty
        </font>
    </h1>
    <h2 align="center">
        
       SunGod PVT
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="pvt.jpg" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Company status: Active (as per the LEI listing) but very newly recorded (it shows registration date 2024 in the identifier) which suggests it is a newer company.
                 
                 
        <li>
            <font size="4">
                A trademark “SUNGOD” has been filed by this company for goods in class 31 (agricultural, horticultural and forestry products; unprocessed pulses, cereals and grains; fresh fruits and vegetables etc) on 13 September 2025.
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Company track record & experience: Since the company appears to be quite new, ask for references of past transactions, proof of import/export licences, trading history.
 
            </font>
        </li>
    </h3>
</body>

EVENTS.HTML
<html>
<body bgcolor="pink">
    <h1 align="center">
        <font  size="10" color="red">
            Rayachoty
        </font>
    </h1>
    <h2 align="center">
        
       SR Events
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="events.webp" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
               SR Events is an event-management and wedding-planning company located near the Vasai-Virar area in Palghar district, Maharashtra.
                 
                 
        <li>
            <font size="4">
                Their emphasis is on delivering creative themes and cost-effective solutions: “They always want their clients to have the best time by flawlessly planning all aspects of a wedding… one of the town’s best and most affordable wedding planners.”
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Weddings & Social Functions – Full wedding planning including décor, stage/backdrop, band/Baraat, photography/videography.
 
            </font>
        </li>
    </h3>
</body>


RESIDENCY.HTML
<html>
<body bgcolor="sky blue">
    <h1 align="center">
        <font  size="10" color="red">
            Rayachoty
        </font>
    </h1>
    <h2 align="center">
        
       Ajay Residency
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="residency.jpg" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                The hotel is located at 41 Milestone, NH-8 (National Highway 8), opposite Haldiram, near Toll Plaza, Kherki Daula, Gurgaon, Haryana – 122002.
                 
                 
        <li>
            <font size="4">
                From the event/venue perspective (another branch/location of “Ajay Residency” in Gurgaon, Sector 84) the venue has: 1 banquet hall, capacity up to ~200 floating guests, 50 vehicle parking, veg & non-veg menu.
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                Suitable for travellers looking for budget-friendly accommodation near Gurgaon/Delhi corridor and needing access via highway.

 
            </font>
        </li>
    </h3>
</body>


MART.HTML
<html>
<body bgcolor="purple">
    <h1 align="center">
        <font  size="10" color="red">
            Rayachoty
        </font>
    </h1>
    <h2 align="center">
        
       Vishal Mega Mart
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Vishal mart.avif" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                Vishal Mega Mart is a large Indian retail chain focused on value-oriented shopping for middle and lower-middle income consumers.
                 
                 
        <li>
            <font size="4">
                The chain is a “one-stop shop” kind of model: offering apparel (men, women, kids), general merchandise (home & kitchen items, travel goods, etc), groceries/fast-moving consumer goods (FMCG), etc
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                They cater heavily to non-metro markets: smaller cities and towns where retail competition is relatively less and cost of operations can be lower.

 
            </font>
        </li>
    </h3>
</body>


TEMPLE.HTML
<html>
<body bgcolor="white">
    <h1 align="center">
        <font  size="10" color="red">
            Rayachoty
        </font>
    </h1>
    <h2 align="center">
        
       Vijaya Durga Temple
    
    </h2>
    <hr>
    <h3>
        <center> 
        <img src="Temple.jpeg" height="388" width="822" >
        </center>
        <br>
        <hr>
        <li>
            <font size="4">
                The temple is located in the Kadapa region of Andhra Pradesh, serving devotees from the district and surrounding villages.
                 
                 
        <li>
            <font size="4">
                It is known for special rituals during certain auspicious periods (such as the “Rāhukāla” lamp ritual) which attract devotees from various parts of the region.
                
            </font>
        </li>
        <br>
        <li>
            <font size="4">
                The presiding deity is Vijaya Durga (often referred to as “Am­māvari” amongst devotees). Devotees believe that worship here yields the goddess’s blessing for success and removal of obstacles.

 
            </font>
        </li>
    </h3>
</body>


```


## OUTPUT

![alt text](<Screenshot 2025-10-25 000853.png>)

![alt text](<Screenshot 2025-10-25 000906.png>)

![alt text](<Screenshot 2025-10-25 000916.png>)


![alt text](<Screenshot 2025-10-25 000929.png>)

![alt text](<Screenshot 2025-10-25 000941.png>)

![alt text](<Screenshot 2025-10-25 000955.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
