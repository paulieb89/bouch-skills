# BOUCH Skills

Free Claude skills for UK professionals. Drop any of these into Claude Code, Cursor, or any AI agent that supports SKILL.md files.

## MCP-Powered Skills

These 4 skills connect to free MCP servers — real data, not AI imagination. Connect the server, drop in the skill, and go.

### Property Quick Comps
Get comparable sales for any UK postcode. Median price, transaction count, price per sqft.

**Requires:** [Property MCP server](https://property-shared.fly.dev/mcp)
```json
{ "mcpServers": { "property": { "url": "https://property-shared.fly.dev/mcp" } } }
```

### P6 Quick Summary
Load a Primavera P6 XER file and get activity count, status breakdown, completion percentage.

**Requires:** [PyP6Xer MCP server](https://pyp6xer-mcp.fly.dev/mcp)
```json
{ "mcpServers": { "pyp6xer": { "url": "https://pyp6xer-mcp.fly.dev/mcp" } } }
```

### Legislation Lookup
Search UK Acts of Parliament and retrieve specific section text with in-force status.

**Requires:** [UK Legal MCP server](https://uk-legal-mcp.fly.dev/mcp)
```json
{ "mcpServers": { "uk-legal": { "url": "https://uk-legal-mcp.fly.dev/mcp" } } }
```

### Pine Function Lookup
Look up Pine Script v6 functions with correct signatures and usage examples.

**Requires:** [PineScript MCP server](https://pinescript-mcp.fly.dev/mcp)
```json
{ "mcpServers": { "pinescript": { "url": "https://pinescript-mcp.fly.dev/mcp" } } }
```

## Standalone Skills

These 5 skills work with any AI agent — no MCP server needed.

| Skill | What it does |
|-------|-------------|
| **Humaniser** | Strips AI writing patterns from business text. British English. |
| **Meeting Actions** | Turns meeting notes into decisions, actions with owners, and open questions. |
| **Client Prep** | Researches a company before a meeting. Brief in 2 minutes. |
| **Workflow Auditor** | Maps a process, finds the bottleneck, recommends one fix. |
| **AI Policy Generator** | Generates a practical AI acceptable use policy for UK businesses. |

## Installation

Copy the skill directory into your project:

```bash
# Example: add the humaniser skill
cp -r humaniser/ your-project/.claude/skills/
```

Or clone the whole repo:

```bash
git clone https://github.com/paulieb89/bouch-skills.git
```

## Professional Skills

For deeper analysis with full expert workflows, structured reports, and decision frameworks:

- **[Property Report Generator](https://bouch.dev/products/property-report/)** — full investment analysis from one address
- **[Deal Screener](https://bouch.dev/products/deal-screener/)** — BUY/WATCH/PASS decision with underwriting criteria
- **[P6 Health Check](https://bouch.dev/products/p6-health-check/)** — schedule audit with health score and recommendations
- **[Legal Research Brief](https://bouch.dev/products/legal-research/)** — case law, citations, Hansard, plain English summary
- **[Pine Script Strategy Builder](https://bouch.dev/products/pine-strategy-builder/)** — validated v6 strategy from plain English

All professional skills are available at [bouch.dev/products](https://bouch.dev/products/).

## About

Built by [BOUCH](https://bouch.dev) — AI consulting for UK businesses. We build MCP servers, Claude skills, and help teams figure out what actually works with AI.

## Licence

Apache 2.0 — use these however you want.
