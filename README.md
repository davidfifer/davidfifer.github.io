# GitHub Pages Architecture — davidfifer.github.io

davidfifer.github.io/                     ← Public portfolio website
│
├── index.html                            ← Homepage (hero, skills, projects)
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── projects/                             ← Project cards link OUT to repos
│
└── (links to external repos)
      │
      ├── davidfifer-portfolio/           ← Curated portfolio hub
      │     ├── python/
      │     ├── java/
      │     ├── ruby/
      │     └── docs/
      │
      ├── python-file-organizer/          ← Standalone Python repo
      │     ├── src/
      │     └── tests/
      │
      ├── java-distributed-scheduler/     ← Java backend system
      │     ├── src/
      │     └── config/
      │
      └── ruby-cli-utils/                 ← Ruby automation tools
            ├── bin/
            └── lib/

# David Fifer — Portfolio Website

Welcome to the source code for my personal portfolio site, hosted at **davidfifer.github.io**.  
This site highlights my work in backend engineering, distributed systems, automation, and developer tooling.  
It serves as a clean, fast, and accessible entry point for recruiters, hiring managers, and collaborators.

---

## 📁 Sitemap

davidfifer.github.io/
│
├── index.html                        ← Main homepage
│
├── assets/                           ← Static assets
│   ├── css/
│   │   ├── main.css
│   │   └── theme.css
│   ├── js/
│   │   ├── main.js
│   │   └── animations.js
│   └── images/
│       ├── headshot.jpg
│       ├── project-thumbnails/
│       └── diagrams/
│
├── projects/                         ← Optional deep‑dive project pages
│   ├── python-file-organizer.html
│   ├── java-scheduler-service.html
│   └── ruby-cli-utils.html
│
├── diagrams/                         ← Architecture diagrams
│   ├── scheduler-architecture.png
│   ├── pipeline-flow.png
│   └── microservice-layout.png
│
├── resume/
│   └── david-fifer-resume.pdf        ← Downloadable resume
│
└── sitemap.xml                       ← SEO sitemap (optional)
