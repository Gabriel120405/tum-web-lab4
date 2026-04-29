---
layout: base.njk
title: Europlasmet - Premium Plastic Solutions
heading: "Europlasmet: Transforming Plastics Into Excellence"
tagline: "High-quality plastic and polymer solutions for modern industries"
ctaText: "Get Started Today"
ctaLink: "#contact"
---

<!-- Hero Section -->
<section id="home" class="relative min-h-screen bg-gradient-to-b from-blue-50 to-white pt-16 pb-12 md:pb-20 flex items-center">
  <div class="max-w-6xl mx-auto px-4 md:px-8 w-full">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-12 items-center">
      <div class="space-y-6 animate-slideIn">
        <h2 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight">
          {{ heading }}
        </h2>
        <p class="text-lg md:text-xl text-gray-600">
          {{ tagline }}
        </p>
        <button class="bg-orange-500 text-white px-8 py-4 rounded-lg font-bold text-lg hover:bg-orange-600 transition shadow-lg hover:shadow-xl">
          {{ ctaText }}
        </button>
      </div>
      
      <div class="hidden md:flex justify-center">
        <svg class="w-full max-w-sm h-auto" viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="plasticGradient" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
              <stop offset="100%" style="stop-color:#1e40af;stop-opacity:1" />
            </linearGradient>
          </defs>
          <circle cx="200" cy="200" r="180" fill="url(#plasticGradient)" />
          <text x="200" y="220" font-size="60" font-weight="bold" text-anchor="middle" fill="white">
            Europlasmet
          </text>
        </svg>
      </div>
    </div>
  </div>
</section>

<!-- Features Section -->
<section id="products" class="py-16 md:py-24 bg-gray-50">
  <div class="max-w-6xl mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-900">Our Products</h2>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition">
        <div class="text-4xl mb-4">🔵</div>
        <h3 class="text-xl font-bold mb-4 text-gray-900">Premium Pellets</h3>
        <p class="text-gray-600">High-grade plastic pellets for industrial applications with exceptional quality standards.</p>
      </div>
      
      <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition">
        <div class="text-4xl mb-4">⚙️</div>
        <h3 class="text-xl font-bold mb-4 text-gray-900">Custom Solutions</h3>
        <p class="text-gray-600">Tailored polymer solutions designed to meet your specific manufacturing requirements.</p>
      </div>
      
      <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl transition">
        <div class="text-4xl mb-4">🌍</div>
        <h3 class="text-xl font-bold mb-4 text-gray-900">Sustainable Materials</h3>
        <p class="text-gray-600">Eco-friendly plastic alternatives that support environmental responsibility.</p>
      </div>
    </div>
  </div>
</section>

<!-- About Section -->
<section id="about" class="py-16 md:py-24 bg-white">
  <div class="max-w-6xl mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900">About Europlasmet</h2>
    
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
      <div class="space-y-6 text-gray-600">
        <p class="text-lg">
          With over 25 years of industry experience, Europlasmet has established itself as a leader in plastic and polymer manufacturing.
        </p>
        <p class="text-lg">
          We combine cutting-edge technology with sustainable practices to deliver products that exceed expectations.
        </p>
        <p class="text-lg">
          Our dedicated team is committed to innovation, quality, and customer satisfaction in every aspect of our business.
        </p>
      </div>
      
      <div class="bg-blue-100 p-8 rounded-lg">
        <h3 class="text-2xl font-bold mb-6 text-gray-900">Key Metrics</h3>
        <div class="space-y-4">
          <div>
            <p class="text-3xl font-bold text-blue-600">25+</p>
            <p class="text-gray-600">Years of Excellence</p>
          </div>
          <div>
            <p class="text-3xl font-bold text-blue-600">500+</p>
            <p class="text-gray-600">Satisfied Clients</p>
          </div>
          <div>
            <p class="text-3xl font-bold text-blue-600">100K+</p>
            <p class="text-gray-600">Tons Produced Annually</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-16 md:py-24 bg-gradient-to-r from-blue-600 to-blue-800 text-white">
  <div class="max-w-6xl mx-auto px-4 md:px-8">
    <h2 class="text-3xl md:text-4xl font-bold mb-12 text-center">Get In Touch</h2>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-blue-700 p-8 rounded-lg text-center">
        <h3 class="text-xl font-bold mb-4">Email</h3>
        <p><a href="mailto:info@europlasmet.com" class="hover:opacity-80 transition">info@europlasmet.com</a></p>
      </div>
      
      <div class="bg-blue-700 p-8 rounded-lg text-center">
        <h3 class="text-xl font-bold mb-4">Phone</h3>
        <p><a href="tel:+15551234567" class="hover:opacity-80 transition">+1 (555) 123-4567</a></p>
      </div>
      
      <div class="bg-blue-700 p-8 rounded-lg text-center">
        <h3 class="text-xl font-bold mb-4">Address</h3>
        <p>123 Industrial Ave, Tech City, TC 12345</p>
      </div>
    </div>
  </div>
</section>
