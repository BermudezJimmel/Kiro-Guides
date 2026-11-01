
# Hands-On 2 — Kiro Crew: How It Works

**Module 2 of 3** · [All modules](README.md) · Previous: [Module 1](Handson-1-Account-Token.md) · Next: [Module 3 — Agent Creation](Handson-3-Agent-Creation.md)

---

## Think of it this way

Kiro Crew is **one always-on process** (the Gateway). The dashboard, the desktop app, and Slack/Discord are all just windows into that same process. Closing the dashboard tab does not stop anything running inside it.

---

## Step 1: Ask it to read something real

In the chat, type:

> **Prompt:** "Open [a real file from your project] and summarize it in 3 bullets."

Watch it actually open and read the file — not a toy example.

## Step 2: Set up a scheduled job — two ways, pick one

**Easiest — just ask for it in chat:**

> **Prompt:** "Every Monday at 9am, summarize my open DBP tasks."

That sentence alone creates the scheduled job. No form to fill.

**Or use the form:** open the **Schedule** page → **New Schedule** → fill in Name, Message, and the time → **Save**.

## Step 3: Run it now, don't wait for Monday

On the **Schedule** page, click your new job to open it, then press **Run Now**.

Watch the result come back immediately.

## Step 4: Notice what it does NOT know

Type:

> **Prompt:** "Check our production AWS account and tell me if anything looks wrong."

Notice it either gives a generic answer or tells you it has no tool wired in for that. **Capability only exists if the right tool/credential is actually connected — it is not automatic.**

**Good to know:** Crew's security is several layers deep (approval prompts, denied commands, sandboxing, audit logging, and more) — every action is logged, not just trusted silently.

---

Done with Module 2? → [Module 3 — Agent Creation](Handson-3-Agent-Creation.md)
