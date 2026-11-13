# Hi, I'm Eric

**Applied AI and full-stack engineer. Founder and operator.**

I build AI products end to end: real-time voice agents, RAG systems with human-in-the-loop workflows, agent tooling, and the infrastructure that keeps them running. zencub-rag serves live search for ZenCub, hap-voice answers a real business phone line, and studio-sentinel has watched my automation server in production since August 2026. groundquote is a public demo of evidence-first document Q&A, and the rest are tools I built for my own work.

## Featured projects

**[zencub-rag](https://github.com/eatusc/zencub-rag)** ([live site](https://search.zencub.com)) - LangGraph RAG over a jiu-jitsu video library: hybrid retrieval with citations back to the exact clips, persistent checkpointed workflows with human approval and recovery, and a committed eval suite. Next.js, Supabase/pgvector, strict TypeScript with zero `any`.

**[hap-voice](https://github.com/eatusc-personal/hap-voice)** - Self-hosted AI receptionist answering the HelpAProduct business line over Twilio Media Streams. Hand-written G.711 codec, energy VAD, and barge-in handling (caller speech aborts in-flight LLM and TTS mid-sentence), with local whisper.cpp STT. Six production dependencies total.

**[hap-testing](https://github.com/eatusc-personal/hap-testing-public)** - Agent-to-agent testing control plane: maps which kinds of testing apply to a codebase, has one agent prove each bug with a failing test and another fix it in an isolated worktree, and counts a fix only when a database trigger can verify it.

**[studio-sentinel](https://github.com/eatusc-personal/studio-sentinel-public)** - Off-box dead-man's switch for a Mac automation server: signed heartbeats to Cloud Run, Slack alerting with a monitored backstop, BigQuery run history with an MCP server, all in Terraform with keyless GitHub Actions deploys.

**[build-loop](https://github.com/eatusc-personal/build-loop)** - Runs Claude Code unattended through a list of build steps, each in its own git worktree. A step only lands when the repo's own test gate passes and every changed file is inside the paths the step declared; what the agent says it did is never used as evidence. Retries are bounded, and a person reviews the branch before anything merges.

**[groundquote](https://github.com/eatusc-personal/groundquote)** ([live demo](https://groundquote.vercel.app)) - Evidence-first RAG document Q&A: short answers tied to the exact source passages, and a clear refusal when the document does not contain enough evidence. Includes an interactive Learn RAG guide.

**[no-slop](https://github.com/eatusc-personal/no-slop)** - Local-first AI writing detector and cleanup engine. One rule engine ported in parity across JavaScript and Python (Django/DRF), exposed as a web app, REST API, CLI, and MCP server.

**[trading-bb](https://github.com/eatusc-personal/trading-bb)** - Market-research dashboard with a peer-divergence scanner built on leave-one-out robust z-scores (median/MAD) and correlation gating. Next.js and FastAPI, with per-provider budget guards that keep each market-data provider inside its quota.

Also on the shelf: a [Manifest V3 Chrome extension](https://github.com/eatusc-personal/marketplace-helper-public) for marketplace listing management.

## Stack

TypeScript, Python, Next.js/React, FastAPI, Django, Postgres (pgvector), Supabase, LangGraph, whisper.cpp, Twilio, Google Cloud (Cloud Run, BigQuery), Terraform.

