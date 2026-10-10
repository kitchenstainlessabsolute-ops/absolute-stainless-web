<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Absolute Kitchen Stainless Klaten</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        steel: {
                            50: '#f8fafc',
                            100: '#f1f5f9',
                            200: '#e2e8f0', // Silver base
                            300: '#cbd5e1',
                            400: '#94a3b8',
                            500: '#64748b', // Metallic gray
                            600: '#475569',
                            700: '#334155', // Dark metallic
                            800: '#1e293b',
                            900: '#0f172a',
                        },
                        accent: {
                            DEFAULT: '#1e3a8a', // Steel blue
                            hover: '#172554',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .hero-bg {
            background-image: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.7)), url('https://placehold.co/1920x1080/1e293b/94a3b8?text=Commercial+Kitchen+Stainless');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        .text-gradient {
            background: linear-gradient(to right, #e2e8f0, #94a3b8, #cbd5e1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="font-sans text-steel-800 bg-steel-50 antialiased selection:bg-accent selection:text-white">

    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-transparent py-5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center">
                <!-- Logo -->
                <div class="flex-shrink-0">
                    <a href="#" class="text-2xl font-bold text-white tracking-wider flex items-center gap-2">
                        <i class="fa-solid fa-fire-burner text-steel-300"></i>
                        ABSOLUTE <span class="font-light text-steel-300">STAINLESS</span>
                    </a>
                </div>
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-6 lg:space-x-8 items-center">
                    <a href="#beranda" class="text-steel-100 hover:text-white font-medium transition-colors duration-200">Beranda</a>
                    <a href="#tentang" class="text-steel-100 hover:text-white font-medium transition-colors duration-200">Tentang Kami</a>
                    <a href="#layanan" class="text-steel-100 hover:text-white font-medium transition-colors duration-200">Layanan</a>
                    <a href="#produk" class="text-steel-100 hover:text-white font-medium transition-colors duration-200">Produk</a>
                    <a href="#kontak" class="text-steel-100 hover:text-white font-medium transition-colors duration-200">Kontak</a>
                    <a href="#kontak" class="bg-accent text-white px-5 py-2.5 rounded-md font-semibold hover:bg-accent-hover transition-all duration-300 shadow-lg shadow-accent/30">Konsultasi</a>
                </div>
                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-white hover:text-steel-300 focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-steel-900 absolute w-full top-full left-0 border-t border-steel-700 shadow-2xl">
            <div class="px-4 pt-2 pb-4 space-y-1 text-center">
                <a href="#beranda" class="block px-3 py-3 rounded-md text-base font-medium text-steel-200 hover:text-white hover:bg-steel-800">Beranda</a>
                <a href="#tentang" class="block px-3 py-3 rounded-md text-base font-medium text-steel-200 hover:text-white hover:bg-steel-800">Tentang Kami</a>
                <a href="#layanan" class="block px-3 py-3 rounded-md text-base font-medium text-steel-200 hover:text-white hover:bg-steel-800">Layanan</a>
                <a href="#produk" class="block px-3 py-3 rounded-md text-base font-medium text-steel-200 hover:text-white hover:bg-steel-800">Produk</a>
                <a href="#kontak" class="block px-3 py-3 rounded-md text-base font-medium text-steel-200 hover:text-white hover:bg-steel-800">Kontak</a>
            </div>
        </div>
    </nav>

    <header id="beranda" class="relative hero-bg min-h-screen flex items-center justify-center pt-20">
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center z-10">
            <span class="inline-block py-1 px-3 rounded-full bg-steel-800/80 border border-steel-500 text-steel-200 text-sm font-semibold tracking-wide mb-6 uppercase">
                Berbasis di Klaten, Jawa Tengah
            </span>
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold tracking-tight mb-6 text-white leading-tight">
                Solusi Dapur Komersial <br/>
                <span class="text-gradient">Profesional & Presisi.</span>
            </h1>
            <p class="mt-4 max-w-2xl text-lg sm:text-xl text-steel-200 mx-auto mb-10 font-light leading-relaxed">
                Produsen & Fabrikasi Kitchen Equipment Stainless Steel Terbaik di Klaten. Dirancang khusus untuk daya tahan maksimal dan kebersihan standar industri.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#kontak" class="bg-accent text-white px-8 py-4 rounded-md font-bold text-lg hover:bg-accent-hover hover:shadow-[0_0_20px_rgba(30,58,138,0.5)] hover:-translate-y-1 transition-all duration-300">
                    <i class="fa-brands fa-whatsapp mr-2"></i> Konsultasi Gratis
                </a>
                <a href="#produk" class="bg-steel-800/50 border border-steel-400 text-white px-8 py-4 rounded-md font-bold text-lg hover:bg-steel-700 transition-all duration-300 backdrop-blur-sm">
                    Lihat Portofolio
                </a>
            </div>
        </div>
        
        <!-- Scroll indicator -->
        <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce hidden sm:block">
            <a href="#tentang" class="text-steel-400 hover:text-white transition-colors">
                <i class="fa-solid fa-arrow-down text-2xl"></i>
            </a>
        </div>
    </header>

    <section id="tentang" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-16">
                <div class="lg:w-1/2">
                    <div class="relative">
                        <img src="https://placehold.co/800x600/e2e8f0/475569?text=Fabrikasi+Stainless+Klaten" alt="Workshop Absolute Kitchen Stainless" class="rounded-lg shadow-2xl relative z-10 w-full object-cover">
                        <div class="absolute -bottom-6 -right-6 w-full h-full bg-steel-200 rounded-lg -z-10"></div>
                        <!-- Floating badge -->
                        <div class="absolute -left-6 top-1/4 bg-white p-4 rounded-lg shadow-xl border-l-4 border-accent hidden md:block z-20">
                            <div class="flex items-center gap-4">
                                <i class="fa-solid fa-location-dot text-3xl text-accent"></i>
                                <div>
                                    <p class="font-bold text-steel-900">Lokasi Strategis</p>
                                    <p class="text-sm text-steel-500">Klaten, Jawa Tengah</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2">
                    <h4 class="text-accent font-bold uppercase tracking-wider text-sm mb-2">Tentang Perusahaan</h4>
                    <h2 class="text-3xl md:text-4xl font-bold text-steel-900 mb-6 leading-tight">Spesialis Fabrikasi <span class="text-steel-500">Stainless Steel</span> Terpercaya</h2>
                    <p class="text-steel-600 mb-6 leading-relaxed text-lg">
                        Berlokasi di <strong>Klaten, Jawa Tengah</strong>, <span class="font-bold text-steel-800">Absolute Kitchen Stainless</span> adalah mitra andalan bagi para pelaku usaha kuliner dan fasilitas kesehatan dalam mewujudkan dapur yang higienis, aman, dan efisien.
                    </p>
                    <p class="text-steel-600 mb-8 leading-relaxed">
                        Kami merancang, memproduksi, dan melakukan instalasi perlengkapan dapur komersial dengan material stainless steel berkualitas tinggi. Layanan kami mencakup berbagai skala bisnis, mulai dari dapur restoran cepat saji, hotel bintang lima, layanan katering skala besar, hingga instalasi gizi standar rumah sakit.
                    </p>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-steel-100 flex items-center justify-center text-accent">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-semibold text-steel-800">Material Grade Terbaik</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-steel-100 flex items-center justify-center text-accent">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-semibold text-steel-800">Presisi & Rapi</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-steel-100 flex items-center justify-center text-accent">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-semibold text-steel-800">Harga Pabrikasi</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-steel-100 flex items-center justify-center text-accent">
                                <i class="fa-solid fa-check"></i>
                            </div>
                            <span class="font-semibold text-steel-800">Custom Sesuai Kebutuhan</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="layanan" class="py-24 bg-steel-50 border-y border-steel-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16 max-w-3xl mx-auto">
                <h4 class="text-accent font-bold uppercase tracking-wider text-sm mb-2">Fokus Kami</h4>
                <h2 class="text-3xl md:text-4xl font-bold text-steel-900 mb-4">Layanan Utama Fabrikasi</h2>
                <p class="text-steel-600">Kami menyediakan solusi spesifik untuk berbagai sektor industri yang membutuhkan standar dapur tingkat tinggi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Card 1 -->
                <div class="bg-white rounded-xl p-8 shadow-[0_4px_20px_rgba(0,0,0,0.05)] border border-steel-100 hover:shadow-xl hover:-translate-y-2 transition-all duration-300 group">
                    <div class="w-16 h-16 bg-steel-50 rounded-lg flex items-center justify-center mb-6 group-hover:bg-accent transition-colors duration-300">
                        <i class="fa-solid fa-utensils text-2xl text-steel-700 group-hover:text-white"></i>
                    </div>
                    <h3 class="text-xl font-bold text-steel-900 mb-3">Dapur Restoran & Kafe</h3>
                    <p class="text-steel-600 text-sm leading-relaxed">
                        Desain efisien untuk workflow koki. Pembuatan meja racik, instalasi exhaust sistem, sink cuci, dan kabinet untuk menjaga ritme kerja yang cepat dan bersih.
                    </p>
                </div>

                <!-- Card 2 -->
                <div class="bg-white rounded-xl p-8 shadow-[0_4px_20px_rgba(0,0,0,0.05)] border border-steel-100 hover:shadow-xl hover:-translate-y-2 transition-all duration-300 group">
                    <div class="w-16 h-16 bg-steel-50 rounded-lg flex items-center justify-center mb-6 group-hover:bg-accent transition-colors duration-300">
                        <i class="fa-solid fa-hotel text-2xl text-steel-700 group-hover:text-white"></i>
                    </div>
                    <h3 class="text-xl font-bold text-steel-900 mb-3">Katering & Hotel</h3>
                    <p class="text-steel-600 text-sm leading-relaxed">
                        Peralatan skala masif yang tahan banting. Pembuatan kwali range, rak penyimpanan bahan baku besar, troli makanan, dan area plating yang luas.
                    </p>
                </div>

                <!-- Card 3 -->
                <div class="bg-white rounded-xl p-8 shadow-[0_4px_20px_rgba(0,0,0,0.05)] border border-steel-100 hover:shadow-xl hover:-translate-y-2 transition-all duration-300 group">
                    <div class="w-16 h-16 bg-steel-50 rounded-lg flex items-center justify-center mb-6 group-hover:bg-accent transition-colors duration-300">
                        <i class="fa-solid fa-hospital text-2xl text-steel-700 group-hover:text-white"></i>
                    </div>
                    <h3 class="text-xl font-bold text-steel-900 mb-3">Instalasi Gizi RS</h3>
                    <p class="text-steel-600 text-sm leading-relaxed">
                        Standar higienitas tertinggi (food grade). Menyediakan meja stainless anti bakteri, sistem pencucian tersentralisasi, dan distribusi makanan pasien.
                    </p>
                </div>

                <!-- Card 4 -->
                <div class="bg-white rounded-xl p-8 shadow-[0_4px_20px_rgba(0,0,0,0.05)] border border-steel-100 hover:shadow-xl hover:-translate-y-2 transition-all duration-300 group">
                    <div class="w-16 h-16 bg-steel-50 rounded-lg flex items-center justify-center mb-6 group-hover:bg-accent transition-colors duration-300">
                        <i class="fa-solid fa-hammer text-2xl text-steel-700 group-hover:text-white"></i>
                    </div>
                    <h3 class="text-xl font-bold text-steel-900 mb-3">Jasa Custom & Tekuk</h3>
                    <p class="text-steel-600 text-sm leading-relaxed">
                        Selain full order, kami juga melayani jasa potong (cutting), tekuk (bending) pelat stainless steel, dan fabrikasi custom sesuai gambar teknik Anda.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="produk" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div class="max-w-2xl">
                    <h4 class="text-accent font-bold uppercase tracking-wider text-sm mb-2">Katalog Kami</h4>
                    <h2 class="text-3xl md:text-4xl font-bold text-steel-900">Produk Unggulan</h2>
                </div>
                <a href="https://www.youtube.com/@AbsoluteKitchenStainless" target="_blank" class="mt-4 md:mt-0 text-accent font-semibold hover:text-steel-900 transition-colors flex items-center gap-2 group">
                    Lihat Video Portofolio <i class="fa-solid fa-arrow-right transform group-hover:translate-x-1 transition-transform"></i>
                </a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Product 1 -->
                <div class="group relative overflow-hidden rounded-xl cursor-pointer shadow-md">
                    <img src="https://placehold.co/600x600/334155/cbd5e1?text=Meja+Stainless+(Worktable)" alt="Meja Stainless" class="w-full h-64 object-cover transform group-hover:scale-110 transition-transform duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-steel-900 via-steel-900/40 to-transparent opacity-80"></div>
                    <div class="absolute bottom-0 left-0 w-full p-6 transform translate-y-2 group-hover:translate-y-0 transition-transform">
                        <h3 class="text-xl font-bold text-white mb-1">Meja Stainless (Worktable)</h3>
                        <p class="text-steel-300 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100">Kuat, kokoh, tanpa sambungan celah kotoran.</p>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="group relative overflow-hidden rounded-xl cursor-pointer shadow-md">
                    <img src="https://placehold.co/600x600/475569/cbd5e1?text=Sink+/+Wastafel+Stainless" alt="Sink Wastafel" class="w-full h-64 object-cover transform group-hover:scale-110 transition-transform duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-steel-900 via-steel-900/40 to-transparent opacity-80"></div>
                    <div class="absolute bottom-0 left-0 w-full p-6 transform translate-y-2 group-hover:translate-y-0 transition-transform">
                        <h3 class="text-xl font-bold text-white mb-1">Sink & Wastafel</h3>
                        <p class="text-steel-300 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100">1 bowl, 2 bowl, hingga desain khusus heavy duty.</p>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="group relative overflow-hidden rounded-xl cursor-pointer shadow-md">
                    <img src="https://placehold.co/600x600/334155/cbd5e1?text=Rak+&+Kabinet+Penyimpanan" alt="Rak dan Kabinet" class="w-full h-64 object-cover transform group-hover:scale-110 transition-transform duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-steel-900 via-steel-900/40 to-transparent opacity-80"></div>
                    <div class="absolute bottom-0 left-0 w-full p-6 transform translate-y-2 group-hover:translate-y-0 transition-transform">
                        <h3 class="text-xl font-bold text-white mb-1">Rak & Kabinet</h3>
                        <p class="text-steel-300 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100">Rak bersusun dan lemari tertutup untuk bahan baku.</p>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="group relative overflow-hidden rounded-xl cursor-pointer shadow-md">
                    <img src="https://placehold.co/600x600/475569/cbd5e1?text=Exhaust+Hood+System" alt="Exhaust Hood" class="w-full h-64 object-cover transform group-hover:scale-110 transition-transform duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-steel-900 via-steel-900/40 to-transparent opacity-80"></div>
                    <div class="absolute bottom-0 left-0 w-full p-6 transform translate-y-2 group-hover:translate-y-0 transition-transform">
                        <h3 class="text-xl font-bold text-white mb-1">Exhaust Hood</h3>
                        <p class="text-steel-300 text-sm opacity-0 group-hover:opacity-100 transition-opacity duration-300 delay-100">Sistem sirkulasi udara asap dapur yang optimal.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="kontak" class="bg-steel-900 pt-20 border-t-4 border-accent relative overflow-hidden">
        <!-- Dekorasi Background -->
        <div class="absolute top-0 left-0 w-full h-full opacity-5 pointer-events-none">
            <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
                <defs>
                    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
                        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="white" stroke-width="1"/>
                    </pattern>
                </defs>
                <rect width="100%" height="100%" fill="url(#grid)" />
            </svg>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="bg-steel-800 rounded-2xl p-8 md:p-12 shadow-2xl mb-16 -mt-32 transform translate-y-16 border border-steel-700 flex flex-col md:flex-row items-center justify-between gap-8">
                <div>
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-2">Butuh Konsultasi Pembuatan Dapur?</h3>
                    <p class="text-steel-300">Tim ahli kami siap mendiskusikan spesifikasi, ukuran, dan penawaran harga terbaik untuk proyek Anda.</p>
                </div>
                <a href="https://wa.me/6280000000000" target="_blank" class="flex-shrink-0 bg-green-500 text-white px-8 py-4 rounded-md font-bold text-lg hover:bg-green-600 hover:shadow-lg hover:shadow-green-500/30 transition-all duration-300 flex items-center gap-3">
                    <i class="fa-brands fa-whatsapp text-2xl"></i> Hubungi WhatsApp
                </a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-12 gap-12 pb-12 pt-16">
                <!-- Info Perusahaan -->
                <div class="md:col-span-5">
                    <a href="#" class="text-2xl font-bold text-white tracking-wider flex items-center gap-2 mb-6">
                        <i class="fa-solid fa-fire-burner text-steel-400"></i>
                        ABSOLUTE <span class="font-light text-steel-400">STAINLESS</span>
                    </a>
                    <p class="text-steel-400 mb-6 leading-relaxed">
                        Produsen dan fabrikasi perlengkapan dapur komersial berbahan stainless steel. Memberikan kualitas pengerjaan terbaik untuk pelanggan di Klaten dan seluruh Indonesia.
                    </p>
                    <div class="flex space-x-4">
                        <a href="https://www.youtube.com/@AbsoluteKitchenStainless" target="_blank" class="w-10 h-10 rounded-full bg-steel-800 flex items-center justify-center text-steel-300 hover:bg-red-600 hover:text-white transition-colors title='YouTube'">
                            <i class="fa-brands fa-youtube text-lg"></i>
                        </a>
                        <a href="https://www.tiktok.com/@absolute_stainless" target="_blank" class="w-10 h-10 rounded-full bg-steel-800 flex items-center justify-center text-steel-300 hover:bg-black hover:text-white transition-colors title='TikTok'">
                            <i class="fa-brands fa-tiktok text-lg"></i>
                        </a>
                    </div>
                </div>

                <!-- Link Cepat -->
                <div class="md:col-span-3">
                    <h3 class="text-lg font-semibold text-white mb-6 uppercase tracking-wider">Navigasi</h3>
                    <ul class="space-y-3">
                        <li><a href="#beranda" class="text-steel-400 hover:text-accent transition-colors">Beranda</a></li>
                        <li><a href="#tentang" class="text-steel-400 hover:text-accent transition-colors">Tentang Kami</a></li>
                        <li><a href="#layanan" class="text-steel-400 hover:text-accent transition-colors">Layanan & Jasa</a></li>
                        <li><a href="#produk" class="text-steel-400 hover:text-accent transition-colors">Katalog Produk</a></li>
                    </ul>
                </div>

                <!-- Alamat & Kontak -->
                <div class="md:col-span-4">
                    <h3 class="text-lg font-semibold text-white mb-6 uppercase tracking-wider">Lokasi & Kontak</h3>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <i class="fa-solid fa-location-dot mt-1.5 mr-3 text-accent"></i>
                            <span class="text-steel-400 leading-relaxed">Jl. Raya Solo - Jogja,<br>Kabupaten Klaten,<br>Jawa Tengah, Indonesia</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa-solid fa-phone mr-3 text-accent"></i>
                            <span class="text-steel-400">Kontak via WhatsApp di atas</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa-solid fa-clock mr-3 text-accent"></i>
                            <span class="text-steel-400">Senin - Sabtu: Jam Kerja</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="py-6 border-t border-steel-800 text-center flex flex-col md:flex-row justify-between items-center">
                <p class="text-steel-500 text-sm mb-4 md:mb-0">
                    &copy; 2026 Absolute Kitchen Stainless Klaten. All rights reserved.
                </p>
                <p class="text-steel-600 text-sm">
                    Desain Profesional untuk Dapur Anda
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Efek Navbar transparan saat di atas, solid saat di-scroll
        const navbar = document.getElementById('navbar');
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('bg-steel-900', 'shadow-lg');
                navbar.classList.remove('bg-transparent', 'py-5');
                navbar.classList.add('py-3');
            } else {
                navbar.classList.add('bg-transparent', 'py-5');
                navbar.classList.remove('bg-steel-900', 'shadow-lg', 'py-3');
            }
        });

        // Fungsionalitas toggle menu pada mode mobile
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Menutup menu mobile ketika salah satu tautan diklik
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html># absolute-stainless-web
website and frontend application for Absolute Kitchen Stainless
