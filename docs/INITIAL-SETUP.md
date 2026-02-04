# Initial Setup

One-time setup instructions for your productivity system.

**Note:** This is reference for initial setup or rebuilding. For ongoing use, see the other guides in this directory.

**Time estimate**: 45-60 minutes for initial setup

---

## Table of Contents

1. [Create Folders](#1-create-folders)
2. [Create Projects](#2-create-projects)
3. [Create Tags](#3-create-tags)
4. [Create Perspectives](#4-create-perspectives)
5. [Add Initial Tasks](#5-add-initial-tasks)
6. [Set Project Review Intervals](#6-set-project-review-intervals)
7. [Set Up Repeating Tasks](#7-set-up-repeating-tasks)
8. [Configure Focus Modes](#8-configure-focus-modes-optional)
9. [Calendar Setup](#9-calendar-setup)
10. [Verification Checklist](#10-verification-checklist)

---

## 1. Create Folders

Folders organize your projects into life areas. Create five top-level folders.

### Steps

1. In OmniFocus sidebar, right-click and select **New Folder** (or press ⌥⌘N)
2. Create these folders:
   - `Clients`
   - `Side Projects`
   - `Volunteer`
   - `Personal`
   - `Business`

### Result

Your sidebar should show:

```
📁 Clients
📁 Side Projects
📁 Volunteer
📁 Personal
📁 Business
📥 Inbox
```

---

## 2. Create Projects

Projects live inside folders. You'll also create one special top-level project.

### Client Projects

1. Select the **Clients** folder
2. Press ⌘N to create a new project
3. Create one project per client/engagement
4. **For each client project**, set it as a single-action list:
   - Select the project
   - Open Inspector (⌥⌘I)
   - Change **Project Type** to **Single Actions**

**Naming guidance:**
- Simple: `Client Name`
- If multiple workstreams for same client: `Client Name (Project X)`, `Client Name (Admin)`

### Side Projects

1. Select the **Side Projects** folder
2. Create one project per side project (software, creative work, open source, etc.)
3. **For each side project**, set it as a single-action list:
   - Select the project
   - Open Inspector (⌥⌘I)
   - Change **Project Type** to **Single Actions**

**Note:** Side projects are treated like clients — they have real scope, deliverables, and backlogs. The difference is you're not getting paid.

### Volunteer Projects

1. Select the **Volunteer** folder
2. Create one project per role/organization
3. **For each volunteer project**, set it as a single-action list:
   - Select the project
   - Open Inspector (⌥⌘I)
   - Change **Project Type** to **Single Actions**

### Personal Projects

1. Select the **Personal** folder
2. Create these projects:
   - `Self Care`
   - `House & Home`
   - `Family`
   - `Finances`
   - `Hobbies` (or specific hobby name)
3. **For each personal project**, set it as a single-action list:
   - Select the project
   - Open Inspector (⌥⌘I)
   - Change **Project Type** to **Single Actions**

**Note:** Personal is for ongoing life maintenance. Scoped projects with deliverables go in Side Projects.

### Business Projects

1. Select the **Business** folder
2. Create one project per company/entity you do books for
3. **For each business project**, set it as a single-action list:
   - Select the project
   - Open Inspector (⌥⌘I)
   - Change **Project Type** to **Single Actions**

**Naming guidance:** `Company Name (Books)` to distinguish from creative/project work

### Popcorn Folder

This folder contains small repeating tasks that maintain life systems — "XP" that accumulates.

1. Create the **Popcorn** folder (right-click sidebar → New Folder, or ⌥⌘N)

2. Inside Popcorn, create the **Movement** project:
   - Select the Popcorn folder
   - Press ⌘N to create a new project
   - Name it `Movement`
   - Open Inspector (⌥⌘I) and set **Project Type** to **Single Actions**

3. Inside Popcorn, create the **Chores** project:
   - Select the Popcorn folder
   - Press ⌘N to create a new project
   - Name it `Chores`
   - Open Inspector (⌥⌘I) and set **Project Type** to **Single Actions**

### Result

All projects should be **single-action lists** (not sequential):

```
📁 Clients
   📋 [Your clients] ⟲
📁 Side Projects
   📋 [Your side projects] ⟲
📁 Volunteer
   📋 [Your volunteer roles] ⟲
📁 Personal
   📋 Self Care ⟲
   📋 House & Home ⟲
   📋 Family ⟲
   📋 Finances ⟲
   📋 Hobbies ⟲
📁 Business
   📋 [Your business entities] ⟲
📁 Popcorn
   📋 Movement ⟲
   📋 Chores ⟲
📥 Inbox
```

(⟲ indicates single-action list — in OmniFocus this appears as a circular arrow icon)

---

## Why Single-Action Lists for Everything?

You'll notice every project is a **single-action list**, not a sequential project. Here's why:

### The Philosophy

OmniFocus is your **hub, not your source of truth**. Client work details live in GitHub/Jira. Volunteer commitments have their own systems. Your job in OmniFocus is to maintain a simple list of *next actions* for each area of focus.

### How It Works

- **Single-action list**: All tasks are available simultaneously. Pick any task, do it, check it off.
- **Sequential project**: Tasks are done in order. Only the first incomplete task is "available."

For most knowledge work, tasks aren't truly sequential. "Write documentation" doesn't block "Fix bug #42"—they're independent actions you choose between based on energy, context, and priority.

### The Workflow

1. **Weekly review**: Check external systems (GitHub, email, meeting notes)
2. **Create tasks**: Add next actions to the relevant single-action list
3. **During the day**: Pick tasks based on context, energy, and due dates
4. **Complete**: Check off tasks as you go

### When You Might Add a Sequential Project Later

If you have a **distinct, time-bound deliverable with true dependencies**, you could create a nested sequential project:

```
📁 Clients
   📋 Client A (Single-Action List) — ongoing work
   📋 Client A: Security Audit — sequential, deadline-driven
      ◯ Run vulnerability scan
      ◯ Document findings
      ◯ Present to client
```

But start simple. You can always add structure later if you need it.

---

## 3. Create Tags

Tags add context to tasks. You'll create a minimal set organized into three categories.

### Access Tag Management

1. Go to **Perspectives** menu > **Tags** (or press ⌘5)
2. You'll see your tag list in the sidebar

### Create Parent Tags

First, create the three category tags:

1. Click **New Tag** button (or press ⌘N)
2. Create: `Energy`
3. Create: `Context`
4. Create: `Special`

### Create Energy Tags (nested under Energy)

1. Select the **Energy** tag
2. Press ⌘N to create a child tag
3. Create:
   - `🔴 Deep` — for tasks requiring focus, no interruptions
   - `🟢 Low` — for tasks you can do when tired or scattered

### Create Context Tags (nested under Context)

1. Select the **Context** tag
2. Create these child tags:
   - `💻 Computer`
   - `📱 Phone`
   - `🏠 Home`
   - `🚗 Errands`
   - `👥 With Others`

### Create Special Tags (nested under Special)

1. Select the **Special** tag
2. Create these child tags:
   - `⚡ 5min` — quick wins for overwhelm moments
   - `🔄 Transition` — tasks for between work blocks
   - `🏃 Movement` — physical/exercise micro-tasks

### Result

```
🏷️ Energy
   🔴 Deep
   🟢 Low
🏷️ Context
   💻 Computer
   📱 Phone
   🏠 Home
   🚗 Errands
   👥 With Others
🏷️ Special
   ⚡ 5min
   🔄 Transition
   🏃 Movement
```

---

## 4. Create Perspectives

Perspectives are saved views that filter your tasks. You'll create seven.

### Access Perspective Management

1. Go to **Perspectives** menu > **Show Perspectives** (⌃⌘P)
2. Click the **+** button to create each new perspective

### Create and Configure Each Perspective

#### 4.1 Today

**Purpose**: Morning planning and daily task management

1. Create new perspective named `Today`
2. Click **View Options** (eye icon in toolbar)
3. Configure:
   - **Presentation**: Custom
   - **Group by**: Ungrouped
   - **Sort by**: Due
   - **Filter by availability**: Available
   - **Filter**: Check both **Due Soon** and **Flagged**
   - **Has a defer date of**: Today or Earlier

#### 4.2 Quick Wins

**Purpose**: Easy tasks when you're overwhelmed

1. Create new perspective named `Quick Wins`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Project
   - **Filter by availability**: Available
   - **Filter by tag**: Click "Specific Tags" and select **⚡ 5min**

#### 4.3 Popcorn

**Purpose**: Quick maintenance tasks between work blocks (movement + chores)

1. Create new perspective named `Popcorn`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Random (or Added)
   - **Filter by availability**: Available
   - **Filter by project**: Click "Specific Folders or Projects" and select **Popcorn** folder

#### 4.4 Client Focus

**Purpose**: Dedicated client work time

1. Create new perspective named `Client Focus`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Due
   - **Filter by availability**: Available
   - **Filter by project**: Click "Specific Folders or Projects" and select **Clients** folder

#### 4.5 Volunteer Focus

**Purpose**: Evening and weekend volunteer work

1. Create new perspective named `Volunteer Focus`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Due
   - **Filter by availability**: Available
   - **Filter by project**: Click "Specific Folders or Projects" and select **Volunteer** folder

#### 4.6 Context Switch

**Purpose**: Low-energy alternatives when stuck

1. Create new perspective named `Context Switch`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Project
   - **Filter by availability**: Available
   - **Filter by tag**: Click "Specific Tags" and select **🟢 Low**

#### 4.7 Weekly Review

**Purpose**: System maintenance

1. Create new perspective named `Weekly Review`
2. Configure:
   - **Presentation**: Custom
   - **Group by**: Project
   - **Sort by**: Project
   - **Filter by availability**: **Remaining** (not Available—this shows everything)

### Add Perspectives to Sidebar

For quick access:
1. Right-click each perspective in the Perspectives window
2. Select **Add to Sidebar**

Recommended sidebar order:
- Today
- Quick Wins
- Popcorn
- Client Focus
- Volunteer Focus

---

## 5. Add Initial Tasks

### Movement Tasks

Add these tasks to the **Movement** project (inside Popcorn folder). For each task, add all three tags: `🏃 Movement`, `⚡ 5min`, and `🔄 Transition`.

| Task | Note |
|------|------|
| 10 pushups | Any style—wall, knee, or standard |
| 20 squats | Bodyweight, go at your own pace |
| 5-minute stretch | Focus on neck, shoulders, and back |
| Walk around the block | Fresh air break |
| Plank for 60 seconds | Or as long as comfortable |
| Standing desk toggle (15 min) | Switch position |
| Take stairs | Next time you need to go up/down |
| Walk during next call | If the call doesn't require screen |
| 10 lunges each leg | Hold onto something if needed |
| Shoulder rolls and neck stretches | Release tension |

**To add tags to a task:**
1. Select the task
2. Open Inspector (⌥⌘I)
3. Click the Tags field and add the tags

### Chores Tasks

Add these tasks to the **Chores** project (inside Popcorn folder). Tag with `⚡ 5min` if the chore is quick.

| Task | Repeat Interval | Note |
|------|-----------------|------|
| Do a load of laundry | Defer 2-3 days | Wash, dry, fold cycle |
| Run dishwasher | Defer 1 day | Or hand wash dishes |
| Take out trash | Weekly (trash day) | Include recycling |
| Wipe kitchen counters | Defer 2 days | Quick wipe down |
| Clean bathroom | Weekly | Quick clean, not deep clean |
| Water plants | Defer 3-7 days | Depends on plants |
| Vacuum/sweep main areas | Weekly | High traffic areas |

**Customize this list** based on what you actually need reminders for. If you never forget something, don't track it.

### Weekly Review Task

Add to **Self Care** project:

- **Task name**: `Weekly Review`
- **Flag it**: Yes (click the flag icon)
- **Tag**: `🔴 Deep`
- **Note**:
  ```
  Weekly review checklist:

  1. Get inbox to zero
  2. Review each project:
     - Is there a clear next action?
     - Is this project still relevant?
     - Any deadlines approaching?
  3. Review "Waiting For" items—follow up needed?
  4. Review calendar—next 2 weeks
  5. Review Popcorn tasks—still the right options?
  6. Celebrate completions!

  Keep it short—better to do 20 min than skip 60 min.
  ```

### External System Sync Tasks (Only If Needed)

Only add these for projects with external systems (GitHub, Jira, etc.):

| Project Type | Task Name | When Needed |
|--------------|-----------|-------------|
| Clients with GitHub/Jira | Check [Client] backlog | Yes |
| Side projects with GitHub | Check [Project] backlog | Yes |
| Projects without external systems | — | No task needed |

**Note for each**: "Check [system] for new issues. Pull in anything that needs action."

---

## 6. Set Project Review Intervals

OmniFocus has a built-in Review feature for project health checks. Set review intervals on each project.

### How to Set Review Interval

1. Select a project
2. Open Inspector (⌥⌘I)
3. Find the **Review** field
4. Set the interval

### Recommended Intervals

| Project Type | Review Interval |
|--------------|-----------------|
| Clients | Every 1 week |
| Side Projects (active) | Every 1 month |
| Side Projects (dormant) | Every 3 months |
| Volunteer | Every 2 weeks |
| Personal (Health, Home, Family) | Every 1 month |
| Business | Every 1 month |
| Popcorn (Movement, Chores) | Every 1 month |

### Using the Review Perspective

1. Go to **Perspectives** > **Review** (or press ⌘6)
2. Projects due for review appear here
3. For each project, ask:
   - Does it have a clear next action?
   - Is it still relevant?
   - Should the review interval change?
4. Click **Mark Reviewed** when done

---

## 7. Set Up Repeating Tasks

### Popcorn Repeat Rules

Each Popcorn task should reappear after completion.

**Movement tasks:**
1. Select a Movement task
2. Open Inspector (⌥⌘I)
3. Click **Repeat** field
4. Set: **Defer another** `4 hours`
5. Repeat for all Movement tasks

**Chores tasks:**
1. Select a Chores task
2. Open Inspector (⌥⌘I)
3. Click **Repeat** field
4. Set interval based on the chore:
   - Daily chores (dishes): **Defer another** `1 day`
   - Every few days (laundry, counters): **Defer another** `2-3 days`
   - Weekly chores (trash): **Weekly** on appropriate day

> **Why "defer another"?** After completing "10 pushups," it will become available again in 4 hours rather than immediately. This prevents the same tasks from cluttering your view.

### Weekly Review Repeat Rule

1. Select the Weekly Review task
2. Open Inspector
3. Set **Repeat**: **Weekly** on **Sunday**
4. Set **Due**: Next Sunday (pick a time, like 6:00 PM)

### Client Backlog Review Repeat Rules

For each client review task:

1. Select the task
2. Open Inspector
3. Set **Repeat**: **Weekly** on **Monday**
4. Set **Due**: Next Monday morning

---

## 8. Configure Focus Modes (Optional)

Focus modes temporarily hide folders/projects to reduce visual noise.

### Create Work Focus

1. Go to **View** menu > **Focus**
2. In the dialog, check only:
   - **Clients** folder
   - **Side Projects** folder
   - **Popcorn** folder
3. Click **Focus**
4. To save: **Perspectives** menu > **Save Focus as Perspective**
5. Name it `Work Focus`

### Create Life Focus

1. Go to **View** menu > **Focus**
2. Check only:
   - **Volunteer** folder
   - **Personal** folder
   - **Business** folder
   - **Popcorn** folder
3. Save as `Life Focus`

### Switching Focus

- Use **View** > **Focus** to switch
- Or use **View** > **Unfocus** to see everything

---

## 9. Calendar Setup

### Weekly Review Appointment

Add a recurring calendar event:

- **Title**: Weekly Review
- **Duration**: 30-45 minutes
- **When**: Sunday evening or Monday morning (your choice)
- **Recurrence**: Weekly
- **Notes**: Link to your Weekly Review checklist

### Movement Prompts

Add short events between meetings:

- **Title**: 🏃 Movement?
- **Duration**: 5 minutes
- **When**: Between your regular meetings/work blocks

These aren't appointments—they're reminders to check your Popcorn perspective.

---

## 10. Verification Checklist

Use this checklist to confirm everything is set up correctly.

### Structure

- [ ] 5 folders exist: Clients, Side Projects, Volunteer, Personal, Business
- [ ] Client projects exist inside Clients folder (one per client)
- [ ] Side projects exist inside Side Projects folder (one per project)
- [ ] Volunteer projects exist inside Volunteer folder (one per role)
- [ ] Personal projects exist inside Personal folder
- [ ] Business projects exist inside Business folder (one per entity)
- [ ] Popcorn folder exists with Movement and Chores projects inside
- [ ] All projects are set to single-action list type

### Tags

- [ ] Energy parent tag with 🔴 Deep and 🟢 Low children
- [ ] Context parent tag with 5 children (Computer, Phone, Home, Errands, With Others)
- [ ] Special parent tag with 3 children (5min, Transition, Movement)

### Perspectives

- [ ] Today perspective shows due/flagged/deferred-today tasks
- [ ] Quick Wins perspective shows only ⚡ 5min tagged tasks
- [ ] Popcorn perspective shows Popcorn folder tasks
- [ ] Client Focus shows only Clients folder
- [ ] Volunteer Focus shows only Volunteer folder
- [ ] Context Switch shows 🟢 Low energy tasks
- [ ] Weekly Review shows all projects and remaining tasks

### Tasks

- [ ] Movement tasks exist with all three special tags (🏃 Movement, ⚡ 5min, 🔄 Transition)
- [ ] Chores tasks exist with appropriate repeat intervals
- [ ] All Popcorn tasks repeat after completion
- [ ] Weekly Review task is flagged and repeats weekly
- [ ] Each client has a backlog review task that repeats weekly

### Calendar

- [ ] Weekly Review appointment exists and repeats
- [ ] At least a few "🏃 Movement?" prompts added between meetings

---

## Quick Reference Card

Once setup is complete, here's your daily workflow:

### Morning (10-15 min)
1. Check calendar
2. Open **Today** perspective
3. Flag 3-5 tasks
4. Glance at **Popcorn**

### During the Day
- **Overwhelmed?** → Open **Quick Wins**, do anything
- **Stuck?** → Open **Context Switch**, do something different
- **Between tasks?** → Open **Popcorn**, do one thing

### End of Day (5 min)
1. Process Inbox to zero
2. Check flagged items
3. Preview tomorrow's calendar

### Weekly (30-45 min)
1. Complete the Weekly Review task checklist
2. Celebrate what you accomplished

---

## Troubleshooting

### "My perspective shows nothing"

- Check that the filter is set to **Available** (or **Remaining** for Weekly Review)
- Make sure tasks have the required tags
- Verify tasks aren't blocked by defer dates

### "Popcorn tasks disappeared"

- They may be deferred. Check later, or:
- Open the Movement or Chores project directly to see all tasks regardless of defer date

### "I keep forgetting the Weekly Review"

- Make sure it's flagged (appears in Today)
- Make sure the calendar appointment is set
- Consider body doubling: schedule review time with a friend nearby

### "System feels overwhelming"

- Focus on just **Today** and **Quick Wins** perspectives
- Ignore the others until you're comfortable
- The system is meant to help, not add pressure
