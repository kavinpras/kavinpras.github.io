<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kavin Prasanna - Bio</title>
    
    <style>
        /* BASE STYLES */
        body {
            /* Keep the custom background image */
            background-image: url('bluespace.jpg');
            background-size: cover;
            background-attachment: fixed;
            color: #FFFFFF;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* HEADER & HERO SECTION */
        .hero {
            min-height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 10px;
            background: rgba(0, 0, 0, 0.4);
        }

        .hero h1 {
            font-size: 4.5em;
            margin: 0;
            /* Text shadow/glow removed for simplicity */
        }

        /* MAIN CONTENT */
        main {
            padding: 40px 20px;
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
            color: #4dcfff;
            /* Underline removed for simplicity */
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        /* SOCIAL ICON STYLES */
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }

        /* CUSTOM IMAGE SIZE (50px by 50px) */
        .social-icon {
            width: 50px;
            height: 50px;
            /* Simple transition for hover effect */
            transition: transform 0.2s ease-in-out; 
            border-radius: 5px; /* Added rounded corners */
        }

        .social-icon:hover {
            transform: scale(1.1);
        }

        /* FOOTER */
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
        <!-- The main title, centered and prominent -->
        <h1>I'm Kavin Prasanna</h1>
    </header>

    <main>
        <section class="about-me">
            <h2>About Me</h2>
            <p>Hello! I'm Kavin, a student at Claremont McKenna College with a passion for the pursuit of knowledge.</p>
            <p>I am also on two CMS teams: Football and Track&Field.</p>
        </section>

        <!-- Social Media Contact Section using Image Tags -->
        <section class="contact">
            <h2>Connect with Me</h2>
            <div class="social-icons">
                
                <!-- Instagram Image Icon -->
                <a href="https://instagram.com/_kavin44" target="_blank" aria-label="Instagram Profile">
                    <img src="Instagram_icon.png" alt="Instagram Icon" class="social-icon">
                </a>
                
                <!-- LinkedIn Image Icon -->
                <a href="https://linkedin.com/in/" target="_blank" aria-label="LinkedIn Profile">
                    <img src="linkedinicon.png" alt="LinkedIn Icon" class="social-icon">
                </a>
                
                <!-- Gmail Image Icon -->
                <a href="mailto:44@gmail.com" target="_blank" aria-label="Send Email">
                    <img src="gmail icon.png" alt="Gmail Icon" class="social-icon">
                </a>
                
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Kavin Prasanna</p>
    </footer>
</body>
</html>