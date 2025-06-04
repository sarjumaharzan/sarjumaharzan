<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Crystal Clean WA</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800">

  <!-- Header with Logo -->
  <header class="bg-blue-800 text-white p-5 shadow-md">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-3">
        <img src="logo.png" alt="Crystal Clean WA Logo" class="h-10 w-10 object-contain">
        <h1 class="text-2xl font-bold">Crystal Clean WA</h1>
      </div>
      <nav class="space-x-4">
        <a href="#services" class="hover:text-yellow-300">Services</a>
        <a href="#about" class="hover:text-yellow-300">About</a>
        <a href="#contact" class="hover:text-yellow-300">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-blue-100 py-16 text-center">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-4xl font-bold mb-4">Professional Cleaning Services in Western Australia</h2>
      <p class="text-lg mb-6">Reliable. Affordable. Spotless every time.</p>
      <a href="#contact" class="bg-blue-700 text-white px-6 py-3 rounded-full hover:bg-blue-600 transition">Book a Service</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-8">Our Cleaning Services</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="p-6 border rounded-lg shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Residential Cleaning</h4>
          <p>Weekly, fortnightly, or once-off cleans tailored to your home needs.</p>
        </div>
        <div class="p-6 border rounded-lg shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Commercial Cleaning</h4>
          <p>Office, retail, and business cleaning with professional standards.</p>
        </div>
        <div class="p-6 border rounded-lg shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">End of Lease Cleaning</h4>
          <p>Deep cleans that help you get your bond back – guaranteed satisfaction.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 bg-gray-100">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-4">Why Choose Crystal Clean WA?</h3>
      <p class="text-lg">We’re a locally-owned, insured cleaning business with a focus on trust, quality, and exceptional customer service. Servicing homes and businesses across Perth and surrounding areas.</p>
    </div>
  </section>

  <!-- Booking Section with Calendar -->
  <section id="contact" class="py-16 bg-white">
    <div class="max-w-2xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-4">Book a Cleaning</h3>
      <p class="mb-6">Please fill out the form below and we will confirm your booking shortly.</p>
      <form class="space-y-4" name="booking" method="POST" data-netlify="true">
        <input type="text" name="name" placeholder="Your Name" class="w-full border p-3 rounded" required />
        <input type="email" name="email" placeholder="Your Email" class="w-full border p-3 rounded" required />
        <input type="tel" name="phone" placeholder="Phone Number" class="w-full border p-3 rounded" required />
        <input type="date" name="date" class="w-full border p-3 rounded" required />
        <textarea name="message" placeholder="Additional Notes (optional)" class="w-full border p-3 rounded" rows="4"></textarea>
        <button type="submit" class="bg-blue-700 text-white px-6 py-3 rounded hover:bg-blue-600">Submit Booking</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-800 text-white text-center py-4 mt-16">
    <p>&copy; 2025 Crystal Clean WA. All rights reserved.</p>
  </footer>

</body>
</html>
