![image](https://github.com/user-attachments/assets/e113e12b-095c-4d01-991b-9803877acc9a)# implement-
Portfolio 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rokaia's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="text-align: center;background-color:rgb(1, 1, 51) ;color: white;">

    <header>
        <nav>
            <h2 class="logo">Rokaia</h2>
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#About">About</a></li>
                <li><a href="#Services">Services</a></li>
                <li><a href="#Contact">Contact</a></li>
            </ul>
        </nav>
    <hr>
    <hr>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h3>Hello, it's</h3>
            <h1>Rokaia Negm</h1>
            <p>And I'm a software engineer..</p>
            <button class="cta">View my work</button>
        </div>
        <div class="hero-image">
            <img src="undraw_coding_joxb-removebg-preview.png" alt="Illustration of a person working on a laptop">
        </div>
    </section>

    <hr>
    <section class="about">
         
        </div>
           <img src="undraw_personal-file_81l0.svg" alt="Illustration of a person reading code">
           1q
           <div class="about-text">
            <h2>About <span>Me</span></h2>
            <p>
                I am a passionate and detail-oriented software engineer with a knack for solving 
                complex problems through clean, efficient code. With expertise in both front-end 
                and back-end development, I specialize in building scalable, user-friendly applications 
                that deliver impactful solutions.
            </p>
            <p>
                A lifelong learner, I stay ahead in the ever-evolving tech landscape by constantly 
                exploring new tools and frameworks. Whether it's debugging tricky issues, optimizing 
                algorithms, or collaborating with cross-functional teams, I thrive on turning ideas into reality.
            </p>
        </div>
    </section>
    <section class="services">
        <h2>Our <span>Services</span></h2>
        <div class="service-container">
            <div class="service-card">
                <h3>Web Application Development</h3>
                <p>Create responsive, user-friendly web applications with seamless functionality across all devices.</p>
                <button class="read-more">Read more</button>
            </div>
            <div class="service-card">
                <h3>UI/UX Design</h3>
                <p>Collaborate on intuitive and visually appealing user interfaces that enhance user engagement and satisfaction.</p>
                <button class="read-more">Read more</button>
            </div>
            <div class="service-card">
                <h3>Software Maintenance</h3>
                <p>Provide ongoing maintenance, updates, and troubleshooting to ensure your software runs smoothly.</p>
                <button class="read-more">Read more</button>
            </div>
        </div>
    </section>
    <hr>
    <section class="contact">
        <h2>Contact <span class="highlight">Me</span></h2>
        <p>Let's build our work together</p>
        
        <div class="contact-form">
            <form action="#" method="POST">
                <div class="form-group">
                    <input type="text" name="name" placeholder="Full Name" required>
                    <input type="email" name="email" placeholder="Email" required>
                    <input type="tel" name="phone" placeholder="Phone Number">
                </div>
                <textarea name="message" placeholder="Your Request"></textarea>
                <button type="submit" class="contact-btn">Contact Us</button>
            </form>
        </div>
     <hr>
     <hr>
        <div class="social-links">
            <a href="instagram.png"><img src="instagram.png" alt="Instagram"></a>
            <a href="linkedin.png"><img src="linkedin.png" alt="LinkedIn"></a>
            <a href="facebook.png"><img src="facebook.png" alt="Facebook"></a>
            <a href="twitter.png"><img src="twitter.png" alt="Twitter"></a>
        </div>


   
        <footer>
            <nav>
                <a href="#Home">Home</a>
                <a href="#About">About</a>
                <a href="#Services">Services</a>
                <a href="#Contact">Contact</a>
            </nav>
        </footer>
    </section>
    

</body>
</html>


css stylesheet

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rokaia's Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: white;
        }

        h1, h2, h3 {
            text-align: center;
        }

        .highlight {
            color: #4db8ff;
        }

        hr {
            border: 1px solid #4db8ff;
            width: 80%;
            margin: 20px auto;
        }

        /* Header */
        header {
            padding: 15px 0;
            text-align: center;
        }

        nav {
            display: flex;

            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: auto;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 60px 20px;
        }

        .hero-text {
            max-width: 600px;
        }

        .cta {
            background-color: #4db8ff;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            font-size: 16px;
            cursor: pointer;
        }

        .cta:hover {
            background-color: #1f91e0;
        }

        /* About Section */
        .about {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 50px 20px;
        }

        .about img {
            width: 250px;
            margin-right: 30px;
        }

        .about-text {
            max-width: 600px;
        }

        /* Services */
        .services {
            text-align: center;
            padding: 50px 20px;
        }

        .service-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .service-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            width: 280px;
            transition: 0.3s ease-in-out;
        }

        .service-card:hover {
            background: rgba(255, 255, 255, 0.2);
        }

        .read-more {
            background-color: #4db8ff;
            border: none;
            padding: 8px 15px;
            border-radius: 20px;
            cursor: pointer;
        }

        .read-more:hover {
            background-color: #1f91e0;
        }

        /* Contact Section */
        .contact {
            text-align: left;
            padding: 50px 20px;
        }

        .contact-form {
            display: flex;
            justify-content: left;
            margin-top: 20px;
        }

        form {
            width: 50%;
            display: flex;
            flex-direction: column;
            align-items: left;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 15px;
            width: 100%;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            border-radius: 10px;
            border: 1px solid #4db8ff;
            background: transparent;
            color: white;
            align-items:last right;
        }

        textarea {
            height: 100px;
            resize: none;
        }

        .contact-btn {
            background: #b3b3b3;
            padding: 10px 25px;
            border: none;
            border-radius: 20px;
            margin-top: 15px;
            cursor: pointer;
            font-size: 16px;
            align-items: center;
        }

        .contact-btn:hover {
            background: #4db8ff;
            color: white;
        }


        /* Footer */
        footer {
            margin-top: 30px;
            background: #031322;
            padding: 30px 0;
            text-align: center;
        }

        
        /* Social Links */
        .social-links {
            margin-top: 30px;
            background-color:#031322 ;
        }

        .social-links a {
            margin: 0 10px;
        }

        .social-links img {
            width: 25px;
        }
        footer nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        footer nav a:hover {
            color: #4db8ff;
        }
    </style>

</body>
</html>


![image](https://github.com/user-attachments/assets/8ebbe37f-2dce-405e-81bf-5201ac147496)

![image](https://github.com/user-attachments/assets/d7b0e41b-4eca-4e3e-ba67-cc2cf9ead208)

![image](https://github.com/user-attachments/assets/98d3835d-18a9-49ae-aeae-9f1c9358b2ea)
