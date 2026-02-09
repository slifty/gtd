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
📁 Popcorn        — Small repeating tasks that maintain life systems (body, home)
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
| Self Care | Medical, fitness, wellness, grooming, clothing |
| House & Home | Maintenance, improvements, household |
| Family & Friends | Family activities, friend relationships, social events |
| Finances | Taxes, insurance, investments, estate planning |
| Hobbies | Music practice, crafts, ongoing pursuits |

Example structure:
```
📁 Personal
   📋 Self Care
      ◯ Schedule annual physical [repeat: yearly]
      ◯ Refill prescription
      ◯ Seasonal wardrobe review [repeat: yearly, April]
      ◯ Drop off dry cleaning
      ◯ Schedule haircut
      ◯ Weekly Review [flagged, repeat: weekly]
   📋 House & Home
      ◯ Schedule HVAC maintenance [repeat: yearly, spring]
      ◯ Fix leaky faucet
      ◯ Get quotes for deck repair
   📋 Family & Friends
      ◯ Plan summer vacation [repeat: yearly, March - checklist in notes]
      ◯ Plan Halloween [repeat: yearly, September - checklist in notes]
      ◯ Plan Christmas [repeat: yearly, November - checklist in notes]
      ◯ Book ferry for vacation
      ◯ Schedule family photos
      ◯ Buy birthday gift for friend
   📋 Finances
      ◯ File taxes [repeat: yearly, February - checklist in notes]
      ◯ Review insurance policies [repeat: yearly]
      ◯ Update beneficiaries
   📋 Hobbies
      ◯ Practice guitar (30 min)
      ◯ Order new strings
```

**Key difference from Side Projects:** Personal tasks are ongoing life maintenance. There's no "done" state for Self Care.

### Business

One project per company/entity you do books for.

Example structure:
```
📁 Business
   📋 My Company (Books)
   📋 Partner's Company (Books)
   📋 Side Business (Books)
```

### Popcorn

Small repeating tasks that maintain life systems. These are "XP" — quick wins that accumulate over time.

| Project | Purpose |
|---------|---------|
| Movement | Micro-exercises between tasks |
| Chores | Household maintenance rhythms |

Example structure:
```
📁 Popcorn
   📋 Movement
      ◯ 10 pushups [repeat: defer 4 hours]
      ◯ 20 squats [repeat: defer 4 hours]
      ◯ Walk around the block [repeat: defer 4 hours]
      ◯ 5-minute stretch [repeat: defer 4 hours]
   📋 Chores
      ◯ Do a load of laundry [repeat: defer 3 days]
      ◯ Run dishwasher [repeat: defer 1 day]
      ◯ Take out trash [repeat: weekly]
      ◯ Wipe kitchen counters [repeat: defer 2 days]
```

**Key characteristics:**
- Tasks repeat after completion (defer, not due)
- Always available, never mandatory
- No guilt if skipped — they resurface naturally
- Done in transitions or when noticed

---

## Tags

### Focus Mode

| Tag | When to Use |
|-----|-------------|
| 🤔 Deep Work | Task requires focus, no interruptions |
| 😎 Shallow | Task can be done when tired, scattered, or waiting |
| *(no tag)* | Any mode — default |

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
| 📥 Daily Review | Recurring tasks for checking external systems |

---

## Perspectives

| Perspective | Shows | Use When |
|-------------|-------|----------|
| **Today** | Due Soon + Flagged + Planned today | Morning planning, daily focus |
| **Quick Wins** | All ⚡ 5min tasks | Overwhelmed, need momentum |
| **Popcorn** | Popcorn folder tasks | Between tasks, quick wins, maintenance |
| **Work Focus** | Clients + Business folders | Professional obligations |
| **Volunteer Focus** | Volunteer folder | Community commitments |
| **Side Quests** | Side Projects folder | Passion projects |
| **Personal Focus** | Personal folder | Life maintenance |
| **Context Switch** | 😎 Shallow tasks | Stuck on hard thing, need change |
| **Daily Review** | 📥 Daily Review tasks | Morning routine, check external systems |

---

## Focus Modes

OmniFocus's built-in Focus feature temporarily hides folders app-wide. These are broader than perspectives.

> **Note**: Focus modes are named "Mode" to distinguish from perspectives (e.g., "Work Mode" vs "Work Focus").

| Focus Mode | Shows | Use When |
|------------|-------|----------|
| Work Mode | Clients + Business + Popcorn | During work hours, professional obligations |
| Projects Mode | Volunteer + Side Projects + Popcorn | Dedicated project time (community + passion) |
| Personal Mode | Personal + Popcorn | Personal life maintenance |
| *(unfocused)* | Everything | Weekly reviews |

### Narrowing to a Single Project

The folder-based perspectives (Work Focus, Volunteer Focus, Side Quests, Personal Focus) show all projects in their folders, grouped by project. To temporarily narrow to a **single project**:

1. Select the project in the sidebar
2. **View → Focus on [Project]** (or right-click → Focus)
3. All perspectives now show only that project's tasks
4. **View → Unfocus** when done

This avoids needing separate perspectives for each client or volunteer role.

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
| Popcorn (Movement) | 4 hours after completion | Always — keep movement options available |
| Popcorn (Chores) | Varies (1-7 days) | Always — household maintenance rhythms |

**Key distinction:**
- **Built-in Review** = "Is this project healthy in OmniFocus?"
- **Recurring task** = "Go check an external system for new things"

If a project has no external system (lives only in your head/OmniFocus), it doesn't need a recurring "check backlog" task — the built-in Review is enough.

---

## Quick Reference: Where Does This Go?

| Type of task | Project |
|--------------|---------|
| Wish list item (books, movies, home ideas) | **Not OmniFocus** — use Obsidian (see PHILOSOPHY.md) |
| Client deliverable work | Relevant client project |
| Client admin (invoice, contract) | Client project (or separate admin project) |
| Volunteer duty | Relevant volunteer project |
| Side project work | Relevant side project |
| Personal health task | Self Care |
| Grooming (haircut, etc.) | Self Care |
| Clothing (wardrobe, dry cleaning) | Self Care |
| House repair/maintenance | House & Home |
| Family activity/responsibility | Family & Friends |
| Friend gift or social plan | Family & Friends |
| Holiday/event planning | Family & Friends |
| Personal taxes, insurance, investments | Finances |
| Hobby practice (ongoing) | Hobbies |
| Bookkeeping (business) | Relevant business project |
| Physical exercise | Popcorn → Movement |
| Household chore (laundry, dishes, etc.) | Popcorn → Chores |
| Meeting follow-up | Project related to meeting topic |
