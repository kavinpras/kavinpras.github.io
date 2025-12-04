<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kavin Prasanna - Bio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /*
            The space background image and styling for the entire body
        */
        body {
            /* Using an external image for a space background */
            background-image: url('bluespace.jpg');
            background-size: cover; /* Ensures the image covers the entire body */
            background-attachment: fixed; /* Keeps the background static when scrolling */
            color: #FFFFFF; /* White text for contrast */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center; /* Center content globally */
        }

        /*
            Styling for the main title section
        */
        .hero {
            min-height: 100vh; /* Make the section take up at least the full viewport height */
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 20px;
            background: rgba(0, 0, 0, 0.4); /* Subtle overlay for better text readability */
        }

        .hero h1 {
            font-size: 4.5em; /* Large text for the main headline */
            margin: 0;
            text-shadow: 0 0 10px #007bff, 0 0 20px #007bff; /* Neon glow effect */
        }

        /*
            Styling for the main content area (About Me, Connect)
        */
        main {
            padding: 40px 20px;
            /* Semi-transparent background for better readability over the space image */
            background: rgba(0, 0, 0, 0.75);
            border-top: 5px solid #007bff;
            box-shadow: 0 -10px 20px rgba(0, 0, 0, 0.5);
        }

        .about-me, .contact {
            max-width: 800px;
            margin: 0 auto 40px;
            padding: 20px;
        }

        h2 {
            color: #4dcfff; /* Light blue color for section headings */
            border-bottom: 2px solid #4dcfff;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        /*
            Styling for the social media icons
        */
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 30px; /* Space between icons */
            margin-top: 20px;
        }

        .social-icons a {
            color: #FFFFFF; /* White icons */
            font-size: 2.5em; /* Large icon size */
            transition: color 0.3s ease-in-out, transform 0.3s ease-in-out;
        }

        .social-icons a:hover {
            color: #4dcfff; /* Change color on hover */
            transform: scale(1.1); /* Slightly enlarge on hover */
        }

        /*
            Styling for the footer
        */
        footer {
            padding: 10px;
            background: #000000;
            border-top: 1px solid #222;
            font-size: 0.8em;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header class="hero">
        <h1>I'm Kavin Prasanna</h1>
    </header>

    <main>
        <section class="about-me">
            <h2>About Me</h2>
            <p>Hello! I'm Kavin Prasanna, a student at Claremont McKenna College with a passion for the pursuit of knowledge.</p>
            <p>I am also on two CMS teams: Football and Track&Field.</p>
        </section>

        <section class="contact">
            <h2>Connect with Me</h2>
            <div class="social-icons">
                <a href="https://instagram.com/_kavin44" target="_blank" aria-label="Instagram Profile">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="https://linkedin.com/in/kavinprasanna" target="_blank" aria-label="LinkedIn Profile">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="mailto:kavinprasanna44@gmail.com" target="_blank" aria-label="Send Email">
                    <i class="fas fa-envelope"></i>
                </a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Kavin Prasanna</p>
    </footer>
</body>
</html>
