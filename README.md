# love-connection
A free relationship and marriage website to connect people for friendship, love, and serious relationships.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- TITLE -->
  <title>TrueConnect – 100% Free Relationship & Marriage Website</title>

  <!-- META DESCRIPTION -->
  <meta name="description" content="TrueConnect is a 100% free relationship and marriage website. Create your free profile, connect safely, and find genuine relationships with no hidden charges.">

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #d63384;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #d63384;
    }
    input, select, textarea {
      width: 100%;
      padding: 8px;
      margin: 8px 0;
    }
    button {
      background: #d63384;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    footer a {
      color: #fff;
      text-decoration: none;
    }
  </style>
</head>

<body>

<header>
  <h1>TrueConnect</h1>
  <p>100% Free | Safe | Simple</p>
  <p>📞 Support: <a href="tel:9877075907" style="color:white;">9877075907</a></p>
  <nav>
    <a href="#about">About</a>
    <a href="#register">Register</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="container" id="about">
  <h2>About Us</h2>
  <p>
    TrueConnect is a 100% free relationship and marriage platform.
    No paid plans, no hidden charges. Create your profile and connect respectfully.
  </p>
</div>

<div class="container" id="register">
  <h2>Free Registration</h2>

  <form id="registerForm">
    <label>Full Name</label>
    <input type="text" placeholder="Enter your name" required>

    <label>Gender</label>
    <select required>
      <option value="">Select</option>
      <option>Male</option>
      <option>Female</option>
      <option>Other</option>
    </select>

    <label>Age</label>
    <input type="number" placeholder="Enter your age" required>

    <label>Looking For</label>
    <select required>
      <option value="">Select</option>
      <option>Friendship</option>
      <option>Relationship</option>
      <option>Marriage</option>
    </select>

    <label>City</label>
    <input type="text" placeholder="Enter your city" required>

    <label>About Yourself</label>
    <textarea rows="4" placeholder="Write something about yourself"></textarea>

    <button type="submit">Create Free Profile</button>
  </form>
</div>

<div class="container" id="contact">
  <h2>Contact Us</h2>
  <p>For any help or support, feel free to contact us.</p>
  <p><strong>📞 Contact Number:</strong> <a href="tel:9877075907">9877075907</a></p>
</div>

<footer>
  <p>© 2026 TrueConnect – Free Relationship & Marriage Website</p>
  <p>Contact: <a href="tel:9877075907">9877075907</a></p>
</footer>

<script>
  document.getElementById("registerForm").addEventListener("submit", function(e) {
    e.preventDefault();
    alert("Profile submitted successfully! (Database coming soon)");
  });
</script>

</body>
</html>
