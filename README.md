body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #eef7ee;
}

header {
  background: linear-gradient(90deg,#2e7d32,#66bb6a);
  color: white;
  padding: 25px;
  text-align: center;
}

nav {
  background: #1b5e20;
  padding: 12px;
  text-align: center;
}

nav a {
  color: white;
  margin: 12px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.container {
  padding: 30px;
  max-width: 1000px;
  margin: auto;
}

.card {
  background: white;
  padding: 20px;
  margin: 20px 0;
  border-radius: 10px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
}

button {
  background: #2e7d32;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background: #1b5e20;
}

input, textarea {
  width: 100%;
  padding: 10px;
  margin: 8px 0;
  border-radius: 5px;
  border: 1px solid #ccc;
}

footer {
  background: #2e7d32;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}<!DOCTYPE html>
<html>
<head>
  <title>FutureFix</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
  <h1>FutureFix 🌍</h1>
  <p>Build a better future together</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="ideas.html">Ideas</a>
  <a href="environment.html">Environment</a>
  <a href="community.html">Community</a>
  <a href="contact.html">Contact</a>
  <a href="login.html">Login</a>
</nav>

<div class="container">

  <div class="card">
    <h2>💡 Innovation</h2>
    <p>Share ideas that could change the world.</p>
  </div>

  <div class="card">
    <h2>🌱 Protect Earth</h2>
    <p>Learn ways to help the environment.</p>
  </div>

  <div class="card">
    <h2>🤝 Help People</h2>
    <p>Support your community and make a difference.</p>
  </div>

</div>

<footer>
  FutureFix 2026
</footer>

</body>
</html>
