# baby-names

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
