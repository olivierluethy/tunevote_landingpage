<div align="center">
  <img src="assets/logo.png" alt="TuneVote" width="150" height="150" />
  <h1>TuneVote — Landing Page</h1>
  <p>
    <b>The marketing site for collaborative music voting.</b><br/>
    A fast, animated long-scroll landing page and blog that tells the TuneVote story — the crowd votes in real time on what plays next.
  </p>
  <p>
    <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
    <img alt="Astro" src="https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=white">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white">
    <img alt="MDX" src="https://img.shields.io/badge/MDX-1B1F24?logo=mdx&logoColor=white">
  </p>
  <p><i>Part of the <a href="https://github.com/olivierluethy?tab=repositories&q=tunevote">TuneVote</a> project — see the <a href="https://github.com/olivierluethy/tunevote_frontend">web client</a> and <a href="https://github.com/olivierluethy/tunevote_api">API</a>.</i></p>
</div>

---

Marketing landing page for **TuneVote**, a (concept) app for collaborative music
sessions where the crowd votes in real time on what plays next — for parties, road
trips and workouts. Built with Astro and Tailwind CSS.

## Features

- Long-scroll landing page with dedicated sections: live voting demo, how it works,
  AI song suggestions, artist dashboard, and top artists / top weekly songs tables.
- Blog powered by Astro content collections + MDX (`/blog` and `/blog/[slug]`).
- Responsive design, Open Graph / social metadata and Lucide icons.

## Tech

- Astro
- Tailwind CSS (+ typography plugin)
- MDX content collections
- lucide-astro

## Run

```bash
npm install
npm run dev
```

Then open http://localhost:4321.

To build for production:

```bash
npm run build
npm run preview
```

## License

Released under the [MIT License](LICENSE) © Olivier Lüthy. You're free to use, modify and distribute this software, including commercially, as long as the copyright notice and license are included.

## Author

Built by **Olivier Lüthy** — [GitHub](https://github.com/olivierluethy).
