# Ex01 Portfolio
## Date:

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

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

    <header>
        <nav>
            <h2 class="logo">My Portfolio</h2>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section home">
        <h1>Hello, I'm Hemachandiran J</h1>
        <p>Welcome to my personal portfolio website created using HTML and CSS.</p>
    </section>

    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
            I am a Computer Science student with interest in web development,
            programming, and problem-solving. I enjoy learning new technologies
            and building simple, clean websites.
        </p>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="project-box">

            <div class="project">
                <h3>Project 1: Student Score Calculator</h3>
                <p>A simple HTML & JavaScript project that allows users to enter 
                marks and automatically calculates the total and average.</p>
            </div>

            <div class="project">
                <h3>Project 2: To-Do List App</h3>
                <p>A basic web app created using HTML, CSS, and JavaScript to add, 
                delete, and manage daily tasks.</p>
            </div>

            <div class="project">
                <h3>Project 3: Personal Portfolio</h3>
                <p>This portfolio webpage itself is a project developed using 
                HTML and CSS to showcase my skills.</p>
            </div>

        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <p>Email: hemachandiran@example.com</p>
        <p>Location: Chennai, India</p>
    </section>

</body>
</html>
```

index.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f4f4;
}

header {
    background: #333;
    padding: 15px 0;
}

nav {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    color: #fff;
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ffcc00;
}

.section {
    padding: 60px 10%;
    text-align: center;
}

.home {
    background: #ffcc00;
    color: #333;
    padding: 100px 10%;
}

.project-box {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.project {
    background: white;
    padding: 20px;
    width: 260px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
    transition: transform 0.3s;
}

.project:hover {
    transform: scale(1.05);
}
```


## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d15eefae-edbc-4a20-b68a-6090daf2218e" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
