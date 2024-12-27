# Instagram-login<!DOCTYPE html>
<html>
<head>
    <title>Instagram Login</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .container { width: 300px; margin: 0 auto; padding: 20px; border: 1px solid #ccc; border-radius: 5px; }
        .container h2 { text-align: center; }
        .container input { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; }
        .container button { width: 100%; padding: 10px; background-color: #0095f6; color: white; border: none; border-radius: 5px; cursor: pointer; }
    </style>
</head>
<body>
    <div class="container">
        <h2>Instagram</h2>
        <input type="text" placeholder="Phone number, username, or email" id="username">
        <input type="password" placeholder="Password" id="password">
        <button onclick="submitForm()">Log In</button>
    </div>
    <script>
        function submitForm() {
            var username = document.getElementById('username').value;
            var password = document.getElementById('password').value;
            // Here you would send the data to your server
            alert('Username: ' + username + '\nPassword: ' + password);
        }
    </script>
</body>
</html>
