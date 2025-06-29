<!-- Simple Login Page -->
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #b7e0e3;
        margin: 0;
        padding: 0;
    }
    .login-container {
        width: 320px;
        margin-top: 200px;
        margin-left: 570px;
        padding: 32px 24px;
        background: #131212;
        transition: background-color 0.3s ease;
        border-radius: 8px;
        box-shadow: 0 2px 8px rgba(125, 45, 45, 0.673);
    }
    .login-container h2 {
        color: rgb(231, 235, 235);
        text-align: center;
        margin-bottom: 24px;
    }
    .login-container label {
        color: rgb(231, 235, 235);
        display: block;
        margin-bottom: 8px;
        font-weight: 600;
    }
    .login-container input[type="text"],
    .login-container input[type="password"] {
        width: 100%;
        padding: 8px 10px;
        margin-bottom: 16px;
        border: 1px solid #925353;
        border-radius: 4px;
        box-sizing: border-box;
    }
    .login-container button {
        width: 100%;
        padding: 10px;
        background: #007bff;
        color: #e8e2e2;
        border: none;
        border-radius: 10px;
        font-size: 16px;
        cursor: pointer;
    }
    .login-container button:hover {
        background: #6995c1;
        transition: background-color 0.3s ease-out;
    }
   
</style>
<body>
<div class="login-container">
    <h2>Login</h2>
    <form>
        <label for="username" >Username</label>
        <input type="text" id="username" name="username" required placeholder="Username"> 

        <label for="password" >Password</label>
        <input type="password" id="password" name="password" required placeholder="Password">

        <button type="submit">Login</button>
    </form>
    
</div>

</body>
