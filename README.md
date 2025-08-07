<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samruthi's GitHub Profile</title>
    <!-- Use Tailwind CSS for a modern, responsive layout -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for a dark theme and modern look */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub's dark theme background color */
            color: #c9d1d9; /* Light text color for readability */
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }
        .section-title {
            position: relative;
            font-size: 2.5rem;
            font-weight: 700;
            color: #58a6ff; /* A vibrant color for titles */
            margin-bottom: 1.5rem;
            text-shadow: 0 0 5px #58a6ff;
            text-align: center;
        }
        /* Style for the project cards with a hover effect */
        .project-card {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .project-card:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }
        /* Typing animation for the welcome message */
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #c9d1d9 }
        }
        #typing-text {
            overflow: hidden; /* Ensures the text is not visible until typed */
            border-right: .15em solid #c9d1d9; /* The blinking cursor */
            white-space: nowrap; /* Keeps the text on a single line */
            margin: 0 auto;
            letter-spacing: .1em;
            animation: 
                typing 3.5s steps(40, end),
                blink-caret .75s step-end infinite;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">
    <div class="container">
        <!-- Welcome Message Section with Typing Effect -->
        <header class="text-center mb-12">
            <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2FwMHV0a3g3ZTFsaXpkOGs5NThvYW95ZWhqYmd0ZmNqY2ZsdmVmMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/b2z6g3U47g3VjC3X3N/giphy.gif" alt="Wave GIF" class="mx-auto" width="100">
            <h1 id="typing-text" class="text-4xl sm:text-5xl font-bold mt-4 mb-2 overflow-hidden border-r-2 border-white whitespace-nowrap animate-typing"></h1>
            <p class="text-lg text-gray-400 mt-2">I am a passionate Full Stack Developer and Artificial Intelligence enthusiast, constantly exploring the intersection of creativity and code.</p>
        </header>

        <!-- About Me Section -->
        <section class="mb-12 p-6 bg-gray-800 rounded-xl shadow-lg">
            <h2 class="section-title">🚀 About Me</h2>
            <ul class="list-disc list-inside space-y-2 text-lg">
                <li>🎓 I'm a student at KGiSL Institute of Technology, with a core academic subject in Data Science.</li>
                <li>💻 My passion lies in building robust full-stack applications and diving deep into the world of Artificial Intelligence.</li>
                <li>🌱 I am always learning and eager to take on new challenges to solve real-world problems with technology.</li>
            </ul>
        </section>

        <!-- Tech Stack Section -->
        <section class="mb-12 p-6 bg-gray-800 rounded-xl shadow-lg">
            <h2 class="section-title">🛠️ My Tech Stack</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <!-- Tech Stack Badges -->
                <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge">
                <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge">
                <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge">
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
                <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Badge">
                <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js Badge">
                <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge">
                <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB Badge">
                <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git Badge">
                <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
            </div>
        </section>

        <!-- Featured Projects Section -->
        <section class="mb-12 p-6 bg-gray-800 rounded-xl shadow-lg">
            <h2 class="section-title">📂 Featured Projects</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Project Card 1 with Hover Effect -->
                <div class="project-card p-6 bg-gray-700 rounded-xl shadow-lg border border-gray-600">
                    <h3 class="text-2xl font-semibold mb-2 text-blue-300">Project Name 1</h3>
                    <p class="text-gray-300 mb-4">A short and engaging description of your project's purpose and functionality.</p>
                    <div class="flex flex-wrap gap-2 text-sm text-gray-400">
                        <span>#React</span>
                        <span>#Node.js</span>
                        <span>#MongoDB</span>
                    </div>
                    <div class="mt-4">
                        <a href="https://github.com/your-username/your-project-1" class="text-blue-400 hover:text-blue-200 transition-colors duration-200 font-medium">View on GitHub →</a>
                        <span class="mx-2">|</span>
                        <a href="https://your-project-1-demo-link.com" class="text-blue-400 hover:text-blue-200 transition-colors duration-200 font-medium">Live Demo →</a>
                    </div>
                </div>
                <!-- Project Card 2 with Hover Effect -->
                <div class="project-card p-6 bg-gray-700 rounded-xl shadow-lg border border-gray-600">
                    <h3 class="text-2xl font-semibold mb-2 text-blue-300">Project Name 2</h3>
                    <p class="text-gray-300 mb-4">Another compelling description, highlighting the key features of your project.</p>
                    <div class="flex flex-wrap gap-2 text-sm text-gray-400">
                        <span>#Python</span>
                        <span>#Flask</span>
                        <span>#MySQL</span>
                    </div>
                    <div class="mt-4">
                        <a href="https://github.com/your-username/your-project-2" class="text-blue-400 hover:text-blue-200 transition-colors duration-200 font-medium">View on GitHub →</a>
                        <span class="mx-2">|</span>
                        <a href="https://your-project-2-demo-link.com" class="text-blue-400 hover:text-blue-200 transition-colors duration-200 font-medium">Live Demo →</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- GitHub Stats Section -->
        <section class="mb-12 p-6 bg-gray-800 rounded-xl shadow-lg text-center">
            <h2 class="section-title">📊 GitHub Stats</h2>
            <div class="flex flex-wrap justify-center items-center gap-4">
                <img src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&theme=dark" alt="Samruthi's GitHub Stats" class="w-full md:w-auto rounded-lg">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-username&theme=dark&layout=compact" alt="Top Languages" class="w-full md:w-auto rounded-lg">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=your-username&theme=dark" alt="GitHub Streak" class="w-full md:w-auto rounded-lg">
            </div>
            <p class="mt-4 text-sm text-gray-500">⚠️ **Note:** Replace `your-username` with your actual GitHub username to display your stats.</p>
        </section>

        <!-- Fun & Interests Section -->
        <section class="mb-12 p-6 bg-gray-800 rounded-xl shadow-lg">
            <h2 class="section-title">❤️ Fun & Interests</h2>
            <ul class="list-disc list-inside space-y-2 text-lg">
                <li>I believe in using technology as a force for good to solve real-world problems.</li>
                <li>I'm always open to connecting with other developers, learning new things, and collaborating on exciting team projects.</li>
            </ul>
        </section>

        <!-- Contact Me Section -->
        <section class="p-6 bg-gray-800 rounded-xl shadow-lg text-center">
            <h2 class="section-title">📧 Contact Me</h2>
            <div class="flex justify-center gap-4">
                <a href="https://linkedin.com/in/your-linkedin-profile"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/></a>
                <a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/></a>
            </div>
            <p class="mt-4 text-sm text-gray-500">⚠️ **Note:** Replace the placeholder links and emails with your actual information.</p>
        </section>
    </div>

    <script>
        // JavaScript for the typing effect on the H1 tag
        window.onload = function() {
            const textElement = document.getElementById('typing-text');
            const textToType = "Hey there, I'm Samruthi Gurusamy! 👋";
            let i = 0;
            const speed = 75; // Typing speed in milliseconds

            function typeWriter() {
                if (i < textToType.length) {
                    textElement.innerHTML += textToType.charAt(i);
                    i++;
                    setTimeout(typeWriter, speed);
                }
            }

            typeWriter();
        };
    </script>
</body>
</html>
