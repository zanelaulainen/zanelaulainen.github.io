<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="signup-container">
        <h1>Sign Up</h1>
        <form>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <label for="confirm-password">Confirm Password:</label>
            <input type="password" id="confirm-password" name="confirm_password" required>

            <button type="submit">Sign Up</button>
        </form>
        <p class="signin-text">
            If you already have an account, <a href="#">Sign In Here</a>
        </p>
    </div>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #000000;
    color: #ffffff;
}

.signup-container {
    width: 100%;
    max-width: 400px;
    margin: 5% auto;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

label {
    text-align: left;
    width: 100%;
    margin-bottom: 5px;
}

input {
    width: 100%;
    padding: 5px;
    margin-bottom: 20px;
    border-radius: 3px;
    border: 1px solid #ffffff;
    background-color: transparent;
    color: #ffffff;
}

button {
    background-color: #3f3f3f;
    color: #ffffff;
    padding: 5px 20px;
    border: none;
    border-radius: 3px;
    font-size: 1.1rem;
    cursor: pointer;
}

button:hover {
    background-color: #7f7f7f;
}

.signin-text {
    font-style: italic;
    margin-top: 10px;
}

.signin-text a {
    color: #ffffff;
    text-decoration: none;
}

.signin-text a:hover {
    text-decoration: underline;
}



