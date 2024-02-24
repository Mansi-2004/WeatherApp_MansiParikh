
//HTML code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="./style.css">
</head>

<body>
 <div id="weather-container">
     <h2>Weather App</h2>
     <input type="text" id="city" placeholder="Enter city">
     <button onclick="getWeather()">Search</button>

     <img id="weather-icon" alt="Weather Icon">
     <div id="temp-div"></div>
     <div id="weather-info"></div>
     <div id="hourly-forecast"></div>
     </div>
     <script src="./script.js"></script>
</body>
</html>
