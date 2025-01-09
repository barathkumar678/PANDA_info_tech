<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learning Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background: url('https://static.vecteezy.com/system/resources/thumbnails/050/392/385/small_2x/abstract-geometric-background-with-light-blue-and-white-gradient-photo.jpg') no-repeat center/cover;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
             background:#ffffff;

            padding: 10px 0;
        }

        nav a {
            color: black;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 1.1em;
        }

        nav a:hover {
            background: #575757;
            border-radius: 5px;
        }

        .hero-section {
            text-align: center;
            color: white;
            padding: 50px 20px;
            background: url('https://www.shutterstock.com/image-photo/female-hands-typing-on-laptop-260nw-1729282783.jpg') no-repeat center/cover;
            background-size: cover;
        }

        .hero-section h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .hero-section p {
            font-size: 1.5em;
        }

        .features {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background: #f9f9f9;
        }

        .feature {
            text-align: center;
            width: 30%;
        }

        .feature h3 {
            margin-bottom: 10px;
            color: #2575fc;
        }

        .about {
            padding: 40px;
            text-align: center;
            background: white;
        }

        .about img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .services {
            padding: 40px;
            background: #f4f4f4;
            text-align: center;
        }

        .services h2 {
            margin-bottom: 20px;
            color: #6a11cb;
        }

        .service {
            display: inline-block;
            width: 30%;
            margin: 10px;
            text-align: center;
        }

        .service img {
            width: 100px;
            height: auto;
            margin-bottom: 10px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to LearnHub</h1>
        <p>Your Gateway to Lifelong Learning</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero-section">
        <h1>Enhance Your Skills</h1>
        <p>Join millions of learners worldwide. Start learning today!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Expert Tutors</h3>
            <p>Learn from the best industry professionals.</p>
        </div>
        <div class="feature">
            <h3>Flexible Learning</h3>
            <p>Learn at your own pace from anywhere.</p>
        </div>
        <div class="feature">
            <h3>Certifications</h3>
            <p>Get certified and boost your career opportunities.</p>
        </div>
    </section>
    <section class="about" id="about">
        <h2>About LearnHub</h2>
        <p>At LearnHub, we are committed to making education accessible to everyone. Our courses are designed to cater to beginners and experts alike. With our user-friendly platform, you can master skills at your own convenience.</p>
        <img src="https://img.freepik.com/free-vector/group-students-watching-online-webinar_74855-5514.jpg?semt=ais_hybrid" alt="About LearnHub">
    </section>
    <section class="services" id="courses">
        <h2>Our Courses</h2>
        <div class="service">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-ohcccj6vAOE0Jr0V67kB6kdXKo0byp4ComWMxv3Lh9GvlV1NaxJ04LAxa3Eqo-hoNr0&usqp=CAU" alt="Web Development">
            <h3>Web Development</h3>
            <p>Build websites and applications from scratch.</p>
        </div>
        <div class="service">
            <img src="https://skillfloor.com/blog/uploads/images/202309/image_870x580_650449aeeebc4.jpg" alt="Data Science">
            <h3>Data Science</h3>
            <p>Analyze data and make informed decisions.</p>
        </div>
        <div class="service">
            <img src="https://blog-frontend.envato.com/cdn-cgi/image/width=4800,quality=75,format=auto/uploads/sites/2/2022/05/graphic-design-tools.png" alt="Graphic Design">
            <h3>Graphic Design</h3>
            <p>Create stunning visuals and graphics.</p>
        </div>
    </section>
    <footer id="contact">
        <p>Contact Us: info@learnhub.com | 6374026811</p>
        <p>&copy; 2025 LearnHub. All Rights Reserved.</p>
    </footer>
</body>
</html>


