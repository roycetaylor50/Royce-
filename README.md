<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Elite Business</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">

  <!-- Navbar -->
  <nav class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">EliteCo</h1>
    <div class="space-x-6">
      <a href="#" class="hover:text-blue-500">Home</a>
      <a href="#services" class="hover:text-blue-500">Services</a>
      <a href="#about" class="hover:text-blue-500">About</a>
      <a href="#contact" class="hover:text-blue-500">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="text-center py-24 bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <h2 class="text-5xl font-bold mb-6">Grow Your Business Faster</h2>
    <p class="text-lg mb-6">We help you scale, market, and dominate your industry.</p>
    <button class="px-8 py-3 bg-white text-blue-600 rounded-2xl font-semibold hover:bg-gray-200">Get Started</button>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-10">Our Services</h3>
    <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">Marketing</h4>
        <p class="text-gray-600">Boost your brand with proven strategies.</p>
      </div>
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">Web Design</h4>
        <p class="text-gray-600">Modern, high-converting websites.</p>
      </div>
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">Consulting</h4>
        <p class="text-gray-600">Expert advice to grow your business.</p>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="bg-white py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-6">About Us</h3>
    <p class="max-w-2xl mx-auto text-gray-600">We are a team dedicated to helping businesses succeed. Our mission is to deliver results, increase revenue, and build strong brands.</p>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-6">Contact Us</h3>
    <p class="text-gray-600 mb-4">Email: contact@eliteco.com</p>
    <button class="px-8 py-3 bg-blue-500 text-white rounded-2xl hover:bg-blue-600">Reach Out</button>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center p-6 shadow mt-10">
    <p class="text-gray-500 text-sm">© 2026 EliteCo. All rights reserved.</p>
  </footer>

</body>
</html>
