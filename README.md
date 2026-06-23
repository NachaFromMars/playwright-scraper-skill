# playwright-scraper-skill — Playwright web scraping with anti-bot protection

> Choose the right scraping method for any site — from simple web_fetch to full Playwright stealth mode for Cloudflare-protected pages. Tested on complex sites including Discuss.com.hk.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
playwright-scraper-skill provides browser-based web scraping via Playwright with two script variants: a simple mode for dynamic JavaScript sites and a stealth mode for sites with strong anti-bot protection (Cloudflare, etc.). A use-case matrix helps you choose the right approach for each target. Successfully tested on complex, heavily-protected sites.

## Features
**Use case matrix:**
| Target | Anti-Bot Level | Method |
|---|---|---|
| Regular sites | Low | `web_fetch` (built-in) |
| Dynamic JS sites | Medium | `playwright-simple.js` |
| Cloudflare-protected ⭐ | High | `playwright-stealth.js` |
| YouTube | Special | deep-scraper (install separately) |
| Reddit | Special | reddit-scraper (install separately) |

## Usage / Quick Start
```bash
npm install
npx playwright install chromium

# Simple (medium anti-bot)
node scripts/playwright-simple.js <url>

# Stealth (Cloudflare, high anti-bot)
node scripts/playwright-stealth.js <url>
```

## Trigger Keywords (OpenClaw)
scrape website, Playwright, anti-bot scraping, Cloudflare scrape, dynamic content scrape, web scraping

## Related Skills
- [crawl-for-ai](https://github.com/NachaFromMars/crawl-for-ai) — Crawl4AI JS-rendering alternative
- [mula-browser](https://github.com/NachaFromMars/mula-browser) — AI-first anti-detect browser

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
