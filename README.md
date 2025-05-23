# Project Responsive Web Design using Bootstrap
## Date:07/05/2025

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(wallpaper\ for\ intel\ 1\ copy.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 35px;
                font-weight: 700;
                margin-left: -50px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                top: 100%;
                padding: 120px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 40px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:#6fa1f8;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: small;
                line-height: 2;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">TECHTONIC INOVATION</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        
        <div class="container">
            <div class="box-container">
                <div class="box">
                                        <h3>INTEL<SUP>&reg;</SUP>AI BOOST</h3>
                    <p>Ultra processors include built-in Al acceleration to boost productivity while maintaining privacy and flexibility.</p>
                </div>
                <div class="box">
                  
                    <h3>HIGH BANDWIDTH MEMORY</h3>
                    <p>64 gigabytes of ultra-high- bandwidth in-package memory and over 1GB of HBM capacity per core.</p>
                </div>
                <div class="box">
                   
                    <h3>IMMERSIVE GRAPHICS</h3>
                    <p>Supercharge your gaming and content creation experience with built-in intel <sup>&reg;</sup> Arc <sup>&trade;</sup> GPUs for ISV certifications.</p>
                </div>
                <div class="box">
                    
                    <h3>LONGER BATTERY LIFE</h3>
                    <p>An optimal balance of power and performance means you'll be able to stay productive longer while unplugged.</p>
                </div>
                <div class="box">
                   
                    <h3>CONNECTIVITY</h3>
                    <p>Cellular modem, Ethernet, Controllers, Silicon Photonics, fabric, WiFi, and Bluetooth connectivity for intel <sup>&reg;</sup> 5g Modem.</p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center>DESIGNED   AND   DEVELOPED  BY  SAI SANJAY R(212223040178) @   2024 </center>
    </footer>
</body>
</html>
```
## OUTPUT:

![Screenshot 2024-05-08 084936](https://github.com/Sachin-0305/Pharma/assets/149985717/4fa20cf9-894b-4dc9-998b-a8e3653f395a)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
