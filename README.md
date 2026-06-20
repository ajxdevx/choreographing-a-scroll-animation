# Choreographing a Scroll Animation

A scroll-driven hero animation built with **GSAP ScrollTrigger** and **Lenis** smooth scrolling. As you scroll, the hero section pins in place while background scaling, a center revealer, cascading image reveals, and split outro text play out in sequence.

**Author:** AJ

## Features

- Pinned hero section with scrubbed scroll timeline
- Center revealer clip-path animation
- Cascading image reveals with staggered timing
- Split outro text that slides apart on scroll
- Smooth scrolling via Lenis integrated with GSAP

## Tech Stack

- [Vite](https://vitejs.dev/) — dev server and bundler
- [GSAP](https://gsap.com/) + ScrollTrigger — scroll animations
- [Lenis](https://lenis.darkroom.engineering/) — smooth scroll

## Getting Started

```bash
npm install
npm run dev
```

Open the URL shown in the terminal (typically `http://localhost:5173`).

## Project Structure

```
├── index.html      # Hero and about sections
├── script.js       # GSAP timeline and Lenis setup
├── styles.css      # Layout and typography
└── public/         # Hero background and image assets
```

## License

ISC
