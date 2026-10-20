# AsoBeast

**Open source App Store Optimization (ASO) tool and keyword rank tracker for the Apple App Store and Google Play.**

AsoBeast imports an app from its store URL, tracks keyword rankings every day to a depth of 200, watches competitors, reviews and metadata, and turns that history into a prioritized queue of ASO work. Run it on your own server with Docker Compose, or use the hosted service at [asobeast.com](https://asobeast.com). Both run the same code, and the self-hosted edition has every feature.

## What it does

- Tracks keywords per storefront, so one app covers many countries from one listing
- Scores popularity and difficulty with the evidence, calculation version and confidence behind each number
- Finds competitors from live search results and shows the keyword gaps between you
- Syncs reviews and ratings, drafts replies, and records every change to your metadata and your competitors'
- Produces an Action Center of deterministic recommendations, each with a priority, the numbers behind it and a measured outcome
- Sends rank, SERP, metadata, review and action alerts by signed webhook or email
- Serves a Model Context Protocol endpoint with 36 read tools and 5 opt-in write tools, so Claude Code, Cursor, VS Code and other MCP clients can work with your instance

## Where your data goes

Every store request runs on the machine hosting AsoBeast, as an ordinary public search. Your keyword list stays in your database and is never sent to an ASO vendor. Email, webhooks, OpenAI and Apple Ads are outbound integrations that stay off until you configure them.

## Get started

- [Source code](https://github.com/AsoBeast/asobeast)
- [Quickstart](https://docs.asobeast.com/quickstart), Docker Compose to a tracked app in about five minutes
- [Documentation](https://docs.asobeast.com)
- [Releases](https://github.com/AsoBeast/asobeast/releases)
- [Contributing](https://github.com/AsoBeast/asobeast/blob/main/CONTRIBUTING.md)
- [Security policy](https://github.com/AsoBeast/asobeast/blob/main/SECURITY.md)

## License

AsoBeast is licensed under the [GNU AGPL-3.0](https://github.com/AsoBeast/asobeast/blob/main/LICENSE), with no open core and no feature held back from the self-hosted edition.
