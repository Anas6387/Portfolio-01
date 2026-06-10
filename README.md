# Portfolio-01

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anas Portfolio</title>

<script src="https://cdn.tailwindcss.com"></script>

<style>
body{
background:#050816;
color:white;
scroll-behavior:smooth;
}

.gradient{
background:linear-gradient(90deg,#8b5cf6,#06b6d4);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.glass{
background:rgba(255,255,255,0.05);
backdrop-filter:blur(10px);
border:1px solid rgba(255,255,255,0.1);
}
</style>

</head>

<body>

<nav class="fixed w-full bg-black/50 backdrop-blur-md z-50">
<div class="max-w-7xl mx-auto px-6 py-4 flex justify-between">
<h1 class="font-bold text-2xl gradient">Anas</h1>

<div class="space-x-6">
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</div>
</nav>

<section class="min-h-screen flex items-center justify-center px-8">

<div class="grid md:grid-cols-2 gap-10 items-center">

<div>

<h3 class="text-purple-400 text-xl">
Hi, I'm
</h3>

<h1 class="text-7xl font-bold gradient">
Anas
</h1>

<h2 class="text-3xl mt-4">
Data Science Enthusiast |
GenAI Builder
</h2>

<p class="mt-6 text-gray-300">
Building AI, Data Analytics and
Machine Learning solutions.
Passionate about creating impactful
technology products.
</p>

<div class="mt-8 flex gap-4">
<a href="#contact"
class="bg-purple-600 px-6 py-3 rounded-xl">
Contact Me
</a>

<a href="#projects"
class="border border-cyan-400 px-6 py-3 rounded-xl">
Projects
</a>
</div>

</div>

<div class="flex justify-center">

<img
src="profile.jpg"
alt="Anas"
class="w-96 rounded-3xl shadow-2xl"
/>

</div>

</div>

</section>

<section id="about" class="py-20 px-8">

<div class="max-w-6xl mx-auto">

<div class="glass p-8 rounded-3xl">

<h2 class="text-4xl font-bold mb-6">
About Me
</h2>

<p class="text-gray-300 leading-8">
I am Anas, a B.Tech student interested in
Data Science, AI, Machine Learning and
Generative AI applications.
I enjoy solving real-world problems using
technology and continuously improving my skills.
</p>

</div>

</div>

</section>

<section id="skills" class="py-20 px-8">

<div class="max-w-6xl mx-auto">

<h2 class="text-4xl font-bold mb-10">
Skills
</h2>

<div class="grid md:grid-cols-4 gap-4">

<div class="glass p-5 rounded-2xl">Python</div>
<div class="glass p-5 rounded-2xl">SQL</div>
<div class="glass p-5 rounded-2xl">Power BI</div>
<div class="glass p-5 rounded-2xl">Machine Learning</div>
<div class="glass p-5 rounded-2xl">Pandas</div>
<div class="glass p-5 rounded-2xl">NumPy</div>
<div class="glass p-5 rounded-2xl">Data Analytics</div>
<div class="glass p-5 rounded-2xl">Generative AI</div>

</div>

</div>

</section>

<section id="projects" class="py-20 px-8">

<div class="max-w-6xl mx-auto">

<h2 class="text-4xl font-bold mb-10">
Projects
</h2>

<div class="grid md:grid-cols-3 gap-8">

<div class="glass p-6 rounded-3xl">

<h3 class="text-2xl font-bold">
AI Resume Screener
</h3>

<p class="mt-4 text-gray-300">
AI-powered resume screening system
for candidate ranking.
</p>

</div>

<div class="glass p-6 rounded-3xl">

<h3 class="text-2xl font-bold">
Sales Dashboard
</h3>

<p class="mt-4 text-gray-300">
Power BI dashboard for business insights.
</p>

</div>

<div class="glass p-6 rounded-3xl">

<h3 class="text-2xl font-bold">
GenAI Assistant
</h3>

<p class="mt-4 text-gray-300">
LLM-powered chatbot assistant.
</p>

</div>

</div>

</div>

</section>

<section id="contact" class="py-20 px-8">

<div class="max-w-4xl mx-auto">

<div class="glass p-10 rounded-3xl">

<h2 class="text-4xl font-bold mb-8">
Contact Me
</h2>

<form class="space-y-5">

<input
type="text"
placeholder="Your Name"
class="w-full p-4 bg-black/30 rounded-xl"
/>

<input
type="email"
placeholder="Your Email"
class="w-full p-4 bg-black/30 rounded-xl"
/>

<textarea
rows="5"
placeholder="Message"
class="w-full p-4 bg-black/30 rounded-xl">
</textarea>

<button
class="bg-purple-600 px-8 py-4 rounded-xl">
Send Message
</button>

</form>

</div>

</div>

</section>

<footer class="text-center py-8 text-gray-400">
© 2026 Anas Portfolio
</footer>

</body>
</html>
