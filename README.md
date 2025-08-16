# Uzence
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alpines</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link rel="stylesheet" href="/style.css">

</head>
<body>

  <header>
    <nav>
        <div style="text-align:right;">
           <a href="#">Features</a>
            
           <a href="#">Posts</a>
           <a href="#">Contact</a>
      </div>
    </nav>
    <div class="background-image"
      style="background-image:url(https://images.pexels.com/photos/32238072/pexels-photo-32238072/free-photo-of-dramatic-waterfall-in-islandia-with-lone-figure.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2);">
    <h1 align="center">Hello, Welcome to Alpines</h1>
    <p align="center">Alpines is a free responsive web template for everyone.</p>
    <div style="text-align:center;">
      <button> Login</button>
      <button>Sign-Up</button>
      <label for="name"></label>
    </div>
  </header>

  <section class="features">
    <div class="cards">
      <div class="card">
        <i class="fas fa-download fa-2x"></i>
        <h3>About Icons</h3>
        <p>Version 4 guidelines and icons for download.</p>
      </div>
      <div class="card">
        <i class="fas fa-file-alt fa-2x"></i>
        <h3>Read Documents</h3>
        <p>Download and edit the documents.</p>
      </div>
    </div>
  </section>

  <section class="posts">
    <h2 align="center">Vestibulum elementum nisi et eleifend pellentesque</h2>
    <p align="center">Photos by Unsplash</p>
    <div class="cards">
      <div class="card">
        <img src="image1.jpg" alt="image1.jpg">
        <h4>Be Happy and Healthy</h4>
        <p>City Capture</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis enim sapiente alias, aut quod magnam similique at autem quos cupiditate in quo ea nostrum sequi placeat repudiandae vitae exercitationem harum!</p>
      </div>
      <div class="card">
        <img src="image2.jpg" alt="">
        <h4>Be Kind and Helpful</h4>
        <p>City Capture</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam, aperiam beatae esse exercitationem animi accusantium velit eos alias recusandae odio fugiat consequatur ipsum voluptatem ratione ullam quis! Magnam, beatae delectus!</p>
      </div>
      <div class="card">
        <img src="image3.jpg" alt="">
        <h4>Be Adaptive and Flexible</h4>
        <p>City Capture</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur officia distinctio voluptate possimus! Quisquam rerum pariatur doloremque praesentium illum quae neque est, facere corporis suscipit aperiam temporibus repellendus dolorem excepturi!</p>
      </div>
      <div class="card">
        <img src="image4.jpg" alt="">
        <h4>Be Quick and Easy</h4>
        <p>City Capture</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem doloribus reprehenderit praesentium harum nobis facilis voluptates nulla accusamus veniam. In enim aperiam distinctio quis voluptas! Error expedita exercitationem repellendus dolore.</p>
      </div>
    </div>
  </section>

  <section class="subscribe">
    <h3>Stay In Touch</h3>
    <p>Subscribe to our newsletter</p>
    <input type="email" placeholder="Enter your email here...">
    <button>Submit Now</button>
  </section>

  <section class="contact">
    <h3>Feel free to send us a message about anything!</h3>
    <form>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <input type="text" placeholder="Subject"><br><br>
      <textarea rows="5" cols="50" placeholder="Leave your message..."></textarea><br><br>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <a href="#top">Go to Top</a>
    <div>
      <a href="#"><i class="fab fa-facebook"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-linkedin"></i></a>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  line-height: 1.6;
}

.hero {
  background:url('https://images.pexels.com/photos/32238072/pexels-photo-32238072/free-photo-of-dramatic-waterfall-in-islandia-with-lone-figure.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2') ;
  background-size:cover;
  color: rgb(255, 255, 255);
  text-align: center;
  padding: 80px 20px;
}

.navbar {
  display: flex;
  justify-content: space-between;
  padding: 0 40px;
}

.navbar ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

.navbar a {
  color: white;
  text-decoration: none;
}

.hero-text h2 {
  margin-top: 40px;
}

.buttons button {
  margin: 10px;
  padding: 10px 20px;
  border: none;
  color: white;
  cursor: pointer;
}

.login {
  background-color: black;
}

.signup {
  background-color: dodgerblue;
}

.container {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 100px 20px;
  gap: 20px;
  background: #e6e6e6;
}

.card {
  background: #fff;
  padding: 30px;
  border-radius: 8px;
  width: 300px;
  text-align: center;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  transition: 0.3s;
}

.card:hover {
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.icon {
  font-size: 40px;
  color: #00bcd4;
  border: 1px solid #00bcd4;
  border-radius: 50%;
  width: 70px;
  height: 70px;
  margin: 0 auto 20px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.card h3 {
  margin-bottom: 10px;
  color: #333;
}

.card p {
  font-size: 14px;
  color: #666;
}

.card a {
  color: #00bcd4;
  text-decoration: none;
}

.arrow {
  cursor: pointer;
  background: #fff;
  padding: 10px 15px;
  justify-content: space-between;
  border-radius: 5px;
  box-shadow: 0 0 8px rgba(0,0,0,0.1);
  transition: background0.3s;
  
}

.arrow:hover {
  background: #dfeef0;
}

.gallery {
  padding: 40px 20px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 20px;
}

.card {
  width: 250px;
}

.card img {
  width: 100%;
}

.subscribe {
  background: #6ec5ff;
  padding: 40px;
  text-align: center;
  color: white;
}

.subscribe input {
  padding: 10px;
  width: 250px;
  margin-right: 10px;
}

.subscribe button {
  padding: 10px 20px;
  background: white;
  color: #6ec5ff;
  border: none;
}

.contact {
  padding: 40px 20px;
  text-align: center;
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 600px;
  margin: auto;
}

.contact input, .contact textarea {
  padding: 10px;
  width: 100%;
}

footer {
  text-align: center;
  padding: 20px;
  background: #eee;
}

.social-icons {
  text-align: center;
  padding: 20px;
  background: #f8f8f8;
}

.social-icons a {
  display: inline-block;
  margin: 0 10px;
  color: #555;
  font-size: 20px;
  transition: color 0.3s ease;
}

.social-icons a:hover {
  color: #3498db; /* Change color on hover */
}

.top {
  margin-bottom: 10px;
}
