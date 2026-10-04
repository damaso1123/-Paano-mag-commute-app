# CLAUDE.md

Guidance for Claude (and any other contributor) working in this repository.

## What this project is

**Paano Mag Commute** ("How to Commute") is an app that helps people get around
the Philippines by public transport. Given where you are and where you want to
go, it should explain the route in plain terms: which rides to take (jeepney,
bus, UV Express, tricycle, MRT/LRT, ferry, etc.), where to board and get off,
where to transfer, and roughly how much it costs.

## Current state

- The repository is brand new: only a README and this file.
- No tech stack has been chosen yet. Do not assume a framework, language, or
  build tool. When a choice is needed, propose options with trade-offs and let
  the owner decide.
- When the stack is chosen, update this file with build, run, and test
  commands.

## About the owner

The owner (Raphael, GitHub `damaso1123`) is a DIY developer and game dev in the
Philippines who likes building things themselves and understanding exactly how
they work. They want to be able to explain the code to others.

## How to work here

- **Prefer simple over clever.** Choose the most straightforward solution that
  works. Avoid heavy frameworks or abstractions unless they clearly pay off.
- **Explain the why.** When adding code, explain the logic behind it in the PR
  or chat, especially algorithms (e.g. route finding, graph search). Teaching is
  part of the job.
- **Keep dependencies few and well known.** Every new dependency should be
  justified in one sentence.
- **Small, readable changes.** One idea per change, clear names, short
  functions. Comments where the logic is not obvious, not on every line.
- **Self-hosting friendly.** The owner runs home servers, so favor designs that
  can run locally or on a small self-hosted machine.
- **Local context matters.** Use Philippine place names, fares in PHP (₱), and
  commuting terms locals actually use. Filipino/Taglish UI text is welcome.
