# Ex03 Places Around Me
## Date: 20-5-26

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
        <title>Mannady map</title>
    </head>
    <body bgcolor="pink">
        <h2 align="center">Mannady</h2>
        <h3 align="center"><b>B Marliya Banu (212225040229)</b>
        </h3>
        <img src="map.png" usemap="#image-map" >

    <map name="image-map">
        <area target="" alt="Egmore" title="Egmore" href="Egmore.html" coords="1093,125,1303,179" shape="rect">
        <area target="" alt="Marina Beach" title="Marina Beach" href="marina.html" coords="1250,395,74" shape="circle">
        <area target="" alt="Nehru Stadium" title="Nehru Stadium" href="NehruStadium.html" coords="852,442,891,430,972,423,1009,448,1007,508,844,508" shape="poly">
        <area target="" alt="Sowcarpet" title="Sowcarpet" href="Sowcarpet.html" coords="1021,195,1176,247" shape="rect">
        <area target="" alt="Temple" title="Temple" href="Temple.html" coords="665,96,640,28,704,11,770,34,743,98" shape="poly">
    
    </map>
    </body>
</html>

Temple.html
<html>
    <head>
        <title>
            Temple
        </title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">Mannady</h1>
        <h2 align="center">Temple</h2>
        <hr>
        <table cellpadding="20" >
            <tr>
                <td valign="middle">
                    <br><br><br>
                     <img src="temple.jpg" align="left" width="350" height="350",border="2">
                </td>
                <td>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>    
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
            </td>
        
        <td>
        <h3 font-color="blue">The city is well known for its beautiful temple architecture, 
            cultural traditions, and religious rituals that attract many visitors every year.
             Agriculture plays an important role in the local economy, 
             especially tapioca cultivation and sago production,
              which provide jobs for many families. 
              Government initiatives and public-private partnerships are improving roads, 
              transportation, tourism facilities, and public services. 
              During the monsoon season, rainfall enhances the beauty of parks, lakes, and natural surroundings, though proper drainage systems are necessary for safety. 
              The housing market is steadily growing because of urban development and better infrastructure.
               These developments improve tourism, economic growth, public safety, and the overall quality of life.</h3>
        </td>
        </tr>
        </table>
    </body>
</html>

Sowcarpet.html

<html>
    <head>
        <title>
            Sowcarpet
        </title>
    </head>
    <body bgcolor="Lavender">
        <h1 align="center">Mannady</h1>
        <h2 align="center">Sowcarpet</h2>
        <hr>
        <table cellpadding="20" >
            <tr>
                <td valign="middle">
                    <br><br><br>
                     <img src="sowcarpet.png" align="right" width="350" height="350",border="2">
                </td>
            <td>
                |
                <br>
                |
                <br>
                |                |
                <br>
                |
                <br>
                |
                <br>    
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |                |
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
            </td>
        
        <td>
        <h3 font-color="blue">Sowcarpet is one of Chennai’s oldest and busiest commercial neighborhoods, well known for its crowded markets, traditional shops, and vibrant street life. The area is famous for wholesale trading, textiles, jewelry, household items, and delicious North Indian street food. People from different communities live and work together, creating a rich cultural atmosphere. Narrow streets filled with colorful stores and busy shoppers make the place lively throughout the day. Popular snacks like chaat, kachori, and sweets attract food lovers from across the city. Sowcarpet represents Chennai’s blend of heritage, business growth, culture, and strong local community traditions.</h3>
        </td>
        </tr>
        </table>
    </body>
</html>

NehruStadium.html

<html>
    <head>
        <title>
            Nehru Stadium
        </title>
    </head>
    <body bgcolor="IndianRed">
        <h1 align="center">Mannady</h1>
        <h2 align="center">Nehru Stadium</h2>
        <hr>
        <table cellpadding="20" >
            <tr>
                <td valign="middle">
                    <br><br><br>
                     <img src="nehru.jpg" align="right" width="350" height="350",border="2">
                </td>
            <td>
                |
                <br>
                |
                <br>
                |                |
                <br>
                |
                <br>
                |
                <br>    
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
            </td>
        
        <td>
        <h3 font-color="blue">Jawaharlal Nehru Stadium is a famous multi-purpose sports stadium in Chennai, known for hosting football matches, athletic events, cultural programs, and public gatherings. Built with modern facilities and a large seating capacity, the stadium attracts sports lovers from across Tamil Nadu. It serves as an important center for national and state-level competitions. The surrounding area is busy and well connected by transport facilities. The stadium encourages young athletes to participate in sports and promotes physical fitness, teamwork, and discipline. Jawaharlal Nehru Stadium represents Chennai’s strong passion for sports, entertainment, and community events.</h3>
        </td>
        </tr>
        </table>
    </body>
</html>

Egmore.html

<html>
    <head>
        <title>
            Egmore Museum
        </title>
    </head>
    <body bgcolor="Lightgreen">
        <h1 align="center">Mannady</h1>
        <h2 align="center">Egmore Museum</h2>
        <hr>
        <table cellpadding="20" >
            <tr>
                <td valign="middle">
                    <br><br><br>
                     <img src="egmore.jpg" align="right" width="350" height="350",border="2">
                </td>
            <td>
                |
                <br>
                |
                <br>
                |                |
                <br>
                |
                <br>
                |
                <br>    
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
            </td>
        
        <td>
        <h3 font-color="blue">The Egmore Museum, located in Egmore, is one of India’s oldest and most famous museums. It showcases ancient sculptures, bronze idols, archaeological collections, coins, paintings, fossils, and cultural artifacts. The museum complex also includes an art gallery and a children’s museum. Its beautiful Indo-Saracenic architecture attracts many visitors and tourists. Students and history lovers visit the museum to learn about South Indian history, art, science, and culture. The Egmore Museum plays an important role in preserving heritage and educating people about the rich traditions and historical achievements of Tamil Nadu and India.</h3>
        </td>
        </tr>
        </table>
    </body>
</html>

marina.html

<html>
    <head>
        <title>
            Marina Beach
        </title>
    </head>
    <body bgcolor="PeachPuff">
        <h1 align="center">Mannady</h1>
        <h2 align="center">Marina Beach</h2>
        <hr>
        <table cellpadding="20" >
            <tr>
                <td valign="middle">
                    <br><br><br>
                     <img src="marina.jpg" align="right" width="350" height="350",border="2">
                </td>
            <td>
                |
                <br>
                |
                <br>
                |                |
                <br>
                |
                <br>
                |
                <br>    
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |                
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
                |
                <br>
            </td>
        
        <td>
        <h3 font-color="blue">Marina Beach is one of the longest urban beaches in the world and a major tourist attraction in Chennai. Known for its golden sand, sea breeze, and beautiful sunrise views, the beach attracts thousands of visitors daily. People enjoy walking, playing, relaxing, and tasting local street foods like sundal and bhajji. Several statues, memorials, and historical landmarks are located along the beach road. Marina Beach is also an important cultural and social gathering place for the city. It reflects the beauty, energy, and coastal charm of Chennai while providing entertainment and relaxation for people of all ages.</h3>
        </td>
        </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<imagemap/imageapp/output/1.png>)
![alt text](<imagemap/imageapp/output/temple.png>)
![alt text](<imagemap/imageapp/output/sowcarpet.png>)
![alt text](<imagemap/imageapp/output/nehru.png>)
![alt text](<imagemap/imageapp/output/egmore.png>)
![alt text](<imagemap/imageapp/output/marina.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
