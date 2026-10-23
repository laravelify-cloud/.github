<p align="center">
  <a href="https://laravelify.cloud">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/laravelify-cloud/laravelify/main/brand/laravelify-brand-assets/04-social/png/laravelify-readme-banner-dark-1600.png">
      <img alt="Laravelify: self-hosted deploys for Laravel, Node.js, and front-end apps" src="https://raw.githubusercontent.com/laravelify-cloud/laravelify/main/brand/laravelify-brand-assets/04-social/png/laravelify-readme-banner-light-1600.png">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://laravelify.cloud"><b>Website</b></a> ·
  <a href="https://laravelify.cloud/#install"><b>Install command builder</b></a> ·
  <a href="https://docs.laravelify.cloud"><b>Documentation</b></a> ·
  <a href="https://docs.laravelify.cloud/quickstart">Quickstart</a> ·
  <a href="https://github.com/laravelify-cloud/laravelify/releases">Releases</a> ·
  <a href="https://laravelify.cloud/#sponsors">Sponsor</a>
</p>

<p align="center">
  <a href="https://github.com/laravelify-cloud/laravelify/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/laravelify-cloud/laravelify?color=6B16ED&include_prereleases"></a>
  <a href="https://github.com/laravelify-cloud/laravelify/actions/workflows/tests.yml"><img alt="Tests" src="https://github.com/laravelify-cloud/laravelify/actions/workflows/tests.yml/badge.svg"></a>
  <a href="https://github.com/laravelify-cloud/laravelify/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/laravelify-cloud/laravelify?style=flat&color=FCD452"></a>
  <a href="https://github.com/laravelify-cloud/laravelify/blob/main/LICENSE"><img alt="MIT license" src="https://img.shields.io/badge/license-MIT-8B5CF6"></a>
</p>

---

**Laravelify** is an open-source, self-hosted control panel that turns one Ubuntu server into a home for your apps: **Laravel** and PHP, **Express**, **NestJS**, **React**, **Vue.js**, **Angular**, **Svelte**, **Astro**, **Next.js**, **Nuxt**, and **SvelteKit**. Push to GitHub and your site deploys, then watch live traffic, errors, attacks, and server load, edit your databases, and run commands, all from one panel. No Docker, no per-seat pricing, no vendor lock-in.

```bash
curl -fsSL https://cdn.laravelify.cloud/install.sh | sudo bash
```

One command on a fresh Ubuntu 22.04, 24.04, or 26.04 server installs the latest release, step by step: nginx, PHP-FPM 8.0–8.5, MySQL 8.4, Redis, Node.js 20/22/24, PM2, Supervisor, Cloudflare, and a firewall. Want only some PHP or Node.js versions? Build your own command at **[laravelify.cloud/#install](https://laravelify.cloud/#install)**.

> [!NOTE]
> Laravelify is in **public beta**. Try it on a fresh server, keep backups, and [tell us what breaks](https://github.com/laravelify-cloud/laravelify/issues).

### Repositories

| Repository | What it is | Built with |
| --- | --- | --- |
| [**laravelify**](https://github.com/laravelify-cloud/laravelify) | The panel: deploys, database tool, backups, monitoring, alerts, terminal, the installer, and the releases | Laravel 13, Livewire 4, Alpine, Tailwind 4 |
| [**laravelify-docs**](https://github.com/laravelify-cloud/laravelify-docs) | The documentation at [docs.laravelify.cloud](https://docs.laravelify.cloud) | Mintlify |
| [**laravelify-website**](https://github.com/laravelify-cloud/laravelify-website) | The website and install command builder at [laravelify.cloud](https://laravelify.cloud) | Next.js 16, Tailwind 4 |
| [**.github**](https://github.com/laravelify-cloud/.github) | This profile and the community files every repository shares | |

### What it does

- 🚀 **Git push to deploy** backends, front ends, and full-stack apps through a GitHub App, with a live build log in a real console and a **Deployments board** of every site
- 🧑‍💻 **VS Code for every site** in the browser, with an **AI Agents chat** (Claude Code, Cursor, GitHub Copilot: switch mid-task and the next one continues) and a **Live Server** that shares your dev server on a random HTTPS address and refreshes on save
- 🗄️ **Database tool**: a fast grid for millions of rows, spreadsheet-style filters, edits with undo, foreign keys both ways, an SQL console, and encrypted columns shown decrypted
- 💾 **S3 backups** of databases and folders on a schedule or as one Full backup: look inside, download parts as SQL, restore a database, some tables, or some folders
- 📈 **Live monitoring**: requests, p95 response times, uptime, grouped Laravel errors, server CPU and memory
- 🛡️ **Attack detection** with one-click IP blocking, 💓 heartbeats for cron jobs
- 💬 **Telegram alerts** for deploys, downtime, crashed workers, error spikes, slow responses, and a full disk
- 🖥️ **Live terminal** for every site: answer the questions a command asks, Ctrl+C, Artisan and PM2 autocomplete
- 🔐 **Separate users**: the panel runs as its own user, and each website runs as its own, so one site cannot read the panel or another site
- ☁️ **Cloudflare tunnels**, two-factor sign-in, 🧰 file manager with trash and versions, logs, health checks
- 🤖 **MCP for AI assistants**: ask Claude Code, Claude Desktop, or Cursor to deploy a repository or read a log

### Get involved

- ⭐ Star [laravelify](https://github.com/laravelify-cloud/laravelify) to follow the beta
- 🐞 Report bugs and ideas in [Issues](https://github.com/laravelify-cloud/laravelify/issues); fix a docs page with a pull request to [laravelify-docs](https://github.com/laravelify-cloud/laravelify-docs)
- 🔒 Report security problems privately: see the [security policy](https://github.com/laravelify-cloud/laravelify/security/policy)
- 💜 Laravelify is free; [sponsors](https://laravelify.cloud/#sponsors) keep it that way
- ☕ Or [buy the maintainer a coffee](https://buymeacoffee.com/arshadarsh01)

<sub>Built and maintained by [Arshad Arshadli](https://github.com/ArshadArshadli01) in Azerbaijan 🇦🇿 · MIT licensed</sub>
