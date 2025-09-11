<script async src=
     crossorigin="anonymous"></script><!DOCTYPE html>
<html lang="en">
<head><!DOCTYPE html>
<html lang="en"><script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9815011330871700"
     crossorigin="anonymous"></script>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baby Names</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header">
        <div class="logo">Baby Names</div>
        <nav class="nav-menu">
            <a href="#">Home</a>
            <a href="#">Boys</a>
            <a href="#">Girls</a>
            <a href="#">Contact Us</a>
            <a href="#">About Us</a>
        </nav>
    </header>

    <main class="main-content">
        <h1>Welcome to Baby Names</h1>
        <p>Find the perfect name for your little one.</p>
        
        <div class="search-container">
            <input type="text" id="searchInput" placeholder="Search baby names...">
            <button onclick="searchNames()">Search</button>
        </div>

        <div class="enquiry-form-container">
            <h2>Enquiry Form</h2>
            <form id="enquiryForm">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Submit</button>
            </form>
        </div>
    </main>

    <script src="script.js"></script>
</body>
<meta name="google-adsense-account" content="ca-pub-9815011330871700">
</html><!-- Random Number Section Start -->
<section style="text-align:center; margin-top:30px;">
  <h2 style="color:#ff4d6d; font-family:Arial, sans-serif;">🎲 आपका यादृच्छिक नंबर</h2>
  <div id="randomNumberBox" style="
      display:inline-block;
      padding:20px 40px;
      margin-top:15px;
      font-size:30px;
      color:#fff;
      background:linear-gradient(135deg, #ff4d6d, #ffccd5);
      border-radius:15px;
      box-shadow:0 5px 15px rgba(0,0,0,0.3);
      font-weight:bold;
      min-width:100px;
      transition: all 0.3s ease;
  ">0</div>
  <br>
  <button onclick="generateRandomNumber()" style="
      margin-top:20px;
      padding:10px 25px;
      font-size:16px;
      background:#ff4d6d;
      color:white;
      border:none;
      border-radius:10px;
      cursor:pointer;
      box-shadow:0 3px 8px rgba(0,0,0,0.2);
      transition: all 0.3s ease;
  " 
  onmouseover="this.style.background='#ff3366';" 
  onmouseout="this.style.background='#ff4d6d';">
    नया नंबर दिखाएँ
  </button>
</section>

<script>
function generateRandomNumber() {
    var number = Math.floor(Math.random() * 100) + 1; // 1 se 100 tak random number
    var box = document.getElementById("randomNumberBox");
    box.textContent = number;
    box.style.transform = "scale(1.2)"; // animation
    setTimeout(function(){ box.style.transform = "scale(1)"; }, 300);
}
window.onload = generateRandomNumber; // page load hote hi number show ho
</script>
<!-- Random Number Section End -->
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
  <section style="text-align:center; margin-top:30px;">
  <h2 style="color:#ff4d6d; font-family:Arial, sans-serif;">🌸 Baby Pink Names 🌸</h2>
  <div id="nameList" style="
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:10px;
      margin-top:20px;
  "></div>
</section>

<script>
// Example: Large array of 500+ names
const names = [];
for(let i=1; i<=500; i++){
    names.push("BabyName"
</script>

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
body 

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
</section><footer>
  <div style="text-align:center; padding:15px; background:#ff4d6d; color:white; border-top:2px solid #ffccd5;">
    <!-- Attractive Hindi Name -->
    <h3>✨ सुनहरी दुनिया ✨</h3>
    
    <!-- Jaipur Address -->
    <p>📍 101, चौराहा बाजार, जयपुर, राजस्थान 302001</p>
    
    <!-- Copyright -->
    <p>&copy; 2025 सुनहरी दुनिया</p>
  </div>
</footer>
<footer>
&copy; 2025 My GitHub Site
</footer>
</body>
</html>

