<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://ng.entrolytics.click/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://ng.entrolytics.click/logo-light.svg">
  <img alt="Entrolytics" src="https://ng.entrolytics.click/logo-light.svg" width="280">
</picture>

# Entrolytics

**First-party growth analytics for the edge.**

Entrolytics is a unified analytics platform that brings together web analytics, link tracking, and conversion pixels into one data plane. Privacy-focused, cookie-free, and built for the modern edge-first web.

---

## 🚀 SDKs & Integrations

### Frontend SDKs

| Package | Description | Install |
|---------|-------------|---------|
| [@entrolytics/react-sdk](https://github.com/entrolytics/react-sdk) | React SDK for Entrolytics | `npm i @entrolytics/react` |
| [@entrolytics/vue-sdk](https://github.com/entrolytics/vue-sdk) | Vue SDK for Entrolytics | `npm i @entrolytics/vue` |
| [@entrolytics/svelte-sdk](https://github.com/entrolytics/svelte-sdk) | SvelteKit SDK for Entrolytics | `npm i @entrolytics/svelte` |
| [@entrolytics/nextjs-sdk](https://github.com/entrolytics/nextjs-sdk) | Next.js SDK for Entrolytics | `npm i @entrolytics/nextjs` |
| [@entrolytics/astro-sdk](https://github.com/entrolytics/astro-sdk) | Astro SDK for Entrolytics | `npm i @entrolytics/astro` |

### Server-Side SDKs

| Package | Description | Install |
|---------|-------------|---------|
| [@entrolytics/node-sdk](https://github.com/entrolytics/node-sdk) | Node.js SDK for Entrolytics | `npm i @entrolytics/node` |
| [entrolytics-ng](https://github.com/entrolytics/python-sdk) | Python SDK for Entrolytics | `pip install entrolytics-ng` |
| [entrolytics-ng/php](https://github.com/entrolytics/php-sdk) | PHP SDK for Entrolytics | `composer require entrolytics-ng/php` |
| [entro-go](https://github.com/entrolytics/go-sdk) | Go SDK for Entrolytics | `go get github.com/entrolytics/entro-go` |

### Platform Integrations

| Package | Description | Platform |
|---------|-------------|----------|
| [@entrolytics/netlify-plugin](https://github.com/entrolytics/netlify-integration) | Netlify integration for Entrolytics | Netlify |
| [@entrolytics/vercel-integration](https://github.com/entrolytics/vercel-integration) | Vercel integration for Entrolytics | Vercel |
| [@entrolytics/shopify-app](https://github.com/entrolytics/shopify-integration) | Shopify app for Entrolytics | Shopify |
| [entrolytics-wordpress](https://github.com/entrolytics/wordpress-plugin) | WordPress plugin for Entrolytics | WordPress |

### Tools & Utilities

| Package | Description |
|---------|-------------|
| [@entrolytics/cli](https://github.com/entrolytics/cli) | CLI for Entrolytics |
| [@entrolytics/api-client](https://github.com/entrolytics/api-client) | TypeScript API client for Entrolytics |

---

## ✨ Features

- **🔒 Privacy-First** — No cookies, no personal data, GDPR compliant by default
- **⚡ Edge-Optimized** — Sub-50ms response times globally via edge runtime
- **📊 Unified Platform** — Web analytics, link tracking, and conversion pixels in one place
- **🔌 Framework Native** — First-class support for React, Vue, Svelte, Next.js, Astro, and more
- **🌍 Self-Hostable** — Deploy on your own infrastructure or use Entrolytics Cloud
- **📈 Real-Time** — Live visitor tracking and instant event streaming
- **🛒 E-commerce Ready** — Built-in revenue tracking and funnel analytics

---

## 📖 Quick Start

### 1. Install the SDK

```bash
# React
npm install @entrolytics/react

# Next.js
npm install @entrolytics/nextjs

# Vue
npm install @entrolytics/vue

# Astro
npm install @entrolytics/astro
```

### 2. Add to your app

```tsx
// Next.js example
import { Analytics } from '@entrolytics/nextjs';

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

### 3. Configure environment

```bash
# .env.local
NEXT_PUBLIC_ENTROLYTICS_NG_WEBSITE_ID=your-website-id
NEXT_PUBLIC_ENTROLYTICS_HOST=https://ng.entrolytics.click
```

---

## 📚 Documentation

Visit [docs.entrolytics.click](https://docs.entrolytics.click) for full documentation.

- [Getting Started](https://docs.entrolytics.click/getting-started)
- [SDK Reference](https://docs.entrolytics.click/sdks)
- [API Documentation](https://docs.entrolytics.click/api)
- [Self-Hosting Guide](https://docs.entrolytics.click/self-hosting)

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](https://github.com/entrolytics/.github/blob/main/CONTRIBUTING.md) for details.

- 🐛 [Report bugs](https://github.com/entrolytics/entrolytics-ng/issues)
- 💡 [Request features](https://github.com/entrolytics/entrolytics-ng/discussions)
- 📝 [Improve docs](https://github.com/entrolytics/docs)

---

## 📄 License

All Entrolytics packages are released under the [MIT License](LICENSE).

---

<p align="center">
  <a href="https://ng.entrolytics.click">Website</a> •
  <a href="https://docs.entrolytics.click">Docs</a> •
  <a href="https://twitter.com/entrolytics">Twitter</a> •
  <a href="https://discord.gg/entrolytics">Discord</a>
</p>
