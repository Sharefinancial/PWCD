<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <style>
        /* Basic styling with overrides */
        body {
            font-family: Arial, sans-serif !important;
            display: flex !important;
            justify-content: center !important;
            align-items: center !important;
            height: 100vh !important;
            margin: 0 !important;
            background-color: #000000 !important; /* Background color of the page */
            overflow: hidden !important; /* Prevent scrolling */
        }
        .container {
            max-width: 400px !important;
            width: 100% !important;
            padding: 20px !important;
            border: 0px solid #ddd !important;
            border-radius: 5px !important;
            background-color: #000000 !important; /* Container background color */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1) !important; /* Optional: Add some shadow for better visibility */
        }
        h2 {
            margin-top: 0 !important;
            color: #ffffff !important; /* Set the Login text color to white */
            text-align: center !important; /* Center align the heading */
        }
        input {
            width: 100% !important;
            padding: 10px !important;
            margin: 5px 0 !important;
            box-sizing: border-box !important;
            border: 1px solid #ddd !important;
            border-radius: 5px !important;
            background-color: #f9f9f9 !important; /* Input background color */
            color: #333 !important; /* Input text color */
        }
        button {
            width: 100% !important;
            padding: 10px !important;
            background-color: #4CAF50 !important; /* Button background color */
            color: white !important; /* Button text color */
            border: none !important;
            border-radius: 5px !important;
            cursor: pointer !important;
        }
        button:hover {
            background-color: #45a049 !important; /* Button hover color */
        }
        .cta-links {
            display: flex !important;
            justify-content: space-between !important;
            margin-top: 10px !important;
        }
        .cta-links a {
            color: #4CAF50 !important; /* Link color */
            text-decoration: none !important;
            font-size: 14px !important;
        }
        .cta-links a:hover {
            text-decoration: underline !important;
        }
        #errorMessage {
            color: red !important;
            margin-top: 10px !important;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Login</h2> <!-- The text "Login" is now white -->
        <form id="loginForm">
            <input type="text" id="username" placeholder="Username" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Login</button>
            <p id="errorMessage"></p>
            <div class="cta-links">
                <a href="/forgot-password">Forgot Password?</a>
                <a href="/sign-up">Not a Member? Sign Up</a>
            </div>
        </form>
    </div>
    <script src="login.js"></script>
</body>
</html>
