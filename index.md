</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Ojari Dey-Foy | Cybersecurity Executive</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .old-gold {
            color: #CFB53B;
        }
        .bg-old-gold {
            background-color: #CFB53B;
        }
        .border-old-gold {
            border-color: #CFB53B;
        }
        .hover-old-gold:hover {
            color: #CFB53B;
        }
        .timeline-item:not(:last-child)::after {
            content: '';
            position: absolute;
            left: 7px;
            top: 24px;
            height: calc(100% - 24px);
            width: 2px;
            background: #CFB53B;
        }
        .skill-bar {
            height: 6px;
            background-color: #2d3748;
        }
        .skill-progress {
            height: 100%;
            background-color: #CFB53B;
        }
        .publication-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body class="bg-black text-gray-200 font-sans">
    <!-- Navigation -->
    <nav class="bg-black border-b border-old-gold sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="text-2xl font-bold old-gold">Dr. Ojari Dey-Foy</div>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="text-gray-200 hover-old-gold transition">About</a>
                <a href="#experience" class="text-gray-200 hover-old-gold transition">Experience</a>
                <a href="#skills" class="text-gray-200 hover-old-gold transition">Skills</a>
                <a href="#education" class="text-gray-200 hover-old-gold transition">Education</a>
                <a href="#contact" class="text-gray-200 hover-old-gold transition">Contact</a>
            </div>
            <button class="md:hidden text-gray-200 focus:outline-none">
                <i class="fas fa-bars text-xl"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-gradient-to-r from-black to-gray-900 py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Dr. Ojari Dey-Foy</h1>
                <h2 class="text-2xl md:text-3xl old-gold font-semibold mb-6">Cybersecurity Executive | EW Strategist | TS/SCI-CI Poly</h2>
                <p class="text-lg mb-8">Bridging technical innovation, electromagnetic spectrum dominance, and policy execution to secure global operations.</p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-old-gold text-black px-6 py-3 rounded font-semibold hover:bg-yellow-600 transition">Contact Me</a>
                    <a href="#experience" class="border border-old-gold text-old-gold px-6 py-3 rounded font-semibold hover:bg-gray-800 transition">View Experience</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <div class="w-64 h-64 md:w-80 md:h-80 bg-old-gold rounded-full flex items-center justify-center">
                        <div class="w-60 h-60 md:w-72 md:h-72 bg-black rounded-full overflow-hidden border-4 border-old-gold">
                            <!-- Placeholder for profile image -->
                            <div class="w-full h-full bg-gray-700 flex items-center justify-center">
                                <i class="fas fa-user text-6xl old-gold"></i>
                            </div>
                        </div>
                    </div>
                    <div class="absolute -bottom-5 -right-5 bg-black border-2 border-old-gold rounded-full p-3">
                        <i class="fas fa-shield-alt text-3xl old-gold"></i>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-900">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center old-gold">Professional Summary</h2>
            <div class="max-w-4xl mx-auto bg-gray-800 p-8 rounded-lg shadow-lg">
                <p class="mb-6 text-lg">As a TS/SCI-cleared Cybersecurity Executive and Electronic Warfare (EW) Strategist, I bring over 13 years of U.S. Army and DoD leadership to the front lines of national defense. With a Doctorate in Cybersecurity & Information Assurance, I specialize in bridging technical innovation, electromagnetic spectrum dominance, and policy execution to secure global operations.</p>
                <p class="mb-6 text-lg">From architecting Zero Trust frameworks and leading multi-agency RMF compliance efforts to engineering advanced 5G/IoT defenses and shaping Army-wide cyber doctrine, I've consistently delivered results where resilience meets complexity.</p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">
                    <div class="flex items-start">
                        <div class="bg-old-gold text-black rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                            <i class="fas fa-check"></i>
                        </div>
                        <div>
                            <h3 class="font-semibold old-gold mb-2">Core Capabilities</h3>
                            <ul class="list-disc list-inside space-y-1">
                                <li>Cyber Strategy & Policy (DoD, Army, OSD, Joint Staff)</li>
                                <li>ZTA | RMF | EMSO | AI/ML-enabled Analytics</li>
                                <li>5G Cybersecurity | SIGINT | CEMA | Multi-Domain Ops</li>
                            </ul>
                        </div>
                    </div>
                    <div class="flex items-start">
                        <div class="bg-old-gold text-black rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">
                            <i class="fas fa-trophy"></i>
                        </div>
                        <div>
                            <h3 class="font-semibold old-gold mb-2">Key Achievements</h3>
                            <ul class="list-disc list-inside space-y-1">
                                <li>Authored critical EXORDs, policy papers, and SITREPs</li>
                                <li>Briefed General Officers and congressional staff</li>
                                <li>Led risk reduction strategies improving security postures by 30%+</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-black">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center old-gold">Professional Experience</h2>
            
            <div class="max-w-4xl mx-auto">
                <!-- Corvus Consulting -->
                <div class="mb-16">
                    <div class="flex items-center mb-6">
                        <div class="bg-old-gold text-black rounded-full w-12 h-12 flex items-center justify-center mr-4">
                            <i class="fas fa-building text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-semibold">Corvus Consulting, LLC</h3>
                            <p class="text-gray-400">3 years 8 months</p>
                        </div>
                    </div>
                    
                    <div class="pl-16 space-y-8">
                        <!-- Senior Cybersecurity Advisor -->
                        <div class="relative timeline-item pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-old-gold border-4 border-black"></div>
                            <div class="bg-gray-900 p-6 rounded-lg shadow-lg">
                                <h4 class="text-xl font-semibold old-gold mb-2">Senior Cybersecurity Advisor</h4>
                                <p class="text-gray-400 mb-3">December 2024 - Present (7 months)</p>
                                <ul class="list-disc list-inside space-y-2">
                                    <li>Highly impactful Senior Cybersecurity Program Advisor providing technical and programmatic expertise for critical Army Cyberspace Operations.</li>
                                    <li>Specializing in shaping cybersecurity strategies, policies, and compliance oversight for complex network operations.</li>
                                    <li>Directly influencing strategic capabilities and safeguarding significant defense assets for cyberspace operations initiatives.</li>
                                </ul>
                            </div>
                        </div>
                        
                        <!-- Senior Cybersecurity Program Analyst -->
                        <div class="relative timeline-item pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-old-gold border-4 border-black"></div>
                            <div class="bg-gray-900 p-6 rounded-lg shadow-lg">
                                <h4 class="text-xl font-semibold old-gold mb-2">Senior Cybersecurity Program Analyst</h4>
                                <p class="text-gray-400 mb-3">December 2023 - December 2024 (1 year 1 month)</p>
                                <ul class="list-disc list-inside space-y-2">
                                    <li>Proven track record of leading complex risk management initiatives and developing critical cybersecurity policies across the Department of Defense (DoD).</li>
                                    <li>Excels at leveraging advanced SIEM tools like Splunk to drive compliance, enhance threat detection, and significantly reduce organizational cyber risk.</li>
                                </ul>
                            </div>
                        </div>
                        
                        <!-- Senior Strategy and Policy Analyst SME III -->
                        <div class="relative timeline-item pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-old-gold border-4 border-black"></div>
                            <div class="bg-gray-900 p-6 rounded-lg shadow-lg">
                                <h4 class="text-xl font-semibold old-gold mb-2">Senior Strategy and Policy Analyst SME III (EW|EMSO)</h4>
                                <p class="text-gray-400 mb-3">December 2022 - December 2023 (1 year 1 month)</p>
                                <ul class="list-disc list-inside space-y-2">
                                    <li>Specialized in developing and implementing critical cyberspace operations (CO) and EW strategies, plans, and policies.</li>
                                    <li>Directly enabled Multi-Domain Operations (MDO) across diverse Army commands and global theaters.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- US Army -->
                <div class="mb-16">
                    <div class="flex items-center mb-6">
                        <div class="bg-old-gold text-black rounded-full w-12 h-12 flex items-center justify-center mr-4">
                            <i class="fas fa-flag-usa text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-semibold">US Army</h3>
                            <p class="text-gray-400">13 years 6 months</p>
                        </div>
                    </div>
                    
                    <div class="pl-16 space-y-8">
                        <!-- Senior Automation and Information Assurance Manager -->
                        <div class="relative timeline-item pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-old-gold border-4 border-black"></div>
                            <div class="bg-gray-900 p-6 rounded-lg shadow-lg">
                                <h4 class="text-xl font-semibold old-gold mb-2">Senior Automation and Information Assurance Manager</h4>
                                <p class="text-gray-400 mb-3">July 2014 - September 2020 (6 years 3 months)</p>
                                <ul class="list-disc list-inside space-y-2">
                                    <li>Served as the Information Assurance, Senior Help Desk and Local Area Network Manager for a Multi-Domain directorate.</li>
                                    <li>Accountable for all future system fielding to include the creation, maintenance and operating life cycle replacements for all IT systems.</li>
                                    <li>Ensured that classified and unclassified systems were in compliance with Army and Department of Defence (DOD) Information Assurance Vulnerability Assessments (IAVA).</li>
                                </ul>
                            </div>
                        </div>
                        
                        <!-- Senior Intelligence Strategist & Advisor -->
                        <div class="relative timeline-item pl-8">
                            <div class="absolute left-0 top-0 w-4 h-4 rounded-full bg-old-gold border-4 border-black"></div>
                            <div class="bg-gray-900 p-6 rounded-lg shadow-lg">
                                <h4 class="text-xl font-semibold old-gold mb-2">Senior Intelligence Strategist & Advisor</h4>
                                <p class="text-gray-400 mb-3">April 2007 - September 2020 (13 years 6 months)</p>
                                <ul class="list-disc list-inside space-y-2">
                                    <li>Performed research and analysis of all-source data derived from multiple and specialized databases using data mining.</li>
                                    <li>Expert experience in the utilization of Microsoft Office tools and various analytical systems such as Pathfinder, Analyst Notebook, FalconView ENVI, and ArcGIS.</li>
                                    <li>Experience in supporting Joint military operations as well as a full grasp of Intelligence, Surveillance and Reconnaissance (ISR) missions, procedures and processes.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills & Certifications Section -->
    <section id="skills" class="py-20 bg-gray-900">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center old-gold">Skills & Certifications</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <!-- Skills -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold old-gold mb-4 flex items-center">
                        <i class="fas fa-code mr-2"></i> Technical Skills
                    </h3>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>5G Network Security</span>
                                <span>95%</span>
                            </div>
                            <div class="skill-bar rounded-full">
                                <div class="skill-progress rounded-full" style="width: 95%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Zero Trust Architecture (ZTA)</span>
                                <span>90%</span>
                            </div>
                            <div class="skill-bar rounded-full">
                                <div class="skill-progress rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Vulnerability Management</span>
                                <span>88%</span>
                            </div>
                            <div class="skill-bar rounded-full">
                                <div class="skill-progress rounded-full" style="width: 88%"></div>
                            </div>
                        </div>
                    </div>
                    
                    <h3 class="text-xl font-semibold old-gold mt-6 mb-4 flex items-center">
                        <i class="fas fa-language mr-2"></i> Languages
                    </h3>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Spanish (Elementary)</span>
                                <span>40%</span>
                            </div>
                            <div class="skill-bar rounded-full">
                                <div class="skill-progress rounded-full" style="width: 40%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Certifications -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold old-gold mb-4 flex items-center">
                        <i class="fas fa-certificate mr-2"></i> Certifications
                    </h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-8 h-8 flex items-center justify-center mr-3 mt-1 flex-shrink-0">
                                <i class="fas fa-shield-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">CompTIA Advanced Security Practitioner (CASP+) ce Certification</h4>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-8 h-8 flex items-center justify-center mr-3 mt-1 flex-shrink-0">
                                <i class="fas fa-user-secret"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Certified Ethical Hacker (CEH)</h4>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-8 h-8 flex items-center justify-center mr-3 mt-1 flex-shrink-0">
                                <i class="fas fa-chart-line"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Six Sigma Master Black Belt</h4>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-8 h-8 flex items-center justify-center mr-3 mt-1 flex-shrink-0">
                                <i class="fas fa-lock"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Certified Information Security Manager® (CISM)</h4>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Publications -->
                    <h3 class="text-xl font-semibold old-gold mt-6 mb-4 flex items-center">
                        <i class="fas fa-book mr-2"></i> Publications
                    </h3>
                    <div class="bg-gray-700 p-4 rounded-lg publication-card transition duration-300">
                        <h4 class="font-medium mb-2">A Delphi Approach to Develop a Universal Cyber Security Framework for Consumer Based Internet of Things</h4>
                        <p class="text-sm text-gray-300">Dr. Ojari Dey-Foy</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-20 bg-black">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center old-gold">Education</h2>
            
            <div class="max-w-2xl mx-auto">
                <div class="bg-gray-900 p-8 rounded-lg shadow-lg">
                    <div class="flex items-start mb-6">
                        <div class="bg-old-gold text-black rounded-full w-12 h-12 flex items-center justify-center mr-4 flex-shrink-0">
                            <i class="fas fa-graduation-cap text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold old-gold">Capella University</h3>
                            <p class="text-gray-300">Doctorate of Information Technology, Cyber-Security/Information Assurance</p>
                            <p class="text-gray-400">2016 - 2019</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="bg-old-gold text-black rounded-full w-12 h-12 flex items-center justify-center mr-4 flex-shrink-0">
                            <i class="fas fa-university text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold old-gold">American Intercontinental University</h3>
                            <p class="text-gray-300">Masters, IT- Network Security</p>
                            <p class="text-gray-400">2007 - 2009</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-900">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center old-gold">Contact Me</h2>
            
            <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold old-gold mb-6">Get In Touch</h3>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-10 h-10 flex items-center justify-center mr-4 mt-1 flex-shrink-0">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-medium old-gold">Email</h4>
                                <a href="mailto:deyfoy@gmail.com" class="text-gray-300 hover:text-old-gold transition">deyfoy@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-10 h-10 flex items-center justify-center mr-4 mt-1 flex-shrink-0">
                                <i class="fab fa-linkedin-in"></i>
                            </div>
                            <div>
                                <h4 class="font-medium old-gold">LinkedIn</h4>
                                <a href="https://www.linkedin.com/in/ojari-dey-foy" target="_blank" class="text-gray-300 hover:text-old-gold transition">linkedin.com/in/ojari-dey-foy</a>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-old-gold text-black rounded-full w-10 h-10 flex items-center justify-center mr-4 mt-1 flex-shrink-0">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-medium old-gold">Location</h4>
                                <p class="text-gray-300">Washington DC-Baltimore Area</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold old-gold mb-6">Send a Message</h3>
                    <form>
                        <div class="mb-4">
                            <label for="name" class="block text-gray-300 mb-2">Name</label>
                            <input type="text" id="name" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:border-old-gold">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block text-gray-300 mb-2">Email</label>
                            <input type="email" id="email" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:border-old-gold">
                        </div>
                        <div class="mb-4">
                            <label for="message" class="block text-gray-300 mb-2">Message</label>
                            <textarea id="message" rows="4" class="w-full bg-gray-700 border border-gray-600 rounded px-4 py-2 focus:outline-none focus:border-old-gold"></textarea>
                        </div>
                        <button type="submit" class="bg-old-gold text-black px-6 py-3 rounded font-semibold hover:bg-yellow-600 transition w-full">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-8 border-t border-gray-800">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <p class="text-gray-400">© 2023 Dr. Ojari Dey-Foy. All rights reserved.</p>
                </div>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover-old-gold transition">
                        <i class="fab fa-linkedin-in text-xl"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover-old-gold transition">
                        <i class="fab fa-twitter text-xl"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover-old-gold transition">
                        <i class="fab fa-github text-xl"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Mobile menu toggle functionality would go here
        // This is a placeholder for actual implementation
        const mobileMenuButton = document.querySelector('.md:hidden');
        mobileMenuButton.addEventListener('click', () => {
            alert('Mobile menu would open here in a full implementation');
        });
    </script>
</body>
</html>
