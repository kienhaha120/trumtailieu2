<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Trumtailieu - Đăng nhập</title>
  <link rel="stylesheet" href="styles/style.css"/>
</head>
<body class="login-page">
  <div class="overlay">
    <div class="login-box">
      <h1>📘 TRUM TÀI LIỆU</h1>
      <input type="text" id="email" placeholder="Email đăng nhập" />
      <input type="password" id="password" placeholder="Mật khẩu" />
      <button onclick="login()">Đăng nhập</button>
      <p id="error" class="error"></p>
    </div>
  </div>
  <script src="scripts/app.js"></script>
</body>
</html>
