# 🐩 Tia - Poodle Sprite Generator

A pixel sprite generator built for my poodle, Tia.

Live demo: [tia-poodle.vercel.app](https://tia-poodle.vercel.app)

Built with [Claude Code](https://claude.com/claude-code) as a fast, single-file prototype - and made as a Mother's Day gift, since Tia is our precious family dog.

## Quick Start

This is a self-contained static HTML app - no build step, no dependencies.

```bash
open index.html
```

Or serve it locally:

```bash
npx serve .
```

## About This Project

Tia is a static pixel sprite - hand-tuned to one dog, not a generalized generator. Where [Cat Collector](https://github.com/jocelynmhorng/cat-collector) builds a full pipeline (color extraction, pattern detection, live preview) to generate a sprite from *any* uploaded photo, this project works in the opposite direction: it starts from a single reference photo of Tia and renders one fixed, polished sprite of her.

The goal was speed and precision over flexibility - going from a photo to a deployed, pixel-accurate character in a single sitting, entirely in one `index.html` file, with Claude Code handling the build.

It's less "app" and more "portrait" — a small, complete piece rather than a partial system. And it doubled as a personal gift: I built and deployed it in time to share with my mom for Mother's Day. It was a fun way to bring my pet into a digital interface, letting family members who aren't nearby interact with her and stay connected through the app.


## Stack

- Vanilla HTML/JS (single-file build)
- Deployed on [Vercel](https://vercel.com)

---

*A companion project to [Cat Collector](https://github.com/jocelynmhorng/cat-collector) - turns out my poodle wanted pixel-art representation too.*
