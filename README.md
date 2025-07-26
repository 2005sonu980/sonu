<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>College Login</title>
  <style>
    /* Reset some default styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-container {
      background: white;
      padding: 2.5rem 3rem;
      border-radius: 8px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      width: 350px;
    }

    .login-container h2 {
      text-align: center;
      color: #333;
      margin-bottom: 1.5rem;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      margin-bottom: 0.5rem;
      font-weight: 600;
      color: #555;
    }

    input[type="text"],
    input[type="password"] {
      padding: 0.6rem 0.8rem;
      margin-bottom: 1.3rem;
      border: 1.5px solid #ddd;
      border-radius: 5px;
      font-size: 1rem;
      transition: border-color 0.3s ease;
    }

    input[type="text"]:focus,
    input[type="password"]:focus {
      border-color: #3a86ff;
      outline: none;
      box-shadow: 0 0 5px rgba(58, 134, 255, 0.4);
    }

    button {
      padding: 0.75rem;
      background-color: #3a86ff;
      color: white;
      font-size: 1.1rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #2c6cd1;
    }

    .forgot-password {
      margin-top: 0.8rem;
      text-align: right;
      font-size: 0.9rem;
    }

    .forgot-password a {
      color: #3a86ff;
      text-decoration: none;
    }

    .forgot-password a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>College Login</h2>
    <form action="#" method="post">
      <label for="username">Username or Email</label>
      <input type="text" id="username" name="username" placeholder="Enter your username or email" required />

      <label for="password">Password</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" required />

      <button type="submit">Login</button>

      <div class="forgot-password">
        <a href="#">Forgot password?</a>
      </div>
    </form>
  </div>
</body>
</html>
