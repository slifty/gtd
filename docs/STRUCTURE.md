# System Structure

The current structure of your OmniFocus setup. Reference this when you need to remember what exists.

---

## Folders

```
📁 Clients        — Paid freelance/contract work
📁 Volunteer      — Elected/appointed roles, community involvement
📁 Side Projects  — Unpaid projects with real scope (software, creative, open source)
📁 Personal       — Life maintenance (health, home, family, hobbies)
📁 Business       — Bookkeeping and company admin
```

---

## Projects

All projects are **single-action lists** (tasks available simultaneously, not sequential).

### Clients

One project per client engagement. If you have sub-projects for a single client (e.g., multiple workstreams), keep them as separate projects — the relationship is clear from naming.

Example structure:
```
📁 Clients
   📋 Client A
   📋 Client B
   📋 Client C (Admin)      — if client has separate admin needs
   📋 Client C (Project X)  — workstream for same client
```

### Volunteer

One project per role or organization.

Example structure:
```
📁 Volunteer
   📋 Board Role
   📋 Community Organization
   📋 Committee Work
```

### Side Projects

Unpaid projects that have real scope — software, creative work, open source, passion projects. These are treated like clients: one project per effort, with backlog reviews and milestones.

Example structure:
```
📁 Side Projects
   📋 TV Kitchen
      ◯ Review TV Kitchen backlog [repeat: weekly]
      ◯ Implement pipeline caching
      ◯ Write README documentation
   📋 Personal Website
      ◯ Review website backlog [repeat: weekly]
      ◯ Add blog section
      ◯ Fix mobile nav
   📋 Open Source Contrib
      ◯ Review open PRs I've submitted
```

**Key difference from Personal:** Side projects have deliverables and could be "done." Personal is ongoing life maintenance.

### Personal

Life maintenance organized by area. Recurring life events (annual trips, holidays) live as recurring tasks with checklists in the notes — not as separate projects.

| Project | Purpose |
|---------|---------|
| Health & Body | Medical, fitness, wellness |
| House & Home | Maintenance, improvements, household |
| Family | Family activities, responsibilities |
| Hobbies | Music practice, crafts, ongoing pursuits |

Example structure:
```
📁 Personal
   📋 Health & Body
      ◯ Schedule annual physical [repeat: yearly]
      ◯ Refill prescription
      ◯ Weekly Review [flagged, repeat: weekly]
   📋 House & Home
      ◯ Schedule HVAC maintenance [repeat: yearly, spring]
      ◯ Fix leaky faucet
      ◯ Get quotes for deck repair
   📋 Family
      ◯ Plan summer vacation [repeat: yearly, March - checklist in notes]
      ◯ Book ferry for vacation
      ◯ Schedule family photos
      ◯ Plan kid's birthday party
   📋 Hobbies
      ◯ Practice guitar (30 min)
      ◯ Order new strings
```

**Key difference from Side Projects:** Personal tasks are ongoing life maintenance. There's no "done" state for Health & Body.

### Business

One project per company/entity you do books for.

Example structure:
```
📁 Business
   📋 My Company (Books)
   📋 Partner's Company (Books)
   📋 Side Business (Books)
```

### Top-Level

| Project | Purpose |
|---------|---------|
| Movement Snacks | Micro-exercises, always visible |

---

## Tags

### Energy

| Tag | When to Use |
|-----|-------------|
| 🔴 Deep | Task requires focus, no interruptions |
| 🟢 Low | Task can be done when tired, scattered, or waiting |
| *(no tag)* | Normal energy — default |

### Context

| Tag | When to Use |
|-----|-------------|
| 💻 Computer | Must have laptop/desktop |
| 📱 Phone | Can do from phone only |
| 🏠 Home | Must be physically at home |
| 🚗 Errands | Out running errands |
| 👥 With Others | Requires another person present |
| *(no tag)* | Any context — default |

### Special

| Tag | When to Use |
|-----|-------------|
| ⚡ 5min | Quick win, good for overwhelm moments |
| 🔄 Transition | Good for between work blocks |
| 🏃 Movement | Physical activity, exercise |

---

## Perspectives

| Perspective | Shows | Use When |
|-------------|-------|----------|
| **Today** | Due + Flagged + Deferred today | Morning planning, throughout day |
| **Quick Wins** | All ⚡ 5min tasks | Overwhelmed, need momentum |
| **Movement Break** | 🏃 Movement + 🔄 Transition tasks | Between tasks, need to move |
| **Client Focus** | Clients folder only | Dedicated client work time |
| **Volunteer Focus** | Volunteer folder only | Evening/weekend volunteer time |
| **Context Switch** | 🟢 Low energy tasks | Stuck on hard thing, need change |
| **Weekly Review** | All projects, remaining tasks | Weekly system maintenance |

---

## Focus Modes

| Focus | Shows | Use When |
|-------|-------|----------|
| Work | Clients + Side Projects + Movement Snacks | During work hours, building things |
| Life | Volunteer + Personal + Business + Movement Snacks | Evenings, weekends, life maintenance |
| *(unfocused)* | Everything | Weekly reviews |

---

## Project Review Intervals

Use OmniFocus's built-in Review feature for project health checks. Set review intervals on each project:

| Project Type | Review Interval | Purpose |
|--------------|-----------------|---------|
| Clients | Weekly | Active engagement, needs frequent attention |
| Volunteer | Biweekly | Community commitments |
| Side Projects (active) | Monthly | Passion projects, less urgency |
| Side Projects (dormant) | 3 months | Keep on radar without clutter |
| Personal | Monthly | Life maintenance |
| Business | Monthly | Bookkeeping cycles |

**What to ask during Review:**
- Does this project have a clear next action?
- Is this project still relevant?
- Should the review interval change?

---

## Recurring Tasks

Recurring tasks are for **syncing with external systems**, not project health (that's what Review is for).

| Task Type | Frequency | When Needed |
|-----------|-----------|-------------|
| Check [Client] backlog | Weekly (Monday) | Clients with GitHub/Jira — pull in new work |
| Check [Side Project] backlog | Weekly or biweekly | Side projects with GitHub — pull in new issues |
| Weekly Review | Weekly (Sunday) | Always — system maintenance |
| Movement Snacks | 4 hours after completion | Always — keep movement options available |

**Key distinction:**
- **Built-in Review** = "Is this project healthy in OmniFocus?"
- **Recurring task** = "Go check an external system for new things"

If a project has no external system (lives only in your head/OmniFocus), it doesn't need a recurring "check backlog" task — the built-in Review is enough.

---

## Quick Reference: Where Does This Go?

| Type of task | Project |
|--------------|---------|
| Client deliverable work | Relevant client project |
| Client admin (invoice, contract) | Client project (or separate admin project) |
| Volunteer duty | Relevant volunteer project |
| Side project work | Relevant side project |
| Personal health task | Health & Body |
| House repair/maintenance | House & Home |
| Family activity/responsibility | Family |
| Hobby practice (ongoing) | Hobbies |
| Bookkeeping | Relevant business project |
| Physical exercise | Movement Snacks |
| Meeting follow-up | Project related to meeting topic |
