# Ex01 Portfolio
## Date:05.02.2026

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }

        /* Tab buttons */
        .tabs {
            display: flex;
            background-color: #333;
        }

        .tabs button {
            flex: 1;
            padding: 15px;
            color: white;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }

        .tabs button:hover {
            background-color: #555;
        }

        .tabs button.active {
            background-color: #2196F3;
        }

        /* Tab content */
        .tab-content {
            display: none;
            padding: 20px;
            background-color: white;
        }

        .tab-content h2 {
            color: #333;
        }
    </style>
</head>
<body>

    <!-- Tabs -->
    <div class="tabs">
        <button class="tablink active" onclick="openTab(event, 'home')">Home</button>
        <button class="tablink" onclick="openTab(event, 'about')">About</button>
        <button class="tablink" onclick="openTab(event, 'contact')">Contact</button>
    </div>

    <!-- Tab Contents -->
    <div id="home" class="tab-content" style="display:block;">
        <h2>Welcome</h2>
        <p>Hello! This is Natchathira. It is my portfolio website.</p>
    </div>

    <div id="about" class="tab-content">
        <h2>About Me</h2>
        <p>I am a student learning Modern Web Application Development.</p>
    </div>

    <div id="contact" class="tab-content">
        <h2>Contact</h2>
        <p>Email: admin@email.com</p>
        <p>Phone: 9876543210</p>
    </div>

    <!-- JavaScript -->
    <script>
        function openTab(event, tabName) {
            let i, content, links;

            content = document.getElementsByClassName("tab-content");
            for (i = 0; i < content.length; i++) {
                content[i].style.display = "none";
            }

            links = document.getElementsByClassName("tablink");
            for (i = 0; i < links.length; i++) {
                links[i].classList.remove("active");
            }

            document.getElementById(tabName).style.display = "block";
            event.currentTarget.classList.add("active");
        }
    </script>

</body>
</html>
```

## OUTPUT
<img width="1919" height="1086" alt="Screenshot 2026-02-02 153124" src="https://github.com/user-attachments/assets/3d05bae6-488f-42a8-8bdc-cd5d7cc31f5c" />
<img width="1919" height="1087" alt="Screenshot 2026-02-02 153103" src="https://github.com/user-attachments/assets/f39e6b88-4a27-40b6-a295-4e44c18fb8ca" />
<img width="1919" height="1088" alt="Screenshot 2026-02-02 153048" src="https://github.com/user-attachments/assets/ed46999a-79f9-407a-b3f9-996036dfd897" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
