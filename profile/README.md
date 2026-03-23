<div align="center">
  <img src="https://raw.githubusercontent.com/entrolytics/.github/main/media/entrov2.png" alt="Entrolytics" width="64" height="64">

  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6.svg?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Next.js](https://img.shields.io/badge/Next.js-16-000000.svg?logo=next.js)](https://nextjs.org/)
  [![Fastify](https://img.shields.io/badge/Fastify-5-000000.svg?logo=fastify)](https://www.fastify.io/)
  [![npm](https://img.shields.io/npm/v/@entrolytics/nextjs-sdk.svg?logo=npm&label=nextjs-sdk)](https://www.npmjs.com/package/@entrolytics/nextjs-sdk)
  [![GitHub stars](https://img.shields.io/github/stars/entrolytics/entrolytics.svg?logo=github)](https://github.com/entrolytics/entrolytics/stargazers)

</div>

---

## Overview

**Entrolytics** is a privacy-first analytics platform for product and growth teams that need speed, control, and developer ergonomics.

Today, the ecosystem combines:

- **Core platform monorepo** (`entrolytics/`) with Web, API, and Worker apps
- **Dual database architecture**: PostgreSQL (metadata) + ClickHouse (analytics)
- **Real-time analytics pipeline** with Redis + BullMQ + WebSockets
- **External package ecosystem** (`ecosystem-external-packages/`) spanning SDKs, clients, middleware, plugins, and mobile

## Key Capabilities

<table>
<tr>
<td width="50%">

### Analytics Platform
- Real-time pageviews, events, sessions, and funnels
- High-throughput ingestion (100K events/sec target)
- Conversion and revenue analytics
- First-party, cookie-light tracking model

### Data & Infra
- PostgreSQL + ClickHouse split by workload
- Redis-backed buffering, caching, and queues
- Materialized views for fast dashboard queries
- WebSocket-powered live dashboard updates

</td>
<td width="50%">

### Developer Experience
- End-to-end type safety with TypeScript + tRPC
- Framework SDKs for React/Vue/Svelte/Next.js/Astro/Angular
- Server/client packages for Node, Go, Python, PHP, and more
- Self-host friendly with Docker-based local infra

### Ecosystem Delivery
- Unified package/version governance
- Shared conventions across all external packages
- Cross-framework middleware and plugins
- Mobile SDK support (React Native, Android, iOS)

</td>
</tr>
</table>

## Tech Stack

<div align="center">

| Technology | Description |
|------------|-------------|
| ![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=next.js) | Dashboard and app platform |
| ![Fastify](https://img.shields.io/badge/Fastify-5-000000?style=for-the-badge&logo=fastify) | High-performance ingestion/API layer |
| ![tRPC](https://img.shields.io/badge/tRPC-11-2596BE?style=for-the-badge&logo=trpc&logoColor=white) | End-to-end typed API contracts |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) | Metadata and application state |
| ![ClickHouse](https://img.shields.io/badge/ClickHouse-Analytics-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=000) | OLAP event analytics at scale |
| ![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=for-the-badge&logo=redis&logoColor=white) | Queueing, caching, and real-time fanout |

</div>

## SDKs, Clients & Integrations

### Framework SDKs

| Package | Install |
|---------|---------|
| [![React](https://img.shields.io/badge/@entrolytics/react--sdk-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/entrolytics/react-sdk) | `npm i @entrolytics/react-sdk` |
| [![Vue](https://img.shields.io/badge/@entrolytics/vue--sdk-4FC08D?style=flat-square&logo=vue.js&logoColor=white)](https://github.com/entrolytics/vue-sdk) | `npm i @entrolytics/vue-sdk` |
| [![Svelte](https://img.shields.io/badge/@entrolytics/svelte--sdk-FF3E00?style=flat-square&logo=svelte&logoColor=white)](https://github.com/entrolytics/svelte-sdk) | `npm i @entrolytics/svelte-sdk` |
| [![Next.js](https://img.shields.io/badge/@entrolytics/nextjs--sdk-000000?style=flat-square&logo=next.js)](https://github.com/entrolytics/nextjs-sdk) | `npm i @entrolytics/nextjs-sdk` |
| [![Astro](https://img.shields.io/badge/@entrolytics/astro--sdk-BC52EE?style=flat-square&logo=astro&logoColor=white)](https://github.com/entrolytics/astro-sdk) | `npm i @entrolytics/astro-sdk` |
| [![Angular](https://img.shields.io/badge/@entrolytics/angular--sdk-DD0031?style=flat-square&logo=angular&logoColor=white)](https://github.com/entrolytics/angular-sdk) | `npm i @entrolytics/angular-sdk` |

### Clients

| Package | Install |
|---------|---------|
| [![API Client](https://img.shields.io/badge/@entrolytics/api--client-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/entrolytics/api-client) | `npm i @entrolytics/api-client` |
| [![tRPC Client](https://img.shields.io/badge/@entrolytics/trpc--client-2596BE?style=flat-square&logo=trpc&logoColor=white)](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/client/trpc) | `npm i @entrolytics/trpc-client` |
| [![Node.js](https://img.shields.io/badge/@entrolytics/node--sdk-339933?style=flat-square&logo=node.js&logoColor=white)](https://github.com/entrolytics/node-sdk) | `npm i @entrolytics/node-sdk` |
| [![Drizzle](https://img.shields.io/badge/@entrolytics/drizzle--client-C5F74F?style=flat-square&logo=drizzle&logoColor=black)](https://github.com/entrolytics/drizzle-client) | `npm i @entrolytics/drizzle-client` |
| [![Redis](https://img.shields.io/badge/@entrolytics/redis--client-DC382D?style=flat-square&logo=redis&logoColor=white)](https://github.com/entrolytics/redis-client) | `npm i @entrolytics/redis-client` |
| [![Go](https://img.shields.io/badge/github.com/entrolytics/go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/entrolytics/go) | `go get github.com/entrolytics/go` |
| [![Python](https://img.shields.io/badge/entrolytics-PyPI-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/client/python) | `pip install entrolytics` |
| [![PHP](https://img.shields.io/badge/entrolytics/php-777BB4?style=flat-square&logo=php&logoColor=white)](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/client/php) | `composer require entrolytics/php` |

### Middleware, Plugins & Mobile

| Category | Package |
|----------|---------|
| Middleware | [@entrolytics/fastify-middleware](https://github.com/entrolytics/fastify-middleware), [Flask middleware](https://github.com/entrolytics/flask-middleware), [Laravel middleware](https://github.com/entrolytics/laravel) |
| Plugins | [@entrolytics/vercel-integration](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/plugin/vercel), [@entrolytics/netlify-plugin](https://github.com/entrolytics/netlify-plugin), [@entrolytics/shopify-app](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/plugin/shopify), [WordPress plugin](https://github.com/entrolytics/entrolytics-ecosystem/tree/main/ecosystem-external-packages/plugin/wordpress) |
| Mobile | [@entrolytics/react-native](https://github.com/entrolytics/react-native), [Android SDK](https://github.com/entrolytics/android-sdk), [iOS SDK](https://github.com/entrolytics/ios-sdk) |
| Tooling | [@entrolytics/cli](https://github.com/entrolytics/cli), [@entrolytics/shared](https://github.com/entrolytics/shared), [@entrolytics/utilities](https://github.com/entrolytics/utilities) |

## Quick Start

<table>
<tr>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:download.svg?color=%236366f1" width="48"><br>
<strong>1. Install</strong><br>
<code>npm i @entrolytics/nextjs-sdk</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:code.svg?color=%236366f1" width="48"><br>
<strong>2. Add SDK</strong><br>
Add <code>&lt;Analytics /&gt;</code> to your layout
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:settings.svg?color=%236366f1" width="48"><br>
<strong>3. Configure</strong><br>
Set Website ID in <code>.env.local</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:bar-chart-3.svg?color=%236366f1" width="48"><br>
<strong>4. Analyze</strong><br>
Track events and monitor dashboards
</td>
</tr>
</table>

### Example: Next.js

```tsx
// app/layout.tsx
import { Analytics } from '@entrolytics/nextjs-sdk'

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html>
      <body>
        {children}
        <Analytics />
      </body>
    </html>
  )
}
```

```bash
# .env.local
NEXT_PUBLIC_ENTROLYTICS_WEBSITE_ID=your-website-id
NEXT_PUBLIC_ENTROLYTICS_HOST=https://entrolytics.click
```

## Documentation

<div align="center">

| Resource | Link |
|----------|------|
| Platform Docs | [docs.entrolytics.click](https://docs.entrolytics.click) |
| API Reference | [docs.entrolytics.click/api](https://docs.entrolytics.click/api) |
| SDK Documentation | [docs.entrolytics.click/sdks](https://docs.entrolytics.click/sdks) |
| Self-Hosting Guide | [docs.entrolytics.click/self-hosting](https://docs.entrolytics.click/self-hosting) |

</div>

## Contributing

<div align="center">

[![Contributors](https://img.shields.io/github/contributors/entrolytics/entrolytics.svg?logo=github)](https://github.com/entrolytics/entrolytics/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/entrolytics/entrolytics.svg?logo=github)](https://github.com/entrolytics/entrolytics/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/entrolytics/entrolytics.svg?logo=github)](https://github.com/entrolytics/entrolytics/pulls)

</div>

We welcome contributions across both the core platform and external package ecosystem.

| Type | Action |
|------|--------|
| Platform Issues | [Open Issue](https://github.com/entrolytics/entrolytics/issues) |
| Ecosystem Issues | [Open Issue](https://github.com/entrolytics/entrolytics-ecosystem/issues) |
| Feature Ideas | [Start Discussion](https://github.com/orgs/entrolytics/discussions) |

## License

Entrolytics packages are released under the [MIT License](https://opensource.org/licenses/MIT).

---

<div align="center">

  [![Website](https://img.shields.io/badge/Website-entrolytics.click-6366f1?style=for-the-badge)](https://entrolytics.click)
  [![Docs](https://img.shields.io/badge/Docs-docs.entrolytics.click-6366f1?style=for-the-badge)](https://docs.entrolytics.click)
  [![Core Repo](https://img.shields.io/badge/GitHub-entrolytics-111111?style=for-the-badge&logo=github)](https://github.com/entrolytics/entrolytics)
  [![Ecosystem Repo](https://img.shields.io/badge/GitHub-entrolytics--ecosystem-111111?style=for-the-badge&logo=github)](https://github.com/entrolytics/entrolytics-ecosystem)

  <br>
  <sub>Built with care by the Entrolytics team</sub>

</div>
