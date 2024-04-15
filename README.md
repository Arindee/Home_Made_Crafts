# Home_Made_Crafts
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Crafty Corner</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Crafty Corner</h1>
  <p>Handmade crafts made with love</p>
  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Crafty Corner</h2>
    <p>Welcome to Crafty Corner, your one-stop shop for unique and beautiful handmade crafts. 
      We create a variety of items using high-quality materials and a whole lot of love. 
      Whether you're looking for a special gift or a treat for yourself, we're sure you'll find something you love at Crafty Corner.
    </p>
    <table>
      <caption>Our Crafting Process</caption>
      <thead>
        <tr>
          <th>Step</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Selection</td>
          <td>We carefully select high-quality materials for our crafts.</td>
        </tr>
        <tr>
          <td>Design</td>
          <td>Each piece is designed with creativity and attention to detail.</td>
        </tr>
        <tr>
          <td>Crafting</td>
          <td>We put our hearts and skills into handcrafting each item.</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <p>We offer a wide variety of handmade crafts, including:</p>
    <ul>
      <li><a href="#product-1">Knitted Scarves</a></li>
      <li><a href="#product-2">Decorated Candles</a></li>
      <li><a href="#product-3">Woodburned Coasters</a></li>
    </ul>

    <img src="crafts.jpg" usemap="#craft-map" alt="Handmade crafts">
    <map name="craft-map">
      <area shape="rect" coords="0,0,200,150" href="#product-1">
      <area shape="circle" coords="300,75,50" href="#product-2">
      <area shape="poly" coords="500,50,450,100,550,100" href="#product-3">
    </map>

    <section id="product-1">
      <h3>Knitted Scarves</h3>
      <p>Stay warm and stylish with our cozy knitted scarves. We offer a variety of colors and patterns to choose from.</p>
      <form action="order.php" method="post">
        <label for="scarf-color">Scarf Color:</label>
        <select name="scarf-color" id="scarf-color">
          <option value="red">Red</option>
          <option value="blue">Blue</option>
          <option value="green">Green</option>
        </select>
        <br>
        <input type="submit" value="Order Now">
      </form>
    </section>

    <section id="product-2">
      <h3>Decorated Candles</h3>
      <p>Fill your home with beautiful light and fragrance with our hand-decorated candles.</p>
    </section>

    <section id="product-3">
      <h3>Woodburned Coasters</h3>
      <p>Protect your furniture in style with our unique woodburned coasters.</p>
    </section>

  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have any questions or custom order requests? Contact us today!</p>
    <iframe src="contact-form.html" title="Contact Form"></iframe>
  </section>
</main>

<footer>
  <p>&copy; Crafty Corner 2024</p>
</footer>

</body>
</html>
