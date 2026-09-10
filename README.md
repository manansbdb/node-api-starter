<p align="center">
  <img src="docs/banner.svg" alt="Node API Starter banner" width="100%" />
</p>

<h1 align="center">node-api-starter</h1>

<p align="center">
  <strong>EN</strong> Minimal Express-style Node.js HTTP API scaffold<br/>
  <strong>PT</strong> Scaffold mínimo de API HTTP Node.js estilo Express
</p>

<p align="center">
  <a href="https://github.com/manansbdb/node-api-starter/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge" alt="Node.js" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A **minimal Express API** scaffold with entrypoint, app factory, and a `/health` route. | Um scaffold de **API Express mínima** com entrypoint, app factory e rota `/health`. |
| Clone, `npm install`, `npm start` — or copy `src/` into a new project. | Clona, `npm install`, `npm start` — ou copia `src/` para um projeto novo. |

```mermaid
flowchart LR
  A["🚀 npm start"] --> B["📄 src/index.js"]
  B --> C["🧩 src/app.js"]
  C --> D["❤️ /health"]
  style A fill:#339933,stroke:#166534,color:#fff
  style B fill:#2563eb,stroke:#1d4ed8,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/node-api-starter.git
cd node-api-starter
```

### 2) Install & run / Instala e corre

```bash
npm install
npm start
# or watch mode:
npm run dev
```

### 3) Copy scaffold / Copia o scaffold

```bash
cp -R src package.json /path/to/your-project/
cd /path/to/your-project && npm install
```

### Requirements / Requisitos

- Node.js 18+
- `npm`

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/node-api-starter.git
cd node-api-starter
npm install && npm start
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `package.json` | Scripts + Express dependency |
| `src/index.js` | Entrypoint |
| `src/app.js` | App factory |
| `src/routes/health.js` | Sample health route |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
node-api-starter/
├── docs/banner.svg
├── package.json
├── src/index.js
├── src/app.js
├── src/routes/health.js
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
