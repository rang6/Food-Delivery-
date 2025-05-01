<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QuickBite - Food Delivery</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-red-500 text-white p-4">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">QuickBite</h1>
      <nav class="space-x-4">
        <a href="#" class="hover:underline">Home</a>
        <a href="#menu" class="hover:underline">Menu</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-white py-16">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-4">Delicious Food Delivered Fast</h2>
      <p class="text-lg mb-6">Order your favorite meals from the comfort of your home.</p>
      <a href="#menu" class="bg-red-500 text-white px-6 py-3 rounded-lg hover:bg-red-600">Order Now</a>
    </div>
  </section>

  <!-- Features -->
  <section class="py-12 bg-gray-100">
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div>
        <h3 class="text-xl font-semibold mb-2">Fast Delivery</h3>
        <p>Get your food delivered in under 30 minutes.</p>
      </div>
      <div>
        <h3 class="text-xl font-semibold mb-2">Fresh Ingredients</h3>
        <p>We use only the freshest ingredients to prepare your meals.</p>
      </div>
      <div>
        <h3 class="text-xl font-semibold mb-2">Affordable Prices</h3>
        <p>Enjoy tasty meals without breaking the bank.</p>
      </div>
    </div>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="py-16 bg-white">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold mb-8">Our Popular Dishes</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-gray-100 p-4 rounded-lg">
          <h4 class="text-xl font-semibold mb-2">Burger Combo</h4>
          <p>$5.99 - A juicy burger with fries and a drink.</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg">
          <h4 class="text-xl font-semibold mb-2">Pizza Slice</h4>
          <p>$3.99 - Large cheesy slice with your choice of toppings.</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg">
          <h4 class="text-xl font-semibold mb-2">Chicken Wrap</h4>
          <p>$4.99 - Spiced chicken wrapped in fresh flatbread.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-12 bg-gray-100">
    <div class="container mx-auto text-center">
      <h2 class="text-2xl font-bold mb-4">Contact Us</h2>
      <p class="mb-2">Email: support@quickbite.com</p>
      <p>Phone: +1-800-FOODNOW</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-red-500 text-white text-center p-4">
    <p>&copy; 2025 QuickBite. All rights reserved.</p>
  </footer>

</body>
</html>
