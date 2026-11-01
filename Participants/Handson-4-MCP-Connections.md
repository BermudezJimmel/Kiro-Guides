
# Hands-On 4 — Connect Your Own Tools (MCP)

**Module 4 of 7** · [All modules](README.md) · Previous: [Module 3](Handson-3-Agent-Creation.md) · Next: [Module 5 — Subagents](Handson-5-Subagents.md)

---

## Think of it this way

MCP is the plug. Jira, AWS, GitHub, your own internal API — each connects through one. Crew itself never changes; what you plug into it does.

---

## Step 1: See what you have before connecting anything

> **Prompt:** "What tools and connections do you currently have access to?"

Remember the answer — you'll compare it after Step 2.

## Step 2: Add a connection

Open **Customize → Connections → MCP Servers → Add Server**. Pick one from the directory, or **Add Custom** for something internal to DBP.

## Step 3: Ask the same question again

> **Prompt:** "What tools and connections do you have access to now?"

The new one should show up. Every agent on this gateway can now use it — you wire it once, not per agent.

## Step 4: Use it

> **Prompt:** "Using [the tool you just connected], [a real small task]."

---

Done with Module 4? → [Module 5 — Subagents](Handson-5-Subagents.md)
