# Site Studio Pair

Marketing website and documentation hub for the Studio Pair life-management app.

Site Studio Pair is the public-facing website for [Studio Pair](https://github.com/LennyObez/studio-pair), a collaborative life-management app for couples, families, and small groups. It showcases features, pricing, documentation, and support resources. Built with the [Pulsar Framework](https://github.com/LennyObez/pulsar-framework) as a real-world demonstration of Pulsar-powered website development.


## Features

- Product marketing with hero section, module showcase, and pricing comparison
- Documentation hub with getting started guides and module-by-module reference
- Support portal with FAQ and contact form
- Privacy policy and terms of service
- Multilingual content in English, French, Dutch, and German
- SEO: semantic HTML, Open Graph, JSON-LD structured data, sitemap, hreflang tags
- Accessible: WCAG 2.1 AA, keyboard navigation, screen reader support
- Responsive: mobile-first design with prominent app download CTAs
- Dark mode with automatic detection and manual toggle
- Performance: Lighthouse 95+, optimized images (WebP/AVIF), lazy loading

## Tech stack

| Layer | Technology |
|-------|-----------|
| Framework | Pulsar Framework (PHP 8.5+ HMVC) |
| Templating | Pulsar template engine |
| CMS | Pulsar CMS extension |
| Styling | Pulsar UI design system with Studio Pair theme |
| Forms | Pulsar Form extension |
| i18n | Pulsar i18n module (EN, FR, NL, DE) |
| Analytics | Pulsar analytics extension |
| Hosting | AWS EC2 |

## Project structure

```
site-studio-pair/
├── app/
│   └── Modules/
│       ├── Home/
│       ├── Features/
│       ├── Pricing/
│       ├── Docs/
│       ├── Support/
│       └── Legal/
├── bootstrap/
├── config/
├── database/
├── lang/
├── public/
├── resources/
│   ├── views/
│   └── css/
├── storage/
├── tests/
├── tools/
├── .github/
├── CHANGELOG.md
└── LICENSE
```

## Pulsar Framework showcase

This repository serves as a reference implementation for building websites with the [Pulsar Framework](https://github.com/LennyObez/pulsar-framework). It demonstrates:

- HMVC module structure for page-based websites
- Pulsar template engine with layouts and reusable components
- Pulsar CMS extension for managing documentation content
- Internationalization with four languages and hreflang SEO
- Pulsar security defaults (CSRF, CSP, HSTS, rate limiting)
- Pulsar Form extension for contact form handling
- Dark mode with automatic detection and manual toggle
- Deployment on AWS EC2

## Contributing

This repository does not accept external contributions.

## Security

See [SECURITY.md](.github/SECURITY.md).

## License

Source-available -- see [LICENSE](LICENSE) for details.
