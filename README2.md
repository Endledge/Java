# Java - Full Web Development

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio</title>
    <link rel="shortcut icon" href="CLARK123.jpg">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fff8f1;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #231077, #1edba3);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
        }

        nav {
            background-color: #333;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffbd69;
        }

        .container {
            padding: 2rem;
        }

        .title {
            text-align: center;
            font-size: 2rem;
            color: #18b694;
            margin-bottom: 2rem;
        }

        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }

        .card {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            padding: 1rem;
            text-align: center;
            width: 250px;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;  
            border-radius: 8px;
            margin-bottom: 1rem;
        }

        .card h3 {
            color: #1798b8;
            margin-bottom: 0.5rem;
        }

        .card p {
            margin-bottom: 0.5rem;
        }

        .price {
            color: #1e175f;
            font-weight: bold;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 3rem;
        }

        @media screen and (max-width: 1000px) {
            .photo-gallery {
                justify-content: center;
            }
        }

        @media screen and (max-width: 768px) {
            .photo-gallery {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>My Portfolio</h1>
        <p></p>
        
    </header>

    <nav>
        <a href="http://127.0.0.1:5500/PORTFOLIO.html">Home</a>
        <a href="http://127.0.0.1:5500/PORTFOLIO2.html">Portfolio</a>
        <a href="http://127.0.0.1:5500/PORTFOLIO3.html">Contact</a>
    </nav>

    <div class="container">
        <h2 class="title">Portfolio</h2>

        <div class="photo-gallery">

            <div class="card">
                <a href="http://127.0.0.1:5500/website/act1.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 1">
                </a>
                <h3>Activity 1</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act2.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 2">
                </a>
                <h3>Activity 2</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act3.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 3">
                </a>
                <h3>Activity 3</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act4.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 4">
                </a>
                <h3>Activity 4</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/ACT5.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 5">
                </a>
                <h3>Activity 5</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act6.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 6">
                </a>
                <h3>Activity 6</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act7.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 7">
                </a>
                <h3>Activity 7</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act8.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 8">
                </a>
                <h3>Activity 8</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act9.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 9">
                </a>
                <h3>Activity 9</h3>
                <p></p>
                <p class="price"></p>
            </div>
        
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act10.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 10">
                </a>
                <h3>Activity 10</h3>
                <p></p>
                <p class="price"></p>
            </div>
           
            <div class="card">
                <a href="http://127.0.0.1:5500/website/act11.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 10">
                </a>
                <h3>Activity 11</h3>
                <p></p>
                <p class="price"></p>
            </div>

            <div class="card">
                <a href="http://127.0.0.1:5500/website/act12.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 10">
                </a>
                <h3>Activity 12</h3>
                <p></p>
                <p class="price"></p>
            </div>

            <div class="card">
                <a href="http://127.0.0.1:5500/website/act13.html" target="_blank">
                    <img src="compsci.jpg" alt="Activity 10">
                </a>
                <h3>Activity 13</h3>
                <p></p>
                <p class="price"></p>
            </div>
        </div>

    <footer>
        <p>© 2025 Portfolio | All Rights Reserved</p>
    </footer>

</body>
</html>


        // PORTFOLIO 3 //


<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contact</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="shortcut icon" href="CLARK123.jpg">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fff8f1;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #3d0f88, #08d687);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        nav {
            background-color: #333;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffbd69;
        }

        .contact-container {
            background: white;
            max-width: 600px;
            margin: 3rem auto;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .contact-container h2 {
            text-align: center;
            font-size: 2rem;
            color: #18b694;
            margin-bottom: 1rem;
        }

        .contact-container p {
            text-align: center;
            margin-bottom: 2rem;
        }

        form label {
            display: block;
            margin: 15px 0 5px;
            font-weight: 500;
        }

        form input[type="text"],
        form input[type="email"],
        form input[type="tel"],
        form textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.05);
            transition: border-color 0.3s ease;
        }

        form input:focus,
        form textarea:focus {
            border-color: #22806b;
            background-color: #fff;
            outline: none;
        }

        .form-buttons {
            display: flex;
            justify-content: space-between;
            gap: 1rem;
            margin-top: 20px;
        }

        .form-buttons button {
            flex: 1;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s;
        }
        .map-container {
         display: flex;
         justify-content: center;
         margin: 3rem auto;
        padding: 0 1rem;
        max-width: 1000px;
        }

        .map-container iframe {
         border-radius: 15px;
         width: 100%;
        }

        .form-buttons .submit-btn {
            background-color: #ff5733;
            color: white;
        }

        .form-buttons .submit-btn:hover {
            background-color: #e14c2a;
            transform: scale(1.05);
        }

        .form-buttons .clear-btn {
            background-color: #ccc;
            color: #333;
        }

        .form-buttons .clear-btn:hover {
            background-color: #bbb;
            transform: scale(1.05);
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 3rem;
        }

        footer a {
            color: #ffbd69;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media screen and (max-width: 768px) {
            nav {
                flex-direction: column;
                text-align: center;
            }

            .contact-container {
                margin: 2rem 1rem;
            }

            .form-buttons {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Contact</h1>
</header>

<nav>
    <a href="http://127.0.0.1:5500/PORTFOLIO.html">Home</a>
    <a href="http://127.0.0.1:5500/PORTFOLIO2.html">Portfolio</a>
    <a href="http://127.0.0.1:5500/PORTFOLIO3.html">Contact</a>
</nav>

<div class="contact-container">
    <h2></h2>
    <p>Have questions, feedback, or want to place an order? Fill out the form below!</p>

    <form id="contactForm">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <div class="form-buttons">
            <button type="submit" class="submit-btn">Submit</button>
            <button type="button" class="clear-btn" onclick="document.getElementById('contactForm').reset();">Clear</button>
        </div>
    </form>
</div>
<div>
    <div class="map-container">
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d3926.0604622840287!2d123.80981818247758!3d10.256707531715772!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sph!4v1744743726701!5m2!1sen!2sph" 
            width="100%" 
            height="450" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
            
        </iframe>
    </div>
</div>

<footer>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:clarkendledge051@gmail.com">clarkendledge051@gmail.com</a> | Phone: 0907-066-3236</p>
    <p>© 2025 Contact | All Rights Reserved</p>
</footer>

<script>
    document.getElementById('contactForm').addEventListener('submit', function(event) {
        event.preventDefault(); 
        alert("Message sent successfully!");
        this.reset(); 
    });
</script>

</body>
</html>