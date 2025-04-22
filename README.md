# Ex04 Places Around Me
# Date:22.04.2025
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
#map.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGEMAP</title>
</head>
<body>
    
    <img align="center" src="/static/web.png" width="1900" height="1050" usemap="#image-map">
    <map name="image-map">
        <area  title="poorvika" href="poorvika.html" coords="1272,591,33" shape="circle">
        <area title="vikash" href="vikash.html" coords="898,258,683,173" shape="rect">
        <area  title="royal" href="royal.html" coords="1121,721,76" shape="circle">
        <area  title="bank" href="bank.html" coords="1228,627,1368,659" shape="rect">
        <area  title="food" href="food.html" coords="1644,337,83" shape="circle">
    </map>
</body>
</html>


#poorvika.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagemap</title>
    <center>
    <h1>POORVIKA MOBILE</h1>
    </center>
</head>
<body style="background-color:beige ;" >
    <center>
    <img src="/static/poor.jpg" width="500" height="350" usemap="#image-map">
    </center>
   <p>Poorvika Mobiles is a leading multi-brand retail chain that deals in mobile  phones and connections,accessories,
   recharges and internet data cards.Born out of the idea of amalgamating the look, touch and feel of mobile outlets with the choice,
   convenience and elegance that modern retail provides.</p>

   <p><a herf="">Driven by the mantra 'Think Mobile,Think Poorvika'</a>,today.poorvika has set up 390 and more one-stop-mobiles-shops across 60 cities
in Tamilnadu,Pondicherry,,Karnataka,Maharashtra,Kerala. It has progressively grown into the largest mobile retail chain in South India
with more than 200 touch points across the state. Headed by Mr.Uvaraj ,chief Executive Officer,amd  Mrs.Kanni Uvaraj,Managing director,
poorvika believes in the power of teamwork and cooperation, in thinking  big together, and in the power of unity.</p>

   <h2>Brief</h2>
   <p>client wanted the type to be clear and easy to understand looks. The word "poorvika should be bold and should work as a standalone. The 
    mascot/icon that can ressemble values of product or the brand name. The logo should not have any critically sharp edges which they have 
    now in their old logo. this become very difficult while doing led sign boardds, as they are not able to fix led modules in the edges.
    primary focus is print based layouts and the logo should convey gracem elegance of poorvika in the real world.
   </p>
</body>
</html>


#royal.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagemap</title>
    <h1 align="center">ROYAL ENFIELD SHOWROOM </h1>
</head>
<body style="background-color: aqua;">
    <center>
        <img src="/static/royal.jpg" width="500" height="350" usemap="#image-map">
        </center>
    Royal enfield os one of the hottest motorcycle brands available in India.
    It made its debut in 1955 for highway patrolling by indian army.
    find an authentic Royal enfield motorcycle dealer near you online in INDIA.
    Search your nearby bike dealers on our website using country.

    <h2>1891</h2>
     <p>In November 1891, entrepreneurs Bob Walker Smith and Albert Eadie buy George Townsend & Co. of Hunt End, Redditch.
         Townsend’s is a well-respected needle manufacturer of almost 50 years standing which has recently begun manufacturing bicycles.</p>
    <h2>1893</h2>
    <p>The duo win a contract to supply precision parts to the Royal Small Arms Factory of Enfield, Middlesex. To celebrate this prestigious order, 
        they rename their undertaking the Enfield Manufacturing Company Ltd. and call their first Bob Walker Smith designed bicycle, 
        the Enfield. The following year, their bicycles are renamed Royal Enfields and the trademark ‘Made Like A Gun’ is introduced.</p>
</body>
</html>


#vikash hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagemap</title>
    <center>
    <h1 align="center">VIKASH HOTEL</h1>
    </center>
</head>
<body style="background-color: beige;">
    <center>
        <img src="/static/vikash.jpg" width="400" height="350" usemap="#image-map">
        </center>
    <h2>WELCOME TO HOTEL VIKAS</h2>
    <p>Hotel vikas is the next generation magazine for senior hotel CEOs and decision makers. Hotel vikass is distinct and unique as it cuts through the unnessary filler-content and
        information overload and delivers straight message for CxOs. Hotel vikas short-format with concise and crisp makes it easier for busy CEOs to know the technology trends and get clear idea about the future of hospitality
        industry.
    </p>
    <h2>The Unique Features of Hotel Vikas are:</h2>
    <ul>
        <li>Small tabloid format of 4-color pages specifically designed for busy CEOs and decision makers who do not have time to go through 
            through big magazines.
        </li>
        <li>Small sixe of Hotel vikas makes it easily readable and valuable.</li>
        <li>Only pre-screened advertiser per category. Maximum of 6 advertisementss in easily readable and valuable.</li>
        <li>Only advertisers related to Hotel CEOs & Decision makers are accepted.</li>
        <li>Interview of Hotel CEOs or technology leaders.</li>
    </ul>
</body>
</html>

#bank.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagemap</title>
    <h1 align="center" >BANK</h1>
</head>
<body style="background-color: lightpink;">
    <center>
        <img src="/static/bank.jpg" width="500" height="350" usemap="#image-map">
        </center>
    Bank do many things,their primary role is to take in funds called deposites from those with money,pool,them,and lend them
    to those who need funds. Banks are intermediaries between depositors (who lend money to the bank)and borrowers to whomthe bank lends money.

    <h2>Provides safety and security</h2>
    
    <p>Banks are financial institutions that deal in monetary transactions. Banks form an integral part of any society. 
        There are numerous banks located in different parts of our country. While earlier there were limited number of banks with a few 
        branches in big cities and towns in India, a number of new banks have opened in the last few decades with branches in every nook and corner of the country.
         Banks provide a lot of services based on the customer’s requirements. They provide locker facilities, safe deposits, 
        ATM Services, Fixed Deposits, money transfer, loan for business and houses and several other monetary services to their customers.</p>
</body>
</html>

#food.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagemap</title>
    <center>
    <h1 align="center">STANDARD FOOD SPECIALITIES</h1>
    </center>
</head>
<body style="background-color: rgb(0, 217, 255);">
    <center>
        <img src="/static/image.png" width="500" height="350" usemap="#image-map">
        </center>
    <p>A speciality food is a food that is typocally considered as a "unique and high-value food item made in small quanities fron high-quality
ingredients. Consumers typically pay higher prices for specialty foods, and may perceive them as having various benefits compared to non-specialty food.
    </p> 
    <p>compared to staple foods,specialty foods may have higher prices due to more expensive ingredients and labor. some food stores 
specialize in or predominantly purvey specialty foods. several organizations exist that promote specialty foods and its purveyors.
    </p>
    <h2>specialty foods</h2>
    Foods that have been described as specialty foods include:
    <ul>
        <li>Alici from the Gulf of Trieste near Barcola.</li>
        <li>Artisanal foods.</li>
        <li>Caviar.</li>
        <li>Cheesse and artisan cheese.</li>
        <li>specialty coffee-sometimes referred to as artisanal coffee.</li>
        <li>High-quality chocolate.</li>
    </ul>
</body>
</html>

```
# NAME: HARINE S
# REGISTER NO: 212224230081

# OUTPUT

![Screenshot 2025-04-22 162351](https://github.com/user-attachments/assets/401d964b-5b0a-4f2d-b526-a16468bb2ad4)

![Screenshot 2025-04-22 162406](https://github.com/user-attachments/assets/1a7f90d0-29d9-410c-a68a-1c20e81b01a8)

![Screenshot 2025-04-22 162425](https://github.com/user-attachments/assets/d1944f31-861d-4bec-8e14-2913f1bfec1e)

![Screenshot 2025-04-22 162443](https://github.com/user-attachments/assets/d72d9bda-f82e-4ed1-8c8e-c22c0bfff977)

![Screenshot 2025-04-22 162454](https://github.com/user-attachments/assets/d0892823-c879-45bd-a2db-5e64f1ab827a)

![Screenshot 2025-04-22 162508](https://github.com/user-attachments/assets/410f7b98-7af9-40be-b711-f114798f2923)


# RESULT
The program for implementing image maps using HTML is executed successfully.
