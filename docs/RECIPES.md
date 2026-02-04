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

4. **Glance at Movement Snacks** — Prime yourself. Remember these exist.

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

6. **Review Movement Snacks**
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

2. **Add the backlog review task**
   - Add task: `Review [Client] backlog`
   - Set repeat: Weekly on Monday
   - Tag: 💻 Computer, ⚡ 5min
   - Note: "Check [GitHub/Jira/system] for open issues. Update OmniFocus with new milestones."

3. **Add any known tasks**
   - Current deliverables with deadlines
   - Administrative tasks (contracts, invoicing)
   - Waiting-for items

4. **Update STRUCTURE.md** (optional)
   - Add the new client to the Clients table
   - Update recurring tasks list

### Example result

```
📋 New Client
   ◯ Review New Client backlog [repeat: weekly Monday]
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

2. **Add initial tasks**
   - Any immediate commitments
   - Recurring meetings (add prep tasks)
   - People to meet/contact

3. **Consider recurring reviews**
   - If there's an external system (email list, shared docs), add a review task

4. **Update Life Focus mode** (if needed)
   - Volunteer folder should already be included

---

## Adding a New Personal Project

**Time:** 5 minutes

### Steps

1. **Decide which folder**
   - Health & Body — medical, fitness, wellness
   - House & Home — maintenance, improvements
   - Family — family activities, responsibilities
   - Bad Idea Factory — creative projects
   - Music & Creative — music, art, hobbies

2. **Add tasks to existing project** (preferred)
   - Most "projects" are just tasks in an existing single-action list

3. **Or create a sub-project** (rare)
   - Only if it's a distinct, time-bound effort
   - Example: "Kitchen Renovation" as a project under House & Home

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
