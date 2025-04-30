# Wealth-Builder-Passive-Income-AI-Agency
Passive Income Ai Agency
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WealthBuilder SA - Passive Income Platform</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #3b82f6 0%, #8b5cf6 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .progress-bar {
            transition: width 0.5s ease-in-out;
        }
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Navigation -->
    <nav class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center">
                    <i class="fas fa-coins text-2xl mr-2"></i>
                    <span class="font-bold text-xl">WealthBuilder SA</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#how-it-works" class="hover:text-gray-200">How It Works</a>
                    <a href="#features" class="hover:text-gray-200">Features</a>
                    <a href="#testimonials" class="hover:text-gray-200">Success Stories</a>
                    <a href="#faq" class="hover:text-gray-200">FAQ</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-6">Build Passive Income For Life</h1>
                <p class="text-xl mb-8">Join thousands of South Africans earning daily income through our revolutionary agent network. Start with just R50 and grow your wealth automatically.</p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="#register" class="bg-white text-blue-600 hover:bg-gray-100 px-8 py-3 rounded-lg font-semibold text-lg text-center shadow-lg transition duration-300">Register Now</a>
                    <a href="#how-it-works" class="border-2 border-white text-white hover:bg-white hover:text-blue-600 px-8 py-3 rounded-lg font-semibold text-lg text-center transition duration-300">Learn More</a>
                </div>
            </div>
            <div class="md:w-1/2 relative">
                <img src="https://images.unsplash.com/photo-1554224155-6726b3ff858f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Happy people" class="rounded-lg shadow-2xl floating">
                <div class="absolute -bottom-5 -left-5 bg-yellow-400 text-gray-800 p-4 rounded-lg shadow-lg">
                    <div class="text-2xl font-bold">R2,458</div>
                    <div class="text-sm">Average Daily Earnings</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">25,000+</div>
                    <div class="text-gray-600">Active Agents</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">R18M+</div>
                    <div class="text-gray-600">Paid Out Monthly</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">9 Provinces</div>
                    <div class="text-gray-600">Nationwide Coverage</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">24/7</div>
                    <div class="text-gray-600">Support Available</div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-16">How It Works</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white p-8 rounded-xl shadow-md card-hover transition duration-300">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-user-plus text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">1. Register & Activate</h3>
                    <p class="text-gray-600 text-center">Sign up with your basic details and activate your agent account with just R50. This gives you access to our earning platform.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md card-hover transition duration-300">
                    <div class="bg-purple-100 w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-network-wired text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">2. Join The Network</h3>
                    <p class="text-gray-600 text-center">You're automatically placed in our proven 3x10 forced matrix system that generates income from multiple levels.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md card-hover transition duration-300">
                    <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-wallet text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4">3. Earn Daily</h3>
                    <p class="text-gray-600 text-center">Watch your earnings grow daily as our system works for you. Withdraw anytime or reinvest to grow faster.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section id="features" class="py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-16">Powerful Features</h2>
            <div class="flex flex-col md:flex-row items-center mb-16">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Mobile app" class="rounded-lg shadow-xl">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h3 class="text-2xl font-bold mb-4">Mobile-Friendly Platform</h3>
                    <p class="text-gray-600 mb-6">Access your earnings and manage your account from any smartphone. No computer needed - perfect for township entrepreneurs.</p>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>Real-time earnings dashboard</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>Instant withdrawal notifications</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                            <span>Network growth tracking</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="flex flex-col md:flex-row-reverse items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://images.unsplash.com/photo-1579621970563-ebec7560ff3e?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Training" class="rounded-lg shadow-xl">
                </div>
                <div class="md:w-1/2 md:pr-12">
                    <h3 class="text-2xl font-bold mb-4">Comprehensive Training</h3>
                    <p class="text-gray-600 mb-6">We provide free training to all agents through WhatsApp groups, YouTube tutorials, and local workshops in all provinces.</p>
                    <div class="bg-blue-50 p-4 rounded-lg">
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-2 rounded-full mr-3">
                                <i class="fas fa-graduation-cap text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Agent Certification</h4>
                                <p class="text-sm text-gray-600">Become a certified WealthBuilder agent and unlock higher earning tiers.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-16">Success Stories</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Thandi" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold">Thandi M.</h4>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"From unemployed to earning R8,000/month! This program changed my life. I can now support my kids and even started saving for a house."</p>
                    <div class="mt-4 text-sm text-gray-500">Soweto, Johannesburg</div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Sipho" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold">Sipho K.</h4>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"I was skeptical at first but after 3 months I'm making more than my previous job. The training helped me understand how to maximize my earnings."</p>
                    <div class="mt-4 text-sm text-gray-500">Khayelitsha, Cape Town</div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Nomsa" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold">Nomsa D.</h4>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"Retired with no pension, now I earn R5,000 every month without stress. The system works if you follow the simple steps they teach you."</p>
                    <div class="mt-4 text-sm text-gray-500">Mamelodi, Pretoria</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Earnings Calculator -->
    <section class="py-20 gradient-bg text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-6">Earnings Calculator</h2>
            <p class="text-center text-xl mb-12 max-w-2xl mx-auto">See how much you could earn based on your investment level and network growth</p>
            
            <div class="bg-white bg-opacity-10 backdrop-filter backdrop-blur-lg rounded-xl p-8 max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <div class="mb-6">
                            <label class="block mb-2 font-medium">Initial Investment</label>
                            <div class="flex items-center">
                                <span class="mr-2">R</span>
                                <input type="range" min="50" max="5000" value="500" step="50" class="w-full" id="investmentRange">
                                <span class="ml-2 w-20 text-right" id="investmentValue">500</span>
                            </div>
                        </div>
                        <div class="mb-6">
                            <label class="block mb-2 font-medium">Network Size</label>
                            <div class="flex items-center">
                                <input type="range" min="1" max="100" value="10" class="w-full" id="networkRange">
                                <span class="ml-2 w-20 text-right" id="networkValue">10</span>
                            </div>
                        </div>
                        <div class="mb-6">
                            <label class="block mb-2 font-medium">Timeframe (months)</label>
                            <div class="flex items-center">
                                <input type="range" min="1" max="60" value="12" class="w-full" id="timeRange">
                                <span class="ml-2 w-20 text-right" id="timeValue">12</span>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-center">
                        <div class="bg-white bg-opacity-20 rounded-lg p-6">
                            <div class="text-center mb-4">
                                <div class="text-sm text-white text-opacity-80">Projected Monthly Earnings</div>
                                <div class="text-3xl font-bold" id="monthlyEarnings">R4,250</div>
                            </div>
                            <div class="h-2 bg-white bg-opacity-30 rounded-full mb-2">
                                <div class="h-2 bg-green-400 rounded-full progress-bar" style="width: 65%"></div>
                            </div>
                            <div class="flex justify-between text-xs text-white text-opacity-80">
                                <span>Beginner</span>
                                <span>Advanced</span>
                            </div>
                        </div>
                        <div class="mt-6 grid grid-cols-2 gap-4">
                            <div class="bg-white bg-opacity-10 rounded-lg p-3 text-center">
                                <div class="text-sm">Total Invested</div>
                                <div class="font-semibold" id="totalInvested">R500</div>
                            </div>
                            <div class="bg-white bg-opacity-10 rounded-lg p-3 text-center">
                                <div class="text-sm">Projected Profit</div>
                                <div class="font-semibold" id="projectedProfit">R51,000</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration -->
    <section id="register" class="py-20 bg-white">
        <div class="container mx-auto px-6 max-w-4xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-6">Ready to Start Earning?</h2>
            <p class="text-center text-gray-600 mb-12">Join thousands of South Africans building financial freedom through passive income.</p>
            
            <div class="bg-gray-100 rounded-xl p-8">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold mb-4">Registration Benefits</h3>
                        <ul class="space-y-3">
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                                <span>Free training and support</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                                <span>Daily earnings from day 1</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                                <span>Access to our agent community</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                                <span>Withdraw anytime via EFT or mobile money</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check-circle text-green-500 mt-1 mr-2"></i>
                                <span>No monthly fees or hidden costs</span>
                            </li>
                        </ul>
                        <div class="mt-6 bg-blue-50 p-4 rounded-lg">
                            <div class="flex">
                                <div class="bg-blue-100 p-2 rounded-full mr-3">
                                    <i class="fas fa-gift text-blue-600"></i>
                                </div>
                                <div>
                                    <h4 class="font-semibold">Limited Time Offer</h4>
                                    <p class="text-sm text-gray-600">First 100 registrations this week get free R50 activation credit!</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div>
                        <form class="space-y-4">
                            <div>
                                <label class="block text-gray-700 mb-1">Full Name</label>
                                <input type="text" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-1">ID Number</label>
                                <input type="text" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-1">Mobile Number</label>
                                <input type="tel" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-1">Email (optional)</label>
                                <input type="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-1">Province</label>
                                <select class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                                    <option>Select your province</option>
                                    <option>Gauteng</option>
                                    <option>Western Cape</option>
                                    <option>KwaZulu-Natal</option>
                                    <option>Eastern Cape</option>
                                    <option>Limpopo</option>
                                    <option>Mpumalanga</option>
                                    <option>North West</option>
                                    <option>Free State</option>
                                    <option>Northern Cape</option>
                                </select>
                            </div>
                            <button type="submit" class="w-full gradient-bg text-white py-3 rounded-lg font-semibold shadow-lg hover:opacity-90 transition duration-300">Complete Registration</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6 max-w-4xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-16">Frequently Asked Questions</h2>
            
            <div class="space-y-4">
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <button class="flex justify-between items-center w-full focus:outline-none">
                        <h3 class="text-lg font-semibold text-left">How much does it cost to join?</h3>
                        <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                    </button>
                    <div class="mt-4 text-gray-600">
                        The minimum activation fee is just R50, which gives you full access to the WealthBuilder platform and starts your passive income journey. You can invest more to increase your earning potential.
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <button class="flex justify-between items-center w-full focus:outline-none">
                        <h3 class="text-lg font-semibold text-left">How do I get paid?</h3>
                        <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                    </button>
                    <div class="mt-4 text-gray-600">
                        Earnings are paid daily directly to your mobile money account (like CashSend or eWallet) or via EFT to your bank account. Minimum withdrawal is R100 with no maximum limit.
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <button class="flex justify-between items-center w-full focus:outline-none">
                        <h3 class="text-lg font-semibold text-left">Is this a pyramid scheme?</h3>
                        <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                    </button>
                    <div class="mt-4 text-gray-600">
                        No, WealthBuilder is a registered financial services provider (FSP 12345) that operates legally in South Africa. We use a forced matrix compensation model that rewards both personal effort and team building, similar to many legitimate network marketing companies worldwide.
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <button class="flex justify-between items-center w-full focus:outline-none">
                        <h3 class="text-lg font-semibold text-left">What if I don't recruit anyone?</h3>
                        <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                    </button>
                    <div class="mt-4 text-gray-600">
                        You'll still earn from our system's automatic placement of new members. However, actively building your network significantly increases your earning potential. Our training will show you simple, effective ways to grow your team.
                    </div>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <button class="flex justify-between items-center w-full focus:outline-none">
                        <h3 class="text-lg font-semibold text-left">How soon can I start earning?</h3>
                        <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                    </button>
                    <div class="mt-4 text-gray-600">
                        Most agents see their first earnings within 24-48 hours of activation. Your earnings will grow as your network expands. Top performers reach R10,000+ monthly within 3-6 months.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i class="fas fa-coins text-2xl mr-2"></i>
                        <span class="font-bold text-xl">WealthBuilder SA</span>
                    </div>
                    <p class="text-gray-400">Empowering South Africans with sustainable passive income solutions since 2018.</p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Agent Login</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Earnings Calculator</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Training Resources</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Contact Support</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Legal</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Terms of Service</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">FSP Disclosure</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Complaints Procedure</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Contact Us</h4>
                    <ul class="space-y-2">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-2 text-gray-400"></i>
                            <span class="text-gray-400">123 Finance Street, Sandton, 2196</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-phone-alt mt-1 mr-2 text-gray-400"></i>
                            <span class="text-gray-400">0861 932 584</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-envelope mt-1 mr-2 text-gray-400"></i>
                            <span class="text-gray-400">support@wealthbuildersa.co.za</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>© 2023 WealthBuilder South Africa. All rights reserved. FSP No: 12345</p>
            </div>
        </div>
    </footer>

    <script>
        // Calculator functionality
        const investmentRange = document.getElementById('investmentRange');
        const investmentValue = document.getElementById('investmentValue');
        const networkRange = document.getElementById('networkRange');
        const networkValue = document.getElementById('networkValue');
        const timeRange = document.getElementById('timeRange');
        const timeValue = document.getElementById('timeValue');
        const monthlyEarnings = document.getElementById('monthlyEarnings');
        const totalInvested = document.getElementById('totalInvested');
        const projectedProfit = document.getElementById('projectedProfit');

        function updateCalculator() {
            const investment = parseInt(investmentRange.value);
            const network = parseInt(networkRange.value);
            const time = parseInt(timeRange.value);
            
            investmentValue.textContent = investment;
            networkValue.textContent = network;
            timeValue.textContent = time;
            
            // Simple calculation for demo purposes
            const monthly = Math.round(investment * network * 0.85);
            const totalInv = investment;
            const profit = Math.round(monthly * time);
            
            monthlyEarnings.textContent = 'R' + monthly.toLocaleString();
            totalInvested.textContent = 'R' + totalInv.toLocaleString();
            projectedProfit.textContent = 'R' + profit.toLocaleString();
            
            // Update progress bar (simple logic for demo)
            const progressWidth = Math.min(100, Math.max(5, (network / 100) * 100));
            document.querySelector('.progress-bar').style.width = progressWidth + '%';
        }

        investmentRange.addEventListener('input', updateCalculator);
        networkRange.addEventListener('input', updateCalculator);
        timeRange.addEventListener('input', updateCalculator);

        // Initialize calculator
        updateCalculator();

        // FAQ accordion
        const faqButtons = document.querySelectorAll('#faq button');
        faqButtons.forEach(button => {
            button.addEventListener('click', () => {
                const answer = button.nextElementSibling;
                const icon = button.querySelector('i');
                
                if (answer.style.maxHeight) {
                    answer.style.maxHeight = null;
                    icon.style.transform = 'rotate(0deg)';
                } else {
                    answer.style.maxHeight = answer.scrollHeight + 'px';
                    icon.style.transform = 'rotate(180deg)';
                }
            });
        });
    </script>
</body>
</html>
