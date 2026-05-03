# SaieeshReddy-Portfolio


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saieesh Reddy | Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", sans-serif;
}

/* Black Background */
body {
    background: #0b0b0b;
    color: #ffffff;
    line-height: 1.6;
}

.container {
    width: 85%;
    margin: auto;
    padding: 40px 0;
}

/* Header */
header {
    text-align: center;
    padding: 60px 20px;
}

header h1 {
    font-size: 2.5rem;
    color: #ffffff;
}

header p {
    color: #b0b0b0;
    margin-top: 10px;
}

.contact {
    margin-top: 15px;
    font-size: 0.9rem;
}

/* Section Titles */
section h2 {
    margin-bottom: 20px;
    border-left: 4px solid #0a66c2;
    padding-left: 10px;
    color: #ffffff;
}

/* Cards */
.card {
    background: #111;
    color: #ffffff;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
    border: 1px solid #222;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: #0a66c2;
}

/* Skills */
.skills {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
}

.skills li {
    background: #0a66c2;
    color: #fff;
    padding: 8px 14px;
    margin: 6px;
    border-radius: 20px;
    font-size: 0.85rem;
}

/* Paragraphs */
section p {
    color: #d0d0d0;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #111;
    color: #aaa;
    margin-top: 40px;
}

/* Responsive */
@media(max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }

    .container {
        width: 90%;
    }
}
</style>

</head>
<body>

<header>
    <h1>Pamuluru Saieesh Reddy</h1>
    <p>Electronics & Communication Engineer</p>
    <div class="contact">
        <p>Email: saieeshreddypamuluru@gmail.com | Phone: +91 7416344275</p>
    </div>
</header>

<section class="container">
    <h2>About Me</h2>
    <p>
        Motivated Electronics and Communication Engineering graduate with strong expertise in programming,
        embedded systems, and image processing. Passionate about solving real-world problems through technology
        and continuously enhancing technical skills.
    </p>
</section>

<section class="container">
    <h2>Education</h2>

    <div class="card">
        <h3>B.E. Electronics and Communication Engineering</h3>
        <p>Sathyabama Institute of Science and Technology (2021 – 2025)</p>
        <strong>CGPA: 8.2</strong>
    </div>

    <div class="card">
        <h3>Intermediate (MPC)</h3>
        <p>Narayana Junior College (2019 – 2021)</p>
        <strong>77.5%</strong>
    </div>

    <div class="card">
        <h3>SSC</h3>
        <p>Ushakiran High School (2019)</p>
        <strong>CGPA: 9.2</strong>
    </div>
</section>

<section class="container">
    <h2>Technical Skills</h2>
    <ul class="skills">
        <li>Python</li>
        <li>C++</li>
        <li>C</li>
    </ul>
</section>

<section class="container">
    <h2>Experience</h2>
    <div class="card">
        <h3>Embedded Systems Intern – RETECH</h3>
        <p>July 2023 – August 2023</p>
        <ul>
            <li>Worked on microcontroller fundamentals and embedded programming</li>
            <li>Developed basic embedded applications</li>
            <li>Gained understanding of real-time system design</li>
        </ul>
    </div>
</section>

<section class="container">
    <h2>Projects</h2>

    <div class="card">
        <h3>Multi-Face Tracking & Clustering</h3>
        <p>
            Implemented a real-time face detection and tracking system using image processing techniques.
            Applied clustering algorithms to group similar faces and enhance recognition accuracy.
            Designed to perform efficiently in dynamic environments with multiple subjects.
        </p>
    </div>
        <h3>IoT Smart Parking System</h3>
        <p>
            Developed an IoT-based smart parking solution to efficiently manage parking spaces using real-time sensors.
            The system allows users to check slot availability, reserve parking remotely, and reduce traffic congestion.
            Improved overall parking efficiency through automation and real-time monitoring.
        </p>
    </div>

    

</section>

<section class="container">
    <h2>Soft Skills</h2>
    <ul class="skills">
        <li>Leadership</li>
        <li>Teamwork</li>
        <li>Quick Learner</li>
        <li>Communication</li>
    </ul>
</section>

<section class="container">
    <h2>Languages</h2>
    <p>English, Telugu</p>
</section>

<footer>
    <p>© 2026 Saieesh Reddy</p>
</footer>

</body>
</html>
