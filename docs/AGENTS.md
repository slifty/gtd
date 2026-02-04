# Agent Instructions

This file helps Claude (and other AI assistants) understand this OmniFocus productivity system so they can effectively help with GTD questions, troubleshooting, and system evolution.

## System Overview

This is a **low-friction GTD system** designed for someone who:
- Freelances or contracts for multiple clients (task details live in external systems like GitHub/Jira)
- Has volunteer commitments (boards, organizations, community roles)
- May do bookkeeping for multiple small businesses
- Wants to maintain personal health, family time, and creative projects
- Struggles with system maintenance and habit consistency
- Uses body doubling and context switching to overcome overwhelm

## Core Philosophy

**Read PHILOSOPHY.md for full context.** Key principles:

1. **OmniFocus is the hub, not the source of truth.** Client work details stay in GitHub/Jira/etc. OmniFocus holds next actions and ensures nothing falls through cracks.

2. **Every project is a single-action list.** No sequential projects. Each project is a flat to-do list for that focus area. Tasks are independent and can be done in any order.

3. **Minimal tag system.** Only three categories: Energy (Deep/Low), Context (Computer/Phone/Home/Errands/With Others), Special (5min/Transition/Movement). Default = normal energy, any context.

4. **Movement is integrated, not blocked.** No "exercise 9-10am" blocks. Instead, micro-movements (Movement Snacks) done between tasks.

5. **Quick wins for overwhelm.** When stuck, do ANY small task to build momentum.

## Current Structure

**Read STRUCTURE.md for complete details.**

### Folders
- **Clients** — freelance/contract work
- **Volunteer** — elected/appointed roles, community involvement
- **Personal** — health, home, family, creative projects, hobbies
- **Business** — bookkeeping and company admin

### Key Perspectives
- **Today** — due + flagged + deferred today
- **Quick Wins** — all ⚡ 5min tasks (for overwhelm)
- **Movement Break** — 🏃 Movement and 🔄 Transition tasks
- **Client Focus** / **Volunteer Focus** — folder-filtered views
- **Context Switch** — 🟢 Low energy tasks (when stuck on hard thing)
- **Weekly Review** — all projects, remaining tasks

### Special Project
- **Movement Snacks** — top-level single-action list, always visible, micro-exercises that repeat after completion

## How to Help

### When user asks about adding something new
- New client → Create single-action list in Clients folder, add "Review [Client] backlog" recurring task
- New volunteer role → Create single-action list in Volunteer folder
- New personal area → Usually add to existing project (Health & Body, House & Home, etc.)
- New task → Add to appropriate project, consider tags (energy, context, 5min if quick)

### When user asks about project structure
- Default: Keep it flat (single-action list)
- Only suggest nested projects for distinct, time-bound deliverables with true sequential dependencies
- Remind them: OmniFocus is hub, details live elsewhere

### When user seems overwhelmed
- Point them to WHEN-STUCK.md
- Suggest Quick Wins perspective
- Suggest Movement Break perspective
- Remind them: pick ANY task, momentum builds

### When user asks about reviews
- Daily: See ROUTINES.md — morning planning (10-15 min), shutdown (5 min)
- Weekly: See ROUTINES.md and RECIPES.md — full review checklist (30-45 min)

### When user asks about tags
- Energy: Only tag if notably deep focus OR notably low energy. Default = normal.
- Context: Only tag if task requires specific context. Default = any context.
- Special: ⚡ 5min for quick wins, 🏃 Movement for physical, 🔄 Transition for between-task activities

### When user wants to change the system
- Encourage experimentation, but remind them: simpler is usually better
- Changes should reduce friction, not add it
- If adding complexity, ask: "What problem does this solve?"

## File Structure

```
omnifocus/
├── README.md                  # Navigation hub, entry point
└── docs/
    ├── AGENTS.md              # This file — instructions for AI assistants
    ├── PHILOSOPHY.md          # Core principles and decision rationale
    ├── STRUCTURE.md           # System structure (folders, projects, tags, perspectives)
    ├── RECIPES.md             # Step-by-step procedures for common tasks
    ├── ROUTINES.md            # Daily planning, shutdown, weekly review
    ├── WHEN-STUCK.md          # Overwhelm protocols and recovery strategies
    └── INITIAL-SETUP.md       # One-time setup instructions
```

## Important Context

- Assume user likely has **ADHD** — minimize friction, decision fatigue, and guilt
- System should be **forgiving** — missing a day isn't failure, it's normal
- **Body doubling** helps — doing reviews with someone nearby
- **Context switching** is a tool, not a failure — use it strategically
- The system evolves — what works now may need adjustment later

## Tone Guidelines

When helping with this system:
- Be practical, not preachy
- Acknowledge that productivity systems are hard to maintain
- Don't add guilt about missed reviews or fallen habits
- Offer simple solutions before complex ones
- Remember: the goal is getting things done, not perfecting the system
