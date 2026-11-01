
# Hands-On 3 — Agent Creation

**Module 3 of 7** · [All modules](README.md) · Previous: [Module 2](Handson-2-How-It-Works.md) · Next: [Module 4 — Connect Your Own Tools](Handson-4-MCP-Connections.md)

---

## Think of it this way

A custom agent (a "crew member" / "mate") is like **onboarding a new associate-level hire**. You don't hand a new hire the keys to everything day one. You give them:
- A **job description** — what they're there to do
- A **toolbox** — what systems they're allowed to touch
- **Boundaries** — what needs permission, what's never allowed

The more specific the job description, the better the agent performs.

---

## Step 1: Create a new crew member

Open **Customize → Mates** → **New mate**.

| Field | What to put |
|---|---|
| Name | Something job-like, e.g. `ticket-triager` |
| Job description | One specific paragraph. Vague = vague results. |
| Toolbox | Start narrow. Only what the job needs. |
| Trigger words | Short phrases that uniquely call this agent, e.g. "triage this ticket" |

**Example prompt to write its job description:**

> "You triage incoming support tickets. Read the ticket, classify severity, and suggest an owner. Never close or reassign a ticket yourself — only recommend."

## Step 2: Test what it CAN do

In its chat, type a message that matches a trigger word:

> **Prompt:** "triage this ticket: login page returns a 500 error for all users since this morning"

Confirm it responds as that agent.

## Step 3: Test the boundary

Ask it to do something outside its job on purpose:

> **Prompt:** "close this ticket for me"

Watch for an approval prompt, or a refusal. **This is the moment that proves the boundary is real, not just a suggestion.**

## Step 4: See the master switch

Open **Settings → Security → YOLO (auto-approve)**.

By default, Crew asks before most actions — what you just saw in Step 3. Turning YOLO on lets it skip asking for a set amount of time. Leave it off while your team is still learning what to trust an agent with.

---

## Example prompts to try on your own agent

- "What's your job, in one sentence?"
- "What tools can you use, and what can't you touch?"
- "Here's a real ticket from our backlog — triage it."
- "Why did you ask for approval just now instead of just doing it?"

---

## Quick Reference — All 3 Modules

| Task | Where |
|---|---|
| Check who's signed in | Settings → Overview |
| See your plan / usage | Ask in chat: "what plan am I on?" |
| Add a scheduled job | Ask in chat, or Schedule page → New Schedule |
| Run a job now | Schedule page → open the job → Run Now |
| Create a crew member | Customize → Mates → New Mate |
| Control how much an agent can do without asking | Settings → Security → YOLO (auto-approve) |

Done with Module 3? → [Module 4 — Connect Your Own Tools](Handson-4-MCP-Connections.md)

← [Back to all modules](README.md)
