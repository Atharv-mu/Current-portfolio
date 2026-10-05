# Atharv Holkar | Portfolio

My personal portfolio website, built to show who I am, what I'm learning and the projects I've built so far. It is a single-page site written with plain HTML, CSS and JavaScript, with a small chat assistant that answers questions about me.

<p align="center">
  <a href="https://atharv-mu.github.io/Current-portfolio/"><img src="https://img.shields.io/badge/Live_Site-Visit-2b59e0?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live site"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

**Live site:** [atharv-mu.github.io/Current-portfolio](https://atharv-mu.github.io/Current-portfolio/)

---

## About me

I'm a B.Tech Computer Science Engineering student at Medi-Caps University and an aspiring web developer. I work with HTML, CSS and JavaScript, and I'm currently learning React, Node.js, Express.js and MongoDB to grow into a full-stack developer. My long-term goal is to build my own technology company, Athinyx.

## What's on the site

- **Intro screen:** a short "system breach, fixed by Atharv" terminal animation before the page loads. It can be skipped with one click.
- **Hero:** a quick introduction with my photo and links to my GitHub and LinkedIn.
- **Skills:** the technologies I work with and am learning, shown as a scrolling strip and grouped cards.
- **Experience and Education:** two timelines covering my roles at E-GyaanShala and Athinyx, and my degree.
- **Projects:** cards for the projects I've built, each with a link to the live version.
- **AI assistant:** a chat box where visitors can ask about my skills, projects, experience, education and how to reach me.
- **Light and dark theme:** dark by default, with a toggle in the header. The choice is remembered.
- **Responsive design:** works on phones, tablets and laptops.
- **Small details:** soft cursor lighting on cards, scroll animations and glowing skill chips. Animations are switched off for visitors who prefer reduced motion.

## Projects featured

| Project | What it is | Stack |
|---|---|---|
| [Nirvanova](https://nirvanova1.netlify.app/) | A smart tourism platform with destination information, location-based recommendations, travel services and emergency information | HTML5, CSS3, JavaScript, Netlify |
| [Teraquerry](https://teraquerry-production.up.railway.app/) | A backend platform that processes system metrics and operations, including a lead finder | Node.js, Express, Railway |
| [Distraction Removal](https://distraction-removal.onrender.com/) | A server-side productivity tool that helps cut distractions | MERN, REST API, Render |
| [Krishihal](https://krishihal.netlify.app/) | An agricultural marketplace connecting farmers directly with consumers for fairer prices. The frontend MVP is live; the backend is planned | HTML5, Tailwind CSS, JavaScript |

## Tech used

**Used to build this site**

![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css) ![JavaScript](https://skillicons.dev/icons?i=js) ![Netlify](https://skillicons.dev/icons?i=netlify) ![GitHub](https://skillicons.dev/icons?i=github) ![VS Code](https://skillicons.dev/icons?i=vscode)

- Plain HTML5, CSS3 and vanilla JavaScript (no framework, no build step)
- Google Fonts: Bricolage Grotesque and Inter
- Netlify Functions and the Anthropic API for the optional AI mode of the chat assistant
- GitHub Pages for hosting

**Technologies I work with and I am learning**

![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css) ![JavaScript](https://skillicons.dev/icons?i=js) ![Tailwind CSS](https://skillicons.dev/icons?i=tailwind) ![React](https://skillicons.dev/icons?i=react) ![Node.js](https://skillicons.dev/icons?i=nodejs) ![Express](https://skillicons.dev/icons?i=express) ![MongoDB](https://skillicons.dev/icons?i=mongodb)

## Project structure

```
Current-portfolio/
├── index.html                  # The whole site: markup, styles and scripts
├── netlify/
│   └── functions/
│       └── chat.js             # Optional serverless function for the AI assistant
└── README.md
```

## Run it locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Atharv-mu/Current-portfolio.git
   ```
2. Open the folder in VS Code and run `index.html` with the Live Server extension, or simply double-click `index.html` to open it in a browser.

No installation is needed.

## How the chat assistant works

The assistant has two modes:

1. **Built-in mode (works everywhere):** it matches the visitor's question against a prepared list of answers about me, such as who I am, my skills, my projects and my goals. It also replies to greetings like "hello" and "thanks". This is the mode used on the GitHub Pages site.
2. **AI mode (optional):** when the site is deployed on Netlify with the `netlify/functions/chat.js` function, the assistant sends questions to an AI model that has been given verified facts about me. If the function is not available or fails, the page falls back to built-in mode automatically.

GitHub Pages only serves static files, so the AI mode cannot run there. To turn it on:

1. Deploy the repository on Netlify through Git (drag and drop does not support functions).
2. Add an environment variable named `ANTHROPIC_API_KEY` in the Netlify site settings.
3. Redeploy the site.

The API key is stored only on the server side and is never included in the page code.

## Roadmap

These are the things I plan to add next:

- **Interactive Q&A for visitors and recruiters:** a feature where anyone, especially recruiters, can ask me their doubts and questions directly through the site, instead of only getting prepared answers. I want it to feel like a real conversation, with questions reaching me when the assistant cannot answer them.
- **A smarter assistant:** more complete and natural answers, including more detail about each project.
- **New projects:** adding my latest work as I build it, including the full backend for Krishihal.

## Contact

<a href="https://github.com/Atharv-mu"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" height="40"></a>
<a href="https://www.linkedin.com/in/atharvholkar/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" height="40"></a>

- GitHub: [github.com/Atharv-mu](https://github.com/Atharv-mu)
- LinkedIn: [linkedin.com/in/atharvholkar](https://www.linkedin.com/in/atharvholkar/)

---

&copy; 2026. All rights reserved by Atharv Holkar.
