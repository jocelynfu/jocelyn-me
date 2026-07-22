# Webflow AI Site Builder

*Webflow's first end-to-end AI product: describe what you want, and AI builds you a site.*

## What it is

AI Site Builder (AISB) solves the "blank start" problem. Instead of staring at an empty canvas or picking through templates, you type a quick description of your business or project, and a multi-step generative AI pipeline builds a full site — structure, layout, copy, colors — ready to customize and publish.

## My role

I proposed AISB and led it from 0 to 1. This wasn't in my original job scope — I pitched taking it on when I joined, and shaped the product from first concept through launch and iteration. I personally iterated on the agentic logic and ran hands-on LLM evals to improve output quality.

## The design philosophy

The hardest call was in 2024, when models were still unreliable at aesthetics — color, imagery, visual polish. The tempting move was to let the model generate everything freely. My call was the opposite: for non-technical users, an unreliable bespoke output is worse than a constrained polished one. So we built the app layer to handle what the model couldn't (aesthetics, color, layout systems) and let the model do what it was genuinely great at (structure and copy).

That architecture — a curated section library with AI-driven retrieval, pre-built style systems, and a multi-stage LLM pipeline with user approval at each step — is what made the output consistently good enough to trust.

## Results

- **$5M+ ARR** in under a year
- **10%+ lift** in site conversion
- Within 6 months of launch, **30%+ of all Webflow site creation** started with AI
- Became a leading growth driver for self-serve Webflow users in 2025

## The lesson

AI product constraints have a half-life. The guardrails that made AISB work in 2024 became unnecessary as models improved — which is exactly what led to the next project, [AI Assistant](ai-assistant.md).
