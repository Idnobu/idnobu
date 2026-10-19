
```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FRAGRANCE HOME AND PROPERTY | Luxury Real Estate</title>
    
    <!-- Google Fonts: Playfair Display (Serif) & Montserrat (Sans-serif) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;300;400;500&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: {
                            light: '#f9ecd3',
                            DEFAULT: '#d4af37', // Classic metallic gold
                            dark: '#aa8c2c',
                        },
                        dark: {
                            100: '#2a2a2a',
                            200: '#1a1a1a',
                            300: '#0f0f0f', // Near black
                        }
                    },
                    fontFamily: {
                        serif: ['"Playfair Display"', 'serif'],
                        sans: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    
    <style>
        /* Custom Styles for extra luxury feel */
        body {
            background-color: #0f0f0f;
            color: #ffffff;
        }
        
        .hero-overlay {
            background: linear-gradient(to bottom, rgba(15,15,15,0.3) 0%, rgba(15,15,15,0.8) 100%);
        }

        .gold-gradient-text {
            background: linear-gradient(to right, #bf953f, #fcf6ba, #b38728, #fbf5b7, #aa771c);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        /* Subtle image zoom on hover */
        .property-card:hover .property-image {
            transform: scale(1.05);
        }
        .property-image {
            transition: transform 0.7s ease;
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-300">

    <!-- Header / Navigation -->
    <header class="fixed w-full z-50 transition-all duration-300 bg-dark-300/90 backdrop-blur-md border-b border-white/5">
        <div class="max-w-screen-2xl mx-auto px-6 lg:px-12">
            <div class="flex justify-between items-center h-24">
                
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center cursor-pointer">
                    <span class="font-serif text-xl md:text-2xl tracking-widest text-white uppercase">
                        Fragrance <span class="text-gold">Home</span><br>
                        <span class="text-xs tracking-[0.3em] text-gray-400 font-sans block mt-1">And Property</span>
                    </span>
                </div>
                
                <!-- Desktop Navigation -->
                <nav class="hidden lg:flex space-x-10 items-center">
                    <a href="#home" class="text-sm tracking-widest uppercase hover:text-gold transition-colors duration-300">Home</a>
                    <a href="#about" class="text-sm tracking-widest uppercase hover:text-gold transition-colors duration-300">The Vision</a>
                    <a href="#collection" class="text-sm tracking-widest uppercase hover:text-gold transition-colors duration-300">Collection</a>
                    <a href="#contact" class="text-sm tracking-widest uppercase hover:text-gold transition-colors duration-300">Contact</a>
                </nav>

                <!-- Dedicated Concierge Number in Header -->
                <div class="hidden lg:flex items-center border border-gold/40 px-5 py-2 hover:bg-gold hover:text-dark-300 transition-all duration-500 cursor-pointer">
                    <i class="fas fa-phone-alt text-sm mr-3"></i>
                    <a href="tel:+2347034504545" class="text-sm tracking-wider font-medium">+234 703 450 4545</a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="lg:hidden flex items-center">
                    <button class="text-gold focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative h-screen flex items-center justify-center overflow-hidden">
        <!-- High-end luxury mansion placeholder -->
        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1613490908578-19c351f042e6?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80')] bg-cover bg-center"></div>
        <div class="absolute inset-0 hero-overlay"></div>
        
        <div class="relative z-10 text-center px-4 max-w-5xl mx-auto mt-20">
            <p class="font-sans text-gold tracking-[0.4em] uppercase text-xs md:text-sm mb-6">Exclusivity Awaits</p>
            <h1 class="font-serif text-5xl md:text-7xl lg:text-8xl text-white font-light leading-tight mb-8">
                Discover Unparalleled <br> <span class="italic text-gold">Luxury Living</span>
            </h1>
            <p class="font-sans text-gray-300 text-lg md:text-xl font-light mb-12 max-w-2xl mx-auto">
                Curating the most prestigious real estate portfolio for the world's most discerning clientele.
            </p>
            <div class="flex flex-col sm:flex-row gap-6 justify-center">
                <a href="#collection" class="bg-gold text-dark-300 px-8 py-4 text-sm tracking-widest uppercase hover:bg-white transition-colors duration-500">
                    Explore Collection
                </a>
                <a href="#contact" class="border border-white text-white px-8 py-4 text-sm tracking-widest uppercase hover:border-gold hover:text-gold transition-colors duration-500">
                    Private Consultation
                </a>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-24 lg:py-32 bg-dark-300 relative">
        <div class="max-w-screen-2xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
                <div class="relative">
                    <!-- Decorative Gold Frame -->
                    <div class="absolute -inset-4 border border-gold/30 -z-10 hidden md:block"></div>
                    <img src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80" alt="Luxury Interior" class="w-full h-auto object-cover grayscale hover:grayscale-0 transition duration-700">
                </div>
                
                <div class="pl-0 lg:pl-12">
                    <h4 class="text-gold tracking-[0.3em] uppercase text-xs mb-4">The Vision</h4>
                    <h2 class="font-serif text-4xl md:text-5xl text-white mb-8">Redefining the Art of Real Estate.</h2>
                    <p class="font-light text-gray-400 leading-relaxed mb-6">
                        FRAGRANCE HOME AND PROPERTY represents the pinnacle of luxury real estate. We do not merely sell houses; we curate lifestyles. Our bespoke approach ensures that every estate, penthouse, and modern architectural masterpiece in our portfolio meets an exacting standard of excellence.
                    </p>
                    <p class="font-light text-gray-400 leading-relaxed mb-10">
                        With an unwavering commitment to discretion, integrity, and exceptional service, our private client advisors orchestrate seamless transactions for individuals who demand nothing but the absolute best.
                    </p>
                    
                    <!-- Signature / Sign-off -->
                    <div class="flex items-center">
                        <div class="w-12 h-[1px] bg-gold mr-4"></div>
                        <span class="font-serif italic text-xl text-white">Fragrance Management</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Luxury Properties -->
    <section id="collection" class="py-24 lg:py-32 bg-dark-200">
        <div class="max-w-screen-2xl mx-auto px-6 lg:px-12">
            
            <div class="flex flex-col md:flex-row justify-between items-end mb-16">
                <div>
                    <h4 class="text-gold tracking-[0.3em] uppercase text-xs mb-4">Curated Portfolio</h4>
                    <h2 class="font-serif text-4xl md:text-5xl text-white">Featured Estates</h2>
                </div>
                <div class="mt-6 md:mt-0">
                    <a href="#" class="text-sm uppercase tracking-widest text-gray-400 hover:text-gold transition-colors flex items-center">
                        View Complete Collection <i class="fas fa-long-arrow-alt-right ml-3"></i>
                    </a>
                </div>
            </div>

            <!-- Properties Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                
                <!-- Property 1 -->
                <div class="property-card group cursor-pointer bg-dark-300 border border-white/5 hover:border-gold/30 transition-colors duration-500">
                    <div class="relative overflow-hidden h-80">
                        <img src="https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?ixlib=rb-4.0.3&auto=format&fit=crop&w=2075&q=80" alt="Mansion 1" class="property-image w-full h-full object-cover">
                        <div class="absolute top-5 right-5 bg-dark-300/80 backdrop-blur text-gold text-xs tracking-widest uppercase px-3 py-1 border border-gold/50">
                            Available
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="font-serif text-2xl text-white mb-2 group-hover:text-gold transition-colors duration-300">The Sapphire Residence</h3>
                        <p class="text-sm text-gray-500 font-light mb-6 tracking-wide">Bana Island, Lagos</p>
                        
                        <div class="flex justify-between items-center border-t border-white/10 pt-6">
                            <div class="text-white font-medium tracking-wider">Price upon request</div>
                            <div class="flex space-x-4 text-gray-400 text-sm">
                                <span title="Bedrooms">6 <i class="fas fa-bed text-gold/70 ml-1"></i></span>
                                <span title="Bathrooms">8 <i class="fas fa-bath text-gold/70 ml-1"></i></span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Property 2 -->
                <div class="property-card group cursor-pointer bg-dark-300 border border-white/5 hover:border-gold/30 transition-colors duration-500">
                    <div class="relative overflow-hidden h-80">
                        <img src="https://images.unsplash.com/photo-1613545325278-f24b0cae1224?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80" alt="Modern Villa" class="property-image w-full h-full object-cover">
                        <div class="absolute top-5 right-5 bg-dark-300/80 backdrop-blur text-white text-xs tracking-widest uppercase px-3 py-1 border border-white/50">
                            Off-Market
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="font-serif text-2xl text-white mb-2 group-hover:text-gold transition-colors duration-300">Aura Penthouse</h3>
                        <p class="text-sm text-gray-500 font-light mb-6 tracking-wide">Victoria Island, Lagos</p>
                        
                        <div class="flex justify-between items-center border-t border-white/10 pt-6">
                            <div class="text-white font-medium tracking-wider">Price upon request</div>
                            <div class="flex space-x-4 text-gray-400 text-sm">
                                <span title="Bedrooms">4 <i class="fas fa-bed text-gold/70 ml-1"></i></span>
                                <span title="Bathrooms">4.5 <i class="fas fa-bath text-gold/70 ml-1"></i></span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Property 3 -->
                <div class="property-card group cursor-pointer bg-dark-300 border border-white/5 hover:border-gold/30 transition-colors duration-500">
                    <div class="relative overflow-hidden h-80">
                        <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80" alt="Luxury Estate" class="property-image w-full h-full object-cover">
                        <div class="absolute top-5 right-5 bg-dark-300/80 backdrop-blur text-gold text-xs tracking-widest uppercase px-3 py-1 border border-gold/50">
                            Available
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="font-serif text-2xl text-white mb-2 group-hover:text-gold transition-colors duration-300">The Crown Estate</h3>
                        <p class="text-sm text-gray-500 font-light mb-6 tracking-wide">Maitama, Abuja</p>
                        
                        <div class="flex justify-between items-center border-t border-white/10 pt-6">
                            <div class="text-white font-medium tracking-wider">Price upon request</div>
                            <div class="flex space-x-4 text-gray-400 text-sm">
                                <span title="Bedrooms">8 <i class="fas fa-bed text-gold/70 ml-1"></i></span>
                                <span title="Bathrooms">10 <i class="fas fa-bath text-gold/70 ml-1"></i></span>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Elite Call to Action (Customer Service Prominence) -->
    <section class="py-24 bg-dark-300 border-y border-white/5 relative overflow-hidden text-center">
        <!-- Subtle background texture or gradient -->
        <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-gold/10 via-dark-300 to-dark-300"></div>
        
        <div class="relative z-10 max-w-4xl mx-auto px-6">
            <i class="fas fa-gem text-3xl text-gold mb-6"></i>
            <h2 class="font-serif text-4xl md:text-5xl text-white mb-6">Private Client Advisory</h2>
            <p class="text-gray-400 font-light text-lg mb-10 max-w-2xl mx-auto">
                For exclusive viewings, off-market opportunities, or to list your distinguished property with us, connect with our dedicated concierge directly.
            </p>
            
            <a href="tel:+2347034504545" class="inline-flex flex-col items-center justify-center p-8 border border-gold/30 bg-dark-200/50 hover:bg-gold/10 transition-colors duration-500 min-w-[300px]">
                <span class="text-gold tracking-[0.2em] uppercase text-xs mb-3">Direct Line</span>
                <span class="text-4xl md:text-5xl font-light text-white tracking-widest">+234 703 450 4545</span>
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-dark-300 pt-24 pb-10 border-t border-white/5">
        <div class="max-w-screen-2xl mx-auto px-6 lg:px-12">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-16 mb-16">
                
                <!-- Brand Column -->
                <div class="lg:col-span-1">
                    <span class="font-serif text-xl tracking-widest text-white uppercase mb-6 block">
                        Fragrance <span class="text-gold">Home</span><br>
                        <span class="text-xs tracking-[0.3em] text-gray-500 font-sans block mt-1">And Property</span>
                    </span>
                    <p class="text-sm text-gray-500 font-light leading-relaxed mb-8">
                        The ultimate destination for luxury real estate and exclusive properties worldwide.
                    </p>
                </div>

                <!-- Contact Info -->
                <div>
                    <h4 class="text-white text-xs tracking-[0.2em] uppercase mb-6 border-b border-white/10 pb-4 inline-block">Contact</h4>
                    <ul class="space-y-4 text-sm font-light text-gray-400">
                        <li>
                            <a href="tel:+2347034504545" class="hover:text-gold transition-colors flex items-center">
                                <i class="fas fa-phone-alt w-6 text-gold/70"></i> +234 703 450 4545
                            </a>
                        </li>
                        <li>
                            <a href="mailto:concierge@fragrancehome.com" class="hover:text-gold transition-colors flex items-center">
                                <i class="fas fa-envelope w-6 text-gold/70"></i> concierge@fragrancehome.com
                            </a>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt w-6 text-gold/70 mt-1"></i>
                            <span>The Apex Tower, Penthouse Level<br>Victoria Island, Lagos</span>
                        </li>
                    </ul>
                </div>

                <!-- Navigation -->
                <div>
                    <h4 class="text-white text-xs tracking-[0.2em] uppercase mb-6 border-b border-white/10 pb-4 inline-block">Explore</h4>
                    <ul class="space-y-3 text-sm font-light text-gray-400">
                        <li><a href="#home" class="hover:text-gold transition-colors">Home</a></li>
                        <li><a href="#about" class="hover:text-gold transition-colors">The Vision</a></li>
                        <li><a href="#collection" class="hover:text-gold transition-colors">Exclusive Portfolio</a></li>
                        <li><a href="#" class="hover:text-gold transition-colors">Sell Your Property</a></li>
                    </ul>
                </div>

                <!-- Newsletter -->
                <div>
                    <h4 class="text-white text-xs tracking-[0.2em] uppercase mb-6 border-b border-white/10 pb-4 inline-block">The Insider</h4>
                    <p class="text-sm text-gray-500 font-light leading-relaxed mb-4">
                        Subscribe to receive exclusive off-market listings and luxury lifestyle insights.
                    </p>
                    <form class="flex">
                        <input type="email" placeholder="Email Address" class="bg-transparent border border-white/20 text-white text-sm px-4 py-3 w-full focus:outline-none focus:border-gold transition-colors">
                        <button type="button" class="bg-gold text-dark-300 px-4 py-3 hover:bg-white transition-colors">
                            <i class="fas fa-arrow-right"></i>
                        </button>
                    </form>
                    
                    <!-- Social Links -->
                    <div class="flex space-x-5 mt-8">
                        <a href="#" class="text-gray-500 hover:text-gold transition-colors"><i class="fab fa-instagram text-lg"></i></