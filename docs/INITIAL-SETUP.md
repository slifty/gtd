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
   - `Family & Friends`
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

4. Inside Popcorn, create the **Metaphysical** project:
   - Select the Popcorn folder
   - Press ⌘N to create a new project
   - Name it `Metaphysical`
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
   📋 Family & Friends ⟲
   📋 Finances ⟲
   📋 Hobbies ⟲
📁 Business
   📋 [Your business entities] ⟲
📁 Popcorn
   📋 Movement ⟲
   📋 Chores ⟲
   📋 Metaphysical ⟲
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
2. Create: `Focus Mode`
3. Create: `Context`
4. Create: `Special`

### Create Focus Mode Tags (nested under Focus Mode)

1. Select the **Focus Mode** tag
2. Press ⌘N to create a child tag
3. Create:
   - `🤔 Deep Work` — for tasks requiring focus, no interruptions
   - `😎 Shallow` — for tasks you can do when tired or scattered

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
   - `📥 Daily Review` — recurring tasks for checking external systems (backlogs, email, etc.)

### Result

```
🏷️ Focus Mode
   🤔 Deep Work
   😎 Shallow
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
   📥 Daily Review
```

---

## 4. Create Perspectives

Perspectives are saved views that filter your tasks. You'll create nine.

### Access Perspective Management

1. Go to **Perspectives** menu > **Show Perspectives** (⌃⌘P)
2. Click the **+** button to create each new perspective

### Create and Configure Each Perspective

> **Note**: OmniFocus 4 organizes perspective settings into three sections:
> - **Contents** — Filter rules that determine which items appear
> - **Structure** — How items are grouped and sorted
> - **Layout** — Display options (can usually leave as default)
>
> Filter rules use hierarchical logic: **All of the following** (AND), **Any of the following** (OR), or **None of the following** (NOT).

#### 4.1 Today

**Purpose**: Morning planning and daily focus — shows your intentional commitments for today

**Philosophy**: Today is a clean slate. Past-planned items don't roll over automatically; you actively decide what belongs in today during morning planning.

1. Create new perspective named `Today`
2. Configure **Contents** (filter rules):
   - Add `Availability: Available`
   - Add **Any of the following**, then nest inside it:
     - `Status: Due Soon or Flagged`
     - `Has date in range` → **Planned Date** → **Today**
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Ungrouped
   - **Sort actions by**: Due Date

#### 4.2 Quick Wins

**Purpose**: Low-commitment productivity when you have limited time or energy

1. Create new perspective named `Quick Wins`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is tagged with any of` → select **⚡ 5min**
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Projects Order

#### 4.3 Popcorn

**Purpose**: Quick maintenance tasks between work blocks (movement + chores)

1. Create new perspective named `Popcorn`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is contained within project or folder` → select **Popcorn** folder
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Added Date (or use Flexible structure for random feel)

#### 4.4 Work

**Purpose**: Professional obligations — client work and business admin

**Philosophy**: Shows all paid/professional tasks at once, grouped by project. Pick based on priority, deadlines, or energy. To focus on a single client, use OmniFocus's Focus feature (View → Focus on [Project]) rather than creating separate perspectives per client.

1. Create new perspective named `Work`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add **Any of the following**, then nest inside it:
     - `Is contained within project or folder` → select **Clients** folder
     - `Is contained within project or folder` → select **Business** folder
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Due Date

#### 4.5 Volunteer

**Purpose**: Community commitments — roles with external accountability

**Philosophy**: Shows all volunteer tasks grouped by project. These have external accountability (boards, organizations, people depending on you). Use OmniFocus's Focus feature to narrow to a single role when needed.

1. Create new perspective named `Volunteer`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is contained within project or folder` → select **Volunteer** folder
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Due Date

#### 4.6 Side Quests

**Purpose**: Passion projects — purely optional adventures

**Philosophy**: Shows all side project tasks grouped by project. These are things you do because you want to, with no external accountability. Lower priority than volunteer commitments.

1. Create new perspective named `Side Quests`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is contained within project or folder` → select **Side Projects** folder
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Due Date

#### 4.7 Personal

**Purpose**: Life maintenance — health, home, family, hobbies

**Philosophy**: Shows all personal tasks grouped by project. Open this when you have personal time and want to browse available tasks to flag or plan for today.

1. Create new perspective named `Personal`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is contained within project or folder` → select **Personal** folder
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Due Date

#### 4.8 Easy Mode

**Purpose**: Overwhelm recovery — the easiest possible path forward

1. Create new perspective named `Easy Mode`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is tagged with any of` → select **😎 Shallow**
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Projects Order

#### 4.9 Daily Review

**Purpose**: Morning routine — check external systems and pull in new work

**Philosophy**: This perspective collects all your recurring "check backlog" tasks in one place. Open it each morning to sync with external systems (GitHub, Jira, email) before starting focused work.

1. Create new perspective named `Daily Review`
2. Configure **Contents**:
   - Add `Availability: Available`
   - Add `Is tagged with any of` → select **📥 Daily Review**
3. Configure **Structure**:
   - Choose **Organized: Individual Actions**
   - **Group actions by**: Project
   - **Sort actions by**: Projects Order

> **Note**: For weekly project health checks (clear next action? still relevant?), use OmniFocus's built-in **Review** perspective, not a custom one.

### Configure Sidebar

The sidebar is your main navigation. Configure it to show only what you need, in a logical order.

#### How to reorder perspectives

1. Go to **Perspectives** menu > **Show Perspectives** (⌃⌘P)
2. Drag perspectives up/down to reorder
3. The sidebar order matches the Perspectives window order

#### How to show/hide perspectives

1. In the Perspectives window, right-click a perspective
2. Select **Add to Sidebar** or **Remove from Sidebar**

#### Recommended sidebar order

Show these perspectives in this order:

| Position | Perspective | Type | Purpose |
|----------|-------------|------|---------|
| 1 | **Inbox** | Built-in | Capture - process to zero |
| 2 | 🟠 **Today** | Custom | Morning planning, daily focus |
| 3 | 🟠 **Daily Review** | Custom | Morning routine, check external systems |
| 4 | 🩷 **Quick Wins** | Custom | Low-commitment progress |
| 5 | 🩷 **Easy Mode** | Custom | Overwhelm recovery |
| 6 | 🟢 **Popcorn** | Custom | Micro-tasks between work |
| 7 | 🟣 **Work** | Custom | Professional obligations (Clients + Business) |
| 8 | 🟣 **Volunteer** | Custom | Community commitments (Volunteer) |
| 9 | 🟣 **Personal** | Custom | Life maintenance (Personal) |
| 10 | 🟣 **Side Quests** | Custom | Passion projects (Side Projects) |
| 11 | **Forecast** | Built-in | Calendar view, upcoming due dates |
| 12 | **Projects** | Built-in | Navigate project hierarchy |
| 13 | **Review** | Built-in | Weekly project health checks |

**Color taxonomy:**
- 🟠 Orange = Daily workflow
- 🟢 Green = Popcorn
- 🟣 Purple = Life areas
- 🩷 Pink = Recovery

#### Hide these built-in perspectives

These are redundant or not used in this system:

| Perspective | Why Hide |
|-------------|----------|
| **Flagged** | Redundant — Today already shows flagged items |
| **Tags** | Not used for navigation in this system |
| **Nearby** | Location-based, not part of this workflow |

> **Tip**: You can always access hidden perspectives via **Perspectives** menu if needed.

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

### Metaphysical Tasks

Add these tasks to the **Metaphysical** project (inside Popcorn folder).

| Task | Repeat Interval | Note |
|------|-----------------|------|
| Log mood | Defer 4 hours | Quick check-in: how are you feeling? |
| Review a project | Defer 1 day | Open Review perspective, review 1-3 projects |

**Customize this list** with other self-awareness or system maintenance habits that work for you.

### Weekly Review Task

Add to **Self Care** project:

- **Task name**: `Weekly Review`
- **Flag it**: Yes (click the flag icon)
- **Tag**: `🤔 Deep Work`
- **Note**:
  ```
  Weekly review checklist:

  1. Get inbox to zero
  2. Review each project:
     - Is there a clear next action?
     - Is this project still relevant?
     - Any deadlines approaching?
  3. Review calendar—next 2 weeks
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

**For each task:**
- Tag with: 💻 Computer, ⚡ 5min, 📥 Daily Review
- Note: "Check [system] for new issues. Pull in anything that needs action."

The 📥 Daily Review tag ensures these tasks appear in your Daily Review perspective each morning.

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
| Personal (Self Care, Home, Family & Friends) | Every 1 month |
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

Focus modes use OmniFocus's built-in Focus feature to temporarily hide folders app-wide. This is broader than perspectives — it affects the entire app, not just one view.

> **Note**: Focus modes are named "Mode" to distinguish from OmniFocus's built-in Focus feature (e.g., "Work Mode" is a saved focus, not a perspective).

### Create Work Mode

1. Go to **View** menu > **Focus**
2. In the dialog, check only:
   - **Clients** folder
   - **Business** folder
   - **Popcorn** folder
3. Click **Focus**
4. To save: **Perspectives** menu > **Save Focus as Perspective**
5. Name it `Work Mode`

### Create Projects Mode

1. Go to **View** menu > **Focus**
2. Check only:
   - **Volunteer** folder
   - **Side Projects** folder
   - **Popcorn** folder
3. Save as `Projects Mode`

### Create Personal Mode

1. Go to **View** menu > **Focus**
2. Check only:
   - **Personal** folder
   - **Popcorn** folder
3. Save as `Personal Mode`

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
- [ ] Popcorn folder exists with Movement, Chores, and Metaphysical projects inside
- [ ] All projects are set to single-action list type

### Tags

- [ ] Focus Mode parent tag with 🤔 Deep Work and 😎 Shallow children
- [ ] Context parent tag with 5 children (Computer, Phone, Home, Errands, With Others)
- [ ] Special parent tag with 4 children (5min, Transition, Movement, Daily Review)

### Perspectives

- [ ] Today perspective shows due soon/flagged/planned-today tasks
- [ ] Quick Wins perspective shows only ⚡ 5min tagged tasks
- [ ] Popcorn perspective shows Popcorn folder tasks
- [ ] Work shows Clients + Business folders
- [ ] Volunteer shows Volunteer folder
- [ ] Side Quests shows Side Projects folder
- [ ] Personal shows Personal folder
- [ ] Easy Mode shows 😎 Shallow tasks
- [ ] Daily Review shows 📥 Daily Review tagged tasks

### Tasks

- [ ] Movement tasks exist with all three special tags (🏃 Movement, ⚡ 5min, 🔄 Transition)
- [ ] Chores tasks exist with appropriate repeat intervals
- [ ] Metaphysical tasks exist (mood logging, project review)
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
- **Short on time?** → Open **Quick Wins**, knock out something small
- **Overwhelmed?** → Open **Easy Mode**, do the easiest thing
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

- Check that the filter is set to **Available**
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
