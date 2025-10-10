<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darius Thompson | Personal Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Using Inter font, falling back to system sans-serif */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom scrollbar style for aesthetics */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-thumb {
            background: #2563eb; /* Blue accent color */
            border-radius: 4px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        /* Style for the accent color */
        .text-accent {
            color: #2563eb; /* Blue-600 */
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Name -->
                <a href="#" class="text-2xl font-bold text-gray-900 tracking-tight hover:text-accent transition duration-300">
                    Darius Thompson
                </a>
                
                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#about" class="text-gray-600 hover:text-accent font-medium transition duration-300">About</a>
                    <a href="#skills" class="text-gray-600 hover:text-accent font-medium transition duration-300">Skills</a>
                    <a href="#contact" class="text-gray-600 hover:text-accent font-medium transition duration-300">Contact</a>
                </nav>
            </div>
        </div>
    </header>
index.html
    <!-- Main Content -->
    <main>
        
        <!-- Hero Section -->
        <section class="py-16 md:py-24 bg-gray-100" id="hero">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="flex flex-col md:flex-row items-center justify-between gap-12">
                    <!-- Text Content -->
                    <div class="md:w-1/2 text-center md:text-left">
                        <p class="text-xl font-semibold text-accent mb-2">Hello, I'm</p>
                        <h1 class="text-5xl md:text-6xl font-extrabold text-gray-900 leading-tight mb-4">
                            Darius Leekla Thompson
                        </h1>
                        <p class="text-2xl text-gray-600 mb-6">
                            A <span class="font-semibold">Future Software Engineer</span> and <span class="font-semibold">Visionary Leader</span> committed to technological empowerment.
                        </p>
                        <a href="#contact" class="inline-block px-8 py-3 bg-accent text-white font-bold rounded-xl shadow-lg hover:bg-blue-700 transition duration-300 transform hover:scale-105">
                            Get in Touch
                        </a>
                    </div>

                    <!-- Image Placeholder -->
                    <div class="md:w-1/3">
                        <img 
                            src="https://storage.googleapis.com/assist-canvas-storage-public/519420957_122211802844143793_1298500147794368981_n.jpg-8cd80ba7-22e9-4cd5-bb5b-5a752d15c4c8" 
                            onerror="this.onerror=null;this.src='https://placehold.co/400x400/1e293b/ffffff?text=Profile+Photo+Load+Error';" 
                            alt="Darius Thompson Profile Picture" 
                            class="w-full h-auto object-cover rounded-3xl shadow-2xl border-4 border-white transform rotate-3 hover:rotate-0 transition duration-500"
                        >
                    </div>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section class="py-16 md:py-24" id="about">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-gray-900 text-center mb-12 border-b-4 border-accent inline-block pb-1 mx-auto">About Me</h2>
                
                <div class="max-w-4xl mx-auto bg-white p-8 md:p-12 rounded-2xl shadow-xl transition duration-500 hover:shadow-2xl">
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        **Darius Leekla Thompson** is a young visionary who believes that growth and **technology can change lives for the better**. Smart, curious, and passionate about helping people, Darius has always seen technology as a way to empower others and build a brighter future for Liberia and beyond.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        Darius completed high school at Upper Room Christian Academy in Totota at the age of sixteen. His love for learning led him through Ganta United Methodist High School and into higher education, where he studied ICT with a focus on **System Administration** at Starz University. He is currently pursuing his dream by studying **Software Engineering** at BlueCrest University in Congo Town, Liberia.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        Beyond academics, Darius actively works with the Joseph B. Momo Memorial Academic and Technical School System in Maimu, Totota, where he shares his skills and supports educational development. He also serves as an intern in the **Marketing Department at BlueCrest University**, gaining valuable hands-on professional experience.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed font-bold text-gray-800">
                        Darius believes that success is not just about achieving personal goals, but about **lifting others along the way**. Through perseverance, learning, and service, he continues to shape himself into a leader who will use technology to transform lives and communities.
                    </p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="py-16 md:py-24 bg-gray-100" id="skills">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-gray-900 text-center mb-12 border-b-4 border-accent inline-block pb-1 mx-auto">My Expertise</h2>
                
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6 max-w-6xl mx-auto">
                    <!-- Skill Card 1: Software Engineering -->
                    <div class="bg-white p-6 rounded-xl shadow-lg text-center hover:shadow-xl transform hover:-translate-y-1 transition duration-300">
                        <div class="text-4xl mb-3 text-accent">💻</div>
                        <h3 class="font-bold text-gray-900 text-lg">Software Engineering</h3>
                        <p class="text-sm text-gray-500">Studying at BlueCrest University</p>
                    </div>
                    <!-- Skill Card 2: System Administration -->
                    <div class="bg-white p-6 rounded-xl shadow-lg text-center hover:shadow-xl transform hover:-translate-y-1 transition duration-300">
                        <div class="text-4xl mb-3 text-accent">⚙️</div>
                        <h3 class="font-bold text-gray-900 text-lg">System Admin (ICT)</h3>
                        <p class="text-sm text-gray-500">Core ICT & Networking Knowledge</p>
                    </div>
                    <!-- Skill Card 3: Educational Development -->
                    <div class="bg-white p-6 rounded-xl shadow-lg text-center hover:shadow-xl transform hover:-translate-y-1 transition duration-300">
                        <div class="text-4xl mb-3 text-accent">📚</div>
                        <h3 class="font-bold text-gray-900 text-lg">Educational Support</h3>
                        <p class="text-sm text-gray-500">JB Momo Memorial School System</p>
                    </div>
                    <!-- Skill Card 4: Marketing & Outreach -->
                    <div class="bg-white p-6 rounded-xl shadow-lg text-center hover:shadow-xl transform hover:-translate-y-1 transition duration-300">
                        <div class="text-4xl mb-3 text-accent">📈</div>
                        <h3 class="font-bold text-gray-900 text-lg">Professional Internship</h3>
                        <p class="text-sm text-gray-500">Marketing at BlueCrest University</p>
                    </div>
                    <!-- Skill Card 5: Leadership & Service -->
                    <div class="bg-white p-6 rounded-xl shadow-lg text-center hover:shadow-xl transform hover:-translate-y-1 transition duration-300">
                        <div class="text-4xl mb-3 text-accent">💡</div>
                        <h3 class="font-bold text-gray-900 text-lg">Vision & Empowerment</h3>
                        <p class="text-sm text-gray-500">Community and Tech Focus</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="py-16 md:py-24" id="contact">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-gray-900 text-center mb-12 border-b-4 border-accent inline-block pb-1 mx-auto">Get In Touch</h2>
                
                <div class="max-w-3xl mx-auto bg-white p-8 md:p-12 rounded-2xl shadow-xl">
                    <p class="text-center text-lg text-gray-600 mb-8">
                        Have a question or want to collaborate? Send me a message!
                    </p>
                    
                    <!-- Contact Information Grid -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8 text-center md:text-left">
                        <!-- Email -->
                        <div class="flex items-center justify-center md:justify-start space-x-3">
                            <span class="text-xl text-accent">📧</span>
                            <div>
                                <h3 class="font-semibold text-gray-900">Email</h3>
                                <p class="text-gray-700">dariusthompson804@gmail.com</p>
                            </div>
                        </div>
                        <!-- Phone -->
                        <div class="flex items-center justify-center md:justify-start space-x-3">
                            <span class="text-xl text-accent">📞</span>
                            <div>
                                <h3 class="font-semibold text-gray-900">Phone</h3>
                                <p class="text-gray-700">0887508069 / 0555045379</p>
                            </div>
                        </div>
                    </div>

                    <!-- Contact Form (Non-functional, for display only) -->
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
                            <input type="text" id="name" name="name" placeholder="Your Name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-accent focus:border-accent transition duration-300">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
                            <input type="email" id="email" name="email" placeholder="youremail@example.com" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-accent focus:border-accent transition duration-300">
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                            <textarea id="message" name="message" rows="4" placeholder="Your Message..." required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-accent focus:border-accent transition duration-300"></textarea>
                        </div>
                        <div>
                            <button type="submit" class="w-full px-8 py-3 bg-accent text-white font-bold rounded-xl shadow-lg hover:bg-blue-700 transition duration-300 transform hover:scale-[1.01]">
                                Send Message
                            </button>
                        </div>
                    </form>
                    
                    <!-- Note for the user about form functionality -->
                    <p class="text-xs text-center text-gray-500 mt-4">
                        <!-- This form is currently for display. In a live application, you would connect it to a backend service. -->
                    </p>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-400">
            <p>&copy; 2025 Darius Thompson. All rights reserved.</p>
            <div class="mt-4 space-x-4">
                <a href="https://linkedin.com/in/DariusThompson" target="_blank" class="hover:text-accent transition duration-300">LinkedIn (Darius Thompson)</a>
                <a href="https://facebook.com/DARIUS" target="_blank" class="hover:text-accent transition duration-300">Facebook (DA RI US)</a>
                <a href="mailto:dariusthompson804@gmail.com" class="hover:text-accent transition duration-300">Email</a>
            </div>
        </div>
    </footer>

</body>
</html>
