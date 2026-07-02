<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.

# AGENTS.md — Command Center Portfolio

# CURRENT PHASE

Phase Status: IN PROGRESS

Phase 1:
Build only the Developer Command Center Hero.

Allowed:
- Hero
- Three.js background
- Terminal card
- CTA buttons
- Floating panels

Not allowed:
- About
- Projects
- Skills
- Experience
- Contact
- Footer

Stop after completing the hero.

## Project Goal

Build a premium, memorable developer portfolio for Addison Hagan.

This portfolio is not a basic resume website. It should feel like a polished MVP/product experience that can be shown to interviewers, linked on GitHub, added to LinkedIn, and used as a professional career asset.

The current creative direction is:

**Developer Command Center**

A futuristic 3D command-center interface with a dark terminal-inspired design, subtle neon accents, floating panels, clean typography, and recruiter-friendly content.

The site should feel:
- Premium
- Modern
- Technical
- Interactive
- Professional
- Recruiter-friendly
- Fast and usable

The site should not feel:
- Gimmicky
- Overloaded
- Confusing
- Like a game
- Like a generic portfolio template
- Like a student project

---

# Non-Negotiable Rules

## 1. Follow Scope Exactly

Only implement what is requested in the current prompt.

Do not build extra sections.
Do not add placeholder pages.
Do not redesign unrelated components.
Do not refactor unrelated files unless necessary.
Do not “improve” things outside the requested task.

If the task says “hero only,” only work on the hero.

If the task says “icon bar only,” only work on the icon bar.

Always stop after completing the requested task and wait for further instruction.

---

## 2. Preserve Approved Work

Once a section, animation, layout, or component is approved, do not change it unless explicitly instructed.

Do not touch approved:
- hero title
- animated background
- icon bar
- 3D scene
- spacing
- colors
- typography
- layout
- responsive behavior

If a change might affect approved work, explain it first instead of applying it blindly.

---

## 3. This Is a Professional Portfolio

Every decision should support the goal of helping Addison get interviews.

Prioritize:
- clarity
- strong first impression
- readable content
- performance
- accessibility
- clean code
- mobile responsiveness
- polished visual design

Avoid:
- unnecessary complexity
- excessive animation
- hard-to-read text
- slow loading
- confusing interactions
- hidden navigation
- overdesigned UI

Recruiters should understand who Addison is within 5–10 seconds.

---

# Tech Stack

Use:

- Next.js App Router
- TypeScript
- Tailwind CSS
- React
- React Three Fiber
- Drei
- Three.js
- Framer Motion
- GSAP only when needed
- Lucide React for icons

Do not add new dependencies unless there is a clear reason.

Before adding any dependency:
1. Explain why it is needed.
2. Check whether the existing stack can solve the problem.
3. Keep the dependency list minimal.

---

# Design Direction

## Overall Theme

The portfolio should use a futuristic command-center style.

Visual references:
- terminal UI
- cyber interface
- floating glass panels
- 3D grid floor
- holographic cards
- dark matte background
- green and purple neon accents
- clean developer tooling aesthetic

## Color Direction

Use mostly:
- black
- near-black
- dark gray
- muted slate
- white
- soft green accent
- subtle purple accent
- occasional blue accent if needed

Avoid:
- bright rainbow colors
- heavy gradients everywhere
- overly saturated neon
- light theme unless explicitly requested

## Typography

Typography should feel technical and modern.

Use:
- clean sans-serif for readable content
- monospace for terminal/code elements
- strong spacing
- uppercase labels where appropriate

Avoid:
- tiny unreadable text
- too many font families
- inconsistent letter spacing

---

# 3D / Three.js Rules

## 1. 3D Should Support the Portfolio

Three.js should make the site memorable, not harder to use.

The 3D environment should feel like a background/atmosphere, not a video game.

Use 3D for:
- command center background
- grid floor
- floating panels
- subtle depth
- parallax
- interactive hover effects
- particles/code elements

Avoid:
- complicated game controls
- forced camera movement
- long intro animations
- interactions required to access content
- anything that hurts performance

## 2. Performance Matters

The 3D scene must be optimized.

Requirements:
- keep geometry simple
- avoid excessive lights
- avoid huge particle counts
- avoid expensive post-processing unless needed
- lazy-load heavy visual components when possible
- use responsive scaling
- ensure acceptable mobile performance

Mobile should either:
- use a simplified 3D scene, or
- gracefully fall back to a lightweight animated background

Do not let Three.js break the portfolio on phones.

## 3. Accessibility

Do not rely on 3D interactions for core navigation or content.

All important content must be available through normal HTML.

The portfolio should still make sense if:
- animations are reduced
- JavaScript is slower
- the user is on mobile
- the user uses keyboard navigation

Respect reduced motion where possible.

---

# Content Strategy

## Addison’s Positioning

Addison should be positioned as:

**Frontend / Full-stack developer building modern web applications with Next.js, TypeScript, and AI-assisted workflows.**

Possible wording:
- Frontend Developer
- Software Developer
- Full-stack Developer
- Next.js Developer

Avoid overstating experience.

Do not claim senior-level experience.
Do not invent metrics.
Do not invent companies.
Do not fabricate impact numbers.

Use real projects and real skills.

---

# Main Projects To Feature

Use these as the strongest portfolio projects:

## 1. Skinstric AI Internship MVP

Type:
Internship / AI web app

Stack:
Next.js, TypeScript, Tailwind CSS, API integration, responsive UI

Description:
A polished AI-powered skin analysis experience built during Addison’s internship. Includes multi-step user flow, camera/upload experience, demographic analysis flow, and responsive UI matching detailed design references.

Importance:
This should be one of the top featured projects because it shows internship experience and production-style UI implementation.

## 2. Dev Events

Type:
Full-stack event platform

Stack:
Next.js, TypeScript, MongoDB, Mongoose, Cloudinary, Vercel

Description:
A full-stack event discovery and booking platform with CRUD event management, image uploads, dynamic routes, server actions, caching, and deployment.

Importance:
Shows full-stack ability and real application architecture.

## 3. CodeCritic AI

Type:
AI code review app

Stack:
Next.js, TypeScript, MongoDB, OpenAI API, Tailwind CSS

Description:
An AI-powered code review tool with review history, dashboard, API routes, and rate limiting.

Importance:
Shows AI integration and practical developer tooling.

## 4. Real-Time Incident Dashboard

Type:
Real-time dashboard

Stack:
Next.js, Socket.IO, MongoDB

Description:
A real-time incident tracking dashboard with create, update, archive, filtering, searching, and live updates.

Importance:
Shows real-time data handling and dashboard-style UI.

## 5. Movie Vault

Type:
Frontend movie app

Stack:
React, Vite, OMDb API

Description:
A movie discovery app with debounced search, filtering, and favorites.

Importance:
Good supporting project, but not as strong as the top three.

---

# Content Rules

Do not invent project features.

Do not add fake analytics.

Do not claim:
- “98% accuracy”
- “60% improvement”
- “thousands of users”
- “enterprise-grade”
- “production deployed at scale”

unless Addison explicitly provides proof.

Use honest, strong wording.

Good wording:
- “Built”
- “Implemented”
- “Designed”
- “Integrated”
- “Developed”
- “Refactored”
- “Optimized”
- “Created”
- “Improved responsiveness”
- “Matched detailed design references”
- “Handled multi-step user flow”

Avoid unsupported wording:
- “Architected at scale”
- “Led a team”
- “Achieved 98% accuracy”
- “Boosted engagement”
- “Served thousands of users”

---

# Page Structure Plan

The eventual portfolio may include:

1. Hero / Command Center
2. About
3. Featured Projects
4. Project Case Studies
5. Skills / Tech Stack
6. Experience
7. Contact
8. Resume link

Do not implement all of these at once.

Build in phases.

---

# Current Build Philosophy

Work in small, controlled phases.

Recommended order:

## Phase 1 — Hero Command Center
Build:
- full-screen hero
- center terminal card
- 3D background
- command-center grid
- social/resume CTA bar
- floating side panels if requested

Do not build other sections yet.

## Phase 2 — Navigation
Build:
- top nav
- section anchors
- responsive mobile nav

## Phase 3 — Projects
Build:
- project data file
- featured project cards
- command-center style project windows

## Phase 4 — About / Skills
Build:
- concise about section
- technical skill groups
- experience positioning

## Phase 5 — Contact / Resume
Build:
- contact CTA
- resume download
- GitHub/LinkedIn links

## Phase 6 — Polish
Add:
- subtle transitions
- responsive refinements
- accessibility fixes
- performance optimization
- README

---

# Coding Standards

## Components

Use clear component names.

Examples:
- `Hero`
- `CommandCenterHero`
- `TerminalWindow`
- `FloatingPanel`
- `GridFloor`
- `SocialBar`
- `ProjectCard`

Keep files organized.

Recommended structure:

```txt
components/
  hero/
    CommandCenterHero.tsx
    TerminalWindow.tsx
    SocialBar.tsx
    FloatingPanel.tsx
    GridFloor.tsx
  ui/
    Button.tsx
    SectionHeader.tsx
  three/
    CommandScene.tsx
    Particles.tsx
    Grid.tsx
data/
  projects.ts
lib/
  utils.ts

```

# TypeScript

Use TypeScript properly.

Avoid:

any
unused props
unused imports
messy inline objects everywhere

Use types/interfaces when data structures repeat.

# Tailwind

Use Tailwind for styling.

Keep class names readable.

Avoid massive unreadable class strings when possible. If a component becomes too large, split it.

# Animations

Animations should be:

smooth
subtle
purposeful
fast enough to not delay users

Avoid:

constant aggressive motion
distracting loops
huge entrance animations
animation that blocks reading

# Responsive Rules

The portfolio must look good on:

1920px desktop
1440px laptop
1024px tablet
768px tablet/mobile
430px phone
390px phone

Desktop can have richer 3D.

Mobile should be simpler and readable.

Mobile priorities:

readable title
clear role
obvious links
fast load
no horizontal overflow

# Accessibility Rules

Follow basic accessibility standards.

Requirements:

semantic HTML
accessible links/buttons
keyboard focus states
readable contrast
alt text for images
no text hidden only inside canvas
respect reduced motion where practical

Do not put important text only inside a Three.js canvas.

# Git / Commit Rules

Use clean commit messages.

Format:

feat(hero): build command center hero
fix(hero): improve mobile spacing
refactor(hero): split terminal components
style(hero): polish CTA hover states

Commit after meaningful milestones.

Do not commit broken builds.

Before committing, run:

npm run build

If available, also run:

npm run lint

# Testing / Quality Checklist

Before saying a task is complete, verify:

app runs locally
no TypeScript errors
no console errors
no obvious layout breaking
mobile layout works
desktop layout works
links are accessible
no unrelated files changed
requested scope was followed

# Communication Rules For AI Agents

When working on this project:

Restate the requested task briefly.
Identify files that will be changed.
Make only the requested changes.
Explain what was completed.
Mention any issues or assumptions.
Stop and wait for next instruction.

Do not continue building ahead.

Do not make broad creative decisions without approval.

If unsure, ask before changing.

# Current Priority

The current priority is to build the Developer Command Center hero first.

The hero should be inspired by the approved visual direction:

central terminal window
Addison name
software developer positioning
GitHub / LinkedIn / Resume buttons
dark futuristic environment
command-center panels
subtle 3D depth
premium but professional feel

Only implement the hero until instructed otherwise.

# Documentation Rules

Do not remove comments, TODOs, or section headers unless explicitly instructed.

Preserve:
- AGENTS.md instructions
- architecture comments
- file headers
- TODO notes
- accessibility comments

# Data Integrity Rules

Never invent:
- companies
- users
- metrics
- project statistics
- testimonials
- employers
- technologies not used

If information is unknown, ask or use placeholders clearly marked as TODO.

Before marking a task complete:

npm run build

If available:

npm run lint

Do not declare a task complete if the build fails.

# Design Approval Rule

Large visual changes require approval before implementation.

Examples:
- changing color palette
- redesigning hero layout
- replacing animations
- changing typography
- restructuring sections
- replacing Three.js scenes

When uncertain, ask before changing.

# AI Agent Operating Procedure

Before starting:
1. Read AGENTS.md completely.
2. Determine the current phase.
3. Identify only the files necessary for the task.
4. Make the smallest possible change.
5. Verify the build passes.
6. Summarize exactly what changed.
7. Stop and wait for further instructions.

Never:
- continue to the next phase automatically
- add unrequested features
- remove existing functionality
- make large design decisions without approval
- rewrite files unnecessarily

<!-- END:nextjs-agent-rules -->
