# myland.sk.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drone and Geodetic Surveying Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
            text-align: center;
        }
        .choice {
            display: inline-block;
            width: 45%;
            margin: 2em 2%;
            padding: 2em;
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 5px;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .choice:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Drone and Geodetic Surveying Services</h1>
    </header>
    <div class="container">
        <div class="choice" onclick="location.href='droneService.html'">
            <h2>Drone Service</h2>
            <p>Click here to view and pin drone pilot profiles</p>
        </div>
        <div class="choice" onclick="location.href='geodeticSurveying.html'">
            <h2>Geodetic Surveying</h2>
            <p>Click here to view and pin geodetician profiles</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Drone and Geodetic Surveying Services</p>
    </footer>
</body>
</html>
Drone Service Page (droneService.html)
This page will list the profiles of drone pilots.

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drone Service Profiles</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }
        .profile {
            background-color: white;
            margin: 1em 0;
            padding: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .portfolio img {
            width: 100px;
            height: auto;
            margin-right: 10px;
        }
        .feedback p {
            margin: 0.5em 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Drone Service Profiles</h1>
    </header>
    <div class="container">
        <!-- Sample Profile Start -->
        <div class="profile">
            <h3>John Doe</h3>
            <p>Experienced drone pilot specializing in aerial photography and videography.</p>
            <h4>Portfolio</h4>
            <div class="portfolio">
                <img src="portfolio1.jpg" alt="Portfolio Image 1">
                <img src="portfolio2.jpg" alt="Portfolio Image 2">
            </div>
            <h4>Feedback</h4>
            <div class="feedback">
                <p>Guest: Great service! Highly recommend.</p>
                <p>Guest: Professional and punctual.</p>
            </div>
        </div>
        <!-- Sample Profile End -->
        <!-- Add more profiles as needed -->
    </div>
    <footer>
        <p>&copy; 2024 Drone and Geodetic Surveying Services</p>
    </footer>
</body>
</html>
Geodetic Surveying Page (geodeticSurveying.html)
This page will list the profiles of geodeticians.

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geodetic Surveying Profiles</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }
        .profile {
            background-color: white;
            margin: 1em 0;
            padding: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .portfolio img {
            width: 100px;
            height: auto;
            margin-right: 10px;
        }
        .feedback p {
            margin: 0.5em 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Geodetic Surveying Profiles</h1>
    </header>
    <div class="container">
        <!-- Sample Profile Start -->
        <div class="profile">
            <h3>Jane Smith</h3>
            <p>Licensed geodetician with over 10 years of experience in land surveying and mapping.</p>
            <h4>Portfolio</h4>
            <div class="portfolio">
                <img src="survey1.jpg" alt="Survey Image 1">
                <img src="survey2.jpg" alt="Survey Image 2">
            </div>
            <h4>Feedback</h4>
            <div class="feedback">
                <p>Guest: Extremely accurate and detailed surveys.</p>
                <p>Guest: Excellent work and very thorough.</p>
            </div>
        </div>
        <!-- Sample Profile End -->
        <!-- Add more profiles as needed -->
    </div>
    <footer>
        <p>&copy; 2024 Drone and Geodetic Surveying Services</p>
    </footer>
</body>
</html>
