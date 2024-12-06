# Ex04 Places Around Me
## Date:06.12.2024
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS
### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using tag name the map.

### STEP 4
Create clickable regions in the image using tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<body>
    <center><img src="map.png" alt="map image" usemap="#map"></center>
    <map name="#map">
        <area target="_blank" alt="Sri Lanka" title="Sri Lanka" href="map1.html" coords="294,357,316,410,298,433,271,430,253,376,267,333" shape="poly">
        <area target="_blank" alt="Chennai" title="Chennai" href="map2.html" coords="259,255,357,223" shape="rect">
        <area target="_blank" alt="Coimbatore" title="Coimbatore" href="map3.html" coords="49,275,198,315" shape="rect">
        <area target="_blank" alt="Bengaluru" title="Bengaluru" href="map4.html" coords="116,215,211,251" shape="rect">
        <area target="_blank" alt="Hyderabad" title="Hyderabad" href="map5.html" coords="193,92,308,136" shape="rect">
        <area target="_blank" alt="Mumbai" title="Mumbai" href="map6.html" coords="1,33,90,90" shape="rect">
        <area target="_blank" alt="Bay of Bengal" title="Bay of Bengal" href="map7.html" coords="450,2,542,1,543,432,310,439,317,383,363,304,380,260,382,219,354,193,274,174" shape="poly">
    </map>
</body>
</html>
```
# Sri lanka.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sri Lanka</title>
</head>
<body>
    <center><h1>SRI LANKA</h1></center>
    <center><img src="pexels-photo-321570.jpeg" alt="Sri lanka" style="width: 800px;"></center>
    <p>Sri Lanka, often called the "Pearl of the Indian Ocean," is a tropical island nation located in South Asia.

         Known for its stunning landscapes, it boasts lush tea plantations, golden beaches, and ancient ruins.

         Sri Lanka has a rich cultural heritage, with influences from Buddhism, Hinduism, and colonial history.

          Its diverse wildlife and nature reserves, such as Yala National Park, attract nature enthusiasts from around the world.

           The capital city, Colombo, is a vibrant metropolis offering a mix of modernity and tradition. Sri Lanka's cuisine is renowned for its spicy flavors, featuring dishes like rice and curry, and unique street food.</p>
</body>
</html>
```
# Chennai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chennai</title>
</head>
<body>
    <center><h1>CHENNAI</h1></center>
    <center><img src="gettyimages-582726257-612x612.jpg" alt="Chennai" style="width: 800px;"></center>
    <p>Chennai, formerly known as Madras, is the capital city of the Indian state of Tamil Nadu. 
        
        Situated on the Coromandel Coast of the Bay of Bengal, it is one of the largest cultural, economic, and educational centers in South India. 
        
        Chennai is renowned for its rich heritage, bustling markets, and vibrant arts scene. It is home to historical landmarks such as Fort St. George, Marina Beach, and Kapaleeshwarar Temple. 
        
        The city is also a major hub for the Tamil film industry, often referred to as Kollywood. Known for its distinctive cuisine, Chennai offers a variety of traditional dishes like dosas, idlis, and filter coffee.</p>
</body>
</html>
```
# Coimbatore.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coimbatore</title>
</head>
<body>
    <center><h1>COIMBATORE</h1></center>
    <center><img src="photo-1609609830354-8f615d61b9c8.avif" alt="Coimbatore" style="width: 800px;"></center>
    <p>Coimbatore, often referred to as Kovai, is a bustling city in the Indian state of Tamil Nadu.
        
        Known as the "Manchester of South India," it is a major industrial and educational hub, renowned for its textile industry, engineering firms, and vibrant entrepreneurial spirit.
        
        The city boasts a pleasant climate and is surrounded by scenic landscapes, including the Western Ghats. 
        
        Coimbatore is also famous for its thriving IT sector, numerous educational institutions, and rich cultural heritage. Key attractions include Marudamalai Temple, VOC Park, and the beautiful Siruvani Waterfalls.</p>
</body>
</html>
```
# Bengaluru.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bengaluru</title>
</head>
<body>
    <center><h1>BENGALURU</h1></center>
    <center><img src="istockphoto-1433555979-612x612.jpg" alt="Bengaluru" style="width: 800px;"></center>
    <p>Bengaluru, also known as Bangalore, is the capital city of the Indian state of Karnataka. Often referred to as the "Silicon Valley of India," it is renowned for its thriving IT industry and technological advancements.
        
        The city is a major hub for startups and multinational companies, attracting professionals from around the world. 
        
        Bengaluru is also known for its pleasant climate, lush parks, and vibrant cultural scene. Key attractions include Lalbagh Botanical Garden, Bangalore Palace, and the bustling commercial areas of MG Road and Brigade Road.
        
        The city offers a blend of modernity and tradition, making it a dynamic and diverse metropolis.</p>
</body>
</html>
```
# Hyderabad.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hyderabad</title>
</head>
<body>
    <center><h1>HYDERABAD</h1></center>
    <center><img src="istockphoto-467851707-612x612.jpg" alt="Hyderabad" style="width: 800px;"></center>
    <p>Hyderabad, the capital city of the Indian state of Telangana, is a vibrant and culturally rich metropolis. 
        
        Known as the "City of Pearls" due to its historic pearl and diamond trading center, Hyderabad seamlessly blends its historic heritage with modern growth.
        
        The city is renowned for its impressive landmarks like the Charminar, Golconda Fort, and the beautiful Hussain Sagar Lake.
        
        Hyderabad is also a major hub for the technology industry, often referred to as "Cyberabad" due to its thriving IT sector. 
        
        The city's cuisine, particularly the famous Hyderabadi Biryani, is celebrated for its unique flavors and aromatic spices.</p>
</body>
</html>
```
# Mumbai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mumbai</title>
</head>
<body>
    <center><h1>MUMBAI</h1></center>
    <center><img src="premium_photo-1697730489433-4a5fe8a77f96.avif" alt="Mumbai" style="width: 800px;"></center>
    <p>Mumbai, formerly known as Bombay, is the capital city of the Indian state of Maharashtra.
        
        It is a bustling metropolis and the financial, commercial, and entertainment hub of India. 
        
        Known for its iconic landmarks such as the Gateway of India, Marine Drive, and the historic Chhatrapati Shivaji Maharaj Terminus, Mumbai is a city that never sleeps.
        
        The city is home to the Bollywood film industry, making it a major center for arts and culture. With its diverse population, vibrant street food scene, and rich history, Mumbai offers a unique blend of tradition and modernity.</p>
</body>
</html>
```
# Bay of Bengal
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bay of Bengal</title>
</head>
<body>
    <center><h1>BAY OF BENGAL</h1></center>
    <center><img src="istockphoto-1073216888-612x612.jpg" alt="Bay of Bengal" style="width: 800px;"></center>
    <p>The Bay of Bengal is the northeastern part of the Indian Ocean, bounded by India to the west, Bangladesh to the north, and Myanmar and the Andaman and Nicobar Islands to the east.
        
        It is the largest bay in the world, known for its rich biodiversity and significant economic and geopolitical importance. 
        
        The bay plays a crucial role in the climate and weather patterns of the region, influencing monsoons and cyclones.
        
        It is also a vital route for maritime trade, with several major ports along its coast, including Chennai, Visakhapatnam, and Kolkata.
        
        The Bay of Bengal is home to diverse marine life, vibrant coral reefs, and lush mangrove forests, making it an ecological treasure trove.</p>
</body>
</html>
```

## OUTPUT :
![Screenshot 2024-12-06 211350](https://github.com/user-attachments/assets/573039d9-8410-4576-a3c8-ff57aa196c15)
![Screenshot 2024-12-06 211410](https://github.com/user-attachments/assets/57bc22c3-12c9-469e-9485-b9021b15d498)
![Screenshot 2024-12-06 211427](https://github.com/user-attachments/assets/9c1ab635-f685-4673-be77-78c4f137c510)
![Screenshot 2024-12-06 211443](https://github.com/user-attachments/assets/bae213cc-b0e4-4215-a607-433da3b43194)
![Screenshot 2024-12-06 211528](https://github.com/user-attachments/assets/eb6332b6-7148-4d6b-a715-5348f62a2c4d)
![Screenshot 2024-12-06 211543](https://github.com/user-attachments/assets/df1495ce-b86c-4f01-ab11-671b4033b17d)
![Screenshot 2024-12-06 211616](https://github.com/user-attachments/assets/725cfb5a-bb7a-4203-b235-b5f5e19a9dbb)
![Screenshot 2024-12-06 211634](https://github.com/user-attachments/assets/d75af27c-782b-479f-84a3-bec6996236f1)

## RESULT
The program for implementing image maps using HTML is executed successfully.
