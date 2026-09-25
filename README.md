<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankit | Economics & Data</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Permanent+Marker&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #0d0d12;
            color: #ffffff;
            font-family: 'Inter', sans-serif;
            overflow-x: hidden;
        }
        .font-marker {
            font-family: 'Permanent Marker', cursive;
        }
        .neon-border {
            border: 2px solid #8b5cf6;
            box-shadow: 0 0 15px rgba(139, 92, 246, 0.3);
        }
        .card-bg {
            background: linear-gradient(145deg, #1a1a24, #121219);
        }
    </style>
</head>
<body class="antialiased selection:bg-[#ccff00] selection:text-black">

    <!-- Navigation -->
    <nav class="flex justify-between items-center p-8 max-w-7xl mx-auto">
        <div class="font-marker text-2xl tracking-wider text-white">ANKIT.</div>
        <div class="hidden md:flex gap-8 text-sm font-semibold text-gray-300">
            <a href="#" class="hover:text-[#ccff00] transition">Home</a>
            <a href="#projects" class="hover:text-[#ccff00] transition">Projects</a>
            <a href="#about" class="hover:text-[#ccff00] transition">About</a>
        </div>
        <button class="bg-[#8b5cf6] w-10 h-10 rounded-full flex items-center justify-center hover:scale-105 transition">
            <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
        </button>
    </nav>

    <!-- Hero Section -->
    <header class="relative max-w-7xl mx-auto px-8 pt-12 pb-24 flex flex-col md:flex-row items-center justify-between">
        <div class="md:w-3/5 z-10">
            <p class="font-marker text-2xl text-[#ccff00] mb-2 transform -rotate-2">Hey, I'm</p>
            <h1 class="font-marker text-7xl md:text-9xl tracking-tighter text-white mb-6 uppercase drop-shadow-lg">
                ANKIT
            </h1>
            <p class="text-xl text-gray-300 font-semibold mb-8 tracking-wide">
                Economics <span class="text-[#8b5cf6]">•</span> Data Analytics <span class="text-[#8b5cf6]">•</span> Storyteller
            </p>
            <div class="flex gap-4">
                <a href="#projects" class="bg-[#ccff00] text-black font-bold py-3 px-8 rounded-full hover:bg-white transition transform hover:scale-105 flex items-center gap-2">
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z"></path></svg>
                    Explore Data
                </a>
                <a href="#contact" class="border-2 border-gray-600 text-white font-bold py-3 px-8 rounded-full hover:border-[#ccff00] hover:text-[#ccff00] transition">
                    View GitHub ↗
                </a>
            </div>
        </div>
        
        <!-- Placeholder for Character Illustration -->
        <div class="md:w-2/5 mt-12 md:mt-0 relative">
            <div class="absolute inset-0 bg-[#8b5cf6] rounded-full blur-[100px] opacity-30"></div>
            <img src="https://api.dicebear.com/7.x/notionists/svg?seed=Ankit&backgroundColor=transparent" alt="Character Illustration" class="relative z-10 w-full max-w-md mx-auto drop-shadow-2xl hover:scale-105 transition duration-500" />
            <!-- Floating Elements -->
            <div class="absolute top-10 right-10 text-4xl animate-bounce">☕</div>
            <div class="absolute bottom-10 left-0 text-4xl animate-pulse">📊</div>
        </div>
    </header>

    <!-- Featured Projects -->
    <section id="projects" class="max-w-7xl mx-auto px-8 py-16">
        <h2 class="font-marker text-3xl md:text-4xl mb-10 text-white">FEATURED PROJECTS <span class="text-[#8b5cf6]">~</span></h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Project 1 -->
            <div class="card-bg p-4 rounded-3xl hover:-translate-y-2 transition duration-300 border border-gray-800">
                <div class="h-48 rounded-2xl bg-[#2a2a35] mb-4 overflow-hidden relative">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=500&q=80" class="object-cover w-full h-full opacity-70 hover:opacity-100 transition" />
                </div>
                <h3 class="font-bold text-lg text-white">Market Analysis</h3>
                <p class="text-sm text-gray-400">R & Econometrics</p>
            </div>
            <!-- Project 2 -->
            <div class="card-bg p-4 rounded-3xl hover:-translate-y-2 transition duration-300 border border-gray-800">
                <div class="h-48 rounded-2xl bg-[#2a2a35] mb-4 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=500&q=80" class="object-cover w-full h-full opacity-70 hover:opacity-100 transition" />
                </div>
                <h3 class="font-bold text-lg text-white">Financial Trends</h3>
                <p class="text-sm text-gray-400">Python & Pandas</p>
            </div>
            <!-- Project 3 -->
            <div class="card-bg p-4 rounded-3xl hover:-translate-y-2 transition duration-300 border border-gray-800">
                <div class="h-48 rounded-2xl bg-[#2a2a35] mb-4 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=500&q=80" class="object-cover w-full h-full opacity-70 hover:opacity-100 transition" />
                </div>
                <h3 class="font-bold text-lg text-white">Data Visualization</h3>
                <p class="text-sm text-gray-400">PowerBI & SQL</p>
            </div>
            <!-- Project 4 -->
            <div class="card-bg p-4 rounded-3xl hover:-translate-y-2 transition duration-300 border border-gray-800">
                <div class="h-48 rounded-2xl bg-[#2a2a35] mb-4 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?auto=format&fit=crop&w=500&q=80" class="object-cover w-full h-full opacity-70 hover:opacity-100 transition" />
                </div>
                <h3 class="font-bold text-lg text-white">AI Workflows</h3>
                <p class="text-sm text-gray-400">Generative Prompts</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="max-w-7xl mx-auto px-8 py-16 flex flex-col md:flex-row items-center gap-12">
        <h2 class="font-marker text-4xl text-white">SKILLS</h2>
        <div class="flex flex-wrap gap-4 items-center">
            <img src="https://skillicons.dev/icons?i=python,r,mysql,pandas,git,github&theme=dark" alt="Skills" class="h-16 hover:scale-105 transition" />
            <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" class="rounded-lg h-12" />
            <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" class="rounded-lg h-12" />
        </div>
    </section>

    <!-- About Me -->
    <section id="about" class="max-w-7xl mx-auto px-8 py-16">
        <div class="neon-border rounded-3xl p-1 relative overflow-hidden">
            <div class="card-bg rounded-[22px] p-8 md:p-12 flex flex-col md:flex-row gap-8 items-center">
                <div class="md:w-1/3 flex justify-center">
                    <div class="bg-[#ccff00] text-black font-marker text-2xl p-6 rounded-2xl transform -rotate-3 text-center shadow-lg">
                        BOOKS<br/>+ PLANTS<br/>+ COFFEE
                    </div>
                </div>
                <div class="md:w-2/3">
                    <h2 class="font-marker text-3xl mb-4">ABOUT ME</h2>
                    <p class="text-gray-300 leading-relaxed mb-4 text-lg">
                        I'm an MSc Economics student at GIPE Pune, finding stories hidden in data. I enjoy exploring the connection between data, finance, and the real world. 
                    </p>
                    <p class="text-gray-400 leading-relaxed">
                        Currently learning new tools, working on projects, and building my journey toward becoming a data analyst. When I'm not studying, you'll find me with a good book, a coffee, and my cats.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-gray-800 mt-20 pb-12 pt-12">
        <div class="max-w-7xl mx-auto px-8 flex flex-col md:flex-row justify-between items-center gap-8">
            <h2 class="font-marker text-3xl md:text-4xl text-white">
                LET'S FIND <span class="text-[#ccff00]">STORIES</span><br/>IN DATA!
            </h2>
            <div class="text-gray-400 flex flex-col gap-2">
                <div class="flex items-center gap-2">
                    <span>📍</span> Pune, India
                </div>
                <div class="flex items-center gap-2">
                    <span>🎓</span> MSc Economics
                </div>
            </div>
            <div class="flex gap-4">
                <a href="#" class="w-12 h-12 rounded-full bg-gray-800 flex items-center justify-center hover:bg-[#8b5cf6] transition text-white">IN</a>
                <a href="#" class="w-12 h-12 rounded-full bg-gray-800 flex items-center justify-center hover:bg-[#8b5cf6] transition text-white">GH</a>
            </div>
        </div>
    </footer>

</body>
</html>
