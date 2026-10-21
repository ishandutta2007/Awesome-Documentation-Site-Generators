# Awesome-Documentation-Site-Generators

## Top Documentation Site Generators Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Markdown-First Authoring, API Reference Rendering & Agent-Ready Exports*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Documentation Site Generators**. These tools enable teams to turn Markdown, MDX, and OpenAPI specs into searchable, navigable documentation sites—from fully managed platforms with built-in analytics and AI assistants to self-hosted generators that build static HTML or render Markdown in the browser at runtime.



**Examples** include GitBook, ReadMe, Mintlify, Fern, Scalar, Redocly, Docusaurus, Docsify, MkDocs, and VitePress (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, static site generation, and open documentation infrastructure—ideal for developers, technical writers, and organizations seeking transparent, vendor-independent documentation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

### Sector Overview & Market Dynamics

The global developer documentation and technical knowledge management market is currently valued at approximately **.8B – .4B**, growing at a ~16% CAGR fueled by explosive API expansion and AI-agent documentation standards (llms.txt, MCP). The sector is **moderately fragmented** rather than a winner-take-all monopoly: while mega-scale enterprise players like Atlassian Confluence dominate broad internal workspace knowledge, specialized modern developer platforms (GitBook, Mintlify, ReadMe) and deeply entrenched open-source static generators (Docusaurus, MkDocs, Hugo) hold resilient, thriving positions across developer workflows.

| Platform | Company Size (Valuation / Revenue) | Key Focus & Capabilities | Pricing (Starting Paid Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Confluence](https://www.atlassian.com/software/confluence)** | **~ Market Cap** (NASDAQ: TEAM) / **.4B ARR** | Enterprise team workspace and collaborative documentation hub deeply integrated with Atlassian Jira | **.75 / user / month** (billed annually, or .05/user/mo monthly) for Standard tier; includes 250 GB storage, user permissions, audit logs, and 9/5 support | **Free forever for up to 10 users** with 2 GB file storage, unlimited spaces and pages, Jira & Trello integrations, macro library, and community support |
| **[GitBook](https://www.gitbook.com/)** | **~ Valuation** / **~ ARR** (+ raised) | Block-based collaborative documentation with native Git sync, API playgrounds, and AI assistant | ** / site / month** (billed annually, or /mo monthly) for Essential tier; includes 1 user (+/user/mo extra), 2,000 AI credits/mo, custom domain, and analytics | **Free forever for 1 user/admin** with unlimited public documentation spaces, visual block editor, GitHub/GitLab bidirectional sync, and OpenAPI playground |
| **[Mintlify](https://mintlify.com/)** | **~ Valuation** / **.5M Total Raised** (a16z) | Agent-ready MDX documentation platform with automated code snippets, AI assistant, and MCP integration | ** / month** for Pro tier; includes unlimited editor seats, custom subpaths, automated preview deployments, admin APIs, and 10,000 AI credits/month | **Free forever for up to 5 editor seats** with full core MDX platform, unlimited public pages, GitHub sync, custom domain, and MCP server (no credit card required) |
| **[ReadMe](https://readme.com/)** | **~ Valuation** / **~ ARR** ( raised) | Developer hub & API-first documentation platform with interactive API Explorer, metrics, and workflows | ** / project / month** for Pro tier; adds Ask AI Lite, automated API linting, version branching, staging environments, and custom CSS/HTML | **Free forever for 1 project & 1 admin** with unlimited interactive API references, Markdown editor, custom domain, llms.txt & MCP server; plus **14-day free trial** of Pro |
| **[Document360](https://document360.com/)** | **~ Valuation** / **~ ARR** (Kovai.co) | AI-powered knowledge base and technical documentation platform with Eddy AI and analytics | ** / project / month** (billed annually, or /mo monthly) for Professional tier; includes 3 team accounts, 1 public knowledge base, and custom domain | **14-day free trial** with full access to Enterprise knowledge base suite, Eddy AI search/writer, and custom branding (no credit card required) |
| **[Redocly](https://redocly.com/)** | **~ Valuation** / **~ ARR** (Profitable) | OpenAPI documentation, developer portal, and API governance platform by the creators of Redoc | ** / seat / month** for Pro tier; includes custom domain, OpenAPI CLI linting, version branching, and premium docs themes | **Free forever for 1 project & 1 user seat** with OpenAPI/Swagger reference rendering, GitHub/GitLab integration, and 1 preview build |
| **[Fern](https://buildwithfern.com/)** | **~ Valuation** / **.2M Seed Raised** (YC W23) | Open-core API documentation and SDK generator platform turning OpenAPI specs into interactive docs | ** / month** (billed annually, or /mo monthly) for Team tier; includes 5 team members, 1,000 AI credits/mo, custom subpaths, and password-protected docs | **Free forever for up to 2 team members** with 250 AI credits/month, custom domain, guides, OpenAPI reference generation, and web editor |
| **[Archbee](https://www.archbee.com/)** | **~ Valuation** / **~ ARR** (.5M Seed, YC) | Documentation platform for product & engineering teams combining API references with knowledge bases | ** / month** (billed annually, or /mo monthly) for Growing tier; includes 3 editor seats, unlimited public readers, unlimited docs, and custom domain | **14-day free trial** with full access to multi-space documentation, API doc generator, OpenAPI swagger imports, and contextual search |
| **[Scalar](https://scalar.com/)** | **~ Valuation** / **Seed-stage** | Interactive OpenAPI-native documentation platform and REST API client with modern UI | ** / month** (billed annually, or /mo monthly) for Pro tier; includes 15 APIs, 500 Agent credits, custom domains, and Git sync | **Free forever for up to 3 APIs** with 1 client SDK generator (up to 25 endpoints), 50 Agent Scalar AI credits, and full OpenAPI interactive rendering |

## Open-Source GitHub Projects

The leading open-source documentation site generators, frameworks, and API rendering engines—ranked in descending order by GitHub star count:

- **[Hugo](https://github.com/gohugoio/hugo)** [![GitHub stars](https://img.shields.io/github/stars/gohugoio/hugo?style=social&color=white)](https://github.com/gohugoio/hugo/stargazers)
  **The world's fastest framework for building websites** (Apache-2.0) — Written in Go. Blazing sub-millisecond build speeds make it the industry benchmark for massive documentation sites and enterprise knowledge bases with thousands of pages.

- **[Docusaurus](https://github.com/facebook/docusaurus)** [![GitHub stars](https://img.shields.io/github/stars/facebook/docusaurus?style=social&color=white)](https://github.com/facebook/docusaurus/stargazers)
  **Easy to maintain open source documentation websites** (MIT) — Built by Meta. The React & MDX gold standard featuring out-of-the-box versioning, multi-language localization, Algolia DocSearch, and an extensive plugin ecosystem.

- **[Jekyll](https://github.com/jekyll/jekyll)** [![GitHub stars](https://img.shields.io/github/stars/jekyll/jekyll?style=social&color=white)](https://github.com/jekyll/jekyll/stargazers)
  **Transform plain text into static websites and blogs** (MIT) — The battle-tested Ruby static generator with native zero-configuration GitHub Pages hosting support and Liquid templating.

- **[Slate](https://github.com/slatedocs/slate)** [![GitHub stars](https://img.shields.io/github/stars/slatedocs/slate?style=social&color=white)](https://github.com/slatedocs/slate/stargazers)
  **Beautiful static documentation for your API** (Apache-2.0) — Pioneer of the clean, 3-column responsive layout (navigation, documentation, code samples in multiple languages) rendered from clean Markdown.

- **[Docsify](https://github.com/docsifyjs/docsify)** [![GitHub stars](https://img.shields.io/github/stars/docsifyjs/docsify?style=social&color=white)](https://github.com/docsifyjs/docsify/stargazers)
  **A magical documentation site generator with no statically built HTML files** (MIT) — Parses Markdown on the fly in the browser. Zero build steps, instant deployment on any CDN or file server, with modular sidebar and search plugins.

- **[Swagger UI](https://github.com/swagger-api/swagger-ui)** [![GitHub stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers)
  **Interactive API documentation for OpenAPI specifications** (Apache-2.0) — The ubiquitous standard for rendering interactive REST API specifications, allowing developers to execute live test requests directly in the browser.

- **[Material for MkDocs](https://github.com/squidfunk/mkdocs-material)** [![GitHub stars](https://img.shields.io/github/stars/squidfunk/mkdocs-material?style=social&color=white)](https://github.com/squidfunk/mkdocs-material/stargazers)
  **Modern, technical documentation that simply works** (MIT) — The premier theme and extension suite for MkDocs, offering instant offline search, code annotations, mathematical typesetting, dark mode, and multi-language support.

- **[Redoc](https://github.com/Redocly/redoc)** [![GitHub stars](https://img.shields.io/github/stars/Redocly/redoc?style=social&color=white)](https://github.com/Redocly/redoc/stargazers)
  **OpenAPI/Swagger-generated API reference documentation** (MIT) — Extremely responsive 3-panel API documentation with interactive code snippets, deep JSON schema validation, and zero server-side lock-in.

- **[VuePress](https://github.com/vuejs/vuepress)** [![GitHub stars](https://img.shields.io/github/stars/vuejs/vuepress?style=social&color=white)](https://github.com/vuejs/vuepress/stargazers)
  **Vue-powered Static Site Generator** (MIT) — Generates pre-rendered static HTML with SPA routing. Markdown files can leverage Vue components for interactive documentation and live demos.

- **[MkDocs](https://github.com/mkdocs/mkdocs)** [![GitHub stars](https://img.shields.io/github/stars/mkdocs/mkdocs?style=social&color=white)](https://github.com/mkdocs/mkdocs/stargazers)
  **Project documentation with Markdown** (BSD-2-Clause) — The foundational Python documentation generator. Simple YAML configuration, built-in dev server with live reload, and deployable to GitHub Pages in one command.

- **[mdBook](https://github.com/rust-lang/mdBook)** [![GitHub stars](https://img.shields.io/github/stars/rust-lang/mdBook?style=social&color=white)](https://github.com/rust-lang/mdBook/stargazers)
  **Create book-style documentation from Markdown files** (MPL-2.0) — Built in Rust (powers official Rust documentation). Zero runtime dependencies, instant builds, built-in search, and customizable themes.

- **[Eleventy (11ty)](https://github.com/11ty/eleventy)** [![GitHub stars](https://img.shields.io/github/stars/11ty/eleventy?style=social&color=white)](https://github.com/11ty/eleventy/stargazers)
  **Simpler, flexible JavaScript static site generator** (MIT) — Zero client-side JavaScript by default, supports multiple template engines (Markdown, Liquid, Nunjucks, HTML), and delivers ultra-lean web performance.

- **[VitePress](https://github.com/vuejs/vitepress)** [![GitHub stars](https://img.shields.io/github/stars/vuejs/vitepress?style=social&color=white)](https://github.com/vuejs/vitepress/stargazers)
  **Vite & Vue-powered modern static site generator** (MIT) — Successor to VuePress, featuring sub-second dev server startup, lightning-fast HMR, built-in search, i18n, and markdown code groups.

- **[Zola](https://github.com/getzola/zola)** [![GitHub stars](https://img.shields.io/github/stars/getzola/zola?style=social&color=white)](https://github.com/getzola/zola/stargazers)
  **Fast single-binary static site generator with everything built in** (EUPL-1.2) — Written in Rust, with Tera templates, Sass compilation, syntax highlighting, and search indexing without external dependencies.

- **[Scalar](https://github.com/scalar/scalar)** [![GitHub stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers)
  **Modern REST API platform & interactive reference docs** (MIT) — Open-source interactive OpenAPI client and documentation renderer with modern UI, request playgrounds, and multi-language code snippets.

- **[Nextra](https://github.com/shuding/nextra)** [![GitHub stars](https://img.shields.io/github/stars/shuding/nextra?style=social&color=white)](https://github.com/shuding/nextra/stargazers)
  **Simple, powerful and flexible site generation framework with Next.js** (MIT) — Built on Next.js App Router and React Server Components, delivering full React ecosystem integration with MDX support.

- **[Astro Starlight](https://github.com/withastro/starlight)** [![GitHub stars](https://img.shields.io/github/stars/withastro/starlight?style=social&color=white)](https://github.com/withastro/starlight/stargazers)
  **Content-first documentation framework built on Astro** (MIT) — Delivers maximum performance via Astro Islands (minimal client-side JS), Pagefind search out of the box, dark mode, i18n, and WCAG AA accessibility.

- **[Read the Docs](https://github.com/readthedocs/readthedocs.org)** [![GitHub stars](https://img.shields.io/github/stars/readthedocs/readthedocs.org?style=social&color=white)](https://github.com/readthedocs/readthedocs.org/stargazers)
  **Continuous documentation hosting platform** (MIT) — Automatically builds, versions, and hosts documentation from Git repositories using Sphinx and MkDocs, supporting version switching and PDF/ePub exports.

- **[Sphinx](https://github.com/sphinx-doc/sphinx)** [![GitHub stars](https://img.shields.io/github/stars/sphinx-doc/sphinx?style=social&color=white)](https://github.com/sphinx-doc/sphinx/stargazers)
  **Python documentation generator** (BSD-2-Clause) — Powers Python's official documentation and thousands of libraries; unmatched cross-referencing, autodoc docstring extraction, and multiple output formats.

- **[Fern](https://github.com/fern-api/fern)** [![GitHub stars](https://img.shields.io/github/stars/fern-api/fern?style=social&color=white)](https://github.com/fern-api/fern/stargazers)
  **Open-source CLI to output SDKs and docs from OpenAPI** (Apache-2.0) — Generates production-ready API documentation sites and typed SDKs (TypeScript, Python, Go, Java) from OpenAPI definitions.

## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Documentation platforms handling enterprise content must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "hosted platform vs. static generator" distinction matters.** **GitBook, ReadMe, and Mintlify** provide managed hosting, analytics, and AI features—fast to start, but subscription costs scale with seats and features . **Docusaurus, MkDocs, and VitePress** are static generators—you own hosting, but the build output is portable and free . **Choose based on whether you want to operate documentation infrastructure or rent it.**

- **Docsify's no-build model is genuinely different.** **Markdown fetches in the browser at runtime**—no static HTML, no build step, deploy anywhere . **The trade-off**: **no built-in llms.txt or MCP support**, and search/navigation require plugin configuration . **Choose when you want the smallest possible client-side stack.**

- **ReadMe vs. Mintlify: the AI pricing model differs.** **ReadMe's Starter is free with no AI credits**; Pro at $250/month adds Ask AI Lite . **Mintlify's Pro at $450/month includes 10,000 AI credits** with $0.01 per overage . **ReadMe's Pro includes $150/month for Ask AI separately**—stacked on Pro, that's $400 total, still under Mintlify's $450 . **Model your expected AI usage before choosing.**

- **Fern's open-core model is unique.** **The CLI and code generators are Apache-2.0**—running SDK and docs generation in your own CI/CD carries only compute cost . **The hosted Docs and SDK product is a SaaS subscription** with Hobby, Team, and Enterprise tiers . **Choose Fern when you want open-source generators with optional hosted docs.**

- Self-hosted open-source solutions require proper build configuration, hosting setup, and ongoing maintenance. **Documentation is a product**—broken links and outdated content erode trust in the underlying software.



---



**Made for developers, technical writers, and organizations building transparent documentation solutions.**  

Let's make Documentation Site Generators more open, data-driven, and agent-ready.
