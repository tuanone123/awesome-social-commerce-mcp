# Awesome Social & Commerce MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Danh sách tuyển chọn các **máy chủ Model Context Protocol (MCP)** cho **mạng xã hội, marketing, quảng cáo và thương mại điện tử** — để trợ lý AI (Claude, ChatGPT, Gemini, Cursor, Perplexity…) có thể tìm kiếm, đăng bài, chạy quảng cáo và mua hàng thay bạn.

[![MCP](https://img.shields.io/badge/protocol-MCP-blue)](https://modelcontextprotocol.io)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey.svg)](./LICENSE)

🌐 **[English](./README.md)** · **[🇻🇳 Tiếng Việt](./README.vi.md)**

[Model Context Protocol](https://modelcontextprotocol.io) là chuẩn mở kết nối trợ lý AI với công cụ và dữ liệu thật. Danh sách này tập trung vào **hệ sinh thái thương mại**: bán hàng, marketing, quảng cáo và tự động hoá mạng xã hội. Mọi mục đều trỏ tới một máy chủ công khai có thật — server chính chủ và các dự án cộng đồng nổi bật.

---

## Mục lục

- [Ký hiệu](#ký-hiệu)
- [⭐ Nổi bật](#-nổi-bật)
- [Thương mại điện tử & Sàn](#thương-mại-điện-tử--sàn)
- [Thanh toán & Checkout](#thanh-toán--checkout)
- [Quảng cáo & Paid Media](#quảng-cáo--paid-media)
- [Mạng xã hội & Nhắn tin](#mạng-xã-hội--nhắn-tin)
- [Email & CRM](#email--crm)
- [Nội dung, CMS & Thiết kế](#nội-dung-cms--thiết-kế)
- [Dữ liệu web & Thu thập](#dữ-liệu-web--thu-thập)
- [Danh sách liên quan](#danh-sách-liên-quan)
- [Đóng góp](#đóng-góp)

## Ký hiệu

- 🏢 **Chính chủ** — do nền tảng/nhà cung cấp phát hành.
- 👥 **Cộng đồng** — bên thứ ba, không liên kết với nền tảng.
- 🌍 **Remote** — endpoint Streamable HTTP / SSE (không cần cài).
- 💻 **Local** — chạy trên máy bạn (stdio).

---

## ⭐ Nổi bật

- 🌍🏢 **[HOTLIKESHOP](https://github.com/tuanone123/hotlikeshop-mcp)** — Tìm & mua **tài khoản mạng xã hội / MMO, proxy và dịch vụ số** từ mọi trợ lý AI, ngay trong khung chat. Endpoint Streamable HTTP chạy thật (production) với **18 tool** (9 tra cứu · 4 mua hàng · 5 tiện ích), **miễn phí kết nối, tra cứu không cần key**, và quy trình mua an toàn 2 bước `quote_order → buy_product` nên AI không thể tự tiêu tiền. Endpoint: `https://hotlikeshop.com/api/mcp` · Tài liệu: [hotlikeshop.com/ai](https://hotlikeshop.com/ai)

---

## Thương mại điện tử & Sàn

- 👥💻 **[Shopify (shopify-mcp)](https://github.com/GeLi2001/shopify-mcp)** — Truy vấn sản phẩm, đơn hàng, khách hàng và tồn kho qua Shopify Admin API từ Claude hoặc Cursor.
- 🌍🏢 **[HOTLIKESHOP](https://github.com/tuanone123/hotlikeshop-mcp)** — Tài khoản MXH/MMO, proxy và dịch vụ số kèm checkout tự động (xem [Nổi bật](#-nổi-bật)).

## Thanh toán & Checkout

- 🏢 **[Stripe (stripe/ai)](https://github.com/stripe/ai)** — Agent toolkit / MCP chính chủ của Stripe: tạo payment link, hoá đơn, khách hàng và xem số dư.
- 🏢 **[PayPal (agent-toolkit)](https://github.com/paypal/agent-toolkit)** — Toolkit chính chủ PayPal: đơn hàng, hoá đơn, subscription và payout cho AI agent.

## Quảng cáo & Paid Media

- 🌍👥 **[Meta Ads (pipeboard)](https://github.com/pipeboard-co/meta-ads-mcp)** — Chạy quảng cáo Facebook/Instagram: lên campaign, tải creative, chỉnh ngân sách và phân tích hiệu quả.
- 👥 **[Markifact](https://github.com/markifact/markifact-mcp)** — Một server cho Google Ads, Meta Ads, GA4, TikTok Ads và LinkedIn Ads (300+ thao tác, có xác nhận con người khi ghi).
- 👥 **[Synter Media](https://github.com/Synter-Media-AI/mcp-server)** — Quản lý campaign trên Google, Meta, LinkedIn, Microsoft, Reddit và TikTok từ một agent.
- 📚 **[awesome-agentic-advertising](https://github.com/jshorwitz/awesome-agentic-advertising)** — Danh mục chuyên sâu về MCP cho nền tảng quảng cáo (xem [Danh sách liên quan](#danh-sách-liên-quan)).

## Mạng xã hội & Nhắn tin

- 👥💻 **[Reddit (mcp-reddit)](https://github.com/adhikasp/mcp-reddit)** — Lấy và phân tích bài viết, bình luận, thread nổi trên Reddit.
- 👥💻 **[Gmail (Gmail-MCP-Server)](https://github.com/GongRzhe/Gmail-MCP-Server)** — Gửi, tìm, đọc và quản lý Gmail cho quy trình outreach & hỗ trợ.
- 🏢 **[Server tham chiếu (modelcontextprotocol/servers)](https://github.com/modelcontextprotocol/servers)** — Bản tham chiếu chính thức, nền tảng tốt để tự dựng connector mạng xã hội.

## Email & CRM

- 🌍🏢 **[HubSpot (mcp-server)](https://github.com/HubSpot/mcp-server)** — Server chính chủ HubSpot: contact, deal, company, ticket và engagement cho agent marketing & sales.

## Nội dung, CMS & Thiết kế

- 🌍🏢 **[Webflow (mcp-server)](https://github.com/webflow/mcp-server)** — Server chính chủ Webflow để quản lý CMS collection, item và cấu trúc site.
- 🏢 **[WordPress (Automattic/wordpress-mcp)](https://github.com/Automattic/wordpress-mcp)** — Server chính chủ WordPress để đọc và quản lý bài viết, trang, nội dung site.

## Dữ liệu web & Thu thập

- 🌍🏢 **[Bright Data](https://github.com/brightdata/brightdata-mcp)** — Tìm kiếm web + trích xuất dữ liệu có cấu trúc từ Instagram, TikTok, YouTube, X, Reddit, Facebook… (69 tool).
- 🌍🏢 **[Apify (apify-mcp-server)](https://github.com/apify/apify-mcp-server)** — Chạy 5.000+ Apify Actor để thu thập dữ liệu mạng xã hội, sàn TMĐT và web mở.
- 🌍🏢 **[Firecrawl](https://github.com/firecrawl/firecrawl-mcp-server)** — Biến mọi website thành markdown sạch, sẵn sàng cho LLM dùng để nghiên cứu & làm nội dung.

---

## Danh sách liên quan

- **[punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** — Danh mục MCP server tổng hợp lớn nhất.
- **[jshorwitz/awesome-agentic-advertising](https://github.com/jshorwitz/awesome-agentic-advertising)** — MCP server, công cụ và giao thức cho quảng cáo bằng AI.
- **[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)** — Server tham chiếu chính thức + cộng đồng.

## Mới với MCP?

Muốn tự dựng một MCP server cho thương mại? Bắt đầu với hướng dẫn song ngữ, dễ cho người mới: **[mcp-quickstart-vietnamese](https://github.com/tuanone123/mcp-quickstart-vietnamese)** (dựng, test và deploy một remote Streamable HTTP server từng bước).

## Đóng góp

Biết một MCP server social/commerce hay? Rất hoan nghênh đóng góp — vui lòng đọc [hướng dẫn đóng góp](./CONTRIBUTING.md) trước. Giữ cho các mục là thật, công khai và đúng chủ đề.

## Giấy phép

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](./LICENSE)

Trong phạm vi luật cho phép, người duy trì từ bỏ mọi quyền tác giả với danh sách này (CC0 1.0). Các dự án được liệt kê vẫn thuộc giấy phép riêng của chúng.
