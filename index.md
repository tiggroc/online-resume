
<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Ojari Dey-Foy | Cybersecurity Executive</title>
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🔒</text></svg>">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com/"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'tech-blue': '#0a66c2',
                        'exec-green': '#00c4cc',
                        'power-purple': '#6e46ae',
                        'dark-cobalt': '#1a365d',
                        'bright-teal': '#00f0ff'
                    },
                    fontFamily: {
                        sans: ['Inter', 'Helvetica', 'Arial', 'sans-serif'],
                        display: ['Lexend', 'Georgia', 'serif']
                    },
                }
            }
        }
    </script>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Lexend:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
    
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #1a365d 0%, #0a66c2 50%, #00c4cc 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3);
        }
        .skill-chip {
            background: rgba(0, 196, 204, 0.1);
            transition: all 0.3s ease;
        }
        .skill-chip:hover {
            background: rgba(0, 196, 204, 0.2);
            transform: scale(1.05);
        }
        .logo-icon {
            filter: drop-shadow(0 0 8px rgba(0, 244, 255, 0.4));
        }
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 244, 255, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(0, 244, 255, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 244, 255, 0); }
        }
    </style>
</head>
<body class="bg-black text-gray-100 font-sans antialiased">
    <!-- Navigation -->
    <nav class="bg-dark-cobalt border-b border-exec-green/30 backdrop-blur-lg sticky top-0 z-50">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <div class="w-10 h-10 rounded-lg bg-tech-blue flex items-center justify-center mr-3 logo-icon">
                    <i class="fas fa-shield-alt text-white"></i>
                </div>
                <h1 class="text-2xl font-display font-bold bg-clip-text text-transparent bg-gradient-to-r from-tech-blue to-exec-green">
                    Dr. Ojari Dey-Foy
                </h1>
            </div>
            
            <div class="hidden lg:flex space-x-8 items-center">
                <a href="#about" class="text-gray-300 hover:text-white transition-colors duration-300 font-medium">About</a>
                <a href="#experience" class="text-gray-300 hover:text-white transition-colors duration-300 font-medium">Experience</a>
                <a href="#expertise" class="text-gray-300 hover:text-white transition-colors duration-300 font-medium">Expertise</a>
                <a href="#leadership" class="text-gray-300 hover:text-white transition-colors duration-300 font-medium">Leadership</a>
                <a href="#contact" class="px-4 py-2 bg-exec-green text-dark-cobalt rounded-md font-semibold hover:bg-tech-blue transition-colors duration-300">Contact</a>
            </div>
            
            <button class="lg:hidden text-gray-300 focus:outline-none" id="mobile-menu-button">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </div>
        
        <!-- Mobile menu -->
        <div class="lg:hidden hidden bg-dark-cobalt px-6 py-3" id="mobile-menu">
            <div class="flex flex-col space-y-3">
                <a href="#about" class="text-gray-300 hover:text-white transition">About</a>
                <a href="#experience" class="text-gray-300 hover:text-white transition">Experience</a>
                <a href="#expertise" class="text-gray-300 hover:text-white transition">Expertise</a>
                <a href="#leadership" class="text-gray-300 hover:text-white transition">Leadership</a>
                <a href="#contact" class="mt-2 px-4 py-2 bg-exec-green text-dark-cobalt rounded-md font-semibold hover:bg-tech-blue transition text-center">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="gradient-bg pt-24 pb-20 px-6">
        <div class="container mx-auto flex flex-col lg:flex-row items-center">
            <div class="lg:w-1/2 mb-12 lg:mb-0 lg:pr-10">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-display font-bold mb-6 leading-tight">
                    Cybersecurity Leadership <span class="bg-clip-text text-transparent bg-gradient-to-r from-exec-green to-bright-teal">for the</span> Digital Battlefield
                </h1>
                
                <div class="flex items-center mb-8">
                    <div class="w-8 h-8 rounded-full bg-power-purple flex items-center justify-center text-white mr-3">
                        <i class="fas fa-star"></i>
                    </div>
                    <h2 class="text-xl md:text-2xl font-medium text-white/90">
                        TS/SCI-CI Poly Cleared Executive
                    </h2>
                </div>
                
                <p class="text-lg md:text-xl text-gray-300 mb-10 leading-relaxed">
                    Bridging <span class="font-semibold text-white">technical innovation</span>, electromagnetic spectrum dominance, and 
                    <span class="font-semibold text-white">policy execution</span> to secure global operations across defense and enterprise sectors.
                </p>
                
                <div class="flex flex-wrap gap-4">
                    <a href="#contact" class="px-6 py-3 bg-exec-green text-dark-cobalt font-semibold rounded-lg hover:bg-bright-teal transition-all duration-300 flex items-center">
                        <i class="fas fa-paper-plane mr-2"></i> Connect With Me
                    </a>
                    <a href="#experience" class="px-6 py-3 border-2 border-exec-green text-exec-green font-semibold rounded-lg hover:bg-dark-cobalt hover:border-bright-teal hover:text-bright-teal transition-all duration-300 flex items-center">
                        <i class="fas fa-briefcase mr-2"></i> View Experience
                    </a>
                </div>
                
                <div class="mt-12 flex items-center space-x-6">
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-white/10 backdrop-blur-sm border border-bright-teal/20 flex items-center justify-center">
                            <i class="fas fa-medal text-bright-teal"></i>
                        </div>
                        <div class="ml-3">
                            <div class="text-xs text-gray-400">YEARS</div>
                            <div class="text-xl font-bold text-white">13+</div>
                        </div>
                    </div>
                    
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-white/10 backdrop-blur-sm border border-bright-teal/20 flex items-center justify-center">
                            <i class="fas fa-shield-alt text-bright-teal"></i>
                        </div>
                        <div class="ml-3">
                            <div class="text-xs text-gray-400">GOVERNMENT</div>
                            <div class="text-xl font-bold text-white">100%</div>
                        </div>
                    </div>
                    
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full bg-white/10 backdrop-blur-sm border border-bright-teal/20 flex items-center justify-center">
                            <i class="fas fa-layer-group text-bright-teal"></i>
                        </div>
                        <div class="ml-3">
                            <div class="text-xs text-gray-400">CLEARANCE</div>
                            <div class="text-xl font-bold text-white">TS/SCI</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="lg:w-1/2 flex justify-center relative">
                <div class="relative w-64 h-64 md:w-80 md:h-80">
                    <div class="absolute inset-0 rounded-full bg-gradient-to-tr from-tech-blue to-bright-teal blur-xl opacity-30"></div>
                    <div class="w-60 h-60 md:w-72 md:h-72 bg-black rounded-full overflow-hidden border-4 border-old-gold">
    <img src="https://rose-terza-47.tiiny.site/Screenshot_20250702_195737_LinkedIn-size-reduce.jpg/" alt="Dr. Ojari Dey-Foy Profile" class="w-full h-full object-cover">
</div>
                </div>
                
                <div class="absolute -bottom-5 -right-5 w-16 h-16 rounded-full bg-tech-blue border-4 border-dark-cobalt flex items-center justify-center pulse-animation">
                    <i class="fas fa-user-secret text-xl text-white"></i>
                </div>
                
                <div class="absolute -top-10 left-10 w-14 h-14 rounded-lg bg-power-purple/80 backdrop-blur-sm flex items-center justify-center rotate-12 shadow-lg">
                    <i class="fas fa-graduation-cap text-white"></i>
                </div>
                
                <div class="absolute -bottom-10 left-0 w-14 h-14 rounded-lg bg-dark-cobalt/80 backdrop-blur-sm flex items-center justify-center -rotate-12 border border-bright-teal/50">
                    <i class="fas fa-medal text-bright-teal"></i>
                </div>
            </div>
        </div>
    </header>

    <!-- Executive Summary -->
    <section id="about" class="py-20 bg-black/80 backdrop-blur-sm">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-display font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-exec-green to-bright-teal">
                    Executive Profile
                </h2>
                <div class="w-20 h-1 bg-gradient-to-r from-tech-blue to-bright-teal mx-auto"></div>
            </div>
            
            <div class="max-w-5xl mx-auto">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
                    <div class="lg:col-span-8">
                        <div class="bg-gradient-to-br from-dark-cobalt/50 to-dark-cobalt rounded-xl p-8 border border-gray-800 backdrop-blur-sm transition-all duration-500 card-hover">
                            <h3 class="text-2xl font-display font-semibold mb-4 text-white">Strategic Cybersecurity Visionary</h3>
                            <p class="text-gray-300 mb-6 leading-relaxed">
                                With over 13 years of <span class="text-white font-medium">U.S. Army and DoD leadership</span> and a Doctorate in Cybersecurity &amp; Information Assurance, I specialize in sculpting cyber defense architectures that withstand modern adversarial threats while enabling mission success.
                            </p>
                            <p class="text-gray-300 leading-relaxed">
                                My career represents a proven ability to navigate the intersection of <span class="text-white font-medium">technical depth</span>, electromagnetic spectrum dominance, and <span class="text-white font-medium">executive-level policy execution</span>—delivering results where national security meets cutting-edge technology.
                            </p>
                        </div>
                    </div>
                    
                    <div class="lg:col-span-4">
                        <div class="bg-gradient-to-br from-power-purple/10 to-dark-cobalt/90 rounded-xl p-6 border border-gray-800 h-full backdrop-blur-sm transition-all duration-500 card-hover">
                            <div class="flex items-start mb-5">
                                <div class="bg-bright-teal text-dark-cobalt rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-eye"></i>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-lg mb-2 text-white">Vision</h3>
                                    <p class="text-gray-300 text-sm">
                                        Architecting resilient cyber defenses that enable strategic advantage in contested digital environments
                                    </p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="bg-exec-green text-dark-cobalt rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                                    <i class="fas fa-rocket"></i>
                                </div>
                                <div>
                                    <h3 class="font-semibold text-lg mb-2 text-white">Approach</h3>
                                    <p class="text-gray-300 text-sm">
                                        Risk-informed, technology-forward leadership with measurable operational impact
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Value Pillars -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-12">
                    <div class="bg-gradient-to-b from-dark-cobalt/70 to-dark-cobalt rounded-xl p-6 border border-gray-800 backdrop-blur-sm transition-all duration-500 card-hover">
                        <div class="bg-tech-blue/20 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <i class="fas fa-chess-king text-tech-blue"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Strategic Cyber Leadership</h3>
                        <p class="text-gray-300">
                            Shaping Army-wide cyber doctrine and advising at General Officer levels on emerging threats and capability gaps
                        </p>
                    </div>
                    
                    <div class="bg-gradient-to-b from-dark-cobalt/70 to-dark-cobalt rounded-xl p-6 border border-gray-800 backdrop-blur-sm transition-all duration-500 card-hover">
                        <div class="bg-exec-green/20 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <i class="fas fa-network-wired text-exec-green"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Technical Depth</h3>
                        <p class="text-gray-300">
                            Architecting Zero Trust frameworks, 5G/IoT defenses, and advanced analytics for multi-domain operations
                        </p>
                    </div>
                    
                    <div class="bg-gradient-to-b from-dark-cobalt/70 to-dark-cobalt rounded-xl p-6 border border-gray-800 backdrop-blur-sm transition-all duration-500 card-hover">
                        <div class="bg-power-purple/20 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <i class="fas fa-balance-scale text-power-purple"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-3 text-white">Policy Execution</h3>
                        <p class="text-gray-300">
                            Translating complex technical requirements into actionable policy and compliance frameworks
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Executive Experience -->
    <section id="experience" class="py-20 bg-gradient-to-b from-dark-cobalt to-black">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-display font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-tech-blue to-bright-teal">
                    Executive Experience
                </h2>
                <div class="w-20 h-1 bg-gradient-to-r from-exec-green to-tech-blue mx-auto"></div>
            </div>
            
            <div class="max-w-5xl mx-auto">
                <!-- Corvus Experience -->
                <div class="mb-16 relative">
                    <div class="hidden lg:block absolute left-0 top-0 bottom-0 w-0.5 bg-gradient-to-b from-tech-blue via-exec-green to-bright-teal ml-7"></div>
                    
                    <div class="flex items-start lg:items-center mb-8">
                        <div class="bg-tech-blue text-white rounded-xl w-14 h-14 flex items-center justify-center mr-6 flex-shrink-0">
                            <i class="fas fa-building text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-display font-semibold text-white">Corvus Consulting, LLC</h3>
                            <div class="flex items-center mt-1">
                                <span class="text-exec-green text-sm font-medium">3 years 8 months</span>
                                <span class="mx-2 text-gray-500">•</span>
                                <span class="text-gray-400 text-sm">Washington D.C. Area</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="pl-20 space-y-12">
                        <!-- Senior Cybersecurity Advisor -->
                        <div class="relative">
                            <div class="absolute left-0 top-3 w-4 h-4 rounded-full bg-gradient-to-r from-tech-blue to-bright-teal border-4 border-dark-cobalt -ml-12 z-10"></div>
                            <div class="bg-gradient-to-br from-dark-cobalt/70 to-dark-cobalt/90 rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                                <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                                    <h4 class="text-xl font-semibold text-white">Senior Cybersecurity Advisor</h4>
                                    <span class="text-sm text-gray-400 md:text-right">December 2024 - Present</span>
                                </div>
                                <p class="text-gray-300 mb-5">
                                    Providing executive-level technical and programmatic guidance for critical Army Cyberspace Operations initiatives.
                                </p>
                                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                                    <div class="flex items-start">
                                        <div class="text-bright-teal mr-3 mt-1"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Shaping cybersecurity strategies that enhance multi-domain operational capabilities</p>
                                    </div>
                                    <div class="flex items-start">
                                        <div class="text-bright-teal mr-3 mt-1"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Overseeing compliance frameworks for enterprise-level network operations</p>
                                    </div>
                                    <div class="flex items-start">
                                        <div class="text-bright-teal mr-3 mt-1"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Directly influencing $2B+ defense assets through risk-informed decision making</p>
                                    </div>
                                    <div class="flex items-start">
                                        <div class="text-bright-teal mr-3 mt-1"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Advising Army CIO/G-6 on Zero Trust Architecture implementation roadmaps</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Senior Cybersecurity Program Analyst -->
                        <div class="relative">
                            <div class="absolute left-0 top-3 w-4 h-4 rounded-full bg-gradient-to-r from-tech-blue to-bright-teal border-4 border-dark-cobalt -ml-12 z-10"></div>
                            <div class="bg-gradient-to-br from-dark-cobalt/70 to-dark-cobalt/90 rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                                <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                                    <h4 class="text-xl font-semibold text-white">Senior Cybersecurity Program Analyst</h4>
                                    <span class="text-sm text-gray-400 md:text-right">December 2023 - December 2024</span>
                                </div>
                                <p class="text-gray-300 mb-5">
                                    Driving enterprise risk management and policy development across Department of Defense networks.
                                </p>
                                <div class="space-y-3">
                                    <div class="flex items-start">
                                        <div class="text-exec-green mr-3 mt-1"><i class="fas fa-star"></i></div>
                                        <p class="text-gray-300">Led RMF compliance initiatives reducing organizational cyber risk by 32%</p>
                                    </div>
                                    <div class="flex items-start">
                                        <div class="text-exec-green mr-3 mt-1"><i class="fas fa-star"></i></div>
                                        <p class="text-gray-300">Developed advanced SIEM strategies using Splunk for enhanced threat detection</p>
                                    </div>
                                    <div class="flex items-start">
                                        <div class="text-exec-green mr-3 mt-1"><i class="fas fa-star"></i></div>
                                        <p class="text-gray-300">Authored critical policy documents adopted across Army cyber commands</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- US Army Experience -->
                <div class="relative">
                    <div class="flex items-start lg:items-center mb-8">
                        <div class="bg-exec-green text-dark-cobalt rounded-xl w-14 h-14 flex items-center justify-center mr-6 flex-shrink-0">
                            <i class="fas fa-flag-usa text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-display font-semibold text-white">US Army</h3>
                            <div class="flex items-center mt-1">
                                <span class="text-bright-teal text-sm font-medium">13 years 6 months</span>
                                <span class="mx-2 text-gray-500">•</span>
                                <span class="text-gray-400 text-sm">Global Assignments</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="pl-20 space-y-12">
                        <!-- Senior Automation and Information Assurance Manager -->
                        <div class="relative">
                            <div class="absolute left-0 top-3 w-4 h-4 rounded-full bg-gradient-to-r from-tech-blue to-bright-teal border-4 border-dark-cobalt -ml-12 z-10"></div>
                            <div class="bg-gradient-to-br from-dark-cobalt/70 to-dark-cobalt/90 rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                                <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                                    <h4 class="text-xl font-semibold text-white">Senior Automation and Information Assurance Manager</h4>
                                    <span class="text-sm text-gray-400 md:text-right">July 2014 - September 2020</span>
                                </div>
                                <p class="text-gray-300 mb-5">
                                    Operationalized cybersecurity protections for multi-domain command environments spanning classified and unclassified networks.
                                </p>
                                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                                    <div class="bg-black/30 rounded-lg p-3 border border-gray-800">
                                        <div class="text-bright-teal mb-2"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Directed network security for enterprise IT serving 5,000+ users</p>
                                    </div>
                                    <div class="bg-black/30 rounded-lg p-3 border border-gray-800">
                                        <div class="text-bright-teal mb-2"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Achieved 100% DIACAP/RMF compliance ahead of schedule</p>
                                    </div>
                                    <div class="bg-black/30 rounded-lg p-3 border border-gray-800">
                                        <div class="text-bright-teal mb-2"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Pioneered secure BYOD initiatives increasing operational flexibility</p>
                                    </div>
                                    <div class="bg-black/30 rounded-lg p-3 border border-gray-800">
                                        <div class="text-bright-teal mb-2"><i class="fas fa-check-circle"></i></div>
                                        <p class="text-gray-300 text-sm">Reduced incident response times by 40% through automation</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Expertise Section -->
    <section id="expertise" class="py-20 bg-black">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-display font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-power-purple to-exec-green">
                    Core Expertise
                </h2>
                <div class="w-20 h-1 bg-gradient-to-r from-power-purple to-tech-blue mx-auto"></div>
            </div>
            
            <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Technical Expertise -->
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="flex items-center mb-6">
                        <div class="bg-gradient-to-r from-tech-blue to-bright-teal rounded-lg w-12 h-12 flex items-center justify-center mr-4">
                            <i class="fas fa-microchip text-white"></i>
                        </div>
                        <h3 class="text-xl font-display font-semibold text-white">Technical Cyber Capabilities</h3>
                    </div>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">Zero Trust Architecture</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">5G/IoT Cybersecurity</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">Splunk/SIEM Analytics</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">RMF/DIACAP Compliance</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">EW/SIGINT Integration</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">Cloud Security</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">Multi-Domain Ops</span>
                        </div>
                        <div class="skill-chip px-3 py-2 rounded-lg flex items-center">
                            <div class="w-2 h-2 rounded-full bg-bright-teal mr-2"></div>
                            <span class="text-sm">AI/ML for Cyber</span>
                        </div>
                    </div>
                </div>
                
                <!-- Leadership Expertise -->
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="flex items-center mb-6">
                        <div class="bg-gradient-to-r from-power-purple to-exec-green rounded-lg w-12 h-12 flex items-center justify-center mr-4">
                            <i class="fas fa-chess-king text-white"></i>
                        </div>
                        <h3 class="text-xl font-display font-semibold text-white">Executive Leadership</h3>
                    </div>
                    
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="text-exec-green mt-1 mr-4"><i class="fas fa-check-circle"></i></div>
                            <div>
                                <h4 class="font-medium text-white">Cyber Strategy Development</h4>
                                <p class="text-gray-300 text-sm mt-1">Crafting actionable roadmaps aligned with DoD cyber priorities</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="text-exec-green mt-1 mr-4"><i class="fas fa-check-circle"></i></div>
                            <div>
                                <h4 class="font-medium text-white">Policy Implementation</h4>
                                <p class="text-gray-300 text-sm mt-1">Translating NIST/CNSS standards into operational frameworks</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="text-exec-green mt-1 mr-4"><i class="fas fa-check-circle"></i></div>
                            <div>
                                <h4 class="font-medium text-white">Stakeholder Engagement</h4>
                                <p class="text-gray-300 text-sm mt-1">Aligning technical and non-technical audiences on security priorities</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="text-exec-green mt-1 mr-4"><i class="fas fa-check-circle"></i></div>
                            <div>
                                <h4 class="font-medium text-white">Risk Governance</h4>
                                <p class="text-gray-300 text-sm mt-1">Balancing security controls with operational imperatives</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="text-exec-green mt-1 mr-4"><i class="fas fa-check-circle"></i></div>
                            <div>
                                <h4 class="font-medium text-white">Emerging Threat Analysis</h4>
                                <p class="text-gray-300 text-sm mt-1">Anticipating adversary TTPs in evolving digital battlespace</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Certifications -->
            <div class="max-w-5xl mx-auto mt-16">
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="flex items-center mb-6">
                        <div class="bg-gradient-to-r from-bright-teal to-tech-blue rounded-lg w-12 h-12 flex items-center justify-center mr-4">
                            <i class="fas fa-certificate text-white"></i>
                        </div>
                        <h3 class="text-xl font-display font-semibold text-white">Certifications &amp; Clearances</h3>
                    </div>
                    
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="flex items-center">
                            <div class="bg-power-purple/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-lock text-power-purple"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">TS/SCI with CI Poly</h4>
                                <p class="text-gray-300 text-xs">Active Clearance</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="bg-bright-teal/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-user-shield text-bright-teal"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">CASP+</h4>
                                <p class="text-gray-300 text-xs">CompTIA Advanced Security Practitioner|
                                    SecurityX
                                </p>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="bg-exec-green/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-shield-alt text-exec-green"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">CISM</h4>
                                <p class="text-gray-300 text-xs">Certified Information Security Manager</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="bg-tech-blue/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-network-wired text-tech-blue"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">C|EH</h4>
                                <p class="text-gray-300 text-xs">Certified Ethical Hacker</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="bg-power-purple/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-brain text-power-purple"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">C|NDA</h4>
                                <p class="text-gray-300 text-xs">Certified Network Defence Architect</p>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="bg-bright-teal/10 rounded-lg w-10 h-10 flex items-center justify-center mr-3">
                                <i class="fas fa-project-diagram text-bright-teal"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-white">DoD 8570 IAM III</h4>
                                <p class="text-gray-300 text-xs">Information Assurance Manager</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Leadership Impact -->
    <section id="leadership" class="py-20 bg-gradient-to-b from-dark-cobalt/80 to-black">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-display font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-bright-teal to-exec-green">
                    Leadership Impact
                </h2>
                <div class="w-20 h-1 bg-gradient-to-r from-bright-teal to-power-purple mx-auto"></div>
            </div>
            
            <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="text-5xl font-bold mb-4 text-bright-teal">30%+</div>
                    <h3 class="text-xl font-semibold mb-3 text-white">Risk Reduction</h3>
                    <p class="text-gray-300">
                        Improved enterprise security postures through Zero Trust implementation
                    </p>
                    <div class="mt-4 flex items-center">
                        <div class="w-full bg-gray-800 rounded-full h-1.5">
                            <div class="bg-bright-teal h-1.5 rounded-full" style="width: 85%"></div>
                        </div>
                        <span class="ml-2 text-xs text-gray-400">85% efficiency</span>
                    </div>
                </div>
                
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="text-5xl font-bold mb-4 text-exec-green">$2B+</div>
                    <h3 class="text-xl font-semibold mb-3 text-white">Assets Secured</h3>
                    <p class="text-gray-300">
                        Oversight of critical defense infrastructure across multiple domains
                    </p>
                    <div class="mt-4 flex items-center">
                        <div class="w-full bg-gray-800 rounded-full h-1.5">
                            <div class="bg-exec-green h-1.5 rounded-full" style="width: 100%"></div>
                        </div>
                        <span class="ml-2 text-xs text-gray-400">100% compliance</span>
                    </div>
                </div>
                
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="text-5xl font-bold mb-4 text-power-purple">32%</div>
                    <h3 class="text-xl font-semibold mb-3 text-white">Process Efficiency</h3>
                    <p class="text-gray-300">
                        Accelerated incident response and compliance workflows
                    </p>
                    <div class="mt-4 flex items-center">
                        <div class="w-full bg-gray-800 rounded-full h-1.5">
                            <div class="bg-power-purple h-1.5 rounded-full" style="width: 78%"></div>
                        </div>
                        <span class="ml-2 text-xs text-gray-400">78% faster</span>
                    </div>
                </div>
            </div>
            
            <div class="max-w-5xl mx-auto mt-12">
                <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm card-hover">
                    <div class="flex flex-col md:flex-row md:items-center">
                        <div class="md:w-1/2 mb-6 md:mb-0 md:pr-8">
                            <h3 class="text-xl md:text-2xl font-display font-semibold mb-4 text-white">
                                How I Transform Cybersecurity Programs
                            </h3>
                            <p class="text-gray-300 mb-5 leading-relaxed">
                                As a cybersecurity executive, my approach blends technical acumen with strategic vision—aligning security initiatives with organizational mission imperatives while maintaining rigorous compliance standards.
                            </p>
                            <a href="#contact" class="inline-block px-6 py-3 bg-bright-teal text-dark-cobalt font-semibold rounded-lg hover:bg-exec-green transition">
                                Discuss Transformation <i class="fas fa-arrow-right ml-2"></i>
                            </a>
                        </div>
                        
                        <div class="md:w-1/2">
                            <div class="space-y-4">
                                <div class="flex items-start">
                                    <div class="text-exec-green text-xl mt-1 mr-4"><i class="fas fa-arrow-right"></i></div>
                                    <div>
                                        <h4 class="font-semibold text-white">Risk-Informed Decision Making</h4>
                                        <p class="text-gray-300 text-sm mt-1">
                                            Quantifying cyber risk in operational terms to enable executive-level prioritization
                                        </p>
                                    </div>
                                </div>
                                
                                <div class="flex items-start">
                                    <div class="text-power-purple text-xl mt-1 mr-4"><i class="fas fa-arrow-right"></i></div>
                                    <div>
                                        <h4 class="font-semibold text-white">Mission-Aligned Security</h4>
                                        <p class="text-gray-300 text-sm mt-1">
                                            Designing controls that enable rather than inhibit operational success
                                        </p>
                                    </div>
                                </div>
                                
                                <div class="flex items-start">
                                    <div class="text-tech-blue text-xl mt-1 mr-4"><i class="fas fa-arrow-right"></i></div>
                                    <div>
                                        <h4 class="font-semibold text-white">Next-Gen Technology Integration</h4>
                                        <p class="text-gray-300 text-sm mt-1">
                                            Leveraging AI/ML and automation to stay ahead of adversary capabilities
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-black/90">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <div class="text-center mb-16">
                    <h2 class="text-3xl md:text-4xl font-display font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-exec-green to-tech-blue">
                        Executive Contact
                    </h2>
                    <div class="w-20 h-1 bg-gradient-to-r from-tech-blue to-power-purple mx-auto"></div>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-12 gap-8">
                    <div class="md:col-span-5">
                        <div class="bg-gradient-to-br from-dark-cobalt/70 to-black rounded-xl p-8 border border-gray-800 backdrop-blur-sm h-full">
                            <h3 class="text-xl font-display font-semibold mb-6 text-white">Connect With Me</h3>
                            
                            <div class="space-y-6">
                                <div class="flex items-start">
                                    <div class="bg-exec-green/10 rounded-lg w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                                        <i class="fas fa-envelope text-exec-green"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-medium text-gray-300 mb-1">Email</h4>
                                        <a href="mailto:odeyfoy@gmail.com" class="text-bright-teal hover:underline">odeyfoy@gmail.com</a>
                                    </div>
                                </div>
                                
                                <div class="flex items-start">
                                    <div class="bg-tech-blue/10 rounded-lg w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                                        <i class="fas fa-phone text-tech-blue"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-medium text-gray-300 mb-1">Secure Line</h4>
                                        <a href="#" class="text-bright-teal">(631.517.0633)</a>
                                    </div>
                                </div>
                                
                                <div class="flex items-start">
                                    <div class="bg-power-purple/10 rounded-lg w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                                        <i class="fas fa-map-marker-alt text-power-purple"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-medium text-gray-300 mb-1">Location</h4>
                                        <p class="text-gray-300">Greater Washington D.C. Area</p>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="mt-12">
                                <h4 class="font-semibold text-white mb-4">Connect Socially</h4>
                                <div class="flex space-x-4">
                                    <a href="#" class="w-10 h-10 rounded-full bg-tech-blue/10 flex items-center justify-center text-tech-blue hover:bg-tech-blue/30 transition">
                                        <i class="fab fa-linkedin-in"></i></a><a href="https://www.linkedin.com/in/ojari-dey-foy/" class="text-bright-teal hover:underline">LinkedIn</a>
                                    
                                    <a href="#" class="w-10 h-10 rounded-full bg-power-purple/10 flex items-center justify-center text-power-purple hover:bg-power-purple/30 transition">
                                        <i class="fab fa-twitter"></i></a><a href="https://www.x.com/DrDeyFoy" class="text-bright-teal hover:underline">Twitter</a>
                                    
                                    <a href="#" class="w-10 h-10 rounded-full bg-dark-cobalt flex items-center justify-center text-white hover:bg-dark-cobalt/80 transition border border-gray-700">
                                        <i class="fas fa-lock"></i></a><a href="https://signal.me/#p/%2B16315170633" class="text-bright-teal hover:underline">SecComs</a>
                                    
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="md:col-span-7">
                        <div class="bg-gradient-to-br from-dark-cobalt/70 to-dark-cobalt rounded-xl p-8 border border-gray-800 backdrop-blur-sm h-full">
                            <h3 class="text-xl font-display font-semibold mb-6 text-white">Send a Secure Message</h3>
                            <form class="space-y-5">
                                <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                                    <div>
                                        <label for="name" class="block text-sm font-medium text-gray-300 mb-1">Name</label>
                                        <input type="text" id="name" class="w-full px-4 py-3 bg-dark-cobalt border border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-exec-green focus:border-transparent" placeholder="Your name">
                                    </div>
                                    <div>
                                        <label for="organization" class="block text-sm font-medium text-gray-300 mb-1">Organization</label>
                                        <input type="text" id="organization" class="w-full px-4 py-3 bg-dark-cobalt border border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-exec-green focus:border-transparent" placeholder="Your organization">
                                    </div>
                                </div>
                                
                                <div>
                                    <label for="email" class="block text-sm font-medium text-gray-300 mb-1">Email</label>
                                    <input type="email" id="email" class="w-full px-4 py-3 bg-dark-cobalt border border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-exec-green focus:border-transparent" placeholder="Your email">
                                </div>
                                
                                <div>
                                    <label for="subject" class="block text-sm font-medium text-gray-300 mb-1">Subject</label>
                                    <select id="subject" class="w-full px-4 py-3 bg-dark-cobalt border border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-exec-green focus:border-transparent">
                                        <option>General Inquiry</option>
                                        <option>Speaking Engagement</option>
                                        <option>Consulting Opportunity</option>
                                        <option>TS/SCI Secure Contact</option>
                                    </select>
                                </div>
                                
                                <div>
                                    <label for="message" class="block text-sm font-medium text-gray-300 mb-1">Message</label>
                                    <textarea id="message" rows="4" class="w-full px-4 py-3 bg-dark-cobalt border border-gray-700 rounded-lg focus:outline-none focus:ring-2 focus:ring-exec-green focus:border-transparent" placeholder="Your message"></textarea>
                                </div>
                                
                                <div class="pt-2">
                                    <button type="submit" class="w-full px-6 py-3 bg-gradient-to-r from-tech-blue to-exec-green text-dark-cobalt font-semibold rounded-lg hover:from-tech-blue/90 hover:to-exec-green/90 transition">
                                        Send Secure Message <i class="fas fa-paper-plane ml-2"></i>
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark-cobalt/90 border-t border-gray-800 py-12">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="flex items-center mb-6 md:mb-0">
                    <div class="w-10 h-10 rounded-lg bg-tech-blue flex items-center justify-center mr-3">
                        <i class="fas fa-shield-alt text-white"></i>
                    </div>
                    <h3 class="text-xl font-display font-semibold bg-clip-text text-transparent bg-gradient-to-r from-tech-blue to-exec-green">
                        Dr. Ojari Dey-Foy
                    </h3>
                </div>
                
                <div class="flex flex-wrap justify-center gap-6">
                    <a href="#about" class="text-gray-300 hover:text-white transition">About</a>
                    <a href="#experience" class="text-gray-300 hover:text-white transition">Experience</a>
                    <a href="#expertise" class="text-gray-300 hover:text-white transition">Expertise</a>
                    <a href="#leadership" class="text-gray-300 hover:text-white transition">Leadership</a>
                    <a href="#contact" class="text-gray-300 hover:text-white transition">Contact</a>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-10 pt-10">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <p class="text-gray-400 text-sm mb-4 md:mb-0">
                        © 2025 Dr. Ojari Dey-Foy. All rights reserved.
                    </p>
                    
                    <div class="text-gray-400 text-sm">
                        TS/SCI-CI Poly Cleared Cybersecurity Executive
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });
        
        // Calculate durations
        function calculateDuration(startDate, endDate) {
            const start = new Date(startDate);
            const end = endDate === 'Present' ? new Date() : new Date(endDate);
            
            const diffInMonths = (end.getFullYear() - start.getFullYear()) * 12 + (end.getMonth() - start.getMonth());
            const years = Math.floor(diffInMonths / 12);
            const months = diffInMonths % 12;
            
            return { years, months };
        }
        
        // Set Corvus duration
        const corvusDuration = calculateDuration('2022-12-01', 'Present');
        document.getElementById('corvus-duration').textContent = `${corvusDuration.years} years ${corvusDuration.months} months`;
        
        // Set Army duration
        const armyDuration = calculateDuration('2014-07-01', '2020-09-01');
        document.getElementById('us-army-duration').textContent = `${armyDuration.years} years ${armyDuration.months} months`;
        
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
    </script>

</body></html>
