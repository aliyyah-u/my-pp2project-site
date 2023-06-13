---
title: "FfT ICT"
date: 2023-05-30T10:05:50+01:00
draft: false
---

Welcome to FfT's ICT hub. Here you can access our contact details, ICT forms and ICT policies.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MODAL LOGIN FORM</title>
</head>
<body>
<h1>Modal Login Form</h1>
<button onclick="document.getElementById('id01').style.display='block'" style="width: auto;">Login</button>
<div id="id01" class="modal">
<form class="modal-content animate" action="/action_page.php" method="POST">
<div class="imgcontainer">
<span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
<img src="img_avatar.png" alt="Avatar" class="avatar">
</div>
<div class="container">
<!-- Username -->
<label for="uname"><b>Username</b></label>
<input type="text" placeholder="Enter Username" name="uname" required>
<!-- Password -->
<label for="psw"><b>Password</b></label>
<input type="password" placeholder="Enter Password" name="psw" required>
<!-- Submit Button -->
<button type="submit">Login</button>
<label>
<input type="checkbox" checked="checked" name="remember">Remember Me
</label>
</div>
</form>
</div>
</body>
</html>