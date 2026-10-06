<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentinel Guard System | Integrated Security Solutions</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0B132B',
                            navy: '#1C2541',
                            teal: '#00A896',
                            cyan: '#02C39A',
                            lightBg: '#F4F7F9',
                            cardBg: '#1E293B'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-gradient {
            background: linear-gradient(135deg, rgba(11, 19, 43, 0.95) 0%, rgba(28, 37, 65, 0.90) 100%);
        }
        .glow-effect {
            box-shadow: 0 0 25px -5px rgba(2, 195, 154, 0.3);
        }
        .glow-effect-hover:hover {
            box-shadow: 0 0 30px 0px rgba(2, 195, 154, 0.5);
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 antialiased selection:bg-brand-teal selection:text-white pb-16 md:pb-0">

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-semibold text-xs md:text-sm py-2 px-4 text-center flex justify-between items-center max-w-7xl mx-auto rounded-b-lg">
        <div class="hidden sm:flex items-center gap-2">
            <i class="fa-solid fa-shield-halved"></i>
            <span>Securing Today, Protecting Tomorrow.</span>
        </div>
        <div class="mx-auto sm:mx-0 flex items-center gap-4">
            <a href="tel:09517656601" class="hover:underline flex items-center gap-1">
                <i class="fa-solid fa-phone"></i> 09517656601
            </a>
            <span class="text-slate-700">|</span>
            <a href="https://wa.me/639517656601" target="_blank" class="hover:underline flex items-center gap-1">
                <i class="fa-brands fa-whatsapp"></i> WhatsApp Ready
            </a>
        </div>
    </div>

    <!-- Main Navigation Bar -->
    <header class="sticky top-0 z-40 bg-brand-dark/90 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo with Image & Text -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="h-14 w-auto flex items-center justify-center p-1 bg-slate-800/80 rounded-xl border border-slate-700/80 group-hover:border-brand-cyan transition-all">
                    <img src="logo.png" alt="Sentinel Guard System Logo" class="h-12 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='logo.jpg';">
                </div>
                <div>
                    <span class="text-xl font-extrabold tracking-tight text-white block leading-tight group-hover:text-brand-cyan transition-colors">SENTINEL</span>
                    <span class="text-xs font-semibold tracking-wider text-brand-cyan block">GUARD SYSTEM</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden md:flex items-center gap-8 font-medium text-slate-300 text-sm">
                <a href="#packages" class="hover:text-brand-cyan transition-colors">CCTV Packages</a>
                <a href="#services" class="hover:text-brand-cyan transition-colors">Services</a>
                <a href="#hardware" class="hover:text-brand-cyan transition-colors">Equipment</a>
                <a href="#repair" class="hover:text-brand-cyan transition-colors">Repairs</a>
                <a href="#coverage" class="hover:text-brand-cyan transition-colors">Service Area</a>
            </nav>

            <!-- Header Action Button -->
            <div class="hidden lg:flex items-center gap-3">
                <button onclick="openModal()" class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-bold px-5 py-2.5 rounded-lg shadow-md hover:brightness-110 transition-all text-sm">
                    Inquire Now
                </button>
            </div>

            <!-- Mobile Menu Toggle Button -->
            <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white focus:outline-none p-2">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Dropdown Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-brand-navy border-b border-slate-800 px-6 py-4 space-y-3">
            <a href="#packages" class="block text-slate-200 hover:text-brand-cyan font-medium py-1">CCTV Packages</a>
            <a href="#services" class="block text-slate-200 hover:text-brand-cyan font-medium py-1">Services</a>
            <a href="#hardware" class="block text-slate-200 hover:text-brand-cyan font-medium py-1">Equipment Highlights</a>
            <a href="#repair" class="block text-slate-200 hover:text-brand-cyan font-medium py-1">Repairs & Deals</a>
            <a href="#coverage" class="block text-slate-200 hover:text-brand-cyan font-medium py-1">Service Coverage Area</a>
            <button onclick="openModal()" class="w-full mt-2 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-bold py-2.5 rounded-lg text-center">
                Get a Quote
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-brand-dark overflow-hidden py-16 md:py-24 border-b border-slate-800">
        <!-- Background Decorative Elements -->
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_top_right,rgba(2,195,154,0.12),transparent_50%)]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Text Column -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 bg-slate-800/80 border border-brand-teal/40 px-3 py-1.5 rounded-full text-brand-cyan text-xs font-semibold uppercase tracking-wider">
                        <i class="fa-solid fa-shield-check"></i> Integrated Security & Network Solutions
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-tight">
                        SENTINEL GUARD SYSTEM
                        <span class="block text-transparent bg-clip-text bg-gradient-to-r from-brand-teal to-brand-cyan">
                            INTEGRATED SOLUTIONS
                        </span>
                    </h1>
                    <p class="text-slate-300 text-lg md:text-xl max-w-2xl font-light leading-relaxed mx-auto lg:mx-0">
                        Securing Today, Protecting Tomorrow. Full-spectrum CCTV surveillance, network installations, access control, and complete repair services for homes & businesses.
                    </p>

                    <!-- Call To Action Buttons -->
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#packages" class="w-full sm:w-auto px-8 py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-extrabold rounded-xl shadow-lg hover:shadow-brand-teal/20 hover:scale-[1.02] transition-all text-center">
                            <i class="fa-solid fa-boxes-packing mr-2"></i> View CCTV Packages
                        </a>
                        <a href="tel:09517656601" class="w-full sm:w-auto px-8 py-4 bg-slate-800 hover:bg-slate-700 text-white font-bold rounded-xl border border-slate-700 transition-all text-center flex items-center justify-center gap-2">
                            <i class="fa-solid fa-phone text-brand-cyan"></i> Call 09517656601
                        </a>
                        <a href="https://wa.me/639517656601" target="_blank" class="w-full sm:w-auto px-5 py-4 bg-emerald-600 hover:bg-emerald-500 text-white font-bold rounded-xl transition-all text-center flex items-center justify-center gap-2">
                            <i class="fa-brands fa-whatsapp text-xl"></i> WhatsApp
                        </a>
                    </div>

                    <!-- Trust Indicators -->
                    <div class="pt-6 grid grid-cols-2 sm:grid-cols-4 gap-4 text-center border-t border-slate-800/80">
                        <div>
                            <p class="text-slate-400 text-xs uppercase font-medium">Trust</p>
                            <p class="text-slate-200 font-bold text-sm">Secure You Can Trust</p>
                        </div>
                        <div>
                            <p class="text-slate-400 text-xs uppercase font-medium">Service</p>
                            <p class="text-slate-200 font-bold text-sm">Service You Can Rely On</p>
                        </div>
                        <div>
                            <p class="text-slate-400 text-xs uppercase font-medium">Quality</p>
                            <p class="text-slate-200 font-bold text-sm">Quality You Can Count On</p>
                        </div>
                        <div>
                            <p class="text-slate-400 text-xs uppercase font-medium">Protection</p>
                            <p class="text-slate-200 font-bold text-sm">Protection You Deserve</p>
                        </div>
                    </div>
                </div>

                <!-- Right Feature Banner / Logo Showcase Card -->
                <div class="lg:col-span-5 space-y-6" id="repair">
                    <!-- High-Impact Logo Display Badge -->
                    <div class="bg-slate-800/60 p-4 rounded-2xl border border-slate-700/60 flex items-center justify-center backdrop-blur-sm">
                        <img src="logo.png" alt="Sentinel Guard System Security Camera Emblem" class="h-44 w-auto object-contain drop-shadow-2xl hover:scale-105 transition-transform duration-300" onerror="this.onerror=null; this.src='logo.jpg';">
                    </div>

                    <!-- Repair Special Box -->
                    <div class="bg-gradient-to-br from-brand-cardBg to-slate-800 p-6 rounded-2xl border border-slate-700 shadow-2xl relative overflow-hidden glow-effect">
                        <div class="absolute -top-10 -right-10 w-32 h-32 bg-brand-cyan/10 rounded-full blur-2xl"></div>
                        <div class="flex items-center gap-4 border-b border-slate-700 pb-4 mb-4">
                            <div class="w-14 h-14 bg-brand-teal/20 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold">
                                <i class="fa-solid fa-wrench"></i>
                            </div>
                            <div>
                                <span class="bg-amber-500/20 text-amber-300 text-xs font-bold px-2.5 py-0.5 rounded-full uppercase tracking-wide">Special Deal</span>
                                <h3 class="text-xl font-extrabold text-white">REPAIR SPECIAL</h3>
                            </div>
                        </div>
                        <p class="text-slate-300 font-medium text-sm mb-4">
                            Need fast troubleshooting or repairs for existing security systems?
                        </p>
                        <ul class="space-y-2.5 text-sm text-slate-300 mb-6">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> All Security System Repairs</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> Fast & Reliable Service for ALL Brands</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> On-site Inspection & Diagnostics</li>
                        </ul>
                        <button onclick="openModal('System Repair Inquiry')" class="w-full py-3 bg-brand-cyan text-slate-950 font-bold rounded-lg hover:bg-brand-teal transition-colors text-center block">
                            Book Repair Technician Now
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Special CCTV Camera Packages -->
    <section id="packages" class="py-20 bg-slate-950 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-cyan font-bold tracking-widest uppercase text-xs">Complete Security Packages</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">SPECIAL CCTV CAMERA PACKAGES</h2>
                <p class="text-slate-400 mt-3">All-in-one surveillance setups including HD cameras, high-capacity hard drives, professional installation, and mobile app setup.</p>
            </div>

            <!-- Package Cards Grid -->
            <div class="grid md:grid-cols-3 gap-8">
                
                <!-- 4 Channel Package -->
                <div class="bg-brand-cardBg rounded-2xl border border-slate-700 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 group">
                    <div class="bg-slate-800 p-6 border-b border-slate-700 text-center relative">
                        <span class="inline-block bg-slate-700 text-slate-200 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2">4ch Entry Package</span>
                        <h3 class="text-2xl font-black text-white">4 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">15,000</span>
                            <span class="text-slate-400 text-sm font-semibold ml-1">ONLY</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> CCTV Cameras (4x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>4-Channel DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>500GB HDD</strong> (included)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>80 Meters RG6 Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openModal('4 Channel Package - ₱15,000')" class="w-full py-3 bg-slate-800 hover:bg-brand-teal hover:text-slate-950 font-bold rounded-xl border border-slate-600 transition-all text-center">
                            Select 4 Channel Package
                        </button>
                    </div>
                </div>

                <!-- 8 Channel Package (Featured) -->
                <div class="bg-brand-cardBg rounded-2xl border-2 border-brand-cyan overflow-hidden flex flex-col shadow-2xl relative scale-100 lg:scale-105 z-10">
                    <div class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 text-xs font-black uppercase tracking-widest text-center py-1.5">
                        Most Popular Choice
                    </div>
                    <div class="bg-slate-800/90 p-6 border-b border-slate-700 text-center relative">
                        <span class="inline-block bg-brand-cyan/20 text-brand-cyan text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2">8ch Recommended</span>
                        <h3 class="text-2xl font-black text-white">8 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">26,900</span>
                            <span class="text-slate-400 text-sm font-semibold ml-1">ONLY</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> CCTV Cameras (8x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>8-Channel DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> (included)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>160 Meters RG6 Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openModal('8 Channel Package - ₱26,900')" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-center">
                            Select 8 Channel Package
                        </button>
                    </div>
                </div>

                <!-- 16 Channel Package -->
                <div class="bg-brand-cardBg rounded-2xl border border-slate-700 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 group">
                    <div class="bg-slate-800 p-6 border-b border-slate-700 text-center relative">
                        <span class="inline-block bg-slate-700 text-slate-200 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2">16ch Enterprise</span>
                        <h3 class="text-2xl font-black text-white">16 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">52,900</span>
                            <span class="text-slate-400 text-sm font-semibold ml-1">ONLY</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> CCTV Cameras (16x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>16-Channel DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> (included)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>320 Meters RG6 Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openModal('16 Channel Package - ₱52,900')" class="w-full py-3 bg-slate-800 hover:bg-brand-teal hover:text-slate-950 font-bold rounded-xl border border-slate-600 transition-all text-center">
                            Select 16 Channel Package
                        </button>
                    </div>
                </div>

            </div>

            <!-- Included Features Banner -->
            <div class="mt-12 bg-slate-900 border border-slate-800 rounded-xl p-6 grid grid-cols-2 md:grid-cols-5 gap-4 text-center">
                <div class="p-2">
                    <i class="fa-solid fa-hard-drive text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-bold text-white uppercase">1TB / 500GB HDD</p>
                    <p class="text-[10px] text-slate-400">Included per package</p>
                </div>
                <div class="p-2">
                    <i class="fa-solid fa-camera text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-bold text-white uppercase">HD Cameras</p>
                    <p class="text-[10px] text-slate-400">Crystal Clear Night/Day</p>
                </div>
                <div class="p-2">
                    <i class="fa-solid fa-ethernet text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-bold text-white uppercase">RG6 Cable</p>
                    <p class="text-[10px] text-slate-400">Specific lengths per set</p>
                </div>
                <div class="p-2">
                    <i class="fa-solid fa-user-gear text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-bold text-white uppercase">Pro Installation</p>
                    <p class="text-[10px] text-slate-400">Neat and tested setup</p>
                </div>
                <div class="p-2 col-span-2 md:col-span-1">
                    <i class="fa-solid fa-mobile-signal text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-bold text-white uppercase">Remote Mobile App</p>
                    <p class="text-[10px] text-slate-400">Live view anywhere</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Services Section -->
    <section id="services" class="py-20 bg-brand-dark border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-cyan font-bold tracking-widest uppercase text-xs">Comprehensive Capabilities</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">OUR SERVICES</h2>
                <p class="text-slate-400 mt-3">From security systems to enterprise cabling, we provide full end-to-end integration for commercial and residential applications.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- Service 1 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">CCTV Surveillance Systems</h3>
                    <p class="text-slate-400 text-sm">Design, installation, and monitoring configurations tailored for complete property coverage.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-wifi"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">WiFi & LAN Network Installation</h3>
                    <p class="text-slate-400 text-sm">Fast, stable, and secure internet and local network architecture for homes and businesses.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-sitemap"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Structured Cabling Solutions</h3>
                    <p class="text-slate-400 text-sm">Neat, organized, and optimized network cabling for maximum data performance.</p>
                </div>

                <!-- Service 4 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-road-barrier"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Gate Barrier & Vehicle Access</h3>
                    <p class="text-slate-400 text-sm">Smart controlled vehicle access systems for residential subdivisions and commercial centers.</p>
                </div>

                <!-- Service 5 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-door-closed"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Access Control & Door Entry</h3>
                    <p class="text-slate-400 text-sm">Biometric readers, keypads, RFID card access, and smart door security.</p>
                </div>

                <!-- Service 6 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-solar-panel"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Solar Power Systems</h3>
                    <p class="text-slate-400 text-sm">Reliable off-grid and grid-tied solar energy setups for continuous power.</p>
                </div>

                <!-- Service 7 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-server"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Server & Network Infrastructure</h3>
                    <p class="text-slate-400 text-sm">Rack setup, switches, routers, multi-WAN load balancing, and firewall deployment.</p>
                </div>

                <!-- Service 8 -->
                <div class="bg-brand-cardBg p-6 rounded-xl border border-slate-800 hover:border-brand-teal transition-all">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-lg flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Technical Support & Maintenance</h3>
                    <p class="text-slate-400 text-sm">Routine preventative maintenance, troubleshooting, hardware upgrades, and emergency repair.</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Hardware & Equipment Showcase -->
    <section id="hardware" class="py-20 bg-slate-950 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-cyan font-bold tracking-widest uppercase text-xs">Quality Hardware</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">HARDWARE & EQUIPMENT HIGHLIGHTS</h2>
                <p class="text-slate-400 mt-3">We supply and deploy industry-grade hardware from leading brands.</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6">
                
                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-box text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">NVR - Network Video Recorder</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-video text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Bullet & Dome Cameras</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-network-wired text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">PoE Switches</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-desktop text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Security Monitors</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-torii-gate text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Gate Barrier Systems</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-keyboard text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Intercom & Keypads</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-lock text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Smart Locks</h4>
                </div>

                <div class="bg-brand-cardBg/60 p-5 rounded-xl border border-slate-800 text-center hover:bg-brand-cardBg transition-colors">
                    <i class="fa-solid fa-wifi text-3xl text-brand-cyan mb-3"></i>
                    <h4 class="font-bold text-white text-sm">Network Routers & Wi-Fi APs</h4>
                </div>

            </div>
        </div>
    </section>

    <!-- Service Coverage & Contact Section -->
    <section id="coverage" class="py-20 bg-brand-dark border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-12">
                
                <!-- Left Column: Service Area & Info -->
                <div class="lg:col-span-6 space-y-6">
                    <span class="text-brand-cyan font-bold tracking-widest uppercase text-xs">Reach & Location</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-white">SERVICE COVERAGE AREA</h2>
                    
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-700 space-y-4">
                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 bg-brand-teal/20 text-brand-cyan rounded-lg flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-lg">Primary Service Coverage</h4>
                                <p class="text-slate-300 text-base mt-1">
                                    Olongapo City, Subic Bay Freeport Zone, Zambales, Bataan (and nearby provinces).
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Direct Contact Card -->
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-700 space-y-4">
                        <h4 class="font-bold text-white text-lg border-b border-slate-700 pb-2">Direct Lines</h4>
                        <div class="space-y-3">
                            <a href="tel:09517656601" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors">
                                <i class="fa-solid fa-phone text-brand-cyan text-xl w-6"></i>
                                <span class="font-bold text-lg">09517656601</span>
                            </a>
                            <a href="https://wa.me/639517656601" target="_blank" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors">
                                <i class="fa-brands fa-whatsapp text-emerald-400 text-xl w-6"></i>
                                <span class="font-bold text-lg">WhatsApp Ready (09517656601)</span>
                            </a>
                            <a href="mailto:sentinelguardsystem@gmail.com" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors">
                                <i class="fa-solid fa-envelope text-brand-cyan text-xl w-6"></i>
                                <span class="font-medium text-sm sm:text-base">sentinelguardsystem@gmail.com</span>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Interactive Inquiry Form -->
                <div class="lg:col-span-6 bg-brand-cardBg p-8 rounded-2xl border border-slate-700">
                    <h3 class="text-2xl font-bold text-white mb-2">Send an Inquiry</h3>
                    <p class="text-slate-400 text-sm mb-6">Fill out the form below for a free estimate or service booking.</p>
                    
                    <form onsubmit="handleFormSubmit(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Full Name</label>
                            <input type="text" required placeholder="John Doe" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-brand-cyan">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Phone Number</label>
                                <input type="tel" required placeholder="09123456789" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-brand-cyan">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Location / City</label>
                                <input type="text" required placeholder="Olongapo City" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-brand-cyan">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Service Required</label>
                            <select class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-brand-cyan">
                                <option>CCTV 4 Channel Package</option>
                                <option>CCTV 8 Channel Package</option>
                                <option>CCTV 16 Channel Package</option>
                                <option>Security System Repair / Maintenance</option>
                                <option>WiFi & Network Installation</option>
                                <option>Access Control & Door Entry</option>
                                <option>Solar Power System</option>
                                <option>Other / Customized Solution</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Message / Project Details</label>
                            <textarea rows="3" placeholder="Tell us about your setup requirements..." class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-brand-cyan"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-bold rounded-lg hover:brightness-110 transition-all">
                            Submit Inquiry
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-slate-950 text-slate-500 py-10 border-t border-slate-800 text-xs text-center">
        <div class="max-w-7xl mx-auto px-4 flex flex-col items-center justify-center space-y-4">
            <!-- Footer Logo Image -->
            <img src="logo.png" alt="Sentinel Guard System Logo" class="h-16 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='logo.jpg';">
            <div>
                <p class="text-slate-300 font-bold text-sm tracking-wider">SENTINEL GUARD SYSTEM - INTEGRATED SOLUTIONS</p>
                <p class="text-slate-400 mt-1">Securing Today, Protecting Tomorrow. &copy; 2026. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Mobile Bottom Quick Call Bar -->
    <div class="fixed bottom-0 inset-x-0 bg-brand-dark/95 border-t border-slate-800 p-3 flex md:hidden gap-2 z-40 backdrop-blur-md">
        <a href="tel:09517656601" class="flex-1 bg-brand-cyan text-slate-950 text-center font-bold py-2.5 rounded-lg flex items-center justify-center gap-2 text-sm">
            <i class="fa-solid fa-phone"></i> Call Now
        </a>
        <a href="https://wa.me/639517656601" target="_blank" class="flex-1 bg-emerald-600 text-white text-center font-bold py-2.5 rounded-lg flex items-center justify-center gap-2 text-sm">
            <i class="fa-brands fa-whatsapp text-lg"></i> WhatsApp
        </a>
    </div>

    <!-- Inquiry Modal -->
    <div id="inquiryModal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-brand-cardBg border border-slate-700 rounded-2xl max-w-lg w-full p-6 relative">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white">
                <i class="fa-solid fa-xmark text-xl"></i>
            </button>
            <h3 id="modalTitle" class="text-xl font-bold text-white mb-2">Request Information</h3>
            <p class="text-xs text-slate-400 mb-4">Leave your details and our technical team will contact you shortly.</p>
            <form onsubmit="handleModalSubmit(event)" class="space-y-3">
                <input type="text" required placeholder="Your Name" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-white text-sm">
                <input type="tel" required placeholder="Phone Number" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-white text-sm">
                <textarea rows="3" placeholder="Additional details..." class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-white text-sm"></textarea>
                <button type="submit" class="w-full py-2.5 bg-brand-cyan text-slate-950 font-bold rounded-lg hover:bg-brand-teal transition-colors text-sm">
                    Send Request
                </button>
            </form>
        </div>
    </div>

    <script>
        // Mobile Navigation Toggle
        const mobileBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        mobileBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Modal Functionality
        const modal = document.getElementById('inquiryModal');
        const modalTitle = document.getElementById('modalTitle');

        function openModal(title = 'Inquire Now') {
            modalTitle.innerText = title;
            modal.classList.remove('hidden');
        }

        function closeModal() {
            modal.classList.add('hidden');
        }

        function handleFormSubmit(e) {
            e.preventDefault();
            // Custom modal replacement for alert
            const banner = document.createElement('div');
            banner.className = 'fixed top-6 right-6 bg-emerald-500 text-slate-950 p-4 rounded-xl font-bold shadow-2xl z-50 animate-bounce';
            banner.innerHTML = '<i class="fa-solid fa-circle-check mr-2"></i> Thank you! Inquiry submitted successfully.';
            document.body.appendChild(banner);
            setTimeout(() => banner.remove(), 4000);
            e.target.reset();
        }

        function handleModalSubmit(e) {
            e.preventDefault();
            closeModal();
            const banner = document.createElement('div');
            banner.className = 'fixed top-6 right-6 bg-emerald-500 text-slate-950 p-4 rounded-xl font-bold shadow-2xl z-50 animate-bounce';
            banner.innerHTML = '<i class="fa-solid fa-circle-check mr-2"></i> Request submitted! We will contact you soon.';
            document.body.appendChild(banner);
            setTimeout(() => banner.remove(), 4000);
            e.target.reset();
        }
    </script>
</body>
</html>
