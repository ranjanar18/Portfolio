# Ex01 Portfolio
## Date:30-10-26

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM


<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
        }

        header {
            background-color: #25274d;
            color: white;
            text-align: center;
            padding: 35px;
        }

        nav {
            background-color: #464866;
            padding: 18px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        section {
            background-color: white;
            margin: 25px;
            padding: 25px;
            border-radius: 10px;
        }

        h2 {
            color: #25274d;
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .project {
            background-color: #e8e9f5;
            padding: 20px;
            border-radius: 10px;
            flex: 1 1 220px;
            transition: 0.3s;
        }

        .project:hover {
            background-color: #cdd2f5;
            transform: translateY(-5px);
        }

        footer {
            background-color: #25274d;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Ranjana R</h1>
        <p>Computer Science Engineering Student</p>
        <p>Welcome to My Personal Portfolio</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>Hello! Welcome to my personal portfolio website.
        I am passionate about technology and programming.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a Computer Science Engineering student.
        I am interested in web development, programming,
        Artificial Intelligence and Machine Learning.</p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <ul>
            <li>HTML and CSS</li>
            <li>Java</li>
            <li>Python</li>
            <li>JavaScript</li>
            <li>Machine Learning</li>
        </ul>
    </section>

    <section id="projects">
        <h2>My Projects</h2>

        <div class="projects">

            <div class="project">
                <h3>Customer Churn Prediction</h3>
                <p>Predicts customer churn using
                Machine Learning techniques.</p>
            </div>

            <div class="project">
                <h3>CareerTwin AI</h3>
                <p>An AI-based resume analysis and
                job recommendation application.</p>
            </div>

            <div class="project">
                <h3>Library Management System</h3>
                <p>Manages library books, student
                details and borrowing records.</p>
            </div>

            <div class="project">
                <h3>Online Quiz Application</h3>
                <p>A web application for answering
                quiz questions and displaying scores.</p>
            </div>

        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: ranjanaramar@gmail.com</p>
        <p>Location: Tamil Nadu, India</p>
    </section>

    <footer>
        <p>© 2026 Ranjana R | My Portfolio</p>
    </footer>

</body>
</html>

## OUTPUT
![alt text](image.png)

![alt text](image-1.png)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.