<script async src=
     crossorigin="anonymous"></script><!DOCTYPE html>
<html lang="en">
<head>
     <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9815011330871700"
     crossorigin="anonymous"></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cute Baby Names</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff0f5;
    }
    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #e60073;
      padding: 15px 20px;
      color: white;
    }
    .navbar h1 {
      margin: 0;
      font-size: 22px;
    }google.com, pub-9815011330871700, DIRECT, f08c47fec0942fa0
    .menu {
      display: flex;
      gap: 15px;
    }
    .menu a {
      text-decoration: none;
      color: white;
      font-weight: bold;
    }
    .dots {
      font-size: 24px;
      cursor: pointer;
    }
    /* Search box */
    .search-box {
      text-align: center;
      margin: 20px;
    }
    .search-box input {
      padding: 10px;
      width: 80%;
      max-width: 400px;
      border-radius: 8px;
      border: 2px solid #e60073;
    }
    /* Names Grid */
    .names {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .card h3 {
      margin: 10px;
      color: #333;
    }
    .boy {
      border-left: 6px solid #0099ff;
    }
    .girl {
      border-left: 6px solid #ff3399;
    }
    footer {
      text-align: center;
      padding: 15px;
      margin-top: 20px;
      background: #e60073;
      color: white;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <div class="navbar">
    <h1>👶 Baby Names</h1>
    <div class="menu">
      <a href="#">Home</a>
      <a href="#">Boys</a>
      <a href="#">Girls</a>
    </div>
    <div class="dots">⋮</div>
  </div>

  <!-- Search -->
  <div class="search-box">
    <input type="text" id="searchInput" placeholder="Search baby names...">
  </div>

  <!-- Names with Pics -->
  <div class="names" id="namesList">
    <div class="card boy">
      <img src="https://picsum.photos/200/150?random=1" alt="Baby Boy">
      <h3>Aarav</h3>
    </div>
    <div class="card boy">
      <img src="https://picsum.photos/200/150?random=2" alt="Baby Boy">
      <h3>Vivaan</h3>
    </div>
    <div class="card girl">
      <img src="https://picsum.photos/200/150?random=3" alt="Baby Girl">
      <h3>Aarohi</h3>
    </div>
    <div class="card girl">
      <img src="https://picsum.photos/200/150?random=4" alt="Baby Girl">
      <h3>Ananya</h3>
    </div>
    <div class="card boy">
      <img src="https://picsum.photos/200/150?random=5" alt="Baby Boy">
      <h3>Krishna</h3>
    </div>
    <div class="card girl">
      <img src="https://picsum.photos/200/150?random=6" alt="Baby Girl">
      <h3>Siya</h3>
    </div>
  </div>

  <footer>Made with ❤️ by Public Rahul</footer>

  <script>
    // 🔍 Search filter
    const searchInput = document.getElementById("searchInput");
    const namesList = document.getElementById("namesList");
    const cards = namesList.getElementsByClassName("card");

    searchInput.addEventListener("keyup", function() {
      const filter = searchInput.value.toLowerCase();
      for (let i = 0; i < cards.length; i++) {
        let txtValue = cards[i].innerText;
        if (txtValue.toLowerCase().indexOf(filter) > -1) {
          cards[i].style.display = "";
        } else {
          cards[i].style.display = "none";
        }
      }
    });
  </script>
</body>
</html># baby-names

📄 index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Baby Names Collection</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6ec;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #e6005c;
    }
    .names {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      font-weight: bold;
      color: #333;
    }
    .boy {
      border-left: 6px solid #0099ff;
    }
    .girl {
      border-left: 6px solid #ff3399;
    }
    footer {
      margin-top: 30px;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>
  <h1>👶 Baby Names Collection</h1>
  <p>Find cute names for boys & girls ✨</p>

  <div class="names">
    <div class="card boy">Aarav</div>
    <div class="card boy">Vivaan</div>
    <div class="card boy">Krishna</div>
    <div class="card girl">Aarohi</div>
    <div class="card girl">Siya</div>
    <div class="card girl">Ananya</div>
  </div>

  <footer>Made with ❤️ by Public Rahul</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Baby Names Collection</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6ec;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #e6005c;
    }
    .search-box {
      margin: 20px auto;
    }
    input[type="text"] {
      padding: 10px;
      width: 80%;
      max-width: 400px;
      border: 2px solid #e6005c;
      border-radius: 8px;
      font-size: 16px;
    }
    .names {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      font-weight: bold;
      color: #333;
      transition: 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .boy {
      border-left: 6px solid #0099ff;
    }
    .girl {
      border-left: 6px solid #ff3399;
    }
    footer {
      margin-top: 30px;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>
  <h1>👶 Baby Names Collection</h1>
  <p>Find cute names for boys & girls ✨</p>

  <!-- 🔍 Search Box -->
  <div class="search-box">
    <input type="text" id="searchInput" placeholder="Search baby names...">
  </div>

  <div class="names" id="namesList">
    <div class="card boy">Aarav</div>
    <div class="card boy">Vivaan</div>
    <div class="card boy">Krishna</div>
    <div class="card girl">Aarohi</div>
    <div class="card girl">Siya</div>
    <div class="card girl">Ananya</div>
    <div class="card boy">Rohan</div>
    <div class="card girl">Priya</div>
    <div class="card boy">Kabir</div>
    <div class="card girl">Ishita</div>
  </div>

  <footer>Made with ❤️ by Public Rahul</footer>

  <script>
    // 🔍 Search filter logic
    const searchInput = document.getElementById("searchInput");
    const namesList = document.getElementById("namesList");
    const cards = namesList.getElementsByClassName("card");

    google.com, pub-9815011330871700, DIRECT, f08c47fec0942fa0searchInput.addEventListener("keyup", function() {
      const filter = searchInput.value.toLowerCase();
      for (let i = 0; i < cards.length; i++) {
        let txtValue = cards[i].textContent || cards[i].innerText;
        if (txtValue.toLowerCase().indexOf(filter) > -1) {
          cards[i].style.display = "";
        } else {
          cards[i].style.display = "none";
        }
      }
    });
  </script>
</body>
</html>
<
body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f4f4f4; }
header { background:#ff4d6d; color:white; padding:15px; text-align:center; }
nav { background:#ffccd5; padding:10px; text-align:center; }
nav a { margin:0 10px; text-decoration:none; color:#333; font-weight:bold; }
section { padding:20px; max-width:800px; margin:auto; background:white; margin-top:20px; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1); }
footer { background:#ff4d6d; color:white; text-align:center; padding:10px; margin-top:20px; }


---

2️⃣ index.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My GitHub Site</title>
<!-- Google AdSense Verification -->
<meta name="google-site-verification" content="YOUR_CODE_HERE">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>Welcome to My GitHub Site</h1>
</header>
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
<a href="privacy.html">Privacy Policy</a>
</nav>
<section>
<h2>Hello!</h2>
<p>This is your homepage. Replace this with your content. Add posts or articles to make your site AdSense ready.</p>
</section>
<footer>
&copy; 2025 My GitHub Site
</footer>
</body>
</html>


---

3️⃣ about.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Us</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>About Us</h1>
</header>
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
<a href="privacy.html">Privacy Policy</a>
</nav>
<section>
<h2>About This Website</h2>
<p>Write something about yourself or your website here. Make it informative for visitors and Google.</p>
</section>
<footer>
&copy; 2025 My GitHub Site
</footer>
</body>
</html>


---

4️⃣ contact.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact Us</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>Contact Us</h1>
</header>
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
<a href="privacy.html">Privacy Policy</a>
</nav>
<section>
<h2>Get in Touch</h2>
<p>Email: yourname@example.com</p>
<p>Phone: +91-XXXXXXXXXX</p>
<p>You can also contact us via social media links here.</p>
</section>
<footer>
&copy; 2025 My GitHub Site
</footer>
</body>
</html>


---

5️⃣ privacy.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Privacy Policy</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>Privacy Policy</h1>
</header>
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
<a href="privacy.html">Privacy Policy</a>
</nav>
<section>
<h2>Privacy Information</h2>
<p>This website respects user privacy. We do not sell or share your data. All data usage is in compliance with Google AdSense policies.</p>
</section>
<footer>
&copy; 2025 My GitHub Site
</footer>
</body>
</html>

