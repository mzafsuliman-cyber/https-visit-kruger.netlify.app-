# https-visit-kruger.netlify.app-
It’s a travel agency were you can book safaris or stays
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Visit Kruger | Luxury Safaris & Stays</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Visit Kruger</h1>
    <p>Luxury Safaris & Exclusive Stays</p>
    <a class="btn" href="https://wa.me/27791001009?text=Hi%2C%20I’d%20like%20to%20make%20a%20booking%20with%20Visit%20Kruger">Book via WhatsApp</a>
  </header>

  <section>
    <h2>Book Your Safari or Stay</h2>
    <form name="booking" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="booking">
      <input type="text" name="name" placeholder="Full Name" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="text" name="phone" placeholder="Phone / WhatsApp">
      <input type="text" name="service" placeholder="Safari or Stay">
      <input type="text" name="dates" placeholder="Preferred Dates">
      <input type="number" name="people" placeholder="Number of People">
      <textarea name="message" placeholder="Message"></textarea>
      <button type="submit">Request Booking</button>
    </form>
    <p class="note">Payment accepted at location.</p>
  </section>

  <footer>
    <p>Email: <a href="mailto:Mzafsuliman@gmail.com">Mzafsuliman@gmail.com</a></p>
    <p>WhatsApp: +27 79 100 1009</p>
  </footer>
</body>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0b0b0b;
  color: #e6e6e6;
}
header {
  text-align: center;
  padding: 60px 20px;
  background: linear-gradient(180deg, #000, #111);
}
h1 {
  font-size: 3em;
  margin-bottom: 10px;
  color: #c9a24d;
}
.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 12px 24px;
  background: #c9a24d;
  color: #000;
  text-decoration: none;
  font-weight: bold;
}
section {
  padding: 40px 20px;
  max-width: 600px;
  margin: auto;
}
form input, form textarea, form button {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border: none;
}
form button {
  background: #c9a24d;
  font-weight: bold;
}
footer {
  text-align: center;
  padding: 20px;
  background: #000;
}
a { color: #c9a24d; }
