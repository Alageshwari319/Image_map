# Ex04 Places Around Me
# Date:05/10/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
imagemap.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body text align="center";>
    <header>
        <h1>Places around me</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot (1).png" title="map places" usemap="#places-map" width="100%">
        <map name="places-map">
            <area shape="rect" coords="369,406,416,442" href="C:\Users\admin\tt\Eligibility-for-Admission\Theatre.html" title="Movie Theatre"/>
            <area shape="rect" coords="264,347,325,386" href="C:\Users\admin\tt\Eligibility-for-Admission\Restaurant.html" title="Restaurant"/>
            <area shape="rect" coords="633,327,668,350" href="C:\Users\admin\tt\Eligibility-for-Admission\Bus Stand.html" title="Bus Stand"/>
            <area shape="rect" coords="372,503,434,547" href="C:\Users\admin\tt\Eligibility-for-Admission\Hotel.html" title="Hotel"/>
            <area shape="rect" coords="345,44,432,80" href="C:\Users\admin\tt\Eligibility-for-Admission\Railway Station.html" title="Railway Station"/>
</body>
</html>

hotel.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: rgb(159, 181, 111);
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: oblique;
        }
        a,p{
            font-size: x-large; font-family: Georgia; text-decoration: bisque;
        }
        p{
            margin-left: 50px;
        }
        a:link{color: blue;
           background-color: transparent;
           text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
            color:skyblue;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande';">Hotel</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Downloads\ABM hotel.webp" title="map places" usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://g.co/kgs/ZBoLkez" title="Hotel" />
        </map>
    </main>
    <h1></h1>
    <a href="https://g.co/kgs/ZBoLkez" title="Visit ABM">ABM Grande</a>
    <p style="color: black;">ABM Grande property is located in a prime location on the highway to Munnar. Guests appreciated the spacious and clean rooms, courteous staff, and ample parking space. The property offers good value for money, making it a budget-friendly option for families and business travelers. However, some guests found the food to be average and suggested improvements in cleanliness and amenities. Overall, ABM Grande is a decent property to stay in Theni with easy accessibility to nearby attractions.<br>This hotel is located on the Kumily highway , also not faraway from main area of Theni. It is easy to locate. This property has got vast car parking area behind the hotel so no worries if you park your own car, it is well protected.
    </p>
    <br>
    <br>
    <table style="background-color:rgb(242, 245, 247); width: 100%; height: 200px;">
        <tr>
            <th align="justify-content"> <p><a href="https://g.co/kgs/ZBoLkez"> <img src="C:\Users\admin\Downloads\hotel icon.png" style="width: 80px; height: 50px;"></a>ABM GRANDE Official Website</p></th>
            <th>       </th>
            <th>       </th>
        </tr>
        <tr>
            <th>Contact us<br>
                Phone:<cite>9123520056</cite>
                Address:<cite>19 Kumuly, NH Road, Theni, Tamil Nadu 625531</cite>
            </th>
        </tr>
    </table>

theatre.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: beige;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: oblique;
        }
        a,p{
            font-size: x-large; font-family: Georgia; text-decoration: bisque;
        }
        p{
            margin-left: 50px;
        }
        a:link{color: azure;
           background-color: transparent;
           text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
            color:skyblue;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande';">Theatre</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Downloads\vetri cinemas.webp" title="map places" usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://g.co/kgs/K7PDxRw" title="Theatre" />
        </map>
    </main>
    <h1></h1>
    <a href="http://www.vetricinemas.in/" title="Visit Vetri Cinemas">Vetri Cinemas</a>
    <p style="color: black;">Vetri Cinemas is a well known theatre in Madurai. Cinema is equipped with comfortable push backed enabled Seating and fully air conditioned. The theatre has ample car and two-wheeler Parking and the canteen caters fresh and quality food items.</p>
    <p> A cinema hall provides redefining movie going experience. Be spoilt for choice! We, offers a wide selection of short eats and beverages that are not only scrumptious but also stored and served under safe and hygienic conditions. The menu selection offers a range of irresistible combos too. </p>
    <br>
    <br>
    <table style="background-color:rgb(242, 245, 247); width: 100%; height: 200px;">
        <tr>
            <th align="justify-content"> <p><a href="http://www.vetricinemas.in/"> <img src="C:\Users\admin\Downloads\theatre icon.png" style="width: 80px; height: 50px;"></a>Vetri Cinemas Official Website</p></th>
            <th>       </th>
            <th>       </th>
        </tr>
        <tr>
            <th>Contact us<br>
                Phone:<cite>9123520056</cite>
                Address:<cite>Boothipuram road, Theni, Tamilnadu</cite>
            </th>
        </tr>
    </table>

restaurant.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: rgb(111, 159, 177);
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: oblique;
        }
        a,p{
            font-size: x-large; font-family: Georgia; text-decoration: bisque;
        }
        p{
            margin-left: 50px;
        }
        a:link{color: azure;
           background-color: transparent;
           text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
            color:skyblue;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande';">Restaurant</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Downloads\rivera hotel.webp" title="map places" usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://g.co/kgs/FNUfUQH" title="Restaurant" />
        </map>
    </main>
    <h1></h1>
    <a href="http://www.theriviera.in/" title="Visit Rivera Hotel">Rivera Hotel</a>
    <p style="color: black;">The Riviera is situated on the riverbank of Kotakudi, Theni, offering stunning views of the river and mountains. The hotel rooms feature full air conditioning, WiFi, and spacious private bathrooms.</p>
    <p>Each room is equipped with a flat-screen television, a kettle, a shower, free toiletries, and a desk. The hotel provides a complimentary buffet breakfast with a variety of multi-cuisine options.</p>
    <br>
    <br>
    <table style="background-color:rgb(242, 245, 247); width: 100%; height: 200px;">
        <tr>
            <th align="justify-content"> <p><a href="http://www.theriviera.in/"> <img src="C:\Users\admin\Downloads\Restaurant icon.jpeg" style="width: 80px; height: 50px;"></a>Rivera Hotel Official Website</p></th>
            <th>       </th>
            <th>       </th>
        </tr>
        <tr>
            <th>Contact us<br>
                Phone:<cite>9123520056</cite>
                Address:<cite>16,Boothipuram road, Theni, Tamilnadu 625531</cite>
            </th>
        </tr>
    </table>

railwaystation.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: beige;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: oblique;
        }
        a,p{
            font-size: x-large; font-family: Georgia; text-decoration: bisque;
        }
        p{
            margin-left: 50px;
        }
        a:link{color: rgba(9, 234, 234, 0.368);
           background-color: transparent;
           text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
            color:skyblue;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande';">Railway station</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Downloads\railway station.webp" title="map places" usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/GkMWJMEzYisgmfQW7" title="Railway Station" />
        </map>
    </main>
    <h1></h1>
    <a href="https://www.goibibo.com/trains/teni-railway-station-teni-stn/" title="Visit Teni">Railway station</a>
    <p style="color: black;">Teni (station code:TENI) is an NSG–6 category Indian railway station in Madurai railway division of Southern Railway zone.[1] It serves Theni, located in Theni district of the Indian state of Tamil Nadu.[2][3]</p>
    <p>It is a railway station on Madurai–Bodinayakkanur branch line, serving the town of Theni in Tamil Nadu state, India. It was closed in 31st of december 2010 as the line was under gauge conversion, from metre to broad gauge until 30 March 2022. From 31 March 2022 once again this station became operational after CRS inspection was successfully conducted between Andipatti to Theni railway station. It is one of the railway stations in Southern Railway zone. It falls under Madurai Division of the Indian Railways.[4] It is one of the rare railway stations in India where all the historic Indian gauges 610mm, 762mm, 1000mm are used. Currently it has been converted to 1676mm broad gauge. Now only one unreserved train is being operated daily between Madurai junction and Theni railway station </p>
    <br>
    <br>
    <table style="background-color:rgb(242, 245, 247); width: 100%; height: 200px;">
        <tr>
            <th align="justify-content"> <p><a href="https://www.goibibo.com/trains/teni-railway-station-teni-stn/"> <img src="C:\Users\admin\Downloads\railway station icon.jpeg" style="width: 80px; height: 50px;"></a>for more details</p></th>
            <th>       </th>
            <th>       </th>
        </tr>
        <tr>
            <th>Contact us<br>
                Phone:<cite>9123520056</cite>
                Address:<cite>Railway Station Rd, Theni, Tamil Nadu 625531</cite>
            </th>
        </tr>
    </table>

busstand.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: beige;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: oblique;
        }
        a,p{
            font-size: x-large; font-family: Georgia; text-decoration: bisque;
        }
        p{
            margin-left: 50px;
        }
        a:link{color: rgba(9, 234, 234, 0.368);
           background-color: transparent;
           text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
            color:skyblue;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande';">Bus Stand</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Downloads\bus stand.webp" title="map places" usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/buRLfdDVDsyrhY2p7" title="Bus Stand" />
        </map>
    </main>
    <h1></h1>
    <a href="https://www.justdial.com/Theni/Theni-Old-Bus-Stand-NGO-Colony-Suppan-Ragavan-Colony-NRT-Nagar-Vadaveeranaickenpatty-T-Nagar/9999P4546-4546-181113164547-C9G2_BZDET" title="Visit Teni">Bus Stand</a>
    <p style="color: black;">This new bus terminus was named after Colonel John Pennycuick, the British engineer who constructed the Mullaiperiyar dam, the life-line of many southern districts.</p>
    <p>Colonel John Pennycuick Bus Terminus is situated at Theni to Periyakulam bye pass road,behind of SIDCO Industrial Estate. This Bus stand caters to an average number of 350 buses per day. The town is well connected with the surrounding major urban centres as well as villages by the bus routes.
        As many as 59 buses can be parked in this terminus which has all the basic amenities including police control room, information officer, reception and driver’s rest room.,</p>
    <br>
    <br>
    <table style="background-color:rgb(242, 245, 247); width: 100%; height: 200px;">
        <tr>
            <th align="justify-content"> <p><a href="https://www.justdial.com/Theni/Theni-Old-Bus-Stand-NGO-Colony-Suppan-Ragavan-Colony-NRT-Nagar-Vadaveeranaickenpatty-T-Nagar/9999P4546-4546-181113164547-C9G2_BZDET"> <img src="C:\Users\admin\Downloads\bus stand icon.png" style="width: 80px; height: 50px;"></a>For more details</p></th>
            <th>       </th>
            <th>       </th>
        </tr>
        <tr>
            <th>Contact us<br>
                Phone:<cite>9123520056</cite>
                Address:<cite>Madurai Main Rd, NGO Colony, Suppan Ragavan Colony, NRT Nagar, Theni, Tamil Nadu 625531</cite>
            </th>
        </tr>
    </table>
```
# OUTPUT

![Screenshot (34)](https://github.com/user-attachments/assets/4e62adfd-ee8c-44c8-ae7a-4d01cef20568)
![Screenshot (39)](https://github.com/user-attachments/assets/378cca3b-26cb-4cc8-b94d-81c83c26c3e5)
![Screenshot (40)](https://github.com/user-attachments/assets/311f2a58-a9ea-4400-9ddb-90e1b7a1c860)
![Screenshot (32)](https://github.com/user-attachments/assets/7427faff-8b08-4c95-8879-1178415a67cc)
![Screenshot (33)](https://github.com/user-attachments/assets/b8c92bf3-458b-47a3-83dd-066e745aa997)
![Screenshot (35)](https://github.com/user-attachments/assets/b3678c34-4d35-4b50-852a-ef96b6fe1a26)
![Screenshot (37)](https://github.com/user-attachments/assets/02cf15e0-a314-416f-accd-515e152e5b5f)
![Screenshot (38)](https://github.com/user-attachments/assets/2613c4a0-8ca3-4435-a3ef-cc1ccb6e9ade)
![Screenshot (41)](https://github.com/user-attachments/assets/22305561-e8d4-4c2d-a38b-d6faf91c164f)

# RESULT
The program for implementing image maps using HTML is executed successfully.
