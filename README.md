<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Hoang — Fullstack Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      .glow:hover {
        box-shadow: 0 0 15px #00ffe5;
        transition: all 0.3s ease-in-out;
      }

      .fade-in {
        opacity: 0;
        animation: fadeIn 2s ease-in forwards;
      }

      @keyframes fadeIn {
        0% { opacity: 0; transform: translateY(20px); }
        100% { opacity: 1; transform: translateY(0); }
      }
    </style>
  </head>

  <body class="bg-[#0f172a] text-white font-sans">
    <!-- Hero section -->
    <section class="min-h-screen flex flex-col justify-center items-center text-center px-4">
      <h1 class="text-5xl md:text-6xl font-bold text-cyan-300 fade-in">Hey, I'm Hoang 👋</h1>
      <p class="mt-4 text-lg md:text-xl max-w-xl fade-in text-slate-300">
        I'm a passionate <span class="text-pink-400">Fullstack Developer</span> from Vietnam 🇻🇳,
        crafting delightful web experiences with React, Next.js, Node.js & a touch of creativity ✨
      </p>

      <div class="mt-6 flex gap-4 fade-in">
        <a href="https://github.com/hanbiro" class="glow bg-gray-800 px-5 py-2 rounded-full hover:bg-gray-700">GitHub</a>
        <a href="mailto:your.email@example.com" class="glow bg-cyan-600 px-5 py-2 rounded-full hover:bg-cyan-500">Email</a>
        <a href="https://linkedin.com/in/your-link" class="glow bg-blue-600 px-5 py-2 rounded-full hover:bg-blue-500">LinkedIn</a>
      </div>
    </section>

    <!-- SVG Wave Divider -->
    <svg class="-mb-1 w-full" viewBox="0 0 1440 150">
      <path fill="#1e293b" fill-opacity="1" d="M0,32L60,53.3C120,75,240,117,360,138.7C480,160,600,160,720,144C840,128,960,96,1080,85.3C1200,75,1320,85,1380,90.7L1440,96V0H1380C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0H0Z"></path>
    </svg>

    <!-- Skills Section -->
    <section class="bg-[#1e293b] py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold text-cyan-400 fade-in">🛠 My Tech Stack</h2>
      <p class="text-slate-300 mt-2 mb-6 fade-in">Technologies I work with:</p>
      <div class="flex flex-wrap justify-center gap-4 fade-in">
        <span class="px-4 py-2 bg-slate-700 rounded-lg">React</span>
        <span class="px-4 py-2 bg-slate-700 rounded-lg">Next.js</span>
        <span class="px-4 py-2 bg-slate-700 rounded-lg">Node.js</span>
        <span class="px-4 py-2 bg-slate-700 rounded-lg">TailwindCSS</span>
        <span class="px-4 py-2 bg-slate-700 rounded-lg">MongoDB</span>
        <span class="px-4 py-2 bg-slate-700 rounded-lg">TypeScript</span>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-6 text-center text-sm text-gray-400">
      🚀 Designed with love by Hoang | Powered by TailwindCSS & GitHub Pages
    </footer>
  </body>
</html>
