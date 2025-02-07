<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raziya's Love</title>
    <style>
        /* General body styling */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        /* Heading styling with glowing effect */
        h1 {
            font-size: 3rem;
            color: #ff80ff;
            text-shadow: 0 0 20px #ff80ff, 0 0 30px #ff33ff;
            animation: glow 2s infinite;
        }

        /* Paragraph styling */
        p {
            font-size: 1.2rem;
            color: #aaa;
            text-align: center;
        }

        /* Link styling */
        a {
            text-decoration: none;
            color: #ff99cc;
            font-weight: bold;
        }

        a:hover {
            color: #fff;
        }

        /* Container for glowing animation */
        .glow {
            position: relative;
            animation: glow-heart 2s infinite;
        }

        /* Keyframe animations */
        @keyframes glow {
            0%, 100% {
                text-shadow: 0 0 20px #ff80ff, 0 0 30px #ff33ff;
            }
            50% {
                text-shadow: 0 0 30px #ff99ff, 0 0 40px #ff80ff;
            }
        }

        @keyframes glow-heart {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
        }
    </style>
</head>
<body>
    <div class="glow">
        <h1>Raziya ❤️</h1>
        <p>“Every moment with you feels like magic.”</p>
        <p><a href="#">Visit the site and feel the love!</a></p>
    </div>
</body>
</html>
