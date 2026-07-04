Hemanth Gantinapalli — Portfolio

A single-file, self-contained developer portfolio built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies to install.

Live demo: add your deployed URL here once live

Show Image Show Image


✨ Features


Terminal-style hero — animated typing sequence introducing who I am and what I build
Interactive stack visualization — click each layer (React → Express → Node → MongoDB) to expand related skills
Git-log styled experience timeline
Terminal-window project cards for FoodCourt, ThinkPlus, and Online Shopping Platform
One-click resume download — PDF is embedded directly in the page (no server required)
Fully responsive — collapses to a mobile-friendly layout with a hamburger nav
Scroll-reveal animations and active-section nav highlighting
Real social links — LinkedIn, GitHub, LeetCode, HackerRank, CodeChef


🛠 Tech Stack


HTML5
CSS3 (custom properties, grid, flexbox — no frameworks)
Vanilla JavaScript (IntersectionObserver, DOM APIs — no libraries)
Google Fonts: JetBrains Mono, Space Grotesk, Inter


📁 Project Structure

portfolio/
└── index.html   # everything lives in this one file

There are no build tools, package managers, or external dependencies beyond the Google Fonts CDN link.

🚀 Deployment

Since this is a static single-file site, it can be deployed anywhere that serves static files.

GitHub Pages


Rename portfolio.html to index.html
Push it to a repo (e.g. hemanthgantinapalli-ai.github.io for a root-domain site, or any repo name for a project site)
Go to Settings → Pages and set the source to your main branch
Your site goes live at https://<username>.github.io or https://<username>.github.io/<repo-name>


Netlify


Go to app.netlify.com/drop
Drag and drop index.html
Get a live URL instantly


Vercel / Cloudflare Pages

Both support drag-and-drop or GitHub-connected deploys of static sites with zero configuration.

✏️ Customizing

Everything — copy, colors, links, projects — lives directly in index.html:

What to changeWhereName, role, summary<section id="home"> and <section id="about">Skills / stack layers<section id="stack">Work experience<section id="experience">Projects<section id="projects">Certifications<section id="certifications">Contact info & social links<section id="contact"> and the hero .social-rowColors / fontsCSS :root variables near the top of the <style> blockResume PDFReplace the RESUME_B64 base64 string in the <script> at the bottom

📄 License

Personal project — feel free to fork the structure for your own portfolio, but please swap in your own content, resume, and photo before publishing.

📬 Contact


Email: hemanthgantinapalli@gmail.com
LinkedIn: hemanth-gantinapalli
GitHub: hemanthgantinapalli-ai
LeetCode: Hemanth_089
HackerRank: hemanthgantinap1
CodeChef: hemanth_0785
