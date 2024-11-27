<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Excellent Business Platform</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to Our Business Platform</h1>
    <nav>
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#transfer">Transfer Money</a></li>
        <li><a href="#videos">Videos</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="services">
      <h2>Our Services</h2>
      <p>We offer top-notch business solutions tailored for your needs.</p>
    </section>

    <section id="transfer">
      <h2>Transfer Money</h2>
      <form id="transferForm">
        <label for="amount">Amount:</label>
        <input type="number" id="amount" name="amount" required>
        <label for="recipient">Recipient:</label>
        <input type="text" id="recipient" name="recipient" required>
        <button type="submit">Transfer</button>
      </form>
      <p id="transferResult"></p>
    </section>

    <section id="videos">
      <h2>Watch Our Videos</h2>
      <video controls>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </section>
  </main>

  <footer id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@businessplatform.com</p>
    <p>Phone: +123-456-7890</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
