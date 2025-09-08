
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Charity: Water Landing Page</title>


  <!-- Adobe Fonts (replace with real link) -->
  <link rel="stylesheet" href="https://use.typekit.net/your-kit-id.css">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'proxima-nova', sans-serif;
      background-color: #ffffff;
      color: #003366;
      line-height: 1.6;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      padding: 1.5rem 2rem;
      border-bottom: 6px solid #002f5e;
      background-color: #fff;
    }

    .logo img {
      height: 200px;
      transition: transform 0.3s ease;
    }

    .logo img:hover {
      transform: scale(1.05);
    }

    .headline {
      font-size: 2.2rem;
      font-weight: 400;
      color: #003366;
      text-align: right;
      max-width: 900px;
      line-height: 1.4;
    }

    .headline .highlight-blue {
      color: #78b6c2;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .headline .highlight-blue:hover {
      color: #5fa2ae;
    }

    .headline strong {
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .headline strong:hover {
      color: #ffcc00;
    }

    /* Main Section */
    .main {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 2rem;
      background-color: #002f5e;
      color: white;
    }

    .text-box {
      flex: 1 1 400px;
      max-width: 550px;
      padding: 1rem;
    }

    .text-box p {
      font-size: 1.3rem;
      margin-bottom: 2rem;
      transition: color 0.3s ease;
    }

    .text-box p:hover {
      color: #cce6f0;
    }

    .cta-button {
      background-color: #78b6c2;
      color: #003366;
      font-weight: bold;
      padding: 0.75rem 1.75rem;
      border: none;
      border-radius: 30px;
      text-decoration: none;
      box-shadow: 2px 4px 8px rgba(0, 0, 0, 0.15);
      transition: background 0.3s ease, transform 0.2s ease;
      display: inline-block;
    }

    .cta-button:hover {
      background-color: #6aa5b0;
      transform: scale(1.05);
    }

    .image-box {
      flex: 1 1 400px;
      padding: 1rem;
      text-align: center;
    }

    .image-box img {
      width: 100%;
      max-width: 450px;
      border: 5px solid #cce6f0;
      border-radius: 10px;
      object-fit: cover;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .image-box img:hover {
      transform: scale(1.03);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }

    /* Tablet */
    @media (max-width: 1024px) {
      .headline {
        font-size: 2rem;
      }

      .text-box p {
        font-size: 1.15rem;
      }
    }

    /* Mobile */
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      .headline {
        font-size: 1.8rem;
        margin-top: 1rem;
        text-align: center;
      }

      .main {
        flex-direction: column;
        text-align: center;
        padding: 2rem 1rem;
      }

      .text-box, .image-box {
        flex: 1 1 100%;
        padding: 1rem 0;
      }

      .cta-button {
        margin-top: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">
      <img src="img/charitywater_logo_horizontal_BlackText.png" alt="charity: water logo">
    </div>
    <div class="headline">
      <span class="highlight-blue">You</span> Spark the <strong>Change</strong>.<br>
      <strong>We</strong> Deliver the <span class="highlight-blue">Water</span>.
    </div>
  </header>

  <!-- Main Content -->
  <section class="main">
    <div class="text-box">
      <p>
        See how student activists are creating 
        <strong>real change</strong> — and how your support fuels their mission 
        and delivers clean water where it matters most.
      </p>
      <a href="#" class="cta-button">JOIN US</a>
    </div>
    <div class="image-box">
      <img src="img/charity-water-img1.jpg" alt="People at a water source">
    </div>
  </section>

</body>
</html>

