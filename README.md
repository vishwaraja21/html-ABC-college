# html-ABC-college

## Ex-02


### index.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <img src="saveetha-logo.jpg" alt="College Logo" width="350px">
    <h1>Saveetha Engineering College</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="academics.html">Academics</a>
    <a href="admission.html">Admission</a>
    <a href="gallery.html">Gallery</a>
</nav>

<article>
    <h2>Welcome to Saveetha Engineering College</h2>
    <p>Welcome to SaveethaEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Veeraiyan — a committed medical professional and philanthropist par excellence. With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</p>
    <h2>Affiliation/Accreditations</h2>
    <li>Autonomous institution affiliated with Anna University</li>
    <li>Approved by AICTE</li>
    <li>NBA accreditation for 5 undergraduate courses</li>
    <li>SIRO recognition by DSIR Government of India</li>
    <li>An 'A' grade from NAAC</li>
    <li>Ranked by NIRF</li>
<article>

<footer>
    &copy; 2024 Saveetha Engineering College. All rights reserved.
</footer>

</body>
</html>


### academics.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="saveetha-logo.jpg" alt="College Logo" width="350px">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Academics</h2>
        <ul>
            <li>B.E
                <ul>
                    <li>Computer Science</li>
                    <li>ECE</li>
                    <li>EEE</li>
                    <li>Chemical</li>
                </ul>
            </li>
            <li>B.Tech
                <ul>
                    <li>Artificial Intelligence</li>
                    <li>Machine Learning</li>
                    <li>Information Technology</li>
                </ul>
            </li>
        </ul>
    </div>
    <footer>
        &copy; 2024 Saveetha Engineering College. All rights reserved.
    </footer>
</body>
</html>



### admissions.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="saveetha-logo.jpg" alt="College Logo" width="350px">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav> 
    <div class="container">
        <h2>Admission Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="course">Course:</label>
            <select id="course" name="course">
                <option value="computer-science">Computer Science</option>
                <option value="mathematics">Information Technology</option>
                <option value="english">Artificial Intelligence</option>
                <option value="sociology">Data Science</option>
                <option value="economics">Machine Learning</option>
                <option value="business-management">Robotics</option>
            </select>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            
            <input type="submit" value="Submit">
        </form>
    </div>
    <footer>
        &copy; 2024 Saveetha Engineering College. All rights reserved.
    </footer>
</body>
</html>



### gallery.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="saveetha-logo.jpg" alt="College Logo" width="350px">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Gallery</h2>
        <img src="https://imgs.search.brave.com/hI-c_72BgkcD_blUbXm_CzX31PWbYJUSvh-sAvg_lwA/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tYWls/LnNhdmVldGhhLmFj/LmluL2ltYWdlcy9z/ZWMvMjAyMi9NQkEv/U2VtaW5hcl9jb25k/dWN0ZWRfYnlfTUJB/X2RlcGFydG1lbnRf/b2ZfU2F2ZWV0aGFf/RW5naW5lZWluZ19D/b2xsZWdlLmpwZw" alt="Gallery Image 2" style="width: 40%;">
        <img src="https://imgs.search.brave.com/ogLfocBqobpUtTLgrk0p5TzYcz53kKkbapJqs-7e77Y/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWFn/ZXMuc3F1YXJlc3Bh/Y2UtY2RuLmNvbS9j/b250ZW50L3YxLzVm/OGE4NWZjMmFkN2E1/MTRjM2ZkYWY2MC8x/NjAzNTkxNTk0NzA1/LUFMUTlFWjNDS1Q1/MFdVQTJSRUJYLzE1/ODE2ODE2NjFwaHBw/MDRxVkQuanBlZw" alt="Gallery Image 3" style="width: 40%;">
        <img src="gate.jpg" alt="">
        <img src="eng.jpg" alt="">
        <img src="https://imgs.search.brave.com/p4PG2FI-UvHJHd8jCDxgQnH3klKVzX7z16SsEx8y2c0/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jb250/ZW50LmpkbWFnaWNi/b3guY29tL2NvbXAv/a2FuY2hpcHVyYW0v/azUvOTk5OXB4eDQ0/Lnh4NDQuMTEwMzI1/MTkxNzA0LmUzazUv/Y2F0YWxvZ3VlL3Nh/dmVldGhhLWVuZ2lu/ZWVyaW5nLWNvbGxl/Z2UtYWRtaXNzaW9u/LW9mZmljZS10aGFu/ZGFsYW0ta2FuY2hp/cHVyYW0tY29sbGVn/ZXMtYjRxd2c4di5q/cGc_dz0zODQwJnE9/NzU" alt="Gallery Image 4" style="width: 40%;">
    </div>
    <footer>
        &copy; 2024 Saveetha Engineering College. All rights reserved.
    </footer>
</body>
</html>



## Output :

![out-ex02-1](https://github.com/KGSatheeshKumar/html-city-tourism/assets/128453421/7a749b09-66c0-4b0a-b15e-dcdf4dfe6426)
![out-ex02-2](https://github.com/KGSatheeshKumar/html-city-tourism/assets/128453421/482259e9-37a9-4b77-9d1a-2336f8ef04b3)
![out-ex02-3](https://github.com/KGSatheeshKumar/html-city-tourism/assets/128453421/8b35a67d-63a2-4d3d-ba2a-2c99957332ec)
![out-ex02-4](https://github.com/KGSatheeshKumar/html-city-tourism/assets/128453421/95c9dddc-34e2-4c15-94ce-75c2ce0d6e55)

## Result :

Thus,Creating a website for college was executed successfully.
