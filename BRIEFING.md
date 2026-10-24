# MCP Briefing — One-Pager

**Prepared:** 2026-10-23 · **For:** Monday's partners' meeting · **Scope:** the loudest MCP explainer on YouTube, cross-referenced against Apple, Microsoft and Alphabet

---

## 1. The video: "MCP In 26 Minutes (Model Context Protocol)"

| Fact | Value |
|---|---|
| Video ID | `kOhLoixrJXo` |
| URL | https://www.youtube.com/watch?v=kOhLoixrJXo |
| Published | 2025-10-15 |
| Length | 26m 23s |
| Views | 264,699 (7,114 likes, 223 comments) |
| Channel | Tina Huang (`@tinahuang1`) |
| Channel ID | `UC2UXDak6o7rBm23k3Vv5dww` |
| Subscribers | 1,360,000 (383 videos, ~64.1M total channel views, on YouTube since 2013, US) |

**Presenter.** Tina Huang, ex-Meta data scientist; she has built MCP servers and clients for her team and for B2B clients, and teaches an MCP module in her AI agents bootcamp (Lonely Octopus).

**The three most concrete claims:**

1. **What MCP is.** MCP (Model Context Protocol), created by **Anthropic**, is "an open protocol that standardizes how your LLM applications connect to and work with your tools and data sources" — unpacked with the **USB-plug analogy**: one universal standard instead of the pre-USB mess of bespoke ports, special cords and adapters.
2. **How it works.** An MCP server exposes exactly three primitives — **Tools** (functions the LLM can invoke, e.g. `list_spreadsheets`, `read_sheet`, `write_sheet`, `create_form`), **Resources** (readable data addressed as URIs, e.g. `sheet://{spreadsheet_id}/{range_name}`) and **Prompt Templates** (reusable templates, e.g. `analyze_sheet_data`, `create_report_template`) — plus a defined **communication life cycle** governing how host, client and server talk over a session.
3. **What you can do with it.** You can build and register your own MCP server both **no-code and with code**: the walkthrough builds a Python Google Sheets & Forms MCP server, sets up Google Cloud Console APIs and OAuth, tests it with MCP Inspector, and registers it in Claude Desktop.

**Name-checks of our three holdings.** **Google (Alphabet)** is name-checked — the entire companion demo is a Google Sheets & Forms MCP server built on Google Cloud Console with the Sheets, Forms and Drive APIs. **Apple and Microsoft are not name-checked**; the tools actually featured are Claude Desktop, MCP Inspector, n8n and the OpenAI Agents SDK.

---

## 2. The three mega-caps

### Apple (AAPL)
- **Sector:** Technology (Consumer Electronics)
- **HQ:** Cupertino, California
- **Latest dividend:** $0.27/share, paid 2026-08-10 (annualized rate $1.08, ~0.31% yield)
- **Splits on record:** 2:1 (1987-06-16), 2:1 (2000-06-21), 2:1 (2005-02-28), 7:1 (2014-06-09), 4:1 (2020-08-31)

### Microsoft (MSFT)
- **Sector:** Technology (Software – Infrastructure)
- **HQ:** Redmond, Washington
- **Latest dividend:** $0.91/share, paid 2026-08-20 (annualized rate $3.92, ~0.75% yield)
- **Splits on record:** nine splits 1987–2003 — 2:1 (1987), 2:1 (1990), 3:2 (1991), 3:2 (1992), 2:1 (1994), 2:1 (1996), 2:1 (1998), 2:1 (1999), 2:1 (2003-02-18); none in the two decades since

### Alphabet (GOOGL)
- **Sector:** Communication Services (Internet Content & Information)
- **HQ:** Mountain View, California
- **Latest dividend:** $0.22/share, paid 2026-09-04 (annualized rate $0.88, ~0.27% yield)
- **Splits on record:** ~2:1 (2014-04-03) and 20:1 (2022-07-18)

---

## 3. Kept news headlines

**None could be kept — no candidates existed.** The Yahoo Finance news feed returned zero headlines for AAPL, MSFT and GOOGL on the research date, verified across repeated retries and against control tickers (GOOG, TSLA): the news source itself was empty, rather than these names lacking coverage. Because there were no candidate headlines, the "keep the two most relevant to AI / agent infrastructure / platform strategy" filter had nothing to operate on, and **no headlines are asserted here**. **Recommendation:** re-pull Yahoo Finance news before the meeting and slot the two keepers per company into this section.

---

## 4. Takeaway

MCP has crossed from developer niche to mainstream awareness — a 26-minute protocol explainer from a 1.36M-subscriber practitioner channel has racked up ~265k views in a year — and the only one of our three mega-caps name-checked in that explainer is Alphabet, whose Google Cloud and Google Workspace tooling appears directly as the demo surface. Against that backdrop the valuation dispersion is striking: Alphabet trades at 16.07x trailing earnings versus Apple's 39.88x, with Microsoft between them at 29.22x — so the cheapest name in the book is the one with the most direct, named exposure to the trend clients are asking about.

---

## Data-quality notes (audit trail)

- **YouTube API quota.** The YouTube Data API quota for this project was exhausted on the research date — the search, video-details and channel-details endpoints all returned quota errors. The video and channel facts above were therefore cross-verified across multiple independent public indexes of the same video; the view and subscriber figures come from an API-sourced catalog of the same video and channel (a separate source recorded 1.04M+ subscribers as a November 2025 milestone, consistent with growth to 1.36M).
- **Transcript.** The transcript service returned no captions for video `kOhLoixrJXo`, so the presenter's claims and the company name-checks were grounded in an independent transcript digest of the same video.
- **News.** See §3 — Yahoo Finance news returned no headlines for any ticker tested.
- **Prices / valuations quoted.** Yahoo Finance quote and profile data on the research date: AAPL $347.73 close, trailing P/E 39.88x; MSFT $524.51 close, trailing P/E 29.22x (forward 22.13x); GOOGL $320.21 close, trailing P/E 16.07x.
- **Corporate actions.** Dividend and split history from Yahoo Finance corporate-actions data; split factors and most-recent-split dates cross-checked against each company's profile field.
