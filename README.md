<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RO Bin Cleaning</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">

  <!-- Navbar -->
  <nav class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">RO Bin Cleaning</h1>
    <div class="space-x-6">
      <a href="#" class="hover:text-blue-500">Home</a>
      <a href="#services" class="hover:text-blue-500">Services</a>
      <a href="#pricing" class="hover:text-blue-500">Pricing</a>
      <a href="#about" class="hover:text-blue-500">About</a>
      <a href="#contact" class="hover:text-blue-500">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="text-center py-24 bg-gradient-to-r from-green-500 to-blue-600 text-white">
    <h2 class="text-5xl font-bold mb-6">Keep Your Garbage Bins Fresh & Clean</h2>
    <p class="text-lg mb-6">We’re Royce & Owen — your local bin cleaning service. Fast, affordable, and no more nasty smells.</p>
    <a href="#contact" class="px-8 py-3 bg-white text-blue-600 rounded-2xl font-semibold hover:bg-gray-200">Get a Free Quote</a>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-10">Our Services</h3>
    <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">🧼 Bin Cleaning</h4>
        <p class="text-gray-600">We deep clean and sanitize your garbage cans.</p>
      </div>
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">🚫 Odor Removal</h4>
        <p class="text-gray-600">Get rid of strong smells and bacteria.</p>
      </div>
      <div class="bg-white p-6 rounded-2xl shadow">
        <h4 class="text-xl font-semibold mb-2">♻️ Monthly Service</h4>
        <p class="text-gray-600">We come regularly so your bins stay fresh.</p>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="bg-white py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-10">Pricing</h3>
    <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      <div class="p-6 border rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Single Clean</h4>
        <p class="text-3xl font-bold mb-4">$15</p>
        <p class="text-gray-600">Per bin</p>
      </div>
      <div class="p-6 border rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Monthly Plan</h4>
        <p class="text-3xl font-bold mb-4">$10</p>
        <p class="text-gray-600">Per bin / visit</p>
      </div>
      <div class="p-6 border rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Bulk Deal</h4>
        <p class="text-3xl font-bold mb-4">Custom</p>
        <p class="text-gray-600">2+ bins discount</p>
      </div>
    </div>
  </section>

  <!-- Before & After -->
  <section class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-10">Before & After</h3>
    <p class="text-gray-600">Add your own photos here to show the difference!</p>
    <div class="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto mt-6">
      <div class="bg-gray-300 h-48 rounded-2xl flex items-center justify-center">Before</div>
      <div class="bg-gray-300 h-48 rounded-2xl flex items-center justify-center">After</div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="bg-white py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-6">About Us</h3>
    <p class="max-w-2xl mx-auto text-gray-600">We’re Royce and Owen, two local guys helping keep our community clean. We started RO Bin Cleaning to make a simple but important job easier for everyone.</p>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 px-6 text-center">
    <h3 class="text-3xl font-bold mb-6">Contact Us</h3>
    <p class="text-gray-600 mb-2">Call or text us: (555) 555-5555</p>
    <p class="text-gray-600 mb-4">Fast responses, same-day service available.</p>

    <!-- Simple Form -->
    <form class="max-w-md mx-auto space-y-4">
      <input type="text" placeholder="Your Name" class="w-full p-3 border rounded-xl">
      <input type="text" placeholder="Address" class="w-full p-3 border rounded-xl">
      <input type="text" placeholder="Number of Bins" class="w-full p-3 border rounded-xl">
      <button class="w-full bg-blue-500 text-white py-3 rounded-xl hover:bg-blue-600">Request Quote</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center p-6 shadow mt-10">
    <p class="text-gray-500 text-sm">© 2026 RO Bin Cleaning. All rights reserved.</p>
  </footer>

</body>
</html>
