Ex04 Places Around Me
Date:24.11.2024
AIM
To develop a website to display details about the places around my house.

DESIGN STEPS
STEP 1
Create a Django admin interface.

STEP 2
Download your city map from Google.

STEP 3
Using tag name the map.

STEP 4
Create clickable regions in the image using tag.

STEP 5
Write HTML programs for all the regions identified.

STEP 6
Execute the programs and publish them.

CODE :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map Example</title>
    <style>
        img {
            max-width: 200%;
            height: auto;
        }
    </style>
</head>
<body>
    <center><h1>Image Map Example</h1></center>
    <center><img src="indian.jpg "usemap="#image-map"></center>

<map name="image-map">
    <area target="_blank" alt="Southern Railway"title="Southern Railway" href="https://en.wikipedia.org/wiki/Southern_Railway_zone" coords="177,218,127,321,100,355,71,308,53,257,80,237,110,210" shape="poly">
    <area target="_blank" alt="Northern Railway"title="Northern Railway" href="https://en.wikipedia.org/wiki/Northern_Railway_zone" coords="116,62,153,119,112,133,90,115,73,89,63,33,80,24,92,39" shape="poly">
    <area target="_blank" alt="Eastern Railway" title="Eastern Railway"  href="https://en.wikipedia.org/wiki/Eastern_Railway_zone"  coords="168,114,153,146,176,177,230,182,228,143,214,129" shape="poly">
    <area target="_blank" alt="Western Railway" title="Western Railway"  href="https://en.wikipedia.org/wiki/Western_Railway_zone"  coords="13,193,83,211,95,155,55,133,5,153" shape="poly">

</map>
    
</body>
</html>


class myhandler(BaseHTTPRequestHandler):
    def do_GET(self):
        print("request received")
        self.send_response(200)
        self.send_header('content-type', 'text/html; charset=utf-8')
        self.end_headers()
        self.wfile.write(content.encode())
server_address = ('',8000)
httpd = HTTPServer(server_address,myhandler)
print("my webserver is running...")
httpd.serve_forever()
OUTPUT :
![image map](https://github.com/user-attachments/assets/e3689baa-78fc-45af-9f17-7bf9d1065bf5)

RESULT
The program for implementing image maps using HTML is executed successfully.
