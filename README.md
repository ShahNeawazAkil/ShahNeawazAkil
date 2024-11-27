<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> SNA Industry </title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to SNA Industry </h1>
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
  </main>

  <footer id="contact">
    <h2>Contact Us</h2>
    <p>Email: gaminggseries9@gmail.com.com</p>
    <p>Phone: +01857502787</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
To add integration with YouTube, Facebook, and Telegram to your website, you can include direct links or embed features like YouTube videos, Facebook pages, and Telegram links/buttons. Here's how you can do it step by step:


---

1. Updated HTML with YouTube, Facebook, and Telegram Links

Add a section for social media and communication platforms.

<section id="social">
  <h2>Connect with Us</h2>
  <div class="social-links">
    <!-- YouTube -->
    <a href="https://www.youtube.com/channel/YourChannelID" target="_blank">
      <img src="youtube-icon.png" alt="YouTube" class="social-icon"> YouTube
    </a>

    <!-- Facebook -->
    <a href="https://www.facebook.com/YourPageID" target="_blank">
      <img src="facebook-icon.png" alt="Facebook" class="social-icon"> Facebook
    </a>

    <!-- Telegram -->
    <a href="https://t.me/YourTelegramChannel" target="_blank">
      <img src="telegram-icon.png" alt="Telegram" class="social-icon"> Telegram
    </a>
  </div>
</section>


---

2. Embed a YouTube Video Directly

If you'd like to embed a YouTube video instead of just linking, use this code:

<section id="videos">
  <h2>Watch Our Videos</h2>
  <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/YourVideoID" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</section>

Replace YourVideoID with the ID of your YouTube video.


---

3. Add Icons for Visual Appeal (CSS)

Use icons for YouTube, Facebook, and Telegram (you can download free icons or use online libraries like Font Awesome).

Update your CSS to style the icons:

.social-links {
  display: flex;
  gap: 1rem;
  justify-content: center;
  margin-top: 1rem;
}

.social-links a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.social-icon {
  width: 30px;
  height: 30px;
}

.social-links a:hover {
  color: #0073e6;
}


---

4. Telegram Chat Link/Button

To let users join a Telegram channel or chat, add a link like this:

<a href="https://t.me/YourTelegramUsername" target="_blank" class="telegram-button">
  Join Us on Telegram
</a>

Style it in CSS:

.telegram-button {
  display: inline-block;
  padding: 0.5rem 1rem;
  background-color: #0088cc;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}

.telegram-button:hover {
  background-color: #006699;
}


---

5. Facebook Page Plugin

To embed a Facebook Page, use the following code:

