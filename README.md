# Daniel Kang

Workflow automation and AI implementation. Toronto, ON.

I find the manual steps in how a team works and replace them with n8n workflows and API integrations.

I'm not a software developer. The code in these repos was written by AI coding tools (Claude Code) under my direction, I set the requirements, review each plan and test the result. The n8n builds, the server setup and the client work I do by hand. Each repo has it's own README that says which was which.

## What's here

- [podcast-to-blog-newsletter-n8n](https://github.com/danielkang-dev/podcast-to-blog-newsletter-n8n) — turns each new podcast episode into a blog draft and a newsletter draft. Live for FiveCardGuys since July 2026.
- [sp500-put-screener](https://github.com/danielkang-dev/sp500-put-screener) — screens about 500 stocks every weekday morning and posts a ranked shortlist to Discord. Live for a private client since August 2026.
- [lead-to-crm-n8n-hubspot](https://github.com/danielkang-dev/lead-to-crm-n8n-hubspot) — sends website enquiries to HubSpot without creating duplicates. Built for Rise Above Finance, tested end to end on a test instance.
- [audio-cleanup-automation](https://github.com/danielkang-dev/audio-cleanup-automation) — cleans up and tags an MP3 library, and lets Claude Code run the whole thing as a tool.

The three client repos are showcase copies (credentials, IDs and client details are removed, so they won't run as is). The working versions are private. I can walk through them on a call.

## How I build

- One record per item — nothing gets processed twice
- Fail closed — if the output doesn't check out the run stops (nothing half-finished goes to the client)
- Alerts — every failure posts to Discord with the step that broke
- Tests before trust — AI-written code gets automated tests and a forced-failure test before it goes live

## Tools

n8n (cloud and self-hosted), APIs and webhooks, MCP, Claude API, Claude Code, HubSpot, Google Workspace, Docker, DigitalOcean, Netlify.

## Get in touch

If your team has a process that eats hours every week, email me at hello@askdanielkang.com or message me on [LinkedIn](https://linkedin.com/in/danieladamkang).
