# Recipes

Step-by-step procedures for common tasks. Follow these when you need to do something and don't want to think about how.

---

## Table of Contents

- [Morning Planning](#morning-planning)
- [End of Day Shutdown](#end-of-day-shutdown)
- [Weekly Review](#weekly-review)
- [Catching Up After Missing Reviews](#catching-up-after-missing-reviews)
- [Onboarding a New Client](#onboarding-a-new-client)
- [Onboarding a New Volunteer Role](#onboarding-a-new-volunteer-role)
- [Adding a New Personal Project](#adding-a-new-personal-project)
- [Onboarding a New Side Project](#onboarding-a-new-side-project)
- [Recurring Life Events](#recurring-life-events)
- [Processing a Meeting](#processing-a-meeting)
- [Processing Email to Tasks](#processing-email-to-tasks)
- [Handling a New GitHub Issue](#handling-a-new-github-issue)
- [Completing a Project](#completing-a-project)
- [Offboarding a Client](#offboarding-a-client)

---

## Morning Planning

**Time:** 10-15 minutes
**When:** Start of your work day

### Steps

1. **Open calendar** — What's blocked today? Any meetings or appointments?

2. **Open Today perspective** — Scan what's due and flagged

3. **Flag 3-5 tasks** — Be realistic. Ask: "If I only did these, would today be a success?"
   - Consider energy: Is today a Deep day or a Low day?
   - Consider calendar: How much unblocked time do you have?

4. **Glance at Popcorn** — Prime yourself. Remember movement and chores exist.

5. **Start working** — Pick a flagged task and begin

### If inbox has items

Process them quickly (2-min rule: do it, defer it, or delete it). Don't let inbox processing eat your morning.

---

## End of Day Shutdown

**Time:** 5 minutes
**When:** End of your work day

### Steps

1. **Process inbox to zero** — Anything captured during the day gets sorted
   - Each item: Do it (<2 min), add to correct project, or delete

2. **Review flagged items** — What got done? Celebrate. What didn't? That's fine.
   - Unflag anything that didn't happen (it'll still be there tomorrow)

3. **Check tomorrow's calendar** — Any prep needed tonight?
   - If yes, add a task or do it now

4. **Close OmniFocus** — You're done for the day

---

## Weekly Review

**Time:** 30-45 minutes
**When:** Sunday evening or Monday morning (pick one, be consistent)

### Steps

1. **Get inbox to zero**
   - Process everything that accumulated
   - Be ruthless: if it's not actionable, delete it

2. **Open Weekly Review perspective**

3. **For each project, ask:**
   - Is there a clear next action? (If not, add one)
   - Is this project still relevant? (If not, put on hold or drop)
   - Any deadlines approaching? (If yes, flag or add due dates)

4. **Check Waiting For items**
   - Any follow-ups needed?
   - Has anything been waiting too long?

5. **Review calendar — next 2 weeks**
   - Any prep tasks to add?
   - Any conflicts to resolve?

6. **Review Popcorn**
   - Are these still the right options?
   - Add or remove as needed

7. **Celebrate completions**
   - Look at what you accomplished
   - Acknowledge progress

### Tips

- Keep it under 45 minutes. Better to do a quick review than skip a thorough one.
- Consider body doubling: do the review with someone nearby
- Put on music or a podcast if that helps

---

## Catching Up After Missing Reviews

**Time:** 45-60 minutes
**When:** You've missed multiple weekly reviews and things feel chaotic

### Steps

1. **Don't panic.** The system is designed to recover.

2. **Process inbox to zero** — This might take a while. That's okay.

3. **Quick scan all projects** — For each:
   - Is anything overdue? Handle or reschedule.
   - Is there an obvious next action? If not, add one.
   - Don't try to be thorough. Just get things moving.

4. **Check calendar for this week** — Any immediate prep needed?

5. **Flag 3 tasks for today** — Just three. Start moving.

6. **Schedule a proper weekly review** — Put it on the calendar for this week

### What NOT to do

- Don't try to process everything perfectly
- Don't reorganize the whole system
- Don't add a bunch of new structure "to prevent this"

The goal is momentum, not perfection.

---

## Onboarding a New Client

**Time:** 10 minutes

### Steps

1. **Create the project**
   - Go to Clients folder
   - Press ⌘N to create new project
   - Name it: `[Client Name]`
   - Set Project Type to **Single Actions** (Inspector → Project Type)

2. **Set the review interval**
   - In Inspector, set **Review** to **Every 1 week**
   - This queues the project in OmniFocus's Review perspective weekly

3. **Add external system sync task** (if applicable)
   - Only if client has GitHub/Jira/external tracker
   - Add task: `Check [Client] backlog`
   - Set repeat: Weekly on Monday
   - Tag: 💻 Computer, ⚡ 5min
   - Note: "Check [GitHub/Jira] for new issues. Pull in anything that needs action."

4. **Add any known tasks**
   - Current deliverables with deadlines
   - Administrative tasks (contracts, invoicing)
   - Waiting-for items

### Example result

```
📋 New Client [review: weekly]
   ◯ Check New Client backlog [repeat: weekly Monday] ← only if external system
   ◯ Complete onboarding paperwork [due: this week]
   ◯ Set up development environment
   ⏸ Waiting: Access credentials from client
```

---

## Onboarding a New Volunteer Role

**Time:** 10 minutes

### Steps

1. **Create the project**
   - Go to Volunteer folder
   - Press ⌘N to create new project
   - Name it: `[Role Name] ([Position])`
   - Set Project Type to **Single Actions**

2. **Set the review interval**
   - In Inspector, set **Review** to **Every 2 weeks**
   - Volunteer commitments need regular attention

3. **Add initial tasks**
   - Any immediate commitments
   - Recurring meetings (add prep tasks)
   - People to meet/contact

4. **Add external system sync task** (only if needed)
   - Only if there's an external system (shared docs, email list, etc.)
   - Add recurring task to check it

---

## Adding a New Personal Project

**Time:** 5 minutes

### First: Personal or Side Project?

- **Side Projects folder** — Has real scope, deliverables, could be "done" (software, creative work, open source)
- **Personal folder** — Ongoing life maintenance, no "done" state

If it's a scoped project, see [Onboarding a New Side Project](#onboarding-a-new-side-project).

### Steps (for Personal)

1. **Decide which project**
   - Health & Body — medical, fitness, wellness
   - House & Home — maintenance, improvements
   - Family — family activities, responsibilities
   - Finances — taxes, insurance, investments, estate planning
   - Hobbies — music, art, ongoing pursuits

2. **Add tasks to existing project** (preferred)
   - Most "projects" are just tasks in an existing single-action list

3. **Or create a sub-project** (rare)
   - Only if it's a distinct, time-bound effort
   - Example: "Kitchen Renovation" as a project under House & Home

---

## Onboarding a New Side Project

**Time:** 10 minutes

Side projects have scope and deliverables, but less urgency than client work.

### Steps

1. **Create the project**
   - Go to Side Projects folder
   - Press ⌘N to create new project
   - Name it: `[Project Name]`
   - Set Project Type to **Single Actions** (Inspector → Project Type)

2. **Set the review interval**
   - In Inspector, set **Review** based on how active the project is:
     - Active project: **Every 1 month**
     - Dormant/back-burner: **Every 3 months**
   - This queues the project in OmniFocus's Review perspective

3. **Add external system sync task** (only if needed)
   - Only if the project has a GitHub repo or external tracker
   - Add task: `Check [Project] backlog`
   - Set repeat: Weekly or biweekly
   - Tag: 💻 Computer, ⚡ 5min
   - Note: "Check GitHub for new issues. Pull in anything to work on."

   **If the project lives only in your head/OmniFocus:** Skip this step. The built-in Review is enough.

4. **Add any known tasks**
   - Current priorities or milestones
   - Ideas to explore
   - Documentation to write

### Example: Side project with GitHub

```
📋 TV Kitchen [review: monthly]
   ◯ Check TV Kitchen GitHub [repeat: weekly] ← has external system
   ◯ Implement pipeline caching
   ◯ Write README documentation
```

### Example: Side project without external system

```
📋 Novel Draft [review: monthly]
   ◯ Write chapter 3 outline        ← no recurring task needed
   ◯ Research 1920s slang
   ◯ Develop antagonist backstory
```

---

## Recurring Life Events

**Time:** 10 minutes to set up, then automatic

**Examples:** Annual vacation, holiday planning, yearly appointments, seasonal tasks

### The Pattern

Don't create a full project with all steps. Instead:

1. **One recurring task** that triggers planning
2. **Checklist in the task notes** with all the steps
3. **Pull out specific tasks** during weekly review as they become actionable

### Why This Works

Most steps in recurring events aren't actionable until their time comes. "Book ferry" in January when reservations open in April is just clutter. Your weekly review naturally surfaces what's next.

You only need the *trigger*, not the whole sequence.

### Setup Steps

1. **Create the recurring task**
   - Project: Relevant personal project (usually Family or Health & Body)
   - Name: "Plan [event name]" (e.g., "Plan summer vacation")
   - Repeat: Yearly, set to appear when planning naturally starts
   - Tag: Consider `🔴 Deep` if planning requires focus

2. **Add checklist to notes**
   ```
   Planning checklist:
   - [ ] Pick dates
   - [ ] Book accommodations
   - [ ] Book transportation
   - [ ] Request time off work
   - [ ] Coordinate with family
   - [ ] Make packing list
   - [ ] [Add your specific steps]
   ```

3. **During weekly review**, when the task appears:
   - Check what's now actionable
   - Create individual tasks for immediate next actions
   - Leave future steps in the checklist

### Example: Annual Vacation

**Recurring task:** "Plan summer vacation" (appears March 1)
**In notes:**
```
Vacation planning checklist:
- [ ] Pick dates with family
- [ ] Book rental house (opens Jan 1)
- [ ] Book ferry (reservations open March 15)
- [ ] Request time off work
- [ ] Renew beach parking permit
- [ ] Schedule pet sitter
- [ ] Pack (week before)
```

**During March weekly review:**
- See "Plan summer vacation" is now available
- Check notes — ferry reservations open March 15
- Create task: "Book ferry for vacation" with defer date of March 15

**During July weekly review (week before trip):**
- Create task: "Pack for vacation"
- Create task: "Confirm pet sitter"

### Other Examples

| Event | Recurring Task | When It Appears |
|-------|---------------|-----------------|
| Annual physical | "Schedule annual physical" | January |
| Holiday gifts | "Plan holiday gifts" | November 1 |
| Tax prep | "Gather tax documents" | February 1 |
| Kid's birthday | "Plan [name]'s birthday" | 6 weeks before |
| Seasonal HVAC | "Schedule HVAC maintenance" | March and September |
| Car registration | "Renew car registration" | 1 month before expiry |

### When to Create a Full Project Instead

Only if the event has unusual complexity:
- Coordinating multiple families or stakeholders
- Managing a budget that needs tracking
- Legal/visa requirements with dependencies
- Multi-week effort with many parallel workstreams

Even then, ask: does this need OmniFocus, or is a shared doc better?

---

## Processing a Meeting

**Time:** 5-10 minutes
**When:** Immediately after a meeting, or during daily shutdown

### Steps

1. **Review your notes** — What did you commit to?

2. **For each commitment:**
   - Create a task in the relevant project
   - Add context: "[from meeting with X on date]" in the task name or note
   - Set due date if there's a deadline
   - Tag appropriately (energy, context)

3. **For each thing you're waiting on:**
   - Create a task: "Waiting: [thing] from [person]"
   - Or use OmniFocus's "On Hold" status

4. **For each decision made:**
   - Document in the appropriate place (not OmniFocus)
   - If it requires action, create the task

### Example

Meeting outcome: "Client will send API docs by Friday, then I'll write integration code"

Tasks created:
- `Waiting: API docs from client [from 2/4 meeting]` — in client project
- `Write API integration code` — in client project, deferred until Friday

---

## Processing Email to Tasks

**Time:** Varies
**When:** During inbox processing or when specific email requires action

### Steps

1. **Read the email** — What action does it require?

2. **If action takes <2 minutes:** Do it now. Reply and archive.

3. **If action takes longer:**
   - Create task in relevant project
   - Task name: Brief description of what to do (not email subject)
   - Note: Reference the email if needed ("see email from X on date")
   - Archive the email

4. **If waiting for response:**
   - Create "Waiting: [response] from [person]"
   - Archive the email

### Anti-patterns

- ❌ Don't copy the email into OmniFocus
- ❌ Don't use email subject as task name
- ❌ Don't leave email in inbox "as a reminder"

---

## Handling a New GitHub Issue

**Time:** 2 minutes
**When:** During backlog review or when assigned an issue

### Steps

1. **Decide: Does this need to be in OmniFocus?**
   - If it's your current focus: Yes
   - If it's backlog for later: No (it'll come up in next review)

2. **If yes, create the task:**
   - Project: Relevant client project
   - Name: Brief description + `(GH #XXX)`
   - Don't copy the issue description

3. **If it has a deadline:**
   - Set due date
   - Consider flagging

### Example

GitHub issue #142: "Authentication fails with special characters in password"

Task: `Fix auth special chars bug (GH #142)` in relevant client project

---

## Completing a Project

**Time:** 5 minutes
**When:** A distinct effort is finished (rare with single-action lists)

### Steps

1. **Review remaining tasks**
   - Complete any that are actually done
   - Delete any that are no longer relevant
   - Move any still-needed tasks to appropriate project

2. **Mark project complete** (if it's a sub-project)
   - Or delete if it was temporary

3. **Celebrate** — You finished something!

---

## Offboarding a Client

**Time:** 15 minutes
**When:** Client engagement ends

### Steps

1. **Complete final tasks**
   - Final invoice submitted
   - Any handoff documentation done
   - Access/credentials returned or revoked

2. **Review remaining tasks**
   - Complete what's done
   - Delete what's no longer needed
   - Note anything for future reference

3. **Handle the project**
   - Option A: Mark as "Completed" (keeps history)
   - Option B: Mark as "Dropped" (engagement ended early)
   - Option C: Put "On Hold" (might resume later)

4. **Update STRUCTURE.md**
   - Remove from active clients list
   - Note in a "Former Clients" section if you want history

5. **Remove from recurring tasks**
   - Delete the "Review [Client] backlog" task

6. **Celebrate** — Another engagement completed!
