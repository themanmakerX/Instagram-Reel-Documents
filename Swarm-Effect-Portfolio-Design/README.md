# Swarm Effect Portfolio Design

Build your own cinematic, single page portfolio website with any AI coding assistant, complete with the **Builder Swarm** effect: on the first visit the page blanks and a swarm of labeled cursors rebuilds it live in front of the visitor.

**Live reference (design and behaviour only):** https://atifsportfolio.netlify.app/

## What's inside

| File | What it is |
|---|---|
| [`PORTFOLIO_BUILDER.md`](./PORTFOLIO_BUILDER.md) | The master spec. Design summary, intake questions, tech stack, design system, section by section build notes, the full Builder Swarm engine, a live visitor counter, privacy rules, deployment and a verification checklist. |
| [`PORTFOLIO_PROMPT.txt`](./PORTFOLIO_PROMPT.txt) | A ready to paste prompt that tells your AI assistant to follow the spec step by step. |

## How to use

1. Download both files.
2. Open your AI coding assistant (Claude, Cursor, Codex, Lovable, Bolt, etc.).
3. Attach `PORTFOLIO_BUILDER.md` and paste the contents of `PORTFOLIO_PROMPT.txt`.
4. Answer the interview questions. Skip anything you don't have and that section stays hidden.
5. Confirm the summary, let it build, then deploy the `dist/` folder to Netlify, Vercel, GitHub Pages or Cloudflare Pages.

## What you get

- Dark editorial design: huge condensed headlines, one accent colour, numbered sections
- Hero with portrait, stats and status chips
- Project portfolio with filters, search and generated thumbnails
- Tools marquee, before/after showcase slider, experience timeline and credential vault
- Creator section with YouTube videos, Shorts and playlists in an in-page player
- Contact section with a local job description matcher
- Live visitor counter, light/dark theme and motion toggles
- **Builder Swarm**: 9 cursors build the page at 1.5x speed with auto-scroll, then show "Agents finished."

## Tech stack

React 19, esbuild, plain CSS with custom properties, self-hosted Fontsource fonts, lucide-react icons. Static output, no backend.

## Ground rules baked into the spec

- No fabricated data. Every name, number and link comes from you.
- No personal content from the reference site. Use it only for layout and motion.
- The assistant must report what it tested and what it could not test.

## Credits

Spec and reference design by **Atif Afzal** ([@themanmakerX](https://github.com/themanmakerX)).
