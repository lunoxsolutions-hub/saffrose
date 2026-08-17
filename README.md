<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHAFFROSE | Luxury Perfumes, Pure Attar, Agarbatti & Body Care</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            850: '#0c271c',
                            900: '#0a1e16',
                            950: '#05120d',
                        },
                        gold: {
                            300: '#f3e5ab',
                            400: '#e5c158',
                            500: '#d4af37',
                            600: '#b89228',
                        },
                        rosebrand: {
                            500: '#e63956',
                            600: '#cc223f',
                        }
                    },
                    fontFamily: {
                        serif: ['Cinzel', 'Playfair Display', 'Georgia', 'serif'],
                        sans: ['Plus Jakarta Sans', 'Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700;800;900&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0a1e16;
            color: #f3f4f6;
        }
        .font-cinzel { font-family: 'Cinzel', serif; }
        .font-playfair { font-family: 'Playfair Display', serif; }
        
        .gold-gradient-text {
            background: linear-gradient(135deg, #fff3c4 0%, #d4af37 50%, #aa820a 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .gold-border-glow {
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.2);
            border: 1px solid rgba(212, 175, 55, 0.3);
        }

        .bg-luxury-pattern {
            background-color: #0a1e16;
            background-image: radial-gradient(#1a3c2e 0.75px, transparent 0.75px), radial-gradient(#1a3c2e 0.75px, #0a1e16 0.75px);
            background-size: 30px 30px;
            background-position: 0 0, 15px 15px;
        }

        /* Custom scrollbars */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #05120d;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e4d3a;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #d4af37;
        }

        .product-card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .product-card-hover:hover {
            transform: translateY(-6px);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.5), 0 0 20px rgba(212, 175, 55, 0.2);
        }
    </style>
</head>
<body class="bg-emerald-950 text-gray-100 antialiased min-h-screen flex flex-col selection:bg-gold-500 selection:text-black">

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-emerald-900 via-rosebrand-600 to-emerald-900 text-white text-xs md:text-sm py-2 px-4 text-center font-medium tracking-wide flex justify-between items-center z-50 border-b border-gold-500/30">
        <div class="hidden sm:flex items-center gap-2">
            <i class="fa-solid fa-location-dot text-gold-400"></i>
            <span>Kakkad, Malappuram, Kerala</span>
        </div>
        <div class="mx-auto sm:mx-0 flex items-center gap-2">
            <span class="animate-pulse text-gold-300">✨ Premium Oudh & Agarbatti Collection</span>
            <span class="hidden md:inline">| Free Shipping on Bulk Orders</span>
        </div>
        <div class="hidden md:flex items-center gap-4">
            <a href="https://wa.me/918921570125" target="_blank" class="hover:text-gold-300 transition flex items-center gap-1">
                <i class="fa-brands fa-whatsapp text-emerald-400"></i> +91 8921570125
            </a>
            <a href="https://instagram.com/shaffrose.perfume" target="_blank" class="hover:text-gold-300 transition">
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
    </div>

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-40 bg-emerald-950/95 backdrop-blur-md border-b border-gold-500/20 shadow-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                
                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" onclick="toggleMobileMenu()" class="md:hidden text-gray-300 hover:text-gold-400 focus:outline-none p-2">
                    <i class="fa-solid fa-bars text-2xl"></i>
                </button>

                <!-- Brand Logo & Name -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="relative w-12 h-12 rounded-full border-2 border-gold-500/80 bg-black flex items-center justify-center p-1 overflow-hidden shadow-lg group-hover:border-gold-400 transition">
                        <svg viewBox="0 0 100 100" class="w-full h-full">
                            <circle cx="50" cy="50" r="46" fill="#000000" stroke="#e63956" stroke-width="4"/>
                            <path d="M 50,22 Q 62,15 68,26 Q 78,20 76,32 Q 68,36 58,32 Z" fill="#e63956"/>
                            <path d="M 54,34 Q 45,46 38,62 Q 36,66 32,68" fill="none" stroke="#22c55e" stroke-width="4" stroke-linecap="round"/>
                            <path d="M 58,34 Q 52,48 44,66 Q 40,71 34,72" fill="none" stroke="#22c55e" stroke-width="3" stroke-linecap="round"/>
                            <text x="50" y="62" font-family="'Brush Script MT', cursive, sans-serif" font-size="28" font-weight="bold" fill="#e63956" text-anchor="middle">Shaffrose</text>
                            <circle cx="80" cy="30" r="6" fill="none" stroke="#ffffff" stroke-width="1"/>
                            <text x="80" y="32.5" font-family="sans-serif" font-size="7" fill="#ffffff" text-anchor="middle" font-weight="bold">R</text>
                        </svg>
                    </div>
                    <div class="flex flex-col">
                        <span class="font-cinzel text-xl sm:text-2xl font-black tracking-widest gold-gradient-text">SHAFFROSE</span>
                        <span class="text-[10px] uppercase tracking-[0.25em] text-emerald-400 font-semibold">Luxury Fragrances & Care</span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                    <a href="#hero" class="text-gold-400 hover:text-gold-300 transition tracking-wide">Home</a>
                    <a href="#about" class="text-gray-300 hover:text-gold-400 transition tracking-wide">Our Story</a>
                    <a href="#products" class="text-gray-300 hover:text-gold-400 transition tracking-wide">Products</a>
                    <a href="#oudh-highlight" class="text-gray-300 hover:text-gold-400 transition tracking-wide">Oudh Special</a>
                    <a href="#quiz-trigger" onclick="openQuiz()" class="text-rosebrand-500 hover:text-rosebrand-400 font-semibold transition flex items-center gap-1.5 bg-rosebrand-500/10 px-3 py-1 rounded-full border border-rosebrand-500/30">
                        <i class="fa-solid fa-wand-magic-sparkles"></i> Scent Finder
                    </a>
                    <a href="#contact" class="text-gray-300 hover:text-gold-400 transition tracking-wide">Contact</a>
                </nav>

                <!-- Actions: Search & Cart -->
                <div class="flex items-center space-x-4">
                    <button onclick="toggleSearchModal()" class="text-gray-300 hover:text-gold-400 p-2 transition" title="Search Products">
                        <i class="fa-solid fa-magnifying-glass text-lg"></i>
                    </button>
                    
                    <button id="cart-btn" onclick="toggleCartDrawer()" class="relative p-2.5 bg-emerald-900/80 border border-gold-500/40 rounded-full hover:bg-gold-500 hover:text-emerald-950 transition group">
                        <i class="fa-solid fa-bag-shopping text-gold-400 group-hover:text-emerald-950 text-lg"></i>
                        <span id="cart-count" class="absolute -top-1 -right-1 bg-rosebrand-500 text-white text-xs font-bold w-5 h-5 rounded-full flex items-center justify-center border-2 border-emerald-950">0</span>
                    </button>

                    <a href="https://wa.me/918921570125?text=Hello%20SHAFFROSE,%20I%20would%20like%20to%20inquire%20about%20your%20products." target="_blank" class="hidden sm:flex items-center gap-2 bg-gradient-to-r from-emerald-600 to-emerald-700 hover:from-emerald-500 hover:to-emerald-600 text-white font-semibold text-xs py-2.5 px-4 rounded-lg shadow-md border border-emerald-400/30 transition">
                        <i class="fa-brands fa-whatsapp text-base text-green-300"></i>
                        <span>WhatsApp Order</span>
                    </a>
                </div>
            </div>
        </div>

        <!-- Mobile Drawer Navigation -->
        <div id="mobile-menu" class="hidden md:hidden bg-emerald-900 border-b border-gold-500/30 px-4 pt-2 pb-6 space-y-3">
            <a href="#hero" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-base font-medium text-gold-400 hover:bg-emerald-800">Home</a>
            <a href="#about" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-base font-medium text-gray-200 hover:bg-emerald-800">Our Story</a>
            <a href="#products" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-base font-medium text-gray-200 hover:bg-emerald-800">Products Collection</a>
            <a href="#oudh-highlight" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-base font-medium text-gray-200 hover:bg-emerald-800">Oudh Collection</a>
            <button onclick="toggleMobileMenu(); openQuiz();" class="w-full text-left px-3 py-2 rounded-md text-base font-medium text-rosebrand-400 bg-rosebrand-500/10 border border-rosebrand-500/30">
                ✨ Scent Quiz / Finder
            </button>
            <a href="#contact" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-base font-medium text-gray-200 hover:bg-emerald-800">Contact Us</a>
            <div class="pt-2 border-t border-emerald-800 flex items-center justify-between text-sm">
                <span class="text-gray-400"><i class="fa-solid fa-phone text-gold-400 mr-2"></i>+91 8921570125</span>
                <a href="https://instagram.com/shaffrose.perfume" target="_blank" class="text-rosebrand-400 hover:underline"><i class="fa-brands fa-instagram mr-1"></i> Instagram</a>
            </div>
        </div>
    </header>

    <!-- Search Overlay Modal -->
    <div id="search-modal" class="fixed inset-0 bg-black/80 backdrop-blur-md z-50 hidden flex items-start justify-center pt-20 px-4">
        <div class="bg-emerald-900 border border-gold-500/40 rounded-2xl w-full max-w-2xl p-6 shadow-2xl relative">
            <button onclick="toggleSearchModal()" class="absolute top-4 right-4 text-gray-400 hover:text-white text-xl">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <h3 class="font-cinzel text-xl font-bold gold-gradient-text mb-4">Search SHAFFROSE Fragrances</h3>
            <div class="relative">
                <input type="text" id="search-input" onkeyup="filterProductsBySearch()" placeholder="Search perfumes, attar, agarbatti, soap, handwash..." class="w-full bg-emerald-950 border border-gold-500/30 rounded-xl py-3.5 pl-12 pr-4 text-white placeholder-gray-400 focus:outline-none focus:border-gold-400 text-lg">
                <i class="fa-solid fa-magnifying-glass absolute left-4 top-4 text-gold-400 text-lg"></i>
            </div>
            <div id="search-results-list" class="mt-4 max-h-80 overflow-y-auto space-y-2 divide-y divide-emerald-800/60">
                <p class="text-gray-400 text-sm py-4 text-center">Type above to discover scents...</p>
            </div>
        </div>
    </div>

    <main class="flex-grow">
        <!-- Hero Section -->
        <section id="hero" class="relative overflow-hidden bg-luxury-pattern py-12 lg:py-24 border-b border-gold-500/20">
            <div class="absolute inset-0 bg-gradient-to-r from-emerald-950 via-emerald-950/80 to-transparent z-10"></div>
            
            <div class="absolute -top-24 -left-24 w-96 h-96 bg-gold-500/10 rounded-full blur-3xl pointer-events-none"></div>
            <div class="absolute -bottom-24 -right-24 w-96 h-96 bg-rosebrand-500/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-20">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    
                    <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                        <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-gold-500/10 border border-gold-500/30 text-gold-300 text-xs sm:text-sm font-semibold tracking-wider uppercase">
                            <i class="fa-solid fa-crown text-gold-400"></i> Artisanal Luxury Fragrances & Personal Care
                        </div>
                        
                        <h1 class="font-cinzel text-3xl sm:text-5xl lg:text-6xl font-black text-white leading-tight">
                            Indulge in <span class="gold-gradient-text">Signature Luxury</span> Fragrances
                        </h1>
                        
                        <p class="text-gray-300 text-base sm:text-lg max-w-2xl font-light leading-relaxed mx-auto lg:mx-0">
                            Crafted in Kakkad, Malappuram. SHAFFROSE brings you an exquisite selection of long-lasting Oudh perfumes, pure traditional attars, rich hand-crafted agarbattis, and soothing body care essentials.
                        </p>

                        <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                            <a href="#products" class="w-full sm:w-auto px-8 py-4 bg-gradient-to-r from-gold-500 to-gold-600 hover:from-gold-400 hover:to-gold-500 text-emerald-950 font-bold rounded-xl shadow-lg shadow-gold-500/20 transition transform hover:-translate-y-0.5 text-center flex items-center justify-center gap-2">
                                <span>Explore Collection</span>
                                <i class="fa-solid fa-arrow-right"></i>
                            </a>
                            <a href="#quiz-trigger" onclick="openQuiz()" class="w-full sm:w-auto px-6 py-4 bg-emerald-900/80 hover:bg-emerald-800 text-gold-300 border border-gold-500/40 font-semibold rounded-xl transition text-center flex items-center justify-center gap-2">
                                <i class="fa-solid fa-wand-magic-sparkles text-rosebrand-400"></i>
                                <span>Find Your Scent</span>
                            </a>
                        </div>

                        <div class="pt-6 grid grid-cols-3 gap-4 border-t border-emerald-800/80 text-left">
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-emerald-900 border border-gold-500/30 flex items-center justify-center text-gold-400 shrink-0">
                                    <i class="fa-solid fa-leaf text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-xs font-bold text-white uppercase tracking-wider">0% Charcoal</h4>
                                    <p class="text-[11px] text-gray-400">Pure Eco Incense</p>
                                </div>
                            </div>
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-emerald-900 border border-gold-500/30 flex items-center justify-center text-gold-400 shrink-0">
                                    <i class="fa-solid fa-clock text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-xs font-bold text-white uppercase tracking-wider">Long Lasting</h4>
                                    <p class="text-[11px] text-gray-400">Signature Notes</p>
                                </div>
                            </div>
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-lg bg-emerald-900 border border-gold-500/30 flex items-center justify-center text-gold-400 shrink-0">
                                    <i class="fa-solid fa-shield-heart text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-xs font-bold text-white uppercase tracking-wider">100% Original</h4>
                                    <p class="text-[11px] text-gray-400">Guaranteed Quality</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Right Hero Display -->
                    <div class="lg:col-span-5 relative">
                        <div class="relative mx-auto max-w-sm sm:max-w-md bg-gradient-to-b from-emerald-900/90 to-emerald-950 p-6 rounded-3xl border border-gold-500/30 shadow-2xl">
                            <div class="absolute -top-3 right-6 bg-rosebrand-500 text-white text-xs font-extrabold uppercase px-3 py-1 rounded-full shadow">
                                Best Seller
                            </div>
                            
                            <div class="relative h-72 rounded-2xl bg-gradient-to-b from-emerald-950 to-black overflow-hidden flex items-center justify-center p-4 border border-gold-500/20 group">
                                <div class="absolute inset-0 opacity-30 bg-[radial-gradient(#d4af37_1px,transparent_1px)] [background-size:16px_16px]"></div>
                                <div class="relative w-44 h-56 flex flex-col items-center justify-center transform group-hover:scale-105 transition duration-500">
                                    <div class="w-16 h-8 bg-gradient-to-r from-gold-600 via-gold-300 to-gold-600 rounded-t-sm shadow-md border border-gold-400"></div>
                                    <div class="w-8 h-3 bg-gold-500 border-x border-gold-300"></div>
                                    <div class="w-40 h-44 bg-gradient-to-b from-amber-500/80 via-amber-700/90 to-amber-900/90 rounded-2xl border-2 border-gold-400/80 p-2 shadow-2xl flex flex-col items-center justify-center relative overflow-hidden backdrop-blur-sm">
                                        <div class="absolute inset-0 bg-gradient-to-tr from-black/80 via-transparent to-amber-400/20"></div>
                                        <div class="w-32 h-28 bg-black/90 border border-gold-500/60 rounded-lg p-2 flex flex-col items-center justify-center text-center z-10">
                                            <span class="text-[9px] text-rosebrand-500 font-bold uppercase tracking-wider">Shaffrose</span>
                                            <h4 class="font-cinzel text-xs font-extrabold text-gold-400 tracking-wider">SHAFF OUDH</h4>
                                            <span class="text-[8px] text-gray-300 uppercase tracking-widest mt-1">PERFUME</span>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="mt-5 text-center">
                                <h3 class="font-cinzel text-xl font-bold text-white">SHAFF OUDH PERFUME</h3>
                                <p class="text-xs text-gray-300 mt-1">Signature Oudh fragrance blending luxury, sophistication & freshness.</p>
                                <div class="mt-4 flex items-center justify-between">
                                    <div>
                                        <span class="text-xs text-gray-400 line-through">₹1,499</span>
                                        <span class="text-xl font-bold text-gold-400 ml-2">₹1,199</span>
                                    </div>
                                    <button onclick="addToCart(1)" class="px-4 py-2 bg-rosebrand-600 hover:bg-rosebrand-500 text-white font-bold text-xs rounded-lg transition shadow-md flex items-center gap-1.5">
                                        <i class="fa-solid fa-cart-plus"></i> Add to Cart
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Brand Story Section -->
        <section id="about" class="py-16 bg-emerald-900/40 border-b border-gold-500/10">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    
                    <div class="relative">
                        <div class="aspect-video sm:aspect-square max-w-md mx-auto rounded-3xl bg-gradient-to-tr from-emerald-950 via-emerald-900 to-black p-8 border border-gold-500/30 flex flex-col justify-center items-center text-center shadow-2xl relative overflow-hidden">
                            <div class="absolute inset-0 bg-luxury-pattern opacity-40"></div>
                            <div class="relative z-10 space-y-4">
                                <div class="w-20 h-20 mx-auto rounded-full bg-black border-2 border-gold-500 p-2 shadow-xl flex items-center justify-center">
                                    <svg viewBox="0 0 100 100" class="w-full h-full">
                                        <circle cx="50" cy="50" r="46" fill="#000000" stroke="#e63956" stroke-width="4"/>
                                        <path d="M 50,22 Q 62,15 68,26 Q 78,20 76,32 Q 68,36 58,32 Z" fill="#e63956"/>
                                        <path d="M 54,34 Q 45,46 38,62 Q 36,66 32,68" fill="none" stroke="#22c55e" stroke-width="4"/>
                                        <text x="50" y="62" font-family="cursive" font-size="28" font-weight="bold" fill="#e63956" text-anchor="middle">Shaffrose</text>
                                    </svg>
                                </div>
                                <h3 class="font-cinzel text-2xl font-bold gold-gradient-text">SHAFFROSE</h3>
                                <p class="text-xs text-emerald-300 font-semibold tracking-widest uppercase">Pure Fragrance & Body Care Essentials</p>
                                <p class="text-xs text-gray-300 italic max-w-xs mx-auto">
                                    "Fragrance gifts that say more than words can convey."
                                </p>
                                <div class="pt-2 text-xs text-gold-400 font-medium">
                                    <i class="fa-solid fa-location-dot mr-1"></i> Kakkad, Malappuram, Kerala
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="space-y-6">
                        <div class="inline-block px-3 py-1 bg-gold-500/10 border border-gold-500/30 rounded-full text-gold-400 text-xs font-semibold uppercase tracking-wider">
                            About Our Brand
                        </div>
                        <h2 class="font-cinzel text-3xl sm:text-4xl font-bold text-white leading-tight">
                            Crafted with Passion & <span class="gold-gradient-text">Traditional Elegance</span>
                        </h2>
                        <p class="text-gray-300 text-sm sm:text-base leading-relaxed">
                            At <strong>SHAFFROSE</strong>, we specialize in luxury personal care and traditional fragrance products that elevate everyday rituals. From deep Arabian Oudh attars and lingering perfumes to 100% charcoal-free aromatic agarbattis, our products are crafted with meticulous attention to purity and aroma intensity.
                        </p>
                        <p class="text-gray-300 text-sm sm:text-base leading-relaxed">
                            Based in <strong>Kakkad, Malappuram (Kerala)</strong>, we serve fragrance enthusiasts across India who seek authentic, long-lasting fragrances and premium body care products.
                        </p>

                        <div class="grid grid-cols-2 gap-4 pt-4">
                            <div class="p-4 bg-emerald-950/80 border border-gold-500/20 rounded-xl">
                                <i class="fa-solid fa-pump-soap text-rosebrand-400 text-xl mb-2"></i>
                                <h4 class="font-bold text-sm text-white">Body & Hand Care</h4>
                                <p class="text-xs text-gray-400">Nutrient-rich soaps and scented hand washes.</p>
                            </div>
                            <div class="p-4 bg-emerald-950/80 border border-gold-500/20 rounded-xl">
                                <i class="fa-solid fa-fire-flame-curved text-gold-400 text-xl mb-2"></i>
                                <h4 class="font-bold text-sm text-white">Athar Agarbatti</h4>
                                <p class="text-xs text-gray-400">0% Charcoal charcoal-free fragrance sticks.</p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Product Catalog Section -->
        <section id="products" class="py-16 bg-luxury-pattern">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="text-center max-w-3xl mx-auto mb-12 space-y-3">
                    <span class="text-gold-400 text-xs font-extrabold uppercase tracking-widest bg-gold-500/10 px-3 py-1 rounded-full border border-gold-500/20">Our Products</span>
                    <h2 class="font-cinzel text-3xl sm:text-4xl font-bold text-white">Discover the <span class="gold-gradient-text">SHAFFROSE Collection</span></h2>
                    <p class="text-gray-300 text-sm">Explore our curated range of perfumes, traditional attars, eco-friendly agarbattis, and luxury soaps.</p>
                </div>

                <!-- Category Filters -->
                <div class="flex items-center justify-center flex-wrap gap-2 mb-10">
                    <button onclick="filterCategory('all')" class="cat-btn active px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border transition border-gold-500 bg-gold-500 text-emerald-950 shadow-md" data-cat="all">
                        All Products
                    </button>
                    <button onclick="filterCategory('oudh')" class="cat-btn px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border border-gold-500/30 bg-emerald-900/60 text-gray-300 hover:border-gold-400 transition" data-cat="oudh">
                        Oudh Collection
                    </button>
                    <button onclick="filterCategory('perfume')" class="cat-btn px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border border-gold-500/30 bg-emerald-900/60 text-gray-300 hover:border-gold-400 transition" data-cat="perfume">
                        Perfumes & Pocket Sprays
                    </button>
                    <button onclick="filterCategory('attar')" class="cat-btn px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border border-gold-500/30 bg-emerald-900/60 text-gray-300 hover:border-gold-400 transition" data-cat="attar">
                        Pure Attar
                    </button>
                    <button onclick="filterCategory('agarbatti')" class="cat-btn px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border border-gold-500/30 bg-emerald-900/60 text-gray-300 hover:border-gold-400 transition" data-cat="agarbatti">
                        Athar Agarbatti
                    </button>
                    <button onclick="filterCategory('bodycare')" class="cat-btn px-4 py-2 text-xs sm:text-sm font-semibold rounded-full border border-gold-500/30 bg-emerald-900/60 text-gray-300 hover:border-gold-400 transition" data-cat="bodycare">
                        Soaps & Hand Wash
                    </button>
                </div>

                <!-- Dynamic Products Grid -->
                <div id="products-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                </div>

            </div>
        </section>

        <!-- Featured Oudh Collection Spotlight -->
        <section id="oudh-highlight" class="py-16 bg-gradient-to-b from-emerald-950 via-emerald-900 to-emerald-950 border-y border-gold-500/20 relative">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-black/60 border border-gold-500/40 rounded-3xl p-8 lg:p-12 shadow-2xl relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-96 h-96 bg-gold-500/10 rounded-full blur-3xl pointer-events-none"></div>
                    
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                        <div class="lg:col-span-7 space-y-4">
                            <span class="text-rosebrand-400 text-xs font-bold uppercase tracking-widest">Royal Fragrance</span>
                            <h2 class="font-cinzel text-3xl sm:text-4xl font-extrabold text-white">
                                SHAFF OUDH <span class="gold-gradient-text">COLLECTION</span>
                            </h2>
                            <p class="text-gray-300 text-sm leading-relaxed">
                                Discover Shaffrose fragrance gifts that say more than words can convey. Imbued with exotic warm spices, dark woods, and precious amber resins crafted for lasting freshness.
                            </p>

                            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-4">
                                <div class="bg-emerald-950/80 p-3 rounded-xl border border-gold-500/20 text-center">
                                    <i class="fa-solid fa-bottle-droplet text-gold-400 text-lg mb-1"></i>
                                    <p class="text-[11px] font-bold text-white">Perfumes</p>
                                </div>
                                <div class="bg-emerald-950/80 p-3 rounded-xl border border-gold-500/20 text-center">
                                    <i class="fa-solid fa-gem text-gold-400 text-lg mb-1"></i>
                                    <p class="text-[11px] font-bold text-white">Pure Attar</p>
                                </div>
                                <div class="bg-emerald-950/80 p-3 rounded-xl border border-gold-500/20 text-center">
                                    <i class="fa-solid fa-soap text-gold-400 text-lg mb-1"></i>
                                    <p class="text-[11px] font-bold text-white">Luxury Soap</p>
                                </div>
                                <div class="bg-emerald-950/80 p-3 rounded-xl border border-gold-500/20 text-center">
                                    <i class="fa-solid fa-hand-holding-droplet text-gold-400 text-lg mb-1"></i>
                                    <p class="text-[11px] font-bold text-white">Hand Wash</p>
                                </div>
                            </div>

                            <div class="pt-4 flex flex-wrap gap-4">
                                <a href="https://wa.me/918921570125?text=Hi%20SHAFFROSE,%20I%20want%20to%20order%20the%20Oudh%20Collection." target="_blank" class="px-6 py-3 bg-rosebrand-600 hover:bg-rosebrand-500 text-white font-bold text-xs rounded-xl shadow-lg transition flex items-center gap-2">
                                    <i class="fa-brands fa-whatsapp text-lg"></i>
                                    <span>Order Oudh Gift Set via WhatsApp</span>
                                </a>
                            </div>
                        </div>

                        <div class="lg:col-span-5 flex justify-center">
                            <div class="relative w-64 h-64 sm:w-72 sm:h-72 bg-gradient-to-tr from-black via-emerald-950 to-amber-950 rounded-full border-2 border-gold-500/50 flex items-center justify-center p-6 shadow-2xl">
                                <div class="relative flex flex-col items-center justify-center">
                                    <div class="w-12 h-16 bg-gradient-to-r from-gold-400 via-gold-200 to-gold-600 rounded-t-full border border-gold-300 shadow-md"></div>
                                    <div class="w-24 h-24 rounded-full bg-amber-500/30 border-2 border-gold-400 flex items-center justify-center relative overflow-hidden backdrop-blur-md shadow-inner">
                                        <div class="w-16 h-16 bg-amber-600/80 rounded-full border border-gold-300 flex items-center justify-center text-center p-1">
                                            <span class="font-cinzel text-[9px] font-bold text-gold-200 uppercase">Pure Oudh</span>
                                        </div>
                                    </div>
                                    <div class="w-20 h-4 bg-gold-600 rounded-b-md"></div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- Reviews -->
        <section class="py-16 bg-emerald-900/30 border-b border-gold-500/10">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-2xl mx-auto mb-12">
                    <span class="text-gold-400 text-xs font-bold uppercase tracking-widest">Testimonials</span>
                    <h2 class="font-cinzel text-3xl font-bold text-white mt-1">Loved by <span class="gold-gradient-text">Fragrance Connoisseurs</span></h2>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-emerald-950/80 border border-gold-500/20 p-6 rounded-2xl space-y-4">
                        <div class="flex text-gold-400 text-xs space-x-1">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-300 text-xs italic leading-relaxed">
                            "The Shaff Oudh perfume is incredible. Long lasting scent that gets compliments wherever I go. Ordering via WhatsApp was super easy!"
                        </p>
                        <div class="pt-2 border-t border-emerald-800/60 flex items-center justify-between text-xs">
                            <span class="font-bold text-white">Fayiz M.</span>
                            <span class="text-gray-400">Malappuram</span>
                        </div>
                    </div>

                    <div class="bg-emerald-950/80 border border-gold-500/20 p-6 rounded-2xl space-y-4">
                        <div class="flex text-gold-400 text-xs space-x-1">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-300 text-xs italic leading-relaxed">
                            "Pineapple & Rose Athar Agarbattis burn smoothly with zero dark smoke. Very fragrant and soothing atmosphere at home."
                        </p>
                        <div class="pt-2 border-t border-emerald-800/60 flex items-center justify-between text-xs">
                            <span class="font-bold text-white">Anjali Nair</span>
                            <span class="text-gray-400">Kozhikode</span>
                        </div>
                    </div>

                    <div class="bg-emerald-950/80 border border-gold-500/20 p-6 rounded-2xl space-y-4">
                        <div class="flex text-gold-400 text-xs space-x-1">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-300 text-xs italic leading-relaxed">
                            "Ameerul Oudh and Dove pocket sprays are super convenient to carry for daily work and travel. Amazing value for money!"
                        </p>
                        <div class="pt-2 border-t border-emerald-800/60 flex items-center justify-between text-xs">
                            <span class="font-bold text-white">Rashid K.</span>
                            <span class="text-gray-400">Manjeri</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Location & Contact Info -->
        <section id="contact" class="py-16 bg-luxury-pattern">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-emerald-900/60 border border-gold-500/30 rounded-3xl p-8 lg:p-12 shadow-2xl">
                    <div class="grid grid-cols-1 lg:grid-cols-2 gap-10">
                        
                        <div class="space-y-6">
                            <div>
                                <span class="text-gold-400 text-xs font-bold uppercase tracking-widest">Get in Touch</span>
                                <h2 class="font-cinzel text-3xl font-bold text-white mt-1">Connect with <span class="gold-gradient-text">SHAFFROSE</span></h2>
                                <p class="text-gray-300 text-sm mt-2">Have a question or wish to place a wholesale/custom gift order? Reach out directly via phone or WhatsApp.</p>
                            </div>

                            <div class="space-y-4 pt-2">
                                <div class="flex items-start gap-4">
                                    <div class="w-10 h-10 rounded-xl bg-emerald-950 border border-gold-500/40 flex items-center justify-center text-gold-400 shrink-0 mt-1">
                                        <i class="fa-solid fa-location-dot"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-xs font-bold text-gold-300 uppercase">Address / Store Location</h4>
                                        <p class="text-sm text-gray-200 font-medium">Kakkad, Malappuram, Kerala, India</p>
                                    </div>
                                </div>

                                <div class="flex items-start gap-4">
                                    <div class="w-10 h-10 rounded-xl bg-emerald-950 border border-gold-500/40 flex items-center justify-center text-gold-400 shrink-0 mt-1">
                                        <i class="fa-brands fa-whatsapp text-lg"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-xs font-bold text-gold-300 uppercase">WhatsApp & Direct Phone</h4>
                                        <a href="https://wa.me/918921570125" target="_blank" class="text-sm text-green-300 font-semibold hover:underline">
                                            +91 8921570125
                                        </a>
                                        <p class="text-[11px] text-gray-400">Available 9:00 AM - 9:00 PM for inquiries</p>
                                    </div>
                                </div>

                                <div class="flex items-start gap-4">
                                    <div class="w-10 h-10 rounded-xl bg-emerald-950 border border-gold-500/40 flex items-center justify-center text-gold-400 shrink-0 mt-1">
                                        <i class="fa-brands fa-instagram text-lg"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-xs font-bold text-gold-300 uppercase">Instagram Handles</h4>
                                        <a href="https://instagram.com/shaffrose.perfume" target="_blank" class="text-sm text-rosebrand-400 font-semibold hover:underline">
                                            @shaffrose.perfume
                                        </a>
                                    </div>
                                </div>
                            </div>

                            <div class="pt-4 flex gap-3">
                                <a href="https://wa.me/918921570125?text=Hello%20SHAFFROSE,%20I%20want%20to%20know%20more%20about%20your%20perfumes." target="_blank" class="flex-1 py-3 bg-emerald-600 hover:bg-emerald-500 text-white font-bold text-xs rounded-xl shadow text-center transition flex items-center justify-center gap-2">
                                    <i class="fa-brands fa-whatsapp text-base"></i> Chat on WhatsApp
                                </a>
                                <a href="tel:8921570125" class="py-3 px-6 bg-emerald-950 border border-gold-500/40 hover:bg-gold-500 hover:text-emerald-950 text-gold-300 font-bold text-xs rounded-xl transition text-center flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-phone"></i> Call Now
                                </a>
                            </div>
                        </div>

                        <!-- Inquiry Form -->
                        <div class="bg-emerald-950/90 border border-gold-500/30 p-6 rounded-2xl">
                            <h3 class="font-cinzel text-lg font-bold text-white mb-4">Send Instant Inquiry</h3>
                            <form id="inquiry-form" onsubmit="sendInquiry(event)" class="space-y-4">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-1">Your Name</label>
                                    <input type="text" id="inquiry-name" required placeholder="Enter full name" class="w-full bg-emerald-900/80 border border-emerald-700/60 rounded-lg py-2.5 px-3 text-xs text-white focus:outline-none focus:border-gold-400">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-1">Mobile / WhatsApp Number</label>
                                    <input type="tel" id="inquiry-phone" required placeholder="10-digit mobile number" class="w-full bg-emerald-900/80 border border-emerald-700/60 rounded-lg py-2.5 px-3 text-xs text-white focus:outline-none focus:border-gold-400">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-1">Product Interested In</label>
                                    <select id="inquiry-product" class="w-full bg-emerald-900/80 border border-emerald-700/60 rounded-lg py-2.5 px-3 text-xs text-white focus:outline-none focus:border-gold-400">
                                        <option value="Shaff Oudh Perfume">Shaff Oudh Perfume</option>
                                        <option value="Shaffrose Dove Pocket Perfume">Shaffrose Dove Pocket Perfume (2 Pack)</option>
                                        <option value="Ameerul Oudh Perfume">Ameerul Oudh Perfume (2 Pack)</option>
                                        <option value="Shaff Oudh Attar">Shaff Oudh Pure Attar</option>
                                        <option value="Athar Agarbatti Series">Athar Agarbatti Series (0% Charcoal)</option>
                                        <option value="Oudh Soap & Hand Wash">Oudh Soap & Hand Wash</option>
                                        <option value="Wholesale / Bulk Order">Wholesale / Bulk Gift Order</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-1">Message / Notes</label>
                                    <textarea id="inquiry-msg" rows="3" placeholder="Tell us your location or inquiry details..." class="w-full bg-emerald-900/80 border border-emerald-700/60 rounded-lg py-2.5 px-3 text-xs text-white focus:outline-none focus:border-gold-400"></textarea>
                                </div>
                                <button type="submit" class="w-full py-3 bg-gradient-to-r from-gold-500 to-gold-600 hover:from-gold-400 hover:to-gold-500 text-emerald-950 font-bold text-xs rounded-xl shadow transition uppercase tracking-wider flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i> Send via WhatsApp
                                </button>
                            </form>
                        </div>

                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-emerald-950 border-t border-gold-500/20 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-black border border-gold-500 flex items-center justify-center p-1">
                            <svg viewBox="0 0 100 100" class="w-full h-full">
                                <circle cx="50" cy="50" r="46" fill="#000000" stroke="#e63956" stroke-width="4"/>
                                <text x="50" y="62" font-family="cursive" font-size="28" font-weight="bold" fill="#e63956" text-anchor="middle">S</text>
                            </svg>
                        </div>
                        <span class="font-cinzel text-xl font-bold gold-gradient-text">SHAFFROSE</span>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Luxury beauty and personal care products designed for daily elegance. Pure fragrances, traditional attars, charcoal-free agarbatti, and nourishing body soaps.
                    </p>
                </div>

                <div>
                    <h4 class="font-cinzel text-sm font-bold text-gold-400 uppercase tracking-wider mb-4">Quick Links</h4>
                    <ul class="space-y-2 text-xs text-gray-300">
                        <li><a href="#hero" class="hover:text-gold-400 transition">Home</a></li>
                        <li><a href="#about" class="hover:text-gold-400 transition">About SHAFFROSE</a></li>
                        <li><a href="#products" class="hover:text-gold-400 transition">Products Catalog</a></li>
                        <li><a href="#oudh-highlight" class="hover:text-gold-400 transition">Oudh Range</a></li>
                        <li><a href="javascript:void(0)" onclick="openQuiz()" class="hover:text-gold-400 transition">Scent Finder Quiz</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-cinzel text-sm font-bold text-gold-400 uppercase tracking-wider mb-4">Products</h4>
                    <ul class="space-y-2 text-xs text-gray-300">
                        <li><a href="#products" onclick="filterCategory('perfume')" class="hover:text-gold-400 transition">Perfumes & Pocket Sprays</a></li>
                        <li><a href="#products" onclick="filterCategory('attar')" class="hover:text-gold-400 transition">Pure Oudh Attar</a></li>
                        <li><a href="#products" onclick="filterCategory('agarbatti')" class="hover:text-gold-400 transition">Athar Agarbatti (0% Charcoal)</a></li>
                        <li><a href="#products" onclick="filterCategory('bodycare')" class="hover:text-gold-400 transition">Oudh Soap & Hand Wash</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-cinzel text-sm font-bold text-gold-400 uppercase tracking-wider mb-4">Location</h4>
                    <p class="text-xs text-gray-300 mb-2">
                        <i class="fa-solid fa-location-dot text-gold-400 mr-1.5"></i> Kakkad, Malappuram, Kerala, India
                    </p>
                    <p class="text-xs text-gray-300 mb-4">
                        <i class="fa-solid fa-phone text-gold-400 mr-1.5"></i> +91 8921570125
                    </p>
                    <div class="flex space-x-3">
                        <a href="https://wa.me/918921570125" target="_blank" class="w-8 h-8 rounded-full bg-emerald-900 border border-gold-500/30 flex items-center justify-center text-green-400 hover:bg-gold-500 hover:text-emerald-950 transition">
                            <i class="fa-brands fa-whatsapp text-sm"></i>
                        </a>
                        <a href="https://instagram.com/shaffrose.perfume" target="_blank" class="w-8 h-8 rounded-full bg-emerald-900 border border-gold-500/30 flex items-center justify-center text-rosebrand-400 hover:bg-gold-500 hover:text-emerald-950 transition">
                            <i class="fa-brands fa-instagram text-sm"></i>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-8 border-t border-emerald-900 flex flex-col sm:flex-row items-center justify-between text-[11px] text-gray-400">
                <p>© 2026 SHAFFROSE. All Rights Reserved. Kakkad, Malappuram.</p>
                <p class="mt-2 sm:mt-0">Designed for Luxury Fragrance Enthusiasts.</p>
            </div>
        </div>
    </footer>

    <!-- Shopping Cart Side Drawer -->
    <div id="cart-drawer" class="fixed inset-0 bg-black/70 backdrop-blur-sm z-50 hidden flex justify-end">
        <div class="bg-emerald-950 border-l border-gold-500/30 w-full max-w-md h-full flex flex-col justify-between p-6 shadow-2xl relative">
            <div>
                <div class="flex items-center justify-between pb-4 border-b border-emerald-800">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-bag-shopping text-gold-400 text-xl"></i>
                        <h3 class="font-cinzel text-lg font-bold text-white">Your Shopping Bag</h3>
                    </div>
                    <button onclick="toggleCartDrawer()" class="text-gray-400 hover:text-white p-2 text-xl">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>

                <div id="cart-items-list" class="mt-4 space-y-4 max-h-[55vh] overflow-y-auto pr-1">
                </div>
            </div>

            <div id="cart-summary" class="border-t border-emerald-800 pt-4 space-y-4">
                <div class="space-y-1.5 text-xs">
                    <div class="flex justify-between text-gray-300">
                        <span>Subtotal</span>
                        <span id="cart-subtotal" class="font-bold text-white">₹0</span>
                    </div>
                    <div class="flex justify-between text-gray-300">
                        <span>Delivery (Kerala)</span>
                        <span class="text-emerald-400 font-semibold">Calculated on WhatsApp</span>
                    </div>
                    <div class="flex justify-between text-sm text-gold-400 font-bold pt-2 border-t border-emerald-900">
                        <span>Estimated Total</span>
                        <span id="cart-total">₹0</span>
                    </div>
                </div>

                <div class="space-y-2">
                    <input type="text" id="cust-name" placeholder="Full Name" class="w-full bg-emerald-900/80 border border-emerald-700 rounded-lg py-2 px-3 text-xs text-white placeholder-gray-400 focus:outline-none">
                    <input type="text" id="cust-address" placeholder="Delivery Address / City (e.g. Malappuram)" class="w-full bg-emerald-900/80 border border-emerald-700 rounded-lg py-2 px-3 text-xs text-white placeholder-gray-400 focus:outline-none">
                </div>

                <button onclick="checkoutWhatsApp()" class="w-full py-3 bg-gradient-to-r from-emerald-600 to-emerald-700 hover:from-emerald-500 hover:to-emerald-600 text-white font-bold text-sm rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                    <i class="fa-brands fa-whatsapp text-lg text-green-300"></i>
                    <span>Place Order via WhatsApp</span>
                </button>
            </div>
        </div>
    </div>

    <!-- Product Detail Quick View Modal -->
    <div id="product-modal" class="fixed inset-0 bg-black/80 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div id="modal-content" class="bg-emerald-950 border border-gold-500/40 rounded-3xl w-full max-w-2xl p-6 shadow-2xl relative max-h-[90vh] overflow-y-auto">
        </div>
    </div>

    <!-- Scent Quiz Modal -->
    <div id="quiz-modal" class="fixed inset-0 bg-black/80 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-emerald-950 border border-gold-500/40 rounded-3xl w-full max-w-lg p-6 sm:p-8 shadow-2xl relative">
            <button onclick="closeQuiz()" class="absolute top-4 right-4 text-gray-400 hover:text-white text-xl">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="quiz-body">
            </div>
        </div>
    </div>

    <!-- JavaScript Logic -->
    <script>
        // Complete SHAFFROSE Master Product Data
        const productsData = [
            {
                id: 1,
                name: "SHAFF OUDH PERFUME",
                category: "perfume",
                isOudh: true,
                price: 1199,
                originalPrice: 1499,
                discount: "20% OFF",
                badge: "Signature Fragrance",
                shortDesc: "Indulge in the signature Shaff Oudh fragrance, blending luxury, sophistication, and long-lasting freshness in every spray.",
                desc: "Crafted for connoisseurs of fine scents. Shaff Oudh perfume opens with vibrant top notes of dark woody resins and soft floral undertones, evolving into a warm amber and musk heart that lingers for over 24 hours.",
                notes: { top: "Agarwood & Rose", heart: "Spicy Amber", base: "Deep Cedarwood & Musk" },
                bgGradient: "from-amber-950 to-emerald-950",
                type: "spray"
            },
            {
                id: 2,
                name: "SHAFF OUDH ATTAR",
                category: "attar",
                isOudh: true,
                price: 499,
                originalPrice: 599,
                discount: "16% OFF",
                badge: "Pure Concentrated",
                shortDesc: "Experience the richness of pure Shaff Oudh Attar, crafted to deliver a deep, long-lasting fragrance with timeless elegance.",
                desc: "Alcohol-free concentrated perfume oil. Traditional distillation technique capturing the majestic warmth of authentic oriental Oudh.",
                notes: { top: "Warm Saffron", heart: "Precious Oud Wood", base: "Rich Earthy Resin" },
                bgGradient: "from-yellow-950 to-emerald-950",
                type: "attar-flask"
            },
            {
                id: 3,
                name: "SHAFF OUDH SOAP",
                category: "bodycare",
                isOudh: true,
                price: 120,
                originalPrice: 140,
                discount: "14% OFF",
                badge: "Luxury Bathing",
                shortDesc: "Cleanse and refresh your skin with the luxurious aroma of Shaff Oudh, leaving you feeling fresh, soft, and revitalized.",
                desc: "Luxury glycerin bathing bar infused with genuine Oudh fragrance oil and skin-nourishing extracts.",
                notes: { top: "Clean Oud Mist", heart: "Moisturizing Oils", base: "Soft Rose" },
                bgGradient: "from-rose-950 to-emerald-950",
                type: "soap"
            },
            {
                id: 4,
                name: "SHAFF OUDH HANDWASH",
                category: "bodycare",
                isOudh: true,
                price: 190,
                originalPrice: 220,
                discount: "13% OFF",
                badge: "Premium Hand Care",
                shortDesc: "Elevate your daily hand care with Shaff Oudh Handwash, offering a rich cleanse and a refined fragrance after every wash.",
                desc: "Rich lather hand wash enriched with antibacterial protection and long-lasting oriental fragrance.",
                notes: { top: "Fresh Oudh", heart: "Botanical Extracts", base: "Hydrating Glycerin" },
                bgGradient: "from-amber-900 to-emerald-950",
                type: "handwash"
            },
            {
                id: 5,
                name: "SHAFF OUDH POCKET SPRAY",
                category: "perfume",
                isOudh: true,
                price: 150,
                originalPrice: 180,
                discount: "16% OFF",
                badge: "Travel Essential",
                shortDesc: "Carry your signature fragrance wherever you go with our compact Shaff Oudh Pocket Spray, designed for freshness anytime.",
                desc: "Convenient pocket-sized 20ml spray. Leak-proof design perfect for daily office, travel, and prayer routines.",
                notes: { top: "Instant Oud Refresh", heart: "Spicy Floral", base: "Smooth Amber" },
                bgGradient: "from-emerald-900 to-black",
                type: "pocket"
            },
            {
                id: 6,
                name: "PINEAPPLE ATHAR AGARBATTI",
                category: "agarbatti",
                isOudh: false,
                price: 170,
                originalPrice: 180,
                discount: "6% OFF",
                badge: "0% Charcoal",
                shortDesc: "Juicy tropical pineapple infused with soothing Athar incense oils. Creates an inviting, sweet floral atmosphere.",
                desc: "Premium eco-friendly incense sticks made with 0% charcoal. Long burning time (40+ sticks pack).",
                notes: { top: "Sweet Pineapple", heart: "Athar Spices", base: "Sandalwood Dust" },
                bgGradient: "from-yellow-900 to-emerald-950",
                type: "agarbatti-tube"
            },
            {
                id: 7,
                name: "JASMINE ATHAR AGARBATTI",
                category: "agarbatti",
                isOudh: false,
                price: 170,
                originalPrice: 180,
                discount: "6% OFF",
                badge: "0% Charcoal",
                shortDesc: "Calming natural Jasmine flower fragrance blended with pure Athar oil for serene evening relaxation.",
                desc: "40+ pieces premium eco sticks. Infuses rooms with authentic fresh jasmine floral aroma.",
                notes: { top: "Fresh Mogra", heart: "Jasmine Sambac", base: "White Musk" },
                bgGradient: "from-green-950 to-emerald-950",
                type: "agarbatti-tube"
            },
            {
                id: 8,
                name: "ROSE AGARBATTI",
                category: "agarbatti",
                isOudh: false,
                price: 170,
                originalPrice: 180,
                discount: "6% OFF",
                badge: "Premium Aroma",
                shortDesc: "Classic romantic Damask Rose scented fragrance sticks. Ideal for daily worship, meditation, and home aroma.",
                desc: "Rich red incense sticks releasing soothing floral notes. Charcoal-free formula protecting indoor air quality.",
                notes: { top: "Damask Rose", heart: "Petal Extracts", base: "Light Amber" },
                bgGradient: "from-rose-950 to-emerald-950",
                type: "agarbatti-tube"
            },
            {
                id: 9,
                name: "LITCHI ATHAR AGARBATTI",
                category: "agarbatti",
                isOudh: false,
                price: 170,
                originalPrice: 180,
                discount: "6% OFF",
                badge: "Exotic Fruit Notes",
                shortDesc: "Exotic blend of sweet Litchi fruit essence and warm Athar notes for a uniquely refreshing ambiance.",
                desc: "Crafted with natural woods and fruity fragrance oils. Burns slowly for extended aroma diffusion.",
                notes: { top: "Fresh Litchi", heart: "Fruity Athar", base: "Earthy Bark" },
                bgGradient: "from-pink-950 to-emerald-950",
                type: "agarbatti-tube"
            },
            {
                id: 10,
                name: "ORANGE ATHAR AGARBATTI",
                category: "agarbatti",
                isOudh: false,
                price: 170,
                originalPrice: 180,
                discount: "6% OFF",
                badge: "Citrus Refresh",
                shortDesc: "Energizing citrus orange zest blended with herbal Athar oils to uplift mood and clear ambient air.",
                desc: "100% natural aroma sticks. Vibrant orange packaging with long-lasting scent residual.",
                notes: { top: "Orange Zest", heart: "Citrus Blossom", base: "Warm Athar" },
                bgGradient: "from-orange-950 to-emerald-950",
                type: "agarbatti-tube"
            },
            {
                id: 11,
                name: "KASTURI PERFUME (2 PACK)",
                category: "perfume",
                isOudh: false,
                price: 230,
                originalPrice: 240,
                discount: "4% OFF",
                badge: "Value 2-Pack",
                shortDesc: "Elegant, fresh, unforgettable. Classic oriental Kasturi fragrance twin pack for daily use.",
                desc: "Includes 2 pocket perfume sprays. Rich deep Kasturi scent loved across Kerala.",
                notes: { top: "Warm Kasturi", heart: "Spicy Herbal", base: "Sensual Musk" },
                bgGradient: "from-amber-950 to-emerald-950",
                type: "twopack"
            },
            {
                id: 12,
                name: "SHAFFROSE DOVE POCKET PERFUME (2 PACK)",
                category: "perfume",
                isOudh: false,
                price: 230,
                originalPrice: 240,
                discount: "4% OFF",
                badge: "French Fragrance",
                shortDesc: "Feel elegant, feel confident. Light, airy French style perfume twin pack perfect for daily freshness.",
                desc: "Soft clean powdery notes reminiscent of luxury soaps. Pack of 2 travel pocket sprays.",
                notes: { top: "French Floral", heart: "Clean Powdery Essence", base: "Soft White Musk" },
                bgGradient: "from-slate-900 to-rose-950",
                type: "twopack"
            },
            {
                id: 13,
                name: "AMEERUL OUDH PERFUME (2 PACK)",
                category: "perfume",
                isOudh: true,
                price: 230,
                originalPrice: 240,
                discount: "4% OFF",
                badge: "Best Seller 2-Pack",
                shortDesc: "Elegant, fresh, unforgettable. Premium oriental Ameerul Oudh twin pack designed for long-lasting royalty.",
                desc: "Includes 2 pocket spray bottles. Infused with natural essences for exotic aroma during prayer, work, or events.",
                notes: { top: "Exotic Spices", heart: "Ameerul Oud", base: "Warm Woody Resin" },
                bgGradient: "from-amber-950 to-black",
                type: "twopack"
            }
        ];

        let cart = [];

        // Dynamic Pro
