# Styled_Profile_Card
## Date: 8/7/25
### REG NO : 212222110013

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

##  Code:
index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="profile-card">
        <img src="profile.png" alt="Profile picture of Harish Ragav S">
        <h1>Harish Ragav S</h1>
        <h2>Student | Aspiring Web Developer</h2>
        <p>
            I’m a 3rd-year Computer Science student at Saveetha Engineering College, passionate about full-stack development, AI tools, and building impactful tech projects.
        </p>

        <hr>

        <div class="section">
            <h3>Contact</h3>
            <p>Email: harishragavs@example.com</p>
            <p>Location: Namakkal, Tamil Nadu</p>
        </div>

        <div class="section">
            <h3>Education</h3>
            <ul>
                <li>B.E. CSE – Saveetha Engineering College (CGPA: 7.6)</li>
                <li>XII – Green Park International School (85.4%)</li>
                <li>X – Trinity International School (89%)</li>
            </ul>
        </div>

        <div class="section">
            <h3>Interests</h3>
            <ul>
                <li>Web Development</li>
                <li>Playing Cricket</li>
                <li>Reading</li>
            </ul>
        </div>

        <div class="section">
            <h3>Links</h3>
            <p>
                <a href="https://github.com/harishragav-s" target="_blank">GitHub</a> |
                <a href="mailto:harishragavs@gmail.com">Email Me</a>
            </p>
        </div>
    </div>

</body>
</html>
```
style.css 
```
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #f0f0f5;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.profile-card {
    background-color: #ffffff;
    border-radius: 12px;
    padding: 30px;
    text-align: center;
    width: 350px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.profile-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.profile-card img {
    border-radius: 50%;
    width: 120px;
    height: 120px;
    object-fit: cover;
}

.profile-card h1 {
    font-size: 24px;
    color: #333;
    margin: 15px 0 5px;
}
.profile-card h2 {
    font-size: 18px;
    color: #666;
    margin: 5px 0 15px;
}

/* Bio text */
.profile-card p {
    font-size: 14px;
    color: #444;
    margin-top: 10px;
}

/* Section divider line */
.profile-card hr {
    margin: 20px 0;
    border: none;
    border-top: 1px solid #ccc;
}

.section {
    margin-top: 20px;
    text-align: left;
}
.section h3 {
    margin-bottom: 5px;
    color: #222;
    font-size: 16px;
}


.section p,
.section ul {
    font-size: 14px;
    color: #555;
    margin: 5px 0;
    padding-left: 10px;
}


.section ul {
    list-style-type: disc;
    padding-left: 20px;
}


.section a {
    color: #0077cc;
    text-decoration: none;
}


.section a:hover {
    text-decoration: underline;
}
```

## Output:

![image](https://github.com/user-attachments/assets/e3a1a65d-cd99-476d-9c1f-a1d4ae2d1010)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
