# 🪐 3D Developer Portfolio (v1)

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000?logo=threedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?logo=framer&logoColor=white)

**[Live site →](https://abubakar17.github.io/My_site_old/)**

The first version of my personal portfolio: an interactive 3D site built with React Three Fiber, with a rotating desktop-setup model, a 3D planet, a starfield background and animated sections.

> My current portfolio lives at **[abubakar17.github.io/Syed-Abubakar-Portfolio](https://abubakar17.github.io/Syed-Abubakar-Portfolio/)**.

## Features

- **3D hero:** a desktop-computer scene rendered with `@react-three/fiber` and `drei`
- **Interactive planet and stars:** a glTF Earth model with an animated particle starfield
- **Tech balls:** skill icons mapped onto floating 3D spheres
- **Experience timeline:** a vertical timeline of roles and internships
- **Project cards:** tilt-on-hover cards built with `react-parallax-tilt`
- **Working contact form:** sends email straight from the browser with EmailJS
- **Smooth motion:** section transitions with Framer Motion

## Run locally

```bash
npm install
npm run dev       # local dev server
npm run deploy    # build and publish to GitHub Pages
```

## Structure

```
src/
├── components/         Hero, About, Experience, Tech, Works, Feedbacks, Contact, Navbar
│   └── canvas/         Three.js scenes: Computers, Earth, Stars, Ball
├── constants/          site content (experience, projects, tech stack)
├── hoc/                section wrapper for scroll animations
└── utils/motion.js     shared Framer Motion variants
```
