<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaura Naturals | Luxury Vedic Aromatics</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Montserrat:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #1a1a1a; color: #ffffff; }
        h1, h2, h3, .brand-font { font-family: 'Playfair Display', serif; }
        
        /* Vibrant Gold and Dark Contrast */
        .text-gold { color: #FFD700; } /* Bright Gold */
        .bg-gold { background-color: #FFD700; }
        .bg-dark-card { background-color: #262626; }
        .border-gold { border-color: #FFD700; }
        
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1602848598730-bb724e610313?auto=format&fit=crop&q=80');
            background-size: cover; background-position: center;
        }

        .logo-box-premium {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            border: 2px solid rgba(255, 215, 0, 0.4);
            transition: all 0.3s ease;
        }
        .logo-box-premium:hover { border-color: #FFD700; }
    </style>
</head>
<body>

    <nav class="flex justify-between items-center px-10 py-6 bg-black sticky top-0 z-50 border-b border-gray-800">
        <div class="text-3xl font-bold brand-font tracking-tight text-gold">Gaura Naturals</div>
        <div class="hidden md:flex space-x-10 font-semibold text-[10px] uppercase tracking-[0.3em] text-gray-300">
            <a href="#" class="hover:text-gold transition">Collection</a>
            <a href="#" class="hover:text-gold transition">Our Story</a>
            <a href="#" class="hover:text-gold transition">Sustainability</a>
        </div>
        <div class="px-8 py-2 bg-gold text-black text-[10px] font-black tracking-widest rounded-none cursor-pointer hover:bg-white transition">
            LOGIN
        </div>
    </nav>

    <section class="hero-section h-[85vh] flex flex-col items-center justify-center px-6 text-center">
        <h1 class="text-8xl md:text-[10rem] mb-0 font-bold tracking-tighter text-white">GAURA</h1>
        <p class="italic text-gold text-3xl md:text-5xl mb-12 font-light">Touch of Nature</p>
        
        <div class="logo-box-premium p-12 rounded-none grid grid-cols-1 md:grid-cols-3 gap-16 max-w-6xl w-full">
            <div class="text-center">
                <span class="text-6xl font-bold text-gold block mb-4 italic">G</span>
                <p class="text-[12px] font-bold uppercase tracking-[0.2em] leading-relaxed">Represents style <br>& modernism</p>
            </div>
            <div class="text-center border-x border-gray-700 px-6">
                <span class="text-6xl font-bold text-gold block mb-4 italic">U</span>
                <p class="text-[12px] font-bold uppercase tracking-[0.2em] leading-relaxed">Forms a drop for <br>our itra segment</p>
            </div>
            <div class="text-center">
                <span class="text-6xl font-bold text-gold block mb-4 italic">A</span>
                <p class="text-[12px] font-bold uppercase tracking-[0.2em] leading-relaxed">Negative space forms <br>a flower petal</p>
            </div>
        </div>
    </section>

    <section class="py-32 px-10 bg-black">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-12">
            <div class="bg-dark-card p-12 text-center border-t-4 border-gold">
                <div class="text-5xl mb-6">🍃</div>
                <h3 class="text-2xl font-bold mb-4 text-white uppercase tracking-widest">Eco-Friendly</h3>
                <p class="text-gray-400 text-sm leading-relaxed">Sustainable products from recycled temple flowers.</p>
            </div>
            <div class="bg-dark-card p-12 text-center border-t-4 border-gold">
                <div class="text-5xl mb-6">✨</div>
                <h3 class="text-2xl font-bold mb-4 text-white uppercase tracking-widest">Handcrafted</h3>
                <p class="text-gray-400 text-sm leading-relaxed">Empowering village women artisans with every product.</p>
            </div>
            <div class="bg-dark-card p-12 text-center border-t-4 border-gold">
                <div class="text-5xl mb-6">🧡</div>
                <h3 class="text-2xl font-bold mb-4 text-white uppercase tracking-widest">Pure Vedic</h3>
                <p class="text-gray-400 text-sm leading-relaxed">100% Charcoal-free & Natural ingredients.</p>
            </div>
        </div>
    </section>

    <footer class="bg-black py-20 px-10 border-t border-gray-900">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-start">
            <div class="mb-12 md:mb-0">
                <h2 class="text-5xl font-bold brand-font mb-6 text-gold">Gaura Naturals</h2>
                <p class="text-gray-400 max-w-md italic mb-8">Incorporated October 2025. Pure Vedic Living.</p>
                <div class="space-y-3 text-xs uppercase tracking-widest font-semibold text-gray-300">
                    <p>📍 Ghaziabad, UP - 201005</p>
                    <p>📧 GAURANATURALSPVTLTD@GMAIL.COM</p>
                    <p>📞 +91 8860140036</p>
                </div>
            </div>
            <div class="text-left md:text-right">
                <p class="text-gold font-black uppercase tracking-[0.3em] mb-4 text-xs">Leadership</p>
                <p class="text-xl text-white font-bold mb-1">Yash Aggarwal</p>
                <p class="text-xl text-white font-bold mb-6">Aparna Gupta</p>
                <p class="text-[10px] text-gray-500 uppercase tracking-widest">© 2026 Gaura Naturals Pvt Ltd</p>
            </div>
        </div>
    </footer>

</body>
</html>
