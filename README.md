<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Excelyno's GitHub Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;700&family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Custom Styles */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
        }
        .font-firacode {
            font-family: 'Fira Code', monospace;
        }
        .glass-card {
            background: rgba(22, 27, 34, 0.6);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(48, 54, 61, 0.5);
        }
        .tech-icon {
            transition: transform 0.3s ease, filter 0.3s ease;
        }
        .tech-icon:hover {
            transform: scale(1.15) translateY(-5px);
            filter: drop-shadow(0 0 8px rgba(56, 194, 255, 0.7));
        }
        .stat-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.3), 0 8px 10px -6px rgba(56, 194, 255, 0.2);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .fade-in {
            animation: fadeIn 0.8s ease-out forwards;
        }
        .delay-1 { animation-delay: 0.2s; }
        .delay-2 { animation-delay: 0.4s; }
        .delay-3 { animation-delay: 0.6s; }
        .delay-4 { animation-delay: 0.8s; }
        
        .separator {
            height: 2px;
            background: linear-gradient(90deg, transparent, #38c2ff, transparent);
            border: 0;
            margin: 4rem 0;
        }
    </style>
</head>
<body class="antialiased">
    <div class="container mx-auto p-4 md:p-8 max-w-6xl">
        
        <!-- === HEADER === -->
        <header class="text-center mb-12 fade-in">
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=32&pause=1000&color=38C2FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Excelyno!+👋;A+Passionate+Software+Engineer;Welcome+to+My+Digital+Playground!" alt="Typing SVG" class="mx-auto" />
            <p class="text-gray-400 mt-4 text-lg">Student at University of Jember, exploring the universe of code and automation.</p>
            <div class="flex justify-center space-x-4 mt-6">
                <a href="mailto:excellentqweee@gmail.com" class="tech-icon"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
                <a href="https://github.com/excelyno" class="tech-icon"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
                <a href="https://linkedin.com/in/your-linkedin-username" class="tech-icon"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
                <a href="https://instagram.com/your-instagram-username" class="tech-icon"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
            </div>
        </header>

        <!-- === ABOUT ME & VISUAL === -->
        <section class="grid md:grid-cols-5 gap-8 items-center mb-16 fade-in delay-1">
            <div class="md:col-span-3 glass-card p-8 rounded-2xl">
                <h2 class="text-3xl font-bold font-firacode mb-4 text-white"><span class="text-[#38C2FF]">></span> About Me</h2>
                <p class="mb-4">
                    Hello! I'm a dedicated Software Engineering student with a deep passion for DevOps and cloud technologies. My journey is all about bridging the gap between development and operations, building robust CI/CD pipelines, and automating everything I can.
                </p>
                <ul class="list-disc list-inside space-y-2 text-gray-300">
                    <li>🔭 Currently mastering <strong class="text-white">Docker, Kubernetes, and GitHub Actions</strong>.</li>
                    <li>🌱 Exploring the world of <strong class="text-white">Infrastructure as Code (IaC)</strong> with Terraform.</li>
                    <li>💬 Ask me about backend development, system architecture, or my DevOps projects.</li>
                    <li>⚡ Fun fact: I'm a nocturnal creature; my best code is written when the moon is high! 🦉</li>
                </ul>
            </div>
            <div class="md:col-span-2 flex items-center justify-center">
                <img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" alt="Coding Illustration" class="w-full max-w-sm h-auto">
            </div>
        </section>

        <hr class="separator">

        <!-- === TECH STACK === -->
        <section class="text-center mb-16 fade-in delay-2">
            <h2 class="text-3xl font-bold font-firacode mb-8 text-white"><span class="text-[#38C2FF]">></span> My Tech Arsenal</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <!-- Languages -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-xl font-bold mb-4 text-white">Languages</h3>
                    <div class="flex justify-center flex-wrap gap-4">
                        <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" class="tech-icon"/>
                    </div>
                </div>
                <!-- Backend -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-xl font-bold mb-4 text-white">Backend</h3>
                    <div class="flex justify-center flex-wrap gap-4">
                        <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" class="tech-icon"/>
                    </div>
                </div>
                <!-- Databases -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-xl font-bold mb-4 text-white">Databases</h3>
                    <div class="flex justify-center flex-wrap gap-4">
                        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" class="tech-icon"/>
                    </div>
                </div>
                <!-- DevOps & Tools -->
                <div class="glass-card p-6 rounded-2xl">
                    <h3 class="text-xl font-bold mb-4 text-white">DevOps & Tools</h3>
                    <div class="flex justify-center flex-wrap gap-4">
                        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" class="tech-icon"/>
                        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions" class="tech-icon"/>
                    </div>
                </div>
            </div>
        </section>

        <hr class="separator">

        <!-- === GITHUB STATS === -->
        <section class="text-center mb-16 fade-in delay-3">
            <h2 class="text-3xl font-bold font-firacode mb-8 text-white"><span class="text-[#38C2FF]">></span> GitHub Statistics</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <img src="https://github-readme-stats.vercel.app/api?username=excelyno&show_icons=true&theme=catppuccin_dark&include_all_commits=true&count_private=true" alt="Excelyno's GitHub Stats" class="w-full h-auto rounded-lg stat-card"/>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=excelyno&layout=compact&langs_count=8&theme=catppuccin_dark" alt="Top Languages" class="w-full h-auto rounded-lg stat-card"/>
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=excelyno&theme=catppuccin_dark&hide_border=true" alt="GitHub Streak" class="w-full md:col-span-2 h-auto rounded-lg stat-card"/>
            </div>
            <div class="mt-6">
                 <img src="https://github-profile-trophy.vercel.app/?username=excelyno&theme=catppuccin_dark&column=8&margin-w=15&margin-h=15" alt="GitHub Trophies" class="mx-auto stat-card rounded-lg"/>
            </div>
        </section>
        
        <!-- === CONTRIBUTION GRAPH === -->
        <section class="text-center mb-16 fade-in delay-4">
            <h2 class="text-3xl font-bold font-firacode mb-8 text-white"><span class="text-[#38C2FF]">></span> Contribution Snake</h2>
            <div class="glass-card p-4 rounded-2xl flex justify-center">
                <picture>
                  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg">
                  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
                  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
                </picture>
            </div>
        </section>

        <hr class="separator">

        <!-- === FOOTER === -->
        <footer class="text-center fade-in delay-4">
             <h3 class="text-xl font-bold text-white mb-4">Wanna Support My Work?</h3>
             <a href="https://www.buymeacoffee.com/excelyno" target="_blank" class="inline-block transition-transform hover:scale-105">
                <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" class="h-14">
             </a>
             <div class="mt-8">
                <img src="https://komarev.com/ghpvc/?username=excelyno&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" class="mx-auto"/>
                <p class="text-sm text-gray-500 mt-4">
                    &copy; 2024 Excelyno. Built with Passion & Code.
                </p>
             </div>
        </footer>

    </div>
</body>
</html>
