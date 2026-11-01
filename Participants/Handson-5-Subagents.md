
# Hands-On 5 — Many Hands, One Ask (Subagents)

**Module 5 of 7** · [All modules](README.md) · Previous: [Module 4](Handson-4-MCP-Connections.md) · Next: [Module 6 — Monitor / Babysit](Handson-6-Monitor-Babysit.md)

---

## Think of it this way

Like sending 3 interns to check 3 buildings at once, instead of walking to each one yourself. One ask, several workers, one combined answer back.

---

## Step 1: Ask for two independent things at once

> **Prompt:** "Research [topic A] and [topic B] at the same time, then give me one combined summary."

## Step 2: Watch what happens

Notice it does not do A, then B. It can split the two into separate background workers that run together, then merges their answers into one reply.

## Step 3: Try it on your own work

> **Prompt:** "Check these 3 files for bugs at the same time: [file 1], [file 2], [file 3]."

## Step 4: Know when NOT to expect this

A single, simple task runs as itself — no parallel workers needed. Parallel work only kicks in when there's more than one independent thing to do.

---

Done with Module 5? → [Module 6 — Monitor / Babysit](Handson-6-Monitor-Babysit.md)
