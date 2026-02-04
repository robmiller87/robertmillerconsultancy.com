# Robert Miller's Personal Website

Source code for [robertmiller.xyz](https://robertmiller.xyz), built with [Astro](https://astro.build) and deployed on [Vercel](https://vercel.com).

## About

I'm Robert Miller — tech builder, former VP of Growth at Fuse (Ethereum L2), and currently exploring the frontier of AI agents.

In January 2026, I built an AI agent named George (after my late grandfather) using [OpenClaw](https://github.com/openclaw/openclaw). Three weeks later, George has:

- Deployed smart contracts on two blockchains
- Entered $110K worth of hackathons autonomously
- Written 19 blog posts at [agent-george.com](https://agent-george.com)
- Built his own on-chain identity (ERC-8004 Token #1 on Base)

This website documents that journey and my thinking on AI, crypto, and what happens when you give an agent a name that means something.

## Current Projects

| Project | Description | Link |
|---------|-------------|------|
| **George** | My AI execution partner | [agent-george.com](https://agent-george.com) |
| **AgentEscrow** | USDC escrow for agent-to-agent work | [GitHub](https://github.com/robmiller87/Circle_Escrow_Hackathon) |
| **AgentReputation** | On-chain reputation for AI agents | [GitHub](https://github.com/robmiller87/agent-reputation) |

## Writing

Recent posts:
- [I Built an OpenClaw Agent and Named Him George, After My Grandfather](https://robertmiller.xyz/posts/2026-01-i-built-an-ai-partner)

## Connect

- **X/Twitter**: [@rob_miller87](https://x.com/rob_miller87)
- **LinkedIn**: [linkedin.com/in/rm16](https://linkedin.com/in/rm16)
- **Farcaster**: [@robmiller87](https://warpcast.com/robmiller87)

---

## Technical Details

### Project Structure

```text
├── public/               # Static assets (images, fonts, favicon)
│   ├── assets/          # Images for blog posts
│   └── fonts/           # Web fonts
├── src/
│   ├── components/      # Reusable UI components
│   ├── content/         # Content collections
│   │   └── blog/        # Blog posts in Markdown
│   ├── layouts/         # Page layouts
│   ├── pages/           # Routes
│   └── styles/          # Global CSS
├── astro.config.mjs     # Astro configuration
└── vercel.json          # Vercel deployment config
```

### Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Installs dependencies                       |
| `npm run dev`     | Starts local dev server at `localhost:4321` |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview build locally                       |

### Deployment

Deployed on Vercel. Push to `main` triggers automatic build and deploy.

---

## License

Dual licensing:
- **Blog posts & documentation**: [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
- **Code**: [MIT License](LICENSE)

---

## Credits

This site is a fork of [Peter Steinberger's personal website](https://github.com/steipete/steipete.me). Huge thanks to [@steipete](https://steipete.me) for open-sourcing such a clean, well-architected template — and for building [OpenClaw](https://github.com/openclaw/openclaw), which powers George.

Also thanks to [Sat Naing](https://github.com/satnaing) for the original [AstroPaper theme](https://astro-paper.pages.dev/) that Pete built upon.

---

*Built by a human. Improved by an agent. 🌉*
