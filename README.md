<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faraz Mubeen Haider</title>
    <style>
        /* Reset and Box Model */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        /* Header Styles */
        .header-container {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        .header-container h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
        }

        .header-container h2 {
            font-size: 1.2em;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.5;
        }

        .header-container h2 strong {
            color: #ffffff; /* Bright white for emphasis */
            font-weight: bold;
        }

        /* Section Styles */
        section {
            max-width: 900px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h1, h2, h3 {
            color: #007acc; /* Consistent heading color */
        }

        /* List Styles */
        ul {
            list-style-type: none; /* Remove bullet points */
            padding: 0;
        }

        ul li {
            margin: 10px 0; /* Space between list items */
        }

        /* Link Styles */
        a {
            color: #007acc; /* Link color */
            text-decoration: none; /* Remove underline */
        }

        a:hover {
            text-decoration: underline; /* Underline on hover */
        }

        /* Social Links Image Styles */
        .social-links img {
            width: 24px; /* Icon size */
            height: 24px; 
            margin-right: 10px; 
            vertical-align: middle; 
        }

        /* Footer Styles */
        footer {
            text-align: center; 
            padding: 10px; 
            background: #007acc; 
            color: white; 
            margin-top: 20px; 
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .header-container h1 {
                font-size: 2em; /* Smaller heading on mobile */
            }
            
            .header-container h2 {
                font-size: 1em; /* Smaller subheading on mobile */
                padding-left: 10px; 
                padding-right: 10px; 
                line-height: 1.4; 
            }
            
            section {
                padding: 15px; /* Reduce padding on mobile */
                margin-top: 10px; 
                box-shadow: none; /* Remove shadow for mobile view */
                border-radius: 5px; /* Rounded corners for mobile view */
                background-color: #ffffff; 
                overflow-x:auto; /* Prevent overflow on small screens */ 
             }
             
             footer {
                 font-size:.8em ;/* Smaller footer text on mobile */ 
             }
         }
    </style>
</head>
<body>

    <div class="header-container">
        <h1>Faraz Mubeen Haider</h1>
        <h2>Welcome to my portfolio! I am a passionate developer and data enthusiast.</h2>
    </div>

    <section id="about">
        <h3>About Me</h3>
        <p>Brief introduction about yourself and your skills.</p>
    </section>

    <section id="portfolio">
        <h3>My Work</h3>
        <ul>
            <li><a href="#">Project One</a> - Description of project one.</li>
            <li><a href="#">Project Two</a> - Description of project two.</li>
            <li><a href="#">Project Three</a> - Description of project three.</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Faraz Mubeen Haider | Follow me on:</p>
        <div class="social-links">
           <!-- Add your social media icons here -->
           <a href="#"><img src="path/to/icon.png" alt="Social Media Icon"></a>
           <!-- Repeat for other icons -->
       </div>
    </footer>

</body>
</html>
