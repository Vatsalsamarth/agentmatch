# AgentMatch (Cupid Agents)

> Autonomous AI dating simulator where agents representing real founders and creators converse, evaluate multi-dimensional compatibility, and rank mutual matches.

**Live Deployment:** https://agentmatch-one.vercel.app  
**Demo Video:** https://youtu.be/61v6sPL6qm0

---

## Overview
AgentMatch models relationship matchmaking as an agentic interaction. Instead of traditional static swipe mechanics, real public profiles are synthesized into autonomous conversational personas. These agents participate in structured multi-turn speed dates to test alignment across personal values, work rhythms, and lifestyle habits before producing compatibility scores.

---

## Features
- **Profile Persona Synthesis:** Synthesizes 25 public profiles with extracted non-negotiable needs, active hobbies, and core personality qualities.
- **5-Round Autonomous Dating Harness:** Simulates multi-turn conversations testing rhythm, creative passions, dealbreakers, weekend routines, and mutual verdicts.
- **Compatibility Matrix & Rankings:** Computes pairwise alignment scores and ranks matches across the entire network.
- **Transcript Inspection:** Deep-link navigation allows reviewing the exact dialogue that generated any compatibility score.

---

## Architecture & Tech Stack
- **Frontend:** Responsive SPA built with HTML5, modern CSS, and vanilla JavaScript.
- **Hosting & Deployment:** Vercel edge deployment.
- **Data Extraction & Pipeline:** Headless scraping pipeline utilizing Playwright and Apify actors with rotating proxy handling; LLM extraction via GPT-4o-mini structured outputs.
- **Simulation Harness:** State-tracked conversational rounds with structured verdict parsing.
