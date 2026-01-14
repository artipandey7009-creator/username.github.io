<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaura Naturals | Touch of Nature</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #fdfaf5; color: #4a3728; }
        h1, h2, h3, .brand-font { font-family: 'Playfair+Display', serif; }
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1602848598730-bb724e610313?auto=format&fit=crop&q=80');
            background-size: cover; background-position: center;
        }
        .bg-gold { background-color: #d4a34f; }
        .text-gold { color: #d4a34f; }
    </style>
</head>
<body>

    <nav class="flex justify-between items-center px-10 py-5 bg-[#fdfaf5] sticky top-0 z-50 shadow-sm">
        <div class="text-3xl font-bold brand-font text-[#634832]">Gaura Naturals</div>
        <div class="hidden md:flex space-x-8 font-medium text-sm uppercase tracking-widest">
            <a href="#products" class="hover:text-gold transition">Products</a>
            <a href="#sustainability" class="hover:text-gold transition">Sustainability</a>
            <a href="#about" class="hover:text-gold transition">About</a>
        </div>
        <div class="flex items-center space-x-5">
            <span class="cursor-pointer text-xl">🛒</span>
            <a href="#" class="text-sm font-semibold border-b border-black">Login</a>
        </div>
    </nav>

    <section class="hero-bg h-[600px] flex flex-col items-center justify-center text-white text-center px-6">
        <h1 class="text-7xl mb-2">GAURA</h1>
        <p class="italic text-gold text-2xl mb-6">Touch of Nature</p>
        <p class="max-w-2xl text-lg font-light leading-relaxed">
            A symbol of peace, purity, and connection to nature. Handcrafted eco-friendly aromatics from recycled temple flowers and cow dung.
        </p>
        
        <div class="mt-12 bg-white/10 backdrop-blur-md p-8 rounded-sm border border-white/20 grid grid-cols-1 md:grid-cols-3 gap-10 max-w-4xl">
            <div>
                <span class="text-3xl font-bold text-gold block mb-2">G</span>
                <p class="text-xs uppercase tracking-tighter">Represents style and <b>modernism</b></p>
            </div>
            <div>
                <span class="text-3xl font-bold text-gold block mb-2">U</span>
                <p class="text-xs uppercase tracking-tighter">Forms a <b>drop</b> representing our itra segment</p>
            </div>
            <div>
                <span class="text-3xl font-bold text-gold block mb-2">A</span>
                <p class="text-xs uppercase tracking-tighter">Negative space forms a <b>flower petal</b></p>
            </div>
        </div>
    </section>

    <section class="py-20 px-10 grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white p-10 text-center rounded-xl shadow-sm border border-orange-100">
            <div class="text-4xl mb-4">🍃</div>
            <h3 class="text-2xl font-bold mb-4">Eco-Friendly</h3>
            <p class="text-sm leading-relaxed text-gray-500">Made from recycled temple flowers and cow dung, supporting environmental sustainability.</p>
        </div>
        <div class="bg-white p-10 text-center rounded-xl shadow-sm border border-orange-100">
            <div class="text-4xl mb-4">✨</div>
            <h3 class="text-2xl font-bold mb-4">Handcrafted</h3>
            <p class="text-sm leading-relaxed text-gray-500">Lovingly crafted by village women artisans, preserving traditional methods.</p>
        </div>
        <div class="bg-white p-10 text-center rounded-xl shadow-sm border border-orange-100">
            <div class="text-4xl mb-4">🧡</div>
            <h3 class="text-2xl font-bold mb-4">Pure & Natural</h3>
            <p class="text-sm leading-relaxed text-gray-500">Free from harmful chemicals, bringing the purest essence of nature to your space.</p>
        </div>
    </section>

    <section id="products" class="py-10 px-10">
        <h2 class="text-4xl text-center mb-16">Our Collection</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-6xl mx-auto">
            <div class="bg-white group overflow-hidden shadow-md">
                <div class="h-80 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1612548403247-aa2873e9422d?auto=format&fit=crop&q=80" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                </div>
                <div class="p-6">
                    <div class="flex space-x-2 mb-2 text-[10px] uppercase font-bold text-gray-400">
                        <span>Handmade</span><span>•</span><span>Charcoal-free</span>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Sambrani Havan Cups</h4>
                    <p class="text-lg font-bold text-gray-800">$12.99</p>
                </div>
            </div>
            <div class="bg-white group overflow-hidden shadow-md">
                <div class="h-80 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1602848598730-bb724e610313?auto=format&fit=crop&q=80" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                </div>
                <div class="p-6">
                    <div class="flex space-x-2 mb-2 text-[10px] uppercase font-bold text-gray-400">
                        <span>Pure Itra</span><span>•</span><span>Traditional</span>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Jasmine Temple Agarbatti</h4>
                    <p class="text-lg font-bold text-gray-800">$15.99</p>
                </div>
            </div>
            <div class="bg-white group overflow-hidden shadow-md">
                <div class="h-80 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1595914108199-041764359489?auto=format&fit=crop&q=80" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                </div>
                <div class="p-6">
                    <div class="flex space-x-2 mb-2 text-[10px] uppercase font-bold text-gray-400">
                        <span>Bamboo-less</span><span>•</span><span>Eco-friendly</span>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Premium Dhoop Cones</h4>
                    <p class="text-lg font-bold text-gray-800">$11.99</p>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-gold my-20 py-16 px-6 text-center text-white">
        <h2 class="text-4xl mb-6 uppercase tracking-widest">Our Mission</h2>
        <p class="max-w-4xl mx-auto text-xl font-light leading-relaxed">
            To revive Vedic practices using recycled temple flowers and cow dung to create sustainable eco-luxury products. We transform natural waste into premium aromatics while empowering village women artisans.
        </p>
    </section>

    <footer class="py-10 px-10 border-t border-orange-100 text-center">
        <div class="text-2xl font-bold brand-font mb-4 text-[#634832]">Gaura Naturals</div>
        <p class="text-sm text-gray-400">© 2026 Gaura Naturals Pvt Ltd. All rights reserved.</p>
    </footer>

</body>
</html>
