```
<!DOCTYPE html>
<html>
<head>
	<title>Smart Vidhyapith Login</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="login-container">
		<h1>Smart Vidhyapith Login</h1>
		<form>
			<label for="username">Username:</label>
			<input type="text" id="username" name="username"><br><br>
			<label for="password">Password:</label>
			<input type="password" id="password" name="password"><br><br>
			<input type="submit" value="Login">
		</form>
		<p>Don't have an account? <a href="register.html">Register</a></p>
	</div>
</body>
</html>
```
CSS (in style.css file):
```
.login-container {
	width: 300px;
	margin: 50px auto;
	padding: 20px;
	border: 1px solid #ccc;
	border-radius: 5px;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.login-container h1 {
	text-align: center;
	margin-bottom: 20px;
}

.login-container form {
	margin-top: 20px;
}

.login-container label {
	display: block;
	margin-bottom: 10px;
}

.login-container input[type="text"], input[type="password"] {
	width: 100%;
	height: 40px;
	margin-bottom: 20px;
	padding: 10px;
	border: 1px solid #ccc;
}

.login-container input[type="submit"] {
	width: 100%;
	height: 40px;
	background-color: #4CAF50;
	color: #fff;
	padding: 10px;
	border: none;
	border-radius: 5px;
	cursor: pointer;
}

.login-container input[type="submit"]:hover {
	background-color: #3e8e41;
}

.login-container p {
	margin-top: 20px;
	text-align: center;
}

.login-container a {
	color: #4CAF50;
	text-decoration: none;
}

.login-container a:hover {
	color: #3e8e41;
}
```
