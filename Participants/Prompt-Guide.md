# Kiro Crew — Prompt Guide for DBP

Ready-to-use prompts for each training topic. Copy, paste into the dashboard chat or CLI, adjust the bracketed parts.

---

## 1. Account & Token Management

```
Check my Kiro Crew login status and tell me whose account is funding requests on this gateway.
```

```
Walk me through revoking and re-creating my API key safely.
```

---

## 2. Kiro Crew — How It Works

```
Summarize [FILE PATH] and tell me the 3 most important open items in it.
```

```
Set up a recurring job that runs every [DAY] at [TIME] and summarizes my open [PROJECT] tasks.
```

```
List everything you would need — tools or credentials — to check the health of our [SYSTEM NAME], and tell me plainly if you can already do it or not.
```

---

## 3. Agent Creation

```
Create a new crew member named [NAME]. Its job: [ONE-SENTENCE JOB DESCRIPTION].
Give it read-only access to [SCOPE]. It should respond when a message contains the words: [TRIGGER WORDS].
It must never [THE ONE THING IT SHOULD NEVER DO].
```

```
Ask [CREW MEMBER NAME] to [TASK WITHIN ITS JOB]. Then ask it to [TASK OUTSIDE ITS JOB] and tell me what happens.
```

```
Show me the current permission rules for [CREW MEMBER NAME], and explain which ones are "ask first" vs "never allowed."
```

---

## 4. Connect Your Own Tools (MCP)

```
What tools and connections do you currently have access to?
```

```
Using [THE TOOL YOU JUST CONNECTED], [A REAL SMALL TASK — e.g. "list my open Jira tickets in project DBP"].
```

```
I just added the [SERVER NAME] MCP server. Confirm you can see it, and list what it now lets you do.
```

---

## 5. Many Hands, One Ask (Subagents)

```
Research [TOPIC A] and [TOPIC B] at the same time, then give me one combined summary.
```

```
Check these files for bugs at the same time: [FILE 1], [FILE 2], [FILE 3]. Report each separately.
```

```
Compare [OPTION A] and [OPTION B] in parallel, then tell me which fits [OUR CONSTRAINT] better.
```

---

## 6. "Keep an Eye on This For Me" (Monitor / Babysit)

```
Watch [A REAL PULL REQUEST URL] and tell me when it's ready to merge.
```

```
Keep an eye on [WHAT TO WATCH — e.g. a CI build, a ticket] and only ping me when something actually changes.
```

```
Stop watching that.
```

---

## 7. Apps: Features You Turn On

```
What apps do I have, and which ones are turned on right now?
```

```
What does this app let me do, and what did turning it on just add?
```

```
I turned on [APP NAME]. Walk me through what it added — any new page, agent, or scheduled job.
```

---

## General-purpose starter prompts (good for day-to-day work)

```
Read [FILE OR FOLDER] and tell me what's outdated, risky, or missing.
```

```
Here is a correction: [WHAT YOU WANT IT TO DO DIFFERENTLY NEXT TIME]. Remember this going forward.
```

```
Before you do [ACTION], tell me what you're about to change and wait for my confirmation.
```

---

*Pair this with [the hands-on modules](README.md) in this folder for the full training flow.*

← [Back to all modules](README.md)
