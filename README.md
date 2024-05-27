<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #004d40;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00695c;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #004d40;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            border-bottom: 2px solid #004d40;
            padding-bottom: 10px;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Webpage</h1>
    </header>
    <nav>
        <a href="#about">About Joy</a>
        <a href="#journey">Challanges&Adventures</a>
        <a href="#career">Career Achievements</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div id="about" class="section">
            <h2>About Joy</h2>
            <p>A professional full-time model in Shanghai who gave up a privileged life to study in the United States and switch an Ingeroir Design Major to a STEM Major, finished a B.S. degree in major Marine Biology. As a non-native English speaker with no formal TOEFL or IELTS training, I took on my first significant life challenge driven by my passion for the ocean. With dedication and hard work, I achieved a commendable 3.4 GPA, earning myself a Bachelor's degree in Marine Biology.
              
After a series of setbacks, including a breakup and being asked to leave my shared apartment, I found solace in a four-day solo wilderness trip. Upon my return, I made a bold decision: to embrace van life.

Driven by a desire for freedom and adventure, I sold my car, taught myself design software, and scoured the market for the perfect van. By May 21, 2021, I had found it in Florida.

Despite juggling summer classes, I managed to complete the modifications wiht all As and move into my Dream Home on Wheels before graduating later that year.
        </div>
        <div id="journey" class="section">
            <h2>Travel Journey</h2>
            <p>I flew to Florida and bought a second-hand Mercedes Sprinter, which I converted into a camper during the summer while attending classes. I then completed a road trip around the United States. In Alaska, I worked as a Marine Biologist for NOAA. When I ran out of money during my travels, I returned to Los Angeles to work as a lab scientist and part-time surf instructor. In my free time, I enjoy spearfishing, surfing, hiking, and teaching children to paint.</p>
        </div>
        <div id="career" class="section">
            <h2>Career Achievements</h2>
            <p>While in the U.S., I completed my degree in Marine Biology and worked for NOAA in Alaska. Later, I worked as a lab scientist in Los Angeles and taught surfing part-time. My journey showcases my professional skills and my determination to pursue my dreams courageously.</p>
        </div>
        <div id="contact" class="section">
            <h2>Contact Me</h2>
            <p>If you are interested in my journey or want to learn more, please contact me through the following:</p>
            <ul>
                <li>Email: example@example.com</li>
                <li>Phone: 123-456-7890</li>
                <li>Social Media: 
                    <a href="#">Weibo</a>, 
                    <a href="#">WeChat</a>, 
                    <a href="#">Instagram</a>
                </li>
            </ul>
        </div>
    </div>
    <footer>
        &copy; 2024 My Personal Webpage. All rights reserved.
    </footer>
</body>
</html>
