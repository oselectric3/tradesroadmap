# TradesRoadmap Frontend — Project Manifest

## 1. Purpose & Scope
Frontend shell for TradesRoadmap SaaS platform.
Includes:
- Navigation header & footer
- Placeholder pages (Home, Pricing, RoadMap, Projects, About, Contact)
- Router & main JS bootstrapping
- Config placeholders
- Assets & styles skeleton

## 2. Authoritative File Tree
/
├── PROJECT_MANIFEST.md
├── README.md
├── index.html
├── .gitignore
├── public/
│   ├── favicon.ico
│   └── robots.txt
├── assets/
│   ├── logos/
│   ├── images/
│   ├── icons/
│   └── mockups/
├── src/
│   ├── styles/
│   │   ├── main.css
│   │   ├── header.css
│   │   ├── footer.css
│   │   ├── pages/
│   │   │   ├── home.css
│   │   │   ├── pricing.css
│   │   │   └── roadmap.css
│   │   └── components/
│   │       ├── pricing-card.css
│   │       └── modal.css
│   ├── scripts/
│   │   ├── main.js
│   │   ├── router.js
│   │   ├── auth.js
│   │   ├── projects.js
│   │   └── roadmap.js
│   ├── pages/
│   │   ├── home.html
│   │   ├── pricing.html
│   │   ├── roadmap.html
│   │   ├── projects.html
│   │   ├── about.html
│   │   └── contact.html
│   ├── components/
│   │   ├── header.html
│   │   ├── footer.html
│   │   ├── pricing-card.html
│   │   ├── project-card.html
│   │   └── modal.html
│   ├── config/
│   │   ├── routes.js
│   │   ├── plans.js
│   │   └── roles.js
│   └── data/
│       ├── projects.mock.js
│       └── users.mock.js
└── docs/
    ├── sitemap.md
    ├── features.md
    └── roadmap.md

## 3. Notes
- RoadMap page is a mount container
- All JS is client-side routing
- Stylesheets are placeholders

This will be the base tree where every file will live somewhere or another. we will fil and edit this folder by folder. 