# happy_new_year_2025
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy New Year 2025</title>
    <style>
        /* Body styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #282c34;
            color: white;
            text-align: center;
            padding: 50px;
            margin: 0;
        }

        /* Header styling */
        h1 {
            font-size: 50px;
            color: #ffcc00;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
        }

        /* Message box styling */
        .message-box {
            background-color: #444;
            padding: 20px;
            border-radius: 15px;
            width: 80%;
            margin: 0 auto;
            border: 2px solid #ffcc00;
        }

        /* Adding an animation */
        @keyframes textAnimation {
            0% { opacity: 0; transform: translateY(-50px); }
            50% { opacity: 1; transform: translateY(0); }
            100% { opacity: 0; transform: translateY(50px); }
        }

        /* Applying animation to the message */
        .message-box h2 {
            font-size: 40px;
            color: #00ffcc;
            animation: textAnimation 3s infinite;
        }
    </style>
</head>
<body>
    <h1>Happy New Year 2025!</h1>
    <div class="message-box">
        <h2>Wishing you a year full of joy, success, and good health!</h2>
        <p>May 2025 bring happiness to you and your loved ones.</p>
    </div>

    <!-- JavaScript to add more fun -->
    <script>
        // Display a popup greeting when the page loads
        window.onload = function() {
            alert("Welcome to the New Year 2025!");
        };
    </script>
</body>
</html>
