# Ex01 Portfolio
## Date:10/2/2026

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
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Reena | Home</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<nav>
  <h1 class="logo">Reena.</h1>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="skills.html">Skills</a></li>
    <li><a href="education.html">Education</a></li>
    <li><a href="toolkit.html">Toolkit</a></li>
  </ul>
</nav>

<section class="hero">
  <img src="reena.jpeg" alt="Reena Profile Photo" class="profile-img">
  <h2>Hi, I'm <span>Reena</span></h2>
  <p><p>Building modern web apps as a Full Stack Developer & ML Engineer</p>
  <a href="skills.html"><button>Explore My Work</button></a>
</section>


<footer>
  <p>© 2026 Reena | Built with ❤️ using HTML & CSS</p>
</footer>

</body>
</html>
```
```
About.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About | Reena</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<nav>
  <h1 class="logo">Reena.</h1>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="skills.html">Skills</a></li>
    <li><a href="education.html">Education</a></li>
    <li><a href="toolkit.html">Toolkit</a></li>
  </ul>
</nav>

<section class="section">
    <img src="reena.jpeg" alt="Reena Photo" class="profile-img">
  <h2>About Me</h2>
  <p>
    Hi, I'm Reena 👋. I am a Computer Science student interested in Frontend Development,
    UI/UX design, Machine Learning, and AI tools.
  </p>
   <p>
    I enjoy creating modern websites and improving my skills by learning new
    technologies every day. I like working on small projects and building
    real-world applications.
  </p>
</section>

<footer>
  <p>© 2026 Reena</p>
</footer>

</body>
</html>

```
```
Skills.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Skills | Reena</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<nav>
  <h1 class="logo">Reena.</h1>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="skills.html">Skills</a></li>
    <li><a href="education.html">Education</a></li>
    <li><a href="toolkit.html">Toolkit</a></li>
  </ul>
</nav>

<section class="section">
  <h2>My Skills</h2>
  <div class="card-container">
    <div class="card">Frontend Developer</div>
  
    <div class="card">ML Engineer</div>
    <div class="card">UI / UX Designer</div>
    <div class="card">Python Developer</div>
    <div class="card">Strong Communication</div>
  </div>
</section>

<footer>
  <p>© 2026 Reena</p>
</footer>

</body>
</html>

```
```
Education.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Education | Reena</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<nav>
  <h1 class="logo">Reena.</h1>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="skills.html">Skills</a></li>
    <li><a href="education.html">Education</a></li>
    <li><a href="toolkit.html">Toolkit</a></li>
  </ul>
</nav>

<section class="section">
  <h2>Education</h2>

  <div class="edu-card">    
    <h3>2024 - 2028</h3>
    <p><strong>SAVEETHA ENGINEERING COLLEGE - Chennai</strong></p>
    <p>Computer Science and Engineering</p>
  </div>

  <div class="edu-card">
    <h3>2023 - 2024</h3>
    <p><strong>S.M. CADER MEERA SAIBO HR. SEC. SCHOOL - Thirunelveli</strong></p>
    <p>Computer Science - Math</p>
  </div>
</section>

<footer>
  <p>© 2026 Reena</p>
</footer>

</body>
</html>

```
```
toolkit.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Education | Reena</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<nav>
  <h1 class="logo">Reena.</h1>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="skills.html">Skills</a></li>
    <li><a href="education.html">Education</a></li>
    <li><a href="toolkit.html">Toolkit</a></li>
  </ul>
</nav>

<section class="section">
  <h2>Education</h2>

  <div class="edu-card">    
    <h3>2024 - 2028</h3>
    <p><strong>SAVEETHA ENGINEERING COLLEGE - Chennai</strong></p>
    <p>Computer Science and Engineering</p>
  </div>

  <div class="edu-card">
    <h3>2023 - 2024</h3>
    <p><strong>S.M. CADER MEERA SAIBO HR. SEC. SCHOOL - Thirunelveli</strong></p>
    <p>Computer Science - Math</p>
  </div>
</section>

<footer>
  <p>© 2026 Reena</p>
</footer>

</body>
</html>

```
## OUTPUT

## Index.html

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/75598101-ba39-4df3-868c-c4284eef3662" />

## About.html

<img width="1919" height="1194" alt="image" src="https://github.com/user-attachments/assets/f5a1ab41-cb44-4192-8ba2-31aea4c66420" />

## Skills.html

<img width="1919" height="1195" alt="image" src="https://github.com/user-attachments/assets/8ade9d21-eea6-448b-a5d9-b2aa538b7d88" />

## Education.html

<img width="1919" height="1193" alt="image" src="https://github.com/user-attachments/assets/37cb9063-f924-40de-b1bb-b158c29839b7" />

## Toolkit.html

<img width="1919" height="1191" alt="image" src="https://github.com/user-attachments/assets/95098a77-63a0-43a7-9040-9769b04375c9" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
