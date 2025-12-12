<div align="center">
  <img src="https://raw.githubusercontent.com/entrolytics/.github/main/media/entrov2.png" alt="Entrolytics" width="64" height="64">
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6.svg?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Next.js](https://img.shields.io/badge/Next.js-15-000000.svg?logo=next.js)](https://nextjs.org/)
  [![npm](https://img.shields.io/npm/v/@entrolytics/nextjs-sdk.svg?logo=npm&label=nextjs-sdk)](https://www.npmjs.com/package/@entrolytics/nextjs-sdk)
  [![GitHub stars](https://img.shields.io/github/stars/entrolytics/entrolytics-ng.svg?logo=github)](https://github.com/entrolytics/entrolytics-ng/stargazers)

</div>

---

## Overview

**Entrolytics** is a unified analytics platform that brings web analytics, link tracking, and conversion pixels into one data plane. Built for the modern edge-first web with sub-50ms response times globally.

**Why Entrolytics?**
- Privacy-focused analytics without cookies or personal data collection
- Edge-optimized for global performance with intelligent routing
- Self-hostable or use Entrolytics Cloud

## Key Features

<table>
<tr>
<td width="50%">

### Web Analytics
- Real-time visitor tracking and pageviews
- Traffic sources and referrer analysis
- Device, browser, and OS breakdown
- Geographic data (country/city level)

### Link Tracking
- Branded short links with analytics
- UTM parameter tracking
- QR code generation
- Click-through rate monitoring

</td>
<td width="50%">

### Conversion Pixels
- E-commerce revenue tracking
- Custom event tracking
- Funnel and conversion analytics
- A/B testing with tag segmentation

### Developer Experience
- Zero-config setup for major frameworks
- Full TypeScript support
- Server-side and client-side tracking
- Comprehensive API and SDKs

</td>
</tr>
</table>

## Tech Stack

<div align="center">

| Technology | Description |
|------------|-------------|
| ![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=for-the-badge&logo=next.js) | Platform & Edge Runtime |
| ![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white) | Type-safe development |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) | Serverless database |
| ![Redis](https://img.shields.io/badge/Redis-Upstash-DC382D?style=for-the-badge&logo=redis&logoColor=white) | Edge caching & rate limiting |
| ![Vercel](https://img.shields.io/badge/Vercel-Edge-000000?style=for-the-badge&logo=vercel) | Global edge deployment |

</div>

## SDKs & Integrations

### Frontend SDKs

| Package | Install |
|---------|---------|
| [![React](https://img.shields.io/badge/@entrolytics/react--sdk-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/entrolytics/entrolytics-react-sdk) | `npm i @entrolytics/react-sdk` |
| [![Vue](https://img.shields.io/badge/@entrolytics/vue--sdk-4FC08D?style=flat-square&logo=vue.js&logoColor=white)](https://github.com/entrolytics/entrolytics-vue-sdk) | `npm i @entrolytics/vue-sdk` |
| [![Svelte](https://img.shields.io/badge/@entrolytics/svelte--sdk-FF3E00?style=flat-square&logo=svelte&logoColor=white)](https://github.com/entrolytics/entrolytics-svelte-sdk) | `npm i @entrolytics/svelte-sdk` |
| [![Next.js](https://img.shields.io/badge/@entrolytics/nextjs--sdk-000000?style=flat-square&logo=next.js)](https://github.com/entrolytics/entrolytics-nextjs-sdk) | `npm i @entrolytics/nextjs-sdk` |
| [![Astro](https://img.shields.io/badge/@entrolytics/astro--sdk-BC52EE?style=flat-square&logo=astro&logoColor=white)](https://github.com/entrolytics/entrolytics-astro-sdk) | `npm i @entrolytics/astro-sdk` |

### Server-Side SDKs

| Package | Install |
|---------|---------|
| [![Node.js](https://img.shields.io/badge/@entrolytics/node--sdk-339933?style=flat-square&logo=node.js&logoColor=white)](https://github.com/entrolytics/entrolytics-node) | `npm i @entrolytics/node-sdk` |
| [![Python](https://img.shields.io/badge/entrolytics--ng-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/entrolytics/entrolytics-python-sdk) | `pip install entrolytics-ng` |
| [![PHP](https://img.shields.io/badge/entrolytics--ng/php-777BB4?style=flat-square&logo=php&logoColor=white)](https://github.com/entrolytics/entrolytics-php-sdk) | `composer require entrolytics-ng/php` |
| [![Go](https://img.shields.io/badge/entrolytics/go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/entrolytics/entrolytics-go-sdk) | `go get github.com/entrolytics/go` |

### Platform Integrations

| Platform | Package |
|----------|---------|
| [![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel)](https://github.com/entrolytics/entrolytics-vercel-integration) | One-click Vercel Marketplace integration |
| [![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://github.com/entrolytics/entrolytics-netlify-integration) | Netlify Build Plugin |
| [![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)](https://github.com/entrolytics/entrolytics-shopify-integration) | Shopify App with e-commerce tracking |
| [![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)](https://github.com/entrolytics/entrolytics-wordpress-plugin) | WordPress plugin with WooCommerce support |

### Tools

| Tool | Description |
|------|-------------|
| [![CLI](https://img.shields.io/badge/@entrolytics/cli-4A4A4A?style=flat-square&logo=windowsterminal&logoColor=white)](https://github.com/entrolytics/entrolytics-cli) | Command-line interface for project setup and analytics |
| [![API Client](https://img.shields.io/badge/@entrolytics/api--client-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/entrolytics/entrolytics-api-client) | TypeScript API client for programmatic access |

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
<strong>2. Add Component</strong><br>
Add <code>&lt;Analytics /&gt;</code> to layout
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:settings.svg?color=%236366f1" width="48"><br>
<strong>3. Configure</strong><br>
Set Website ID in <code>.env</code>
</td>
<td align="center" width="25%">
<img src="https://api.iconify.design/lucide:bar-chart-3.svg?color=%236366f1" width="48"><br>
<strong>4. Track</strong><br>
View analytics in dashboard
</td>
</tr>
</table>

### Example: Next.js

```tsx
// app/layout.tsx
import { Analytics } from '@entrolytics/nextjs-sdk';

export default function RootLayout({ children }) {
  return (
    <html>
      <body>
        {children}
        <Analytics />
      </body>
    </html>
  );
}
```

```bash
# .env.local
NEXT_PUBLIC_ENTROLYTICS_NG_WEBSITE_ID=your-website-id
NEXT_PUBLIC_ENTROLYTICS_HOST=https://ng.entrolytics.click
```

## Documentation

<div align="center">

| Resource | Link |
|----------|------|
| Getting Started | [docs.entrolytics.click/getting-started](https://docs.entrolytics.click/getting-started) |
| SDK Reference | [docs.entrolytics.click/sdks](https://docs.entrolytics.click/sdks) |
| API Documentation | [docs.entrolytics.click/api](https://docs.entrolytics.click/api) |
| Self-Hosting Guide | [docs.entrolytics.click/self-hosting](https://docs.entrolytics.click/self-hosting) |

</div>

## Contributing

<div align="center">

[![Contributors](https://img.shields.io/github/contributors/entrolytics/entrolytics-ng.svg?logo=github)](https://github.com/entrolytics/entrolytics-ng/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/entrolytics/entrolytics-ng.svg?logo=github)](https://github.com/entrolytics/entrolytics-ng/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/entrolytics/entrolytics-ng.svg?logo=github)](https://github.com/entrolytics/entrolytics-ng/pulls)

</div>

We welcome contributions! See our [Contributing Guide](https://github.com/entrolytics/.github/blob/main/CONTRIBUTING.md) for details.

| Type | Action |
|------|--------|
| Bug Report | [Open Issue](https://github.com/entrolytics/entrolytics-ng/issues/new?template=bug_report.md) |
| Feature Request | [Open Discussion](https://github.com/entrolytics/entrolytics-ng/discussions/new?category=ideas) |
| Question | [Start Discussion](https://github.com/entrolytics/entrolytics-ng/discussions) |

## License

All Entrolytics packages are released under the [MIT License](https://opensource.org/licenses/MIT).

---

<div align="center">

  [![Website](https://img.shields.io/badge/Website-ng.entrolytics.click-6366f1?style=for-the-badge)](https://ng.entrolytics.click)
  [![Docs](https://img.shields.io/badge/Docs-docs.entrolytics.click-6366f1?style=for-the-badge)](https://docs.entrolytics.click)
  [![Twitter](https://img.shields.io/badge/Twitter-@entrolytics-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/entrolytics)
  [![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/entrolytics)

  <br>
  <sub>Built with care by the Entrolytics team</sub>

</div>
