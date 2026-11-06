# Cory Hepler

I build systems that run without me and tell me when they can't.

By day I work at Hy-Vee in Lee's Summit, where the first thing I automated was the delivery
drivers' tip and route reconciliation that a person used to compile by hand. After hours I
run a political newsroom staffed by AI agents, with me as the only editor.

## The Baseline

[thebaseline.report](https://thebaseline.report) · [source](https://github.com/hepler1394/the-baseline)

A newsroom that reads the wire around the clock, finds what is breaking by counting
independent newsrooms, checks what public figures claim against sources it fetched itself,
and publishes to the site and Instagram behind an evidence gate written in code. 213
published checks citing 1,670 sources, 10,000 leads a month, 748 scheduled runs across 13
workflows, zero anonymous sources. Four agents (Claude, Codex, Hermes, Grok) share the work
through a mailbox the site hosts; every outage it has had is written up with the guarantee
that came out of it.

Next.js 16 · React 19 · Supabase · Vercel · GitHub Actions · Anthropic and Google models with
failover · Playwright for the cards.

## Also

| | |
|---|---|
| [ig-studio](https://github.com/hepler1394/ig-studio) | Renders Instagram cards in a house style and posts them itself; a dropped link becomes a researched, verified carousel |
| [hyvee-delivery-tracker](https://github.com/hepler1394/hyvee-delivery-tracker) | Driver tip and route reconciliation for store 1380 |
| [Cortex](https://github.com/hepler1394/Cortex) | A personal assistant on the desktop, the phone and Telegram |
| [crimetime](https://github.com/hepler1394/crimetime) | A true-crime podcast studio: drafting, voicing, rendering and publishing episodes |

## How I work with AI

The models write most of the code. I write the rules they work to, the gates that decide
what may ship, the tests that hold the line, and the incident reports when something gets
through. Commits are co-authored and say so. The judgment stays with me; the typing is shared.
