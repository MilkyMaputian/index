<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Generator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Password Generator</h1>

        <form id="passwordForm">
            <div class="unique-section">
                <img src="https://via.placeholder.com/200" alt="Unique Image" class="unique-animation">
                <div class="unique-content">
                    <h2>Generate a Password</h2>
                    <p>Enter your username and password:</p>
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required>
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required>
                    <button type="submit" class="unique-button">Submit</button>
                </div>
            </div>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>
