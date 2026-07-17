# Futuristic Developer Portfolio Dashboard

A neon-themed, dark-mode developer portfolio built for the terminal generation —
featuring animated activity metrics, live repo stats, glowing skill bars,
and a real-time GitHub contribution tracker. All signal, no noise.

## Preview

> Dark grid layout · Neon glow effects · Animated everything

## Features

- **Neon Dark-Mode Grid Layout** — Cyberpunk-inspired UI with CSS grid,
  glowing borders, and animated background patterns
- **GitHub Contribution Graph** — Simulated real-time activity tracker
  visualizing commit history with heatmap-style rendering
- **Repository Showcase Cards** — Animated cards displaying live repo stats
  (stars, forks, language, last updated)
- **Glowing Skill Bars** — Neon-accented proficiency indicators with
  smooth fill animations on load
- **Terminal-Style Bio** — Typewriter effect bio section styled as
  an interactive terminal prompt
- **Status Indicators** — Live-style availability and activity badges

## Getting Started

### Prerequisites

- Node.js 18+
- A GitHub personal access token (for live repo stats)

### Installation

```bash
git clone https://gitlab.com/projects-luxelifee/futuristic-developer-portfolio-dashboard.git
cd futuristic-developer-portfolio-dashboard
npm install



Configuration
Create a .env file in the root:
VITE_GITHUB_USERNAME=your_github_username
VITE_GITHUB_TOKEN=your_personal_access_token


Development:
npm run dev


Production Build:
npm run build
npm run preview


Customization:
File / Section
What to edit

src/data/skills.ts
Skill names and proficiency percentages

src/data/bio.ts
Terminal bio lines and typewriter content

src/config.ts
GitHub username, theme colors, intervals



#Tech Stack:

Framework — React / Vue / Svelte (confirm yours)
Styling — CSS Modules / Tailwind with custom neon theme
Animations — Framer Motion / CSS keyframes
GitHub Data — GitHub REST API v3
