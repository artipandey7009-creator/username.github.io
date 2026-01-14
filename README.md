<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaura Naturals | Luxury Vedic Aromatics</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Montserrat:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #fffaf0; color: #3e2723; }
        h1, h2, h3, .brand-font { font-family: 'Playfair Display', serif; }
        
        .hero-overlay {
            background: linear-gradient(to bottom, rgba(62, 39, 35, 0.7), rgba(0, 0, 0, 0.4)), 
                        url('https://images.unsplash.com/photo-1602848598730-bb724e610313?auto=format&fit=crop&q=80');
            background-size: cover; background-position: center;
        }
        
        /* Vibrant Gold and Rich Brown */
        .color-gold { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .bg-rich-brown { background-color: #3e2723; }
        .border-gold { border-color: #D4AF37; }
        
        .logo-box {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(212, 175, 55, 0.3);
        }
    </style>
</head>
<body>

    <nav class="flex justify-between items-center px-8 py-6 bg-white shadow-md sticky top-0 z-50">
        <div class="text-3xl font-bold brand-font tracking-tight text-[#3e2723]">Gaura Naturals</div>
        <div class="hidden md:flex space-x-10 font-semibold text-xs uppercase tracking-[0.2em] text-gray-700">
            <a href="#" class="hover:text-gold transition">Collection</a>
            <a href="#" class="hover:text-gold transition">Our Story</a>
            <a href="#" class="hover:text-gold transition">Sustainability</a>
        </div>
        <div class="px-6 py-2 bg-rich-brown text-white text-xs font-bold tracking-widest rounded-full cursor-pointer hover:bg-black transition">
            LOGIN
        </div>
    </nav>

    <section class="hero-overlay h-[80vh] flex flex-col items-center justify-center text-white text-center px-6">
        <h1 class="text-8xl md:text-9xl mb-2 font-bold tracking-tighter drop-shadow-2xl">GAURA</h1>
        <p class="italic color-gold text-3xl md:text-4xl mb-10 font-light drop-shadow-md">Touch of Nature</p>
        <p class="max-w-3xl text-lg font-light leading-relaxed mb-12 text-gray-100">
            Handcrafted eco-luxury aromatics from recycled temple flowers and cow dung. 
            Reviving Vedic traditions with a touch of modernism.
        </p>
        
        <div class="logo-box p-10 rounded-lg grid grid-cols-1 md:grid-cols-3 gap-12 max-w-5xl w-full shadow-2xl">
            <div class="text-center">
                <span class="text-5xl font-bold color-gold block mb-3">G</span>
                <p class="text-[11px] font-semibold uppercase tracking-widest leading-normal text-white">Represents style <br>and modernism</p>
            </div>
            <div class="text-center border-x border-white/20 px-6">
                <span class="text-5xl font-bold color-gold block mb-3">U</span>
                <p class="text-[11px] font-semibold uppercase tracking-widest leading-normal text-white">Forms a drop representing <br>our itra segment</p>
            </div>
            <div class="text-center">
                <span class="text-5xl font-bold color-gold block mb-3">A</span>
                <p class="text-[11px] font-semibold uppercase tracking-widest leading-normal text-white">Negative space forms <br>a flower petal</p>
            </div>
        </div>
    </section>

    <section class="py-24 px-10 bg-[#fffaf0]">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-16">
            <div class="text-center">
                <div class="w-20 h-20 bg-white shadow-xl rounded-full flex items-center justify-center mx-auto mb-8 border border-gold">
                    <span class="text-3xl">🍃</span>
                </div>
                <h3 class="text-2xl font-bold mb-4 brand-font">Eco-Friendly</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Sustainable products made from recycled floral waste.</p>
            </div>
            <div class="text-center">
                <div class="w-20 h-20 bg-white shadow-xl rounded-full flex items-center justify-center mx-auto mb-8 border border-gold">
                    <span class="text-3xl">✨</span>
                </div>
                <h3 class="text-2xl font-bold mb-4 brand-font">Handcrafted</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Artisanal products made by village women with love.</p>
            </div>
            <div class="text-center">
                <div class="w-20 h-20 bg-white shadow-xl rounded-full flex items-center justify-center mx-auto mb-8 border border-gold">
                    <span class="text-3xl">🧡</span>
                </div>
                <h3 class="text-2xl font-bold mb-4 brand-font">Pure Essence</h3>
                <p class="text-gray-600 text-sm leading-relaxed">100% Charcoal-free and pure vedic ingredients.</p>
            </div>
        </div>
    </section>

    <section class="bg-rich-brown py-20 px-8 text-center text-white border-y-4 border-gold">
        <h2 class="text-4xl mb-8 brand-font tracking-widest uppercase">Our Mission</h2>
        <p class="max-w-4xl mx-auto text-xl font-light leading-loose text-gray-200">
            To transform natural waste into premium aromatics while empowering village women artisans. 
            We are dedicated to chemical-free living and environmental sustainability.
        </p>
    </section>

    <footer class="bg-white py-16 px-10 border-t border-stone-200">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12">
            <div>
                <h2 class="text-4xl font-bold brand-font mb-6 text-rich-brown">Gaura Naturals Pvt Ltd</h2>
                <p class="text-gray-600 leading-relaxed max-w-md italic">
                    Incorporated in October 2025. Delivering pure vedic aroma to your home.
                </p>
                <div class="mt-8 space-y-2 text-sm font-semibold">
                    <p>📍 Ghaziabad – 201005</p>
                    <p>📧 GAURANATURALSPVTLTD@GMAIL.COM</p>
                    <p>📞 +91 8860140036</p>
                </div>
            </div>
            <div class="flex flex-col md:items-end justify-center">
                <p class="text-sm font-bold uppercase tracking-widest text-gold mb-2">Leadership</p>
                <p class="text-lg text-rich-brown font-semibold">Yash Aggarwal (Director)</p>
                <p class="text-lg text-rich-brown font-semibold">Aparna Gupta (Co-Director)</p>
            </div>
        </div>
        <div class="mt-20 text-center text-[11px] text-gray-400 uppercase tracking-[0.4em]">
            © 2026 Gaura Naturals | Premium Handcrafted Vedic Collection
        </div>
    </footer>

</body>
</html>
