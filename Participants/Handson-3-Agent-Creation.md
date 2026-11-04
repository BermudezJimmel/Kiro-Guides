
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

## Step 0: Turn on the Mates preview (do this first)

Mates is a **feature preview, off by default**. Turn it on once before you can create one:

Open **Settings → Developer → Feature Previews → Mates** and switch it on. The **Mates** entry now appears in the left sidebar.

🧭 **Don't see "Developer" or "Feature Previews"?** Your build may already have Mates on — check the left sidebar for a **Mates** entry. If it's there, skip to Step 1.

## Step 1: Create a new crew member

Open the **Mates** page from the left sidebar, then click **New mate**.

| Field | What to put |
|---|---|
| Name | Something job-like, e.g. `ticket-triager` |
| Job description | One specific paragraph. Vague = vague results. |
| Toolbox | Start narrow. Only what the job needs. |
| Trigger words | Short phrases that uniquely call this agent, e.g. "triage this ticket" |

✅ **You'll know it worked when:** your new mate's name appears in the left-hand list, and its own chat opens on its own, asking what you'd like it to do.

🧭 **Don't see "New mate"?** Look for a **+** button near the top of the Mates list — same action, different spot depending on whether this is your first mate or not.

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

✅ **You'll see one of two things:** a card asking "Allow this?" with Approve/Deny buttons, or a plain written refusal. Both are a pass — either way, it didn't just do it silently.

🧭 **It just did the task, no prompt at all?** Check Step 4 below — Approval mode may already be on Autopilot from an earlier session.

## Step 4: See the master switch

Open **Settings → Security → Approval mode** (sometimes nicknamed "auto-approve" or "YOLO").

✅ **What you're looking for:** a control with two settings — **Supervised** (default, safer: asks before most actions) and **Autopilot** (skips asking for a set amount of time).

By default, Crew is in **Supervised** mode — what you just saw in Step 3. Switching to **Autopilot** lets it skip asking for a while. Leave it on **Supervised** while your team is still learning what to trust an agent with.

---

## Example prompts to try on your own agent

- "What's your job, in one sentence?"
- "What tools can you use, and what can't you touch?"
- "Here's a real ticket from our backlog — triage it."
- "Why did you ask for approval just now instead of just doing it?"

---

Done with Module 3? → [Module 4 — Connect Your Own Tools](Handson-4-MCP-Connections.md)

← [Back to all modules](README.md)
