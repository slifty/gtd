# Philosophy

The principles behind this system. Read this when you're questioning a decision or wondering "why did I set it up this way?"

---

## Core Principle: OmniFocus is the Hub, Not the Source of Truth

Your task details live in external systems:
- **Client work** → GitHub issues, Jira tickets, project management tools
- **Volunteer work** → Email threads, shared documents, meeting notes
- **Business admin** → Accounting software, bank statements, tax documents

OmniFocus holds **next actions** — the things you need to do to move work forward. It doesn't duplicate information; it surfaces what matters now.

### What this means in practice

**Don't copy issue descriptions into OmniFocus.** Instead:
```
✗ "Fix bug where user authentication fails when password contains special characters (see GH #142)"
✓ "Fix auth bug (GH #142)"
```

**Don't track project progress in OmniFocus.** That's what GitHub/Jira is for. OmniFocus tracks *your* next actions.

**Do use OmniFocus to ensure nothing falls through cracks.** Recurring "Review [Client] backlog" tasks pull you back to external systems regularly.

---

## Core Principle: Every Project is a To-Do List

In traditional GTD, a "project" is any outcome requiring multiple steps. That creates complexity: Should "write documentation" be a project with sub-tasks, or a single task?

**In this system, we simplify: every OmniFocus project is a single-action list.**

This means:
- All tasks in a project are available simultaneously
- You pick tasks based on energy, context, and priority — not forced order
- No decision fatigue about where to put things

### When you might break this rule

If you have a **distinct, time-bound deliverable with true sequential dependencies** — like a security audit where you must run scans before documenting findings before presenting to client — you could create a nested sequential project.

But start simple. You probably don't need it.

---

## Core Principle: Minimal Tags

Tags should reduce friction, not create it. Every tag is a decision: "Should I tag this?" More tags = more decisions = more friction.

### The tag system

**Energy (optional):**
- 🔴 Deep — requires focus, no interruptions
- 🟢 Low — can do when tired or scattered
- *No tag = normal energy*

**Context (optional):**
- 💻 Computer, 📱 Phone, 🏠 Home, 🚗 Errands, 👥 With Others
- *No tag = any context*

**Special (use intentionally):**
- ⚡ 5min — quick wins for overwhelm moments
- 🔄 Transition — tasks for between work blocks
- 🏃 Movement — physical micro-tasks

### How to decide

**Default to no tags.** Only add a tag if:
- The task is notably high or low energy (not normal)
- The task requires a specific context you're not always in
- The task is a quick win you want available for overwhelm moments

---

## Core Principle: Movement is Integrated, Not Blocked

Traditional advice: "Block 9-10am for exercise."

Reality for ADHD: That block gets skipped when something urgent comes up. Then guilt. Then the whole system feels broken.

**This system integrates movement into transitions:**
- Movement Snacks: micro-exercises (10 pushups, walk around block, stretch)
- Always available, never mandatory
- Done between tasks, during transitions
- No guilt if skipped — they're always there

### Why this works

- Lower activation energy (2 minutes vs 60 minutes)
- Fits into natural breaks
- Accumulates over the day
- No "failed workout" feeling

---

## Core Principle: Quick Wins Build Momentum

When overwhelmed, the hardest part is starting. The task itself doesn't matter — what matters is **doing something**.

**The Quick Wins perspective exists for this moment:**
1. Open it
2. Pick literally anything
3. Do it
4. Notice: you're moving now

The ⚡ 5min tag isn't about time management. It's about having a list of "easy starts" for when your brain is stuck.

---

## Core Principle: Context Switching is a Tool

Traditional productivity advice: "Don't context switch! Deep work! Focus!"

Reality for ADHD: Sometimes you're stuck. Banging your head against a task makes it worse.

**This system treats context switching as a legitimate strategy:**
- Context Switch perspective: low-energy tasks from different areas
- When stuck on hard thing → do easy thing in different domain → return refreshed

This isn't procrastination. It's strategic disengagement that keeps you productive.

---

## Core Principle: The System Must Be Forgiving

If missing one weekly review breaks everything, the system is too fragile.

**This system assumes you'll fall off sometimes:**
- Inbox will pile up — that's what weekly review is for
- You'll skip movement snacks — they repeat, they'll be back
- You'll miss a client backlog review — you'll catch it next week
- You'll have bad days — Quick Wins perspective is waiting

The goal isn't perfection. The goal is **easy recovery**.

---

## Core Principle: Simpler is Better

When in doubt, don't add it. Every folder, project, tag, and perspective is something to maintain.

**Before adding complexity, ask:**
- What problem does this solve?
- Can I solve it without adding structure?
- Will future-me remember why this exists?

**Signs you need simplification:**
- You avoid parts of the system
- You don't remember what a tag/perspective is for
- Maintenance feels like a chore
- You're spending more time organizing than doing

---

## What Doesn't Belong in OmniFocus

OmniFocus is for **actions you're committed to**. Some things look like tasks but aren't — they're wishes, ideas, or reference lists. Putting them in OmniFocus creates noise and guilt.

### Someday/Maybe Lists

These are things you might want to do but aren't committed to yet:
- Home improvement ideas ("Redo master bathroom")
- Books to read
- Movies and TV shows to watch
- Places to visit
- Things to learn
- Restaurants to try
- Gift ideas for people
- Project ideas for someday

**Why they don't belong in OmniFocus:**
- No clear next action (yet)
- Create guilt during reviews ("Why haven't I done this?")
- Blur the line between commitment and fantasy
- Add noise to your action system

### Where to Put Them Instead

**Obsidian** (or any notes app) works well for wish lists:
- Create simple markdown files by category
- `Books to Read.md`, `Home Improvement Ideas.md`, `Movies to Watch.md`
- Review them when relevant (bored on a Friday, have renovation budget, at the bookstore)
- No task management overhead

**Dedicated apps** for media if you want social features:
- Goodreads for books
- Letterboxd for movies
- These offer recommendations, ratings, and tracking

**The key distinction:** These are *reference lists*, not *action lists*. You browse them when the context is right, not during task reviews.

### The Workflow

When you decide to actually pursue something from a wish list:

1. **In Obsidian**: Mark it or move it to indicate "pursuing this now"
2. **In OmniFocus**: Create an actionable task
   - Not: "Redo master bathroom" (wish)
   - But: "Get quotes for bathroom renovation" (action)

The wish list is where ideas wait. OmniFocus is where commitments live.

---

## Why These Specific Choices?

### Why folders for life areas?
Folders provide top-level organization without affecting task availability. They enable Focus modes (show only Clients during work time) and folder-based perspectives.

### Why single-action lists instead of sequential projects?
Most knowledge work tasks are independent. "Write documentation" doesn't block "Fix bug #42." Single-action lists let you pick based on current context and energy.

### Why Movement Snacks as a top-level project?
So it's always visible, in every Focus mode. Movement should be an option regardless of what you're working on.

### Why separate creative projects from business bookkeeping?
Different mental modes. Creative work and bookkeeping don't belong in the same list. You won't accidentally see "reconcile Q4 expenses" when you're trying to brainstorm project ideas. If you do creative work for an entity you also do books for, keep them in separate projects (one in Personal/Creative, one in Business).

### Why recurring "Review [Client] backlog" tasks?
They pull you back to external systems (GitHub, Jira) on a schedule. Without them, it's easy to forget to check, and tasks fall through cracks.
