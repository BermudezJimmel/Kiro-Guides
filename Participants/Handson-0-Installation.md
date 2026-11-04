
# Installation Guide — Get Kiro Crew Running

**Do this before the session starts.** [All modules](README.md) · Next: [Module 1 — Account & Token Management](Handson-1-Account-Token.md)

---

## Step 1: Download

Open the [Kiro Crew Downloads page](https://github.com/kirodotdev/KiroCrew/releases/latest) and click the file for your OS:

| Your OS | File to click |
|---|---|
| Windows | the file ending in **`Setup-x64.exe`** |
| Mac — Apple Silicon (M1/M2/M3/M4) | the file ending in **`arm64.dmg`** |
| Mac — Intel | the file ending in **`x64.dmg`** |
| Linux | the **`.AppImage`**, **`.deb`**, or **`.rpm`** file |

## Step 2: Install it

- **Windows:** double-click the `.exe`, click through the installer.
- **Mac:** double-click the `.dmg`, drag Kiro Crew into Applications.
- **Linux:** make the `.AppImage` executable and run it, or `dpkg -i` the `.deb` / `rpm -i` the `.rpm`.

## Step 3: Open it, sign in

Open **Kiro Crew** from your Start Menu / Applications, like any other app.

First launch shows a **Set up Kiro** page. Follow it — it signs you in and finishes setup for you. No terminal needed.

**No Kiro account yet?** On that same page, choose **Sign up**. Pick **Google**, **GitHub**, or **AWS Builder ID** — no AWS account or credit card needed. Google is usually the fastest for a first-time sign-up.

**New to Kiro entirely?** Watch this first: [Kiroween 2026 — Kiro Crew, CLI, Web, and IDE in one video](https://www.youtube.com/watch?v=PO3M2TKCUb0) (about 6 minutes).

## Step 4: Check it worked

Look at the dashboard. If you see your name and a chat box ready to type in, you're ready for Module 1. Nothing else to check.

---

**Prefer the terminal?** These lines do everything above at once:
```
curl -fsSL https://download.crew.kiro.dev/cli.sh | sh
kiro-cli login     # sign in the backend FIRST — the gateway checks for this on startup
kirocrew setup
```

> **Note:** the GUI "Set up Kiro" page (Step 3 above) handles this sign-in for you. The `kiro-cli login` line only matters for the terminal path — run it before `kirocrew setup` or setup stalls with no backend signed in.

Next: [Module 1 — Account & Token Management](Handson-1-Account-Token.md)
