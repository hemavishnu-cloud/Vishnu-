<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tamil Nadu Tourism</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Noto+Serif+Tamil:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --primary:#8b0000;
      --secondary:#f4b41a;
      --bg:#fff8f0;
      --dark:#2b2b2b;
    }
    *{margin:0;padding:0;box-sizing:border-box}
    body{
      font-family:Poppins, sans-serif;
      background:var(--bg);
      color:var(--dark);
      line-height:1.6;
    }
    header{
      background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),url('https://images.unsplash.com/photo-1585128792020-803d29415281?auto=format&fit=crop&w=1600&q=80');
      background-size:cover;
      background-position:center;
      color:#fff;
      padding:80px 20px;
      text-align:center;
    }
    header h1{
      font-size:3rem;
      font-family:'Noto Serif Tamil', serif;
    }
    header p{margin:15px 0 25px;font-size:1.1rem}
    .search-bar{
      max-width:600px;
      margin:0 auto;
      display:flex;
      background:#fff;
      border-radius:30px;
      overflow:hidden;
    }
    .search-bar input{
      flex:1;
      border:none;
      padding:15px 20px;
      outline:none;
    }
    .search-bar button{
      background:var(--secondary);
      border:none;
      padding:0 25px;
      cursor:pointer;
      font-weight:600;
    }
    nav{
      background:#fff;
      box-shadow:0 2px 10px rgba(0,0,0,.08);
      position:sticky;top:0;z-index:10;
    }
    nav ul{
      display:flex;
      justify-content:center;
      list-style:none;
      flex-wrap:wrap;
    }
    nav li a{
      display:block;
      padding:15px 20px;
      text-decoration:none;
      color:var(--dark);
      font-weight:500;
    }
    nav li a:hover{color:var(--primary)}
    section{padding:60px 20px;max-width:1200px;margin:auto}
    h2{text-align:center;margin-bottom:40px;color:var(--primary)}
    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }
    .card{
      background:#fff;
      border-radius:15px;
      overflow:hidden;
      box-shadow:0 5px 15px rgba(0,0,0,.1);
      transition:transform .3s;
    }
    .card:hover{transform:translateY(-5px)}
    .card img{width:100%;height:180px;object-fit:cover}
    .card div{padding:15px}
    .card h3{margin-bottom:10px}
    .pill{
      display:inline-block;
      background:var(--secondary);
      color:#000;
      padding:5px 12px;
      border-radius:20px;
      font-size:.8rem;
      margin-top:10px;
    }
    .culture{
      background:url('https://images.unsplash.com/photo-1601132359864-c974e79890f4?auto=format&fit=crop&w=1600&q=80') center/cover;
      color:#fff;
    }
    .culture .card{background:rgba(255,255,255,.9);color:#000}
    footer{
      background:#2b2b2b;
      color:#fff;
      padding:30px 20px;
      text-align:center;
    }
    footer p{font-size:.9rem}
    @media(max-width:600px){header h1{font-size:2.2rem}}
  </style>
</head>
<body><header>
  <h1>தமிழ்நாடு சுற்றுலா | Tamil Nadu Tourism</h1>
  <p>Culture • Heritage • Nature • Experiences</p>
  <div class="search-bar">
    <input type="text" placeholder="Search places, hotels, experiences..." />
    <button>Search</button>
  </div>
</header><nav>
  <ul>
    <li><a href="#destinations">Destinations</a></li>
    <li><a href="#travel">Travel</a></li>
    <li><a href="#culture">Culture</a></li>
    <li><a href="#utilities">Utilities</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav><section id="destinations">
  <h2>Explore Destinations</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1586864387967-d02ef85d93e8?auto=format&fit=crop&w=800&q=80" />
      <div>
        <h3>Temples</h3>
        <p>Ancient Dravidian architecture and spiritual heritage.</p>
        <span class="pill">Spiritual</span>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1593693397690-362cb9666fc2?auto=format&fit=crop&w=800&q=80" />
      <div>
        <h3>Beaches</h3>
        <p>Serene coastlines along the Bay of Bengal.</p>
        <span class="pill">Relax</span>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1590402494682-cd3fb53b1f70?auto=format&fit=crop&w=800&q=80" />
      <div>
        <h3>Hill Stations</h3>
        <p>Misty hills and cool climates.</p>
        <span class="pill">Nature</span>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1621866336457-7d06b7e6b5a9?auto=format&fit=crop&w=800&q=80" />
      <div>
        <h3>Wildlife</h3>
        <p>National parks and rich biodiversity.</p>
        <span class="pill">Adventure</span>
      </div>
    </div>
  </div>
</section><section id="travel">
  <h2>Travel Facilities</h2>
  <div class="grid">
    <div class="card"><div><h3>Hotels</h3><p>Budget to luxury stays.</p></div></div>
    <div class="card"><div><h3>Transport</h3><p>Bus, train, cab & bike rentals.</p></div></div>
    <div class="card"><div><h3>Tour Packages</h3><p>Family, solo, pilgrimage & adventure.</p></div></div>
    <div class="card"><div><h3>Itineraries</h3><p>Expert travel guides.</p></div></div>
  </div>
</section><section id="culture" class="culture">
  <h2>Culture & Experiences</h2>
  <div class="grid">
    <div class="card"><div><h3>Tamil Cuisine</h3><p>Traditional flavors and street food.</p></div></div>
    <div class="card"><div><h3>Festivals</h3><p>Pongal, Chithirai, Karthigai Deepam.</p></div></div>
    <div class="card"><div><h3>Arts & Dance</h3><p>Bharatanatyam, Carnatic music.</p></div></div>
    <div class="card"><div><h3>Handicrafts</h3><p>Kanchipuram silk, Tanjore art.</p></div></div>
  </div>
</section><section id="utilities">
  <h2>Utilities & Support</h2>
  <div class="grid">
    <div class="card"><div><h3>Weather</h3><p>Live weather updates.</p></div></div>
    <div class="card"><div><h3>Emergency</h3><p>Tourist helplines & hospitals.</p></div></div>
    <div class="card"><div><h3>Languages</h3><p>English & தமிழ் support.</p></div></div>
    <div class="card"><div><h3>Accessibility</h3><p>User-friendly & inclusive design.</p></div></div>
  </div>
</section><section id="contact">
  <h2>Contact & Assistance</h2>
  <div class="grid">
    <div class="card"><div><h3>Contact Form</h3><p>Email & inquiry support.</p></div></div>
    <div class="card"><div><h3>Chatbot</h3><p>24/7 travel assistance.</p></div></div>
    <div class="card"><div><h3>Reviews</h3><p>User ratings & feedback.</p></div></div>
    <div class="card"><div><h3>Wishlist</h3><p>Save favorite destinations.</p></div></div>
  </div>
</section><footer>
  <p>© 2026 Tamil Nadu Tourism | Explore the Land of Tamils</p>
</footer></body>
</html>
