<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WiFi Login</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #f0f0f0;
      margin: 0;
    }
    .login-container {
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 400px;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .input-group {
      margin-bottom: 20px;
    }
    .input-group label {
    font-weight: bold;
    }
    .input-group input {
      width: 100%;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ddd;
      margin-top: 8px;
    }
    .btn {
      width: 100%;
      padding: 12px;
      background: #4CAF50;
      color: #fff;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    .btn:hover {
      background: #45a049;
    }
  </style>
</head>
<body>

  <div class="login-container">
    <h2>WiFi Login</h2>
    <form action="your_action_page" method="post">
      <div class="input-group">
        <label for="username">Name</label>
        <input type="text" id="username" name="username" placeholder="Enter your name" required>
      </div>

      <div class="input-group">
        <label for="phone">Phone Number</label>
        <input type="text" id="phone" name="phone" placeholder="Enter your phone number" required>
      </div>

      <button type="submit" class="btn">Login to WiFi</button>
    </form>
  </div>

</body>
</html>
