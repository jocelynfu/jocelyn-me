# Webflow AI Assistant

*Webflow's first truly agentic product: talk to Webflow, and it designs, edits, and builds your live site.*

## What it is

AI Assistant (AIA) is a conversational agent inside Webflow. You describe what you want in natural language — "redesign this hero section," "add a testimonials page," "clean up these classes" — and the agent makes real changes to a live website. It handles design and build, CMS work, animations, component fixes, and knowledge questions. It's general-purpose by design, built for everyone from first-time builders to enterprise teams.

## How it started

[AI Site Builder](ai-site-builder.md) ended at generation — users got a site, but still had to learn Webflow's controls to take it the last mile. From customer conversations, it was clear the bigger bet was agentic: what if you could just *tell* Webflow what to change?

I recruited two engineers, entered the idea in Webflow's 2025 internal hackathon, and won. That earned the greenlight to build it for real. The prototype was later demoed live by Webflow's CPO in the opening keynote of Webflow Conf 2025, and AIA went into public beta in 2026.

## What building it involved

- **Getting AI to speak Webflow.** We iterated through multiple architectural approaches before landing on one that lets the model understand and edit Webflow sites natively — a pivot that now powers Webflow's agentic products broadly.
- **Evals as a first-class product artifact.** Golden datasets built with professional designers, LLM-judge pipelines with human calibration, per-stage quality measurement, and production feedback loops. On an agentic product, evals are arguably the most important thing a PM owns.
- **Designing for trust.** From 30+ user interviews, one theme dominated: users prioritize safety and transparency over raw capability. People won't collaborate with an agent on work they're afraid to lose. That's why AIA ships with clear edit logs, separate threading for agent vs. human changes, and undo-by-message — one clean revert per AI turn.

## My role

I originated the product vision and led it from 0 to 1 — strategy, architecture decisions, evals, and UX. It's the most hands-on PM work I've ever done: building eval datasets, iterating system prompts, and shipping my own PRs on backlog fixes.

## Why I'm proud of it

AIA kicked off a paradigm shift in how Webflow builds AI — both the technical foundation other teams now build on, and the way the team works day to day (continuous improvement on a live surface, with the model unlocking new capabilities every quarter).
