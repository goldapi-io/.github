# 🥇 GoldAPI.io| Real-Time Gold & Silver JSON REST API

Real-time precious metals infrastructure for developers, businesses and AI agents.

GoldAPI.io provides live and historical market data for:

- Gold (XAU)
- Silver (XAG)
- Platinum (XPT)
- Palladium (XPD)

Build:

- Gold price widgets
- Bullion dealer systems
- Jewelry calculators
- Trading applications
- Portfolio dashboards
- AI agents
- Automation workflows
- WordPress plugins
- Internal business tools

---

## 🚀 Quick Example

```javascript
const response = await fetch(
  "https://www.goldapi.io/api/XAU/USD",
  {
    headers: {
      "x-access-token":"YOUR_API_KEY"
    }
  }
);

const data = await response.json();

console.log(data.price);
```

Response:

```json
{
  "metal":"XAU",
  "currency":"USD",
  "price":2391.72,
  "ch":11.6,
  "chp":0.49
}
```

---

## 📚 Documentation

🌐 Website

https://www.goldapi.io

📖 API Documentation

https://www.goldapi.io/api-documentation

🔓 OpenAPI Specification

https://www.goldapi.io/openapi.json

🤖 AI / LLM Documentation

https://www.goldapi.io/llms.txt

⚡ MCP Documentation

https://www.goldapi.io/blog/goldapi-mcp-server

💰 Pricing

https://www.goldapi.io/

---

# 🔧 Repositories

## 🤖 AI & Integrations

### MCP Server

Official MCP server for Claude, ChatGPT, Cursor and AI agents.

Repository:

https://github.com/goldapi-io/goldapi-mcp-server

Install:

```bash
npm install -g @goldapi/mcp-server
```

---

### Zapier Integration

GoldAPI.io workflow automation integration.

Repository:

https://github.com/goldapi-io/goldapi-zapier

---

### WordPress Widgets

Live Gold and Silver widgets and shortcodes for WordPress.

Repository:

https://github.com/goldapi-io/goldapi-wordpress-widgets

Features:

- Live Gold prices
- Live Silver prices
- Mini charts
- Price widgets
- Calculator embeds

---

# 💻 API Examples & SDKs

### JavaScript

JavaScript example for calling the live price API.

https://github.com/goldapi-io/gold-api-examples-js

---

### Node.js / TypeScript

Node.js and TypeScript example project.

https://github.com/goldapi-io/gold-api-examples-node-js

---

### Python

Python example using standard library HTTP calls.

https://github.com/goldapi-io/gold-api-examples-python

---

### Ruby

Ruby example using net/http and environment variables.

https://github.com/goldapi-io/gold-api-examples-ruby

---

### Go

Go example for live precious metals pricing.

https://github.com/goldapi-io/gold-api-examples-go

---

### .NET Core

.NET Core example project.

https://github.com/goldapi-io/gold-api-examples-net-core

---

### Google Sheets

Google Sheets Apps Script integration example.

https://github.com/goldapi-io/gold-api-examples-google-sheet

---

### Excel

Examples for:

- Office Scripts
- VBA
- Power Query

https://github.com/goldapi-io/gold-api-examples-excel

---

# 🤖 AI Agent Ecosystem

GoldAPI is building tools for AI-powered workflows:

- OpenAPI
- MCP Server
- llms.txt
- ChatGPT Actions
- Claude integrations
- Cursor integrations
- Automation workflows

Example prompts:

```text
What is the current Gold price in AUD?

What is current value of 125 grams of 22k Gold in AED?

What was Gold price on January 1st 2025?

Compare Gold and Silver performance.
```

---

# 🌎 Supported Currencies

AED • AUD • BTC • CAD • CHF • CNY • CZK • EGP • EUR • GBP • HKD • INR • JOD • JPY • KRW • KWD • MXN • MYR • OMR • PLN • RUB • SAR • SGD • THB • USD • ZAR

---

# ❤️ Built by GoldAPI.io

Website:

https://www.goldapi.io

Start building:

https://www.goldapi.io/dashboard
