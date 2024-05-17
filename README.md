
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ScriptGaming - About</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #a5a2a2;
    padding: 20px;
    color: #000000;
  }
  
  .logo a {
    color: #000000;
    text-decoration: none;
    font-size: 24px;
    font-weight: bold;
  }
  
  .nav-links {
    display: flex;
    justify-content: space-around;
    list-style: none;
  }
  
  .nav-links li a {
    color: #000000;
    text-decoration: none;
    padding: 8px 15px;
    border-radius: 5px;
  }
  
  .nav-links li a:hover {
    background-color: #555;
  }
  
  .burger {
    display: none;
    flex-direction: column;
    cursor: pointer;
  }
  
  .burger div {
    width: 25px;
    height: 3px;
    background-color: #fff;
    margin: 3px;
  }
  
  @media screen and (max-width: 768px) {
    .nav-links {
      display: none;
    }
    .burger {
      display: flex;
    }
  }

  body {
    background-color: #333;
}
.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #a5a2a2;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    margin-top: 20px;
}
h1, h2 {
    color: #333;
}
p {
    color: #666;
    line-height: 1.6;
}
    </style>
</head>
<body>
    <nav>
        <div class="logo">
          <a href="#">ScriptGaming</a>
        </div>
        <ul class="nav-links">
          <li><a href="file:///C:/Users/sman1batu/Desktop/why/index.html">Home</a></li>
          <li><a href="file:///C:/Users/sman1batu/Desktop/why/1234.html">About</a></li>
          <li><a href="file:///C:/Users/sman1batu/Desktop/why/2344.html">Services</a></li>
          <li><a href="file:///C:/Users/sman1batu/Desktop/why/4565.html">Contact</a></li>
        </ul>
        <div class="burger">
          <div class="line1"></div>
          <div class="line2"></div>
          <div class="line3"></div>
        </div>
      </nav>

      <div class="container">
        <h1>About Me</h1>
        <h2>Im Is?</h2>
        <p>I am a TikTok and YouTube content creator, I am interested in games, history, informatics, I have 2 hobbies, namely swimming and badminton</p>
        <h2>I Live In?</h2>
        <p>
            I live in Indonesia, I am in East Java Province, Malang Regency, Karangploso, Ngenep Village, Karangploso View Housing Block, D3.</p>
        <h2>My Social Media?</h2>
        <p>You Can Find  My Social Media In :</p>
        <ul>
           <a href="https://www.youtube.com/channel/UCpRVp-7o4ZRTx5bPrPya0gg">Youtube</a>
           <a href="#">Tiktok</a>
            <!--Tambahkan lebih banyak tautan ke sosial media jika Anda inginkan-->
        </ul>
    </div>
    
</body>
</html>
