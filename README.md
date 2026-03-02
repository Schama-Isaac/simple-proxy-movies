<div align="center">

# 🎬 Simple Proxy Movies

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)

**A blazing-fast movie proxy API running on the edge with Cloudflare Workers.**

</div>

---

## 📖 About

**Simple Proxy Movies** is a lightweight proxy server deployed on [Cloudflare Workers](https://workers.cloudflare.com/), designed to fetch and relay movie data at the network edge — close to users, with minimal latency.

Whether you're building a movie app or need a reliable CORS-friendly relay for movie APIs, this project has you covered.

---

## ✨ Features

- ⚡ **Edge-deployed** — runs globally on Cloudflare's network
- 🌍 **Low latency** — requests are handled close to the user
- 🔒 **CORS support** — safely consumable from any frontend
- 🎥 **Movie data relay** — proxies movie API responses seamlessly
- 🛠️ **Easy to deploy** — one command with Wrangler CLI

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/) — Cloudflare's Workers CLI

```bash
npm install -g wrangler
```

### Installation

```bash
# Clone the repository
git clone https://github.com/Schama-Isaac/simple-proxy-movies.git
cd simple-proxy-movies

# Install dependencies
npm install
```

### Local Development

```bash
wrangler dev
```

The Worker will be available at `http://localhost:8787`.

---

## 📦 Deployment

Deploy to Cloudflare Workers with a single command:

```bash
wrangler deploy
```

Your proxy will be live at your `workers.dev` subdomain instantly.

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| [Cloudflare Workers](https://workers.cloudflare.com/) | Edge runtime |
| [Wrangler](https://developers.cloudflare.com/workers/wrangler/) | CLI & deployment |

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

<div align="center">

Made with ❤️ by [Schama-Isaac](https://github.com/Schama-Isaac)

</div>