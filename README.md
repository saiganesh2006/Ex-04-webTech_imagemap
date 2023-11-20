# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1:
Create a new django project and app.
## Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.
## Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click.
## Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked.
## Step 5:
 Include pictures and contents for your subpages and map them using urls and views.
# Code:
```
Developed by: D.B.V.Sai Ganesh
Ref.no:23009248
```
## MAP.HTML:
```
map.html:
<!DOCTYPE html>
<html>
    <head>
        <title>Nllore Image Map</title>
    </head>
    <body>
       
        <img src = "C:\Users\admin\Pictures\Screenshots\nellore.png" height="750" width="1800" align="center" usemap="#imgmap">
        <map name="imgmap">
           <area target="" alt="Ranganadha swami temple" title="Ranganadha swami temple" href="temple.html" coords="413,514,389,462,399,406,425,387,449,370,482,367,529,372,565,416,565,476,528,523,470,540" shape="poly">
           <area target="" alt="Nellore Barage" title="Nellore Barage" href="Barage.html" coords="611,709,545,745,492,797,669,773,498,805,562,882,622,888,664,872,695,862,707,836,718,802,715,755,686,711,647,709,624,716" shape="poly">
           <area target="" alt="Penna River" title="Penna River" href="penna.html" coords="1025,286,1020,304,1000,315,992,341,1008,357,1039,374,1065,374,1085,370,1119,349,1126,312,1093,289,1054,286" shape="poly">
           <area target="" alt="MGB Mall" title="MGB Mall" href="MGB.html" coords="1056,157,1021,170,1012,207,1016,229,1026,251,1041,256,1065,260,1088,255,1108,251,1109,224,1106,198,1106,185,1087,162" shape="poly">
           <area target="" alt="Children's Park" title="Children's Park" href="park.html" coords="811,192,839,190,881,188,898,171,899,128,873,107,829,104,806,109,790,120,775,135,774,157,780,177,793,185" shape="poly">
        </map>
    </body>
    </html>
```
## temple.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>SRI THALPAGIARI RANGANADHA SWAMY TEMPLE</title>
    </head>
    <body>
        <h1 align='center'>SRI THALPAGIARI RANGANADHA SWAMY TEMPLE</h1>
        <img src ="C:\Users\admin\Documents\ranganadha temple.jpg"  height="500" width="700" align="center" >
        <p>
        The Sri Ranganthaswami Temple in Nellore, Andhra Pradesh, India is a Hindu temple dedicated to Lord Ranganatha a resting form of Lord Vishnu. This temple, also called Talpagiri Ranganathaswami temple or Ranganayakulu is one of the oldest temples in Nellore. It is located on the banks of the Penna River and is believed to have been constructed in the 12th century. Just before the main entrance of the temple is a huge tower, called Gaaligopuram, which literally means "wind tower". This tower is approximately 70 feet high and has 10 feet of gold plated vessels on top of it, called kalashams. The gopuram was constructed by Yeragudipati Venkatachalam panthulu. Every year during the month of March–April (which varies according to the Indian calendar) a grand festival is celebrated. These are called Brahmotsavam.
      
        </p>
    </body>
</html>
```
## BARAGE.HTML:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Nellore barrage
        </title>
    </head>
    <body>
        <h2 align="center">NELLORE BARRAGE</h2>
        <img height = 400 src="c:\Users\admin\Downloads\nellore barrage.jpeg">
        <p>Nellore Barrage was constructed across Penna River during 1882–1886 
            with the thought of supplying water to the canals of Nellore, Kanupur, Kavali and Kanigiri.
            This barrage is the main source of irrigation of about 3.85 lakh acres of land.
         Each year the water level is increased by 0.90 meters for providing commandability to the increasing 
         demand of the canals of Kanupur and Kavali canals.</p>
    </body>
</html>
```

## PENNA.HTML:
```
<!DOCTYPE html>
<html>
    <head>
        <title>PENNA RIVER</title>
    </head>
    <body>
        <h1 align='center'>PENNA RIVER</h1>
        <img src ="C:\Users\admin\Documents\penna river.jpg" align="center" height="500" width="700"  >
        <p>
       Penna (also known as Pinakini, Penneru, Penner, Pennar, Pennai) is a river of southern India. The Penna river has several sources and mouths. The main stream starts in Nandi Hills in of Karnataka, flowing for 597 km to the north and east through several mountains and plains, draining into the Bay of Bengal in Nellore district of Andhra Pradesh. The river is seasonal, its main source of the water being from rains. Therefore, it appears like small stream during periods of drought. The major tributaries of the Penna are the Jayamangali, Kunderu and Sagileru from the north, and Chitravathi, Papagni and Cheyyeru from the south.
      
        </p>
    </body>
</html>
```
## MGB.HTML:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            MGB MALL
        </title>
        <body>
            <h2>MGB MALL NELLORE</h2>
            <img align="center" src="c:\Users\admin\Downloads\MG-nellore1.jpg">
            <p> MGB Felicity Mall into a trendsetter in the region. 
                It is a vibrating and well-frequented space of 320,000 sq. ft. spanning six floors—the only 
                organized mall in and around an 180kms radius of Nellore, covering four districts (Nellore, Prakasam, Kadapa, and Chittoor). I
                in a span of 36 months, MGB Felicity Mall has received over 13 million visitors and has achieved a very strong YOY growth record 
                with business conversion seeing double digit growth over the previous year. With plentiful options for entertainment, dining, 
                and modern-day shopping, MGB Felicity Mall is a thoughtfully laid out destination—a family entertainment center
                that is today Andhra Pradesh’s largest mall!</p>
        </body>
</html>
```
## Park.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>CHILDRENS PARK</title>
    </head>
    <body>
        <h1 align='center'>CHILDREN'S PARK</h1>
        <img src ="C:\Users\admin\Documents\parkk.jpg" align="center" height="500" width="700"  >
        <p>
      Children's Park is a charming city park with kid-friendly amenities such as a pool, playground, and skating rink. Children's Park is a well-known and popular park for both children and adults in Nellore. There are areas for yoga, meditation, walking, swimming, skating, and badminton in the park. The park has pleasant surroundings and conditions. Children's Park also has a number of recreational facilities. Children's Park is a one-of-a-kind destination for families and children, with a large playground and waterpark. This is a cosy city park known for its kid-friendly amenities.
        </p>
    </body>
</html>
```
# Output:
# MAP:
![nellore](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/82a0bf65-2621-402d-966d-f957b95f0032)

# RANGANADHA SWAMI TEMPLE:
![WhatsApp Image 2023-11-20 at 21 49 03_2bc648d7](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/757971d3-8aa1-480c-8af8-dbf9f5b4ccf1)

# NELLORE BARAGE:
![BARAGE](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/5dfa142b-2d64-49dd-8ec4-e3e0238c0812)

# PENNA RIVER:
![WhatsApp Image 2023-11-20 at 21 49 19_8a23dda2](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/58380b4f-ff15-454e-b2da-f1e51c9d73c9)

# MGB MALL:
![MGB MALL](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/fbdb8f4a-136a-44f6-b5e9-51390e3fc923)

# CHILDRENS PARK:
![WhatsApp Image 2023-11-20 at 21 48 26_cb6d3f7e](https://github.com/saiganesh2006/Ex-04-webTech_imagemap/assets/145742342/7a51a733-ab51-4d39-a394-f4479d2eb188)

# Result:
The program for implementing image map is executed successfully.
