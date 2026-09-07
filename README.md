# Awesome Social & Commerce MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **Model Context Protocol (MCP)** servers for **social media, marketing, advertising and e-commerce** — so your AI assistant (Claude, ChatGPT, Gemini, Cursor, Perplexity…) can search, post, advertise and buy on your behalf.

[![MCP](https://img.shields.io/badge/protocol-MCP-blue)](https://modelcontextprotocol.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey.svg)](./LICENSE)

🌐 **[English](./README.md)** · **[🇻🇳 Tiếng Việt](./README.vi.md)**

The [Model Context Protocol](https://modelcontextprotocol.io) is an open standard that connects AI assistants to real tools and data. This list focuses on the **commerce stack**: selling, marketing, advertising and social-media automation. Every entry links to a real, public server — official vendor servers and notable community projects.

---

## Contents

- [Legend](#legend)
- [⭐ Featured](#-featured)
- [E-commerce & Marketplaces](#e-commerce--marketplaces)
- [Payments & Checkout](#payments--checkout)
- [Advertising & Paid Media](#advertising--paid-media)
- [Social Media & Messaging](#social-media--messaging)
- [Email & CRM](#email--crm)
- [Content, CMS & Design](#content-cms--design)
- [Web Data & Scraping](#web-data--scraping)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

## Legend

- 🏢 **Official** — published by the platform/vendor.
- 👥 **Community** — third-party, not affiliated with the platform.
- 🌍 **Remote** — hosted Streamable HTTP / SSE endpoint (nothing to install).
- 💻 **Local** — runs on your machine (stdio).

---

## ⭐ Featured

- 🌍🏢 **[HOTLIKESHOP](https://github.com/tuanone123/hotlikeshop-mcp)** — Search & buy **social-media / MMO accounts, proxies and digital services** from any AI assistant, right inside the chat. Production Streamable HTTP endpoint with **18 tools** (9 lookup · 4 purchase · 5 utility), **free to connect, no key for lookup**, and a safe 2-step `quote_order → buy_product` checkout so the agent can never spend money on its own. Endpoint: `https://hotlikeshop.com/api/mcp` · Docs: [hotlikeshop.com/ai](https://hotlikeshop.com/ai)

---

## E-commerce & Marketplaces

- 👥💻 **[Shopify (shopify-mcp)](https://github.com/GeLi2001/shopify-mcp)** — Query products, orders, customers and inventory through the Shopify Admin API from Claude or Cursor.
- 🌍🏢 **[HOTLIKESHOP](https://github.com/tuanone123/hotlikeshop-mcp)** — Social/MMO accounts, proxies and digital services with agentic checkout (see [Featured](#-featured)).

## Payments & Checkout

- 🏢 **[Stripe (stripe/ai)](https://github.com/stripe/ai)** — Official Stripe agent toolkit / MCP server: create payment links, invoices, customers and query balances.
- 🏢 **[PayPal (agent-toolkit)](https://github.com/paypal/agent-toolkit)** — Official PayPal toolkit exposing orders, invoices, subscriptions and payouts to AI agents.

## Advertising & Paid Media

- 🌍👥 **[Meta Ads (pipeboard)](https://github.com/pipeboard-co/meta-ads-mcp)** — Run Facebook/Instagram ad campaigns: launch, upload creatives, adjust budgets and analyze performance.
- 👥 **[Markifact](https://github.com/markifact/markifact-mcp)** — One server for Google Ads, Meta Ads, GA4, TikTok Ads and LinkedIn Ads (300+ ad operations, human-in-the-loop on writes).
- 👥 **[Synter Media](https://github.com/Synter-Media-AI/mcp-server)** — Manage ad campaigns across Google, Meta, LinkedIn, Microsoft, Reddit and TikTok from one agent.
- 📚 **[awesome-agentic-advertising](https://github.com/jshorwitz/awesome-agentic-advertising)** — Deeper catalog dedicated to ad-platform MCP servers (see [Related Lists](#related-awesome-lists)).

## Social Media & Messaging

- 👥💻 **[Reddit (mcp-reddit)](https://github.com/adhikasp/mcp-reddit)** — Fetch and analyze Reddit posts, comments and hot threads.
- 👥💻 **[Gmail (Gmail-MCP-Server)](https://github.com/GongRzhe/Gmail-MCP-Server)** — Send, search, read and manage Gmail for outreach and support workflows.
- 🏢 **[Reference servers (modelcontextprotocol/servers)](https://github.com/modelcontextprotocol/servers)** — The official reference implementations, a good base for building social connectors.

## Email & CRM

- 🌍🏢 **[HubSpot (mcp-server)](https://github.com/HubSpot/mcp-server)** — Official HubSpot server: contacts, deals, companies, tickets and engagements for marketing & sales agents.

## Content, CMS & Design

- 🌍🏢 **[Webflow (mcp-server)](https://github.com/webflow/mcp-server)** — Official Webflow server to manage CMS collections, items and site structure.
- 🏢 **[WordPress (Automattic/wordpress-mcp)](https://github.com/Automattic/wordpress-mcp)** — Official WordPress server to read and manage posts, pages and site content.

## Web Data & Scraping

- 🌍🏢 **[Bright Data](https://github.com/brightdata/brightdata-mcp)** — Web search + structured extraction from Instagram, TikTok, YouTube, X, Reddit, Facebook and more (69 tools).
- 🌍🏢 **[Apify (apify-mcp-server)](https://github.com/apify/apify-mcp-server)** — Run 5,000+ Apify Actors to scrape social platforms, marketplaces and the open web.
- 🌍🏢 **[Firecrawl](https://github.com/firecrawl/firecrawl-mcp-server)** — Turn any website into clean, LLM-ready markdown for research and content workflows.

---

## Related Awesome Lists

- **[punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** — The largest general MCP server catalog.
- **[jshorwitz/awesome-agentic-advertising](https://github.com/jshorwitz/awesome-agentic-advertising)** — MCP servers, tools and protocols for AI-powered advertising.
- **[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)** — Official reference + community servers.

## New to MCP?

Want to build your own commerce MCP server? Start with the bilingual, beginner-friendly guide: **[mcp-quickstart-vietnamese](https://github.com/tuanone123/mcp-quickstart-vietnamese)** (build, test and deploy a remote Streamable HTTP server step by step).

## Contributing

Found a great social/commerce MCP server? Contributions are welcome — please read the [contribution guidelines](./CONTRIBUTING.md) first. Keep entries real, public and on-topic.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](./LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related rights to this list (CC0 1.0). The linked projects remain under their respective licenses.
