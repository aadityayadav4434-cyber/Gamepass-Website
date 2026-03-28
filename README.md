# Gamepass-Website
Selling Gamepass or Buying
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GamePass Store - Buy Premium GamePasses</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            animation: whatsapp-bounce 2s infinite;
        }
        .whatsapp-float:hover {
            background-color: #128c7e;
            transform: scale(1.1);
        }
        @keyframes whatsapp-bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        .gamepass-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body class="bg-gradient-to-br from-purple-900 via-blue-900 to-indigo-900 min-h-screen text-white">

    <!-- Header -->
    <header class="bg-black/50 backdrop-blur-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-3xl font-bold bg-gradient-to-r from-purple-400 to-pink-400 bg-clip-text text-transparent">
                🎮 GamePass Store
            </div>
            <div class="hidden md:flex space-x-6">
                <a href="#home" class="hover:text-purple-400 transition">Home</a>
                <a href="#gamepasses" class="hover:text-purple-400 transition">GamePasses</a>
                <a href="#contact" class="hover:text-purple-400 transition">Contact</a>
            </div>
            <div class="md:hidden">
                <i class="fas fa-bars text-2xl cursor-pointer"></i>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="pt-20 pb-32">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-5xl md:text-7xl font-bold mb-8 bg-gradient-to-r from-purple-400 via-pink-400 to-blue-400 bg-clip-text text-transparent">
                Premium GamePasses
            </h1>
            <p class="text-xl md:text-2xl mb-12 max-w-3xl mx-auto opacity-90">
                Get instant access to exclusive gamepasses! Safe, fast, and secure. 
                Message us on WhatsApp to buy now!
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                <a href="https://wa.me/919817826490?text=Hi!%20I%20want%20to%20buy%20a%20GamePass%20🚀" 
                   class="bg-green-500 hover:bg-green-600 text-white px-12 py-4 rounded-full text-xl font-semibold transition-all duration-300 transform hover:scale-105 shadow-2xl" 
                   target="_blank">
                    <i class="fab fa-whatsapp mr-2"></i>Buy Now on WhatsApp
                </a>
                <a href="#gamepasses" class="border-2 border-purple-400 hover:bg-purple-500 text-purple-400 hover:text-white px-12 py-4 rounded-full text-xl font-semibold transition-all duration-300">
                    View GamePasses
                </a>
            </div>
        </div>
    </section>

    <!-- GamePasses Section -->
    <section id="gamepasses" class="py-32 bg-black/30">
        <div class="container mx-auto px-6">
            <div class="text-center mb-20">
                <h2 class="text-4xl md:text-6xl font-bold mb-6 bg-gradient-to-r from-yellow-400 to-orange-500 bg-clip-text text-transparent">
                    🔥 Hot GamePasses
                </h2>
                <p class="text-xl opacity-90 max-w-2xl mx-auto">
                    Choose your favorite gamepass and message us instantly!
                </p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
                <!-- GamePass 1 -->
                <div class="gamepass-card bg-gradient-to-br from-purple-600/80 to-blue-600/80 backdrop-blur-xl rounded-3xl p-8 border border-white/20 hover:border-purple-400 transition-all duration-500 cursor-pointer group" onclick="buyGamepass('VIP Pass')">
                    <div class="text-5xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-crown"></i>
                    </div>
                    <h3 class="text-3xl font-bold mb-4 bg-gradient-to-r from-yellow-400 to-orange-400 bg-clip-text text-transparent">VIP Pass</h3>
                    <div class="space-y-2 mb-8">
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Speed Boost</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Exclusive Items</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">VIP Chat</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                    </div>
                    <div class="text-4xl font-bold text-center mb-6 bg-gradient-to-r from-yellow-400 to-orange-400 bg-clip-text text-transparent">
                        ₹299
                    </div>
                    <a href="https://wa.me/919817826490?text=Hi!%20I%20want%20to%20buy%20VIP%20Pass%20for%20₹299%20🚀" target="_blank" 
                       class="w-full bg-gradient-to-r from-yellow-500 to-orange-500 hover:from-yellow-600 hover:to-orange-600 text-white py-4 px-8 rounded-2xl font-bold text-lg transition-all duration-300 block text-center">
                        Buy on WhatsApp
                    </a>
                </div>

                <!-- GamePass 2 -->
                <div class="gamepass-card bg-gradient-to-br from-pink-600/80 to-purple-600/80 backdrop-blur-xl rounded-3xl p-8 border border-white/20 hover:border-pink-400 transition-all duration-500 cursor-pointer group" onclick="buyGamepass('God Mode')">
                    <div class="text-5xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-god-mode"></i>
                    </div>
                    <h3 class="text-3xl font-bold mb-4 bg-gradient-to-r from-pink-400 to-purple-400 bg-clip-text text-transparent">God Mode</h3>
                    <div class="space-y-2 mb-8">
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Invincibility</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Infinite Resources</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Fly Mode</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                    </div>
                    <div class="text-4xl font-bold text-center mb-6 bg-gradient-to-r from-pink-400 to-purple-400 bg-clip-text text-transparent">
                        ₹499
                    </div>
                    <a href="https://wa.me/919817826490?text=Hi!%20I%20want%20to%20buy%20God%20Mode%20for%20₹499%20🔥" target="_blank" 
                       class="w-full bg-gradient-to-r from-pink-500 to-purple-500 hover:from-pink-600 hover:to-purple-600 text-white py-4 px-8 rounded-2xl font-bold text-lg transition-all duration-300 block text-center">
                        Buy on WhatsApp
                    </a>
                </div>

                <!-- GamePass 3 -->
                <div class="gamepass-card bg-gradient-to-br from-emerald-600/80 to-teal-600/80 backdrop-blur-xl rounded-3xl p-8 border border-white/20 hover:border-emerald-400 transition-all duration-500 cursor-pointer group" onclick="buyGamepass('Ultimate Pack')">
                    <div class="text-5xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fas fa-gem"></i>
                    </div>
                    <h3 class="text-3xl font-bold mb-4 bg-gradient-to-r from-emerald-400 to-teal-400 bg-clip-text text-transparent">Ultimate Pack</h3>
                    <div class="space-y-2 mb-8">
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">All Features</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Lifetime Access</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-lg opacity-75">Priority Support</span>
                            <i class="fas fa-check text-green-400"></i>
                        </div>
                    </div>
                    <div class="text-4xl font-bold text-center mb-6 bg-gradient-to-r from-emerald-400 to-teal-400 bg-clip-text text-transparent">
                        ₹999
                    </div>
                    <a href="https://wa.me/919817826490?text=Hi!%20I%20want%20to%20buy%20Ultimate%20Pack%20for%20₹999%20💎" target="_blank" 
                       class="w-full bg-gradient-to-r from-emerald-500 to-teal-500 hover:from-emerald-600 hover:to-teal-600 text-white py-4 px-8 rounded-2xl font-bold text-lg transition-all duration-300 block text-center">
                        Buy on WhatsApp
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-32 bg-black/50">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-4xl md:text-6xl font-bold mb-8 bg-gradient-to-r from-green-400 to-blue-400 bg-clip-text text-transparent">
                Ready to Buy?
            </h2>
            <p class="text-xl mb-12 opacity-90 max-w-2xl mx-auto">
                Message us instantly on WhatsApp! We respond within 2 minutes 🚀
            </p>
            <div class="bg-gradient-to-r from-green-600/80 to-blue-600/80 backdrop-blur-xl rounded-3xl p-12 max-w-4xl mx-auto border border-white/20">
                <div class="text-6xl mb-8">
                    <i class="fab fa-whatsapp"></i>
                </div>
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h3 class="text-3xl font-bold mb-4">📱 WhatsApp Support</h3>
                        <p class="text-2xl font-semibold mb-6">+91 98178 26490</p>
                        <ul class="text-lg space-y-2 opacity-90">
                            <li><i class="fas fa-clock mr-2 text-green-400"></i>Instant Response</li>
                            <li><i class="fas fa-shield-alt mr-2 text-green-400"></i>100% Safe Payment</li>
                            <li><i class="fas fa-bolt mr-2 text-green-400"></i>Instant Delivery</li>
                        </ul>
                    </div>
                    <a href="https://wa.me/919817826490?text=Hello!%20I'm%20interested%20in%20GamePasses%20🎮" 
                       class="bg-gradient-to-r from-green-500 to-green-600 hover:from-green-600 hover:to-green-700 text-white text-2xl font-bold py-8 px-12 rounded-2xl transition-all duration-300 transform hover:scale-105 shadow-2xl block mx-auto md:mx-0 w-full md:w-auto text-center">
                        <i class="fab fa-whatsapp mr-4"></i>Message Now
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/919817826490?text=Hi!%20I%20saw%20your%20GamePass%20store%20website%20🎮" 
       class="whatsapp-float text-white" target="_blank" title="Chat on WhatsApp">
        <i class="fab fa-whatsapp p-3"></i>
    </a>

    <!-- Smooth Scroll Script -->
    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        function buyGamepass(passName) {
            const message = `Hi! I want to buy ${passName} 🎮`;
            window.open(`https://wa.me/919817826490?text=${encodeURIComponent(message)}`, '_blank');
        }

        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.classList.add('shadow-2xl');
            } else {
                header.classList.remove('shadow-2xl');
            }
        });
    </script>

</body>
</html>
