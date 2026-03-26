<header>
    <h1>Demo Honey Pot</h1>
</header>
<body>
    <main class = "login">
            <h2>เข้าสู่ระบบ</h2>
            <form action="/login" method="POST">
                <label for="email">email : </label>
                <input type="email" name="email" placeholder="email@example.com"><br>
                <label for="password">password : </label>
                <input type="password" name="password" placeholder="password">
                <div class = "login btn">
                    <button type="submit">Login</button>
                </div>
            </form>
    </main>
</body>