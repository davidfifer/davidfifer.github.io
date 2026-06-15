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

