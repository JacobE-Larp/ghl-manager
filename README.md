# ghl-manager

> OpenClaw skill for full GoHighLevel (GHL) management — built for fitness coaching businesses.

## What it does

Turns your OpenClaw agent into a GHL operations manager that can:

- **Inspect** your entire GHL account before making changes
- **Build** automations, pipelines, and workflows from natural language requests
- **Modify** existing systems safely (clone → modify → replace)
- **Diagnose & repair** broken workflows, failed SMS/email, pipeline issues
- **Prevent** duplicates and accidental deletions

## Example prompts

- "Build a no-show follow-up"
- "Create a 12-week check-in automation"
- "Fix why my reminders aren't firing"
- "Create a nurture sequence for new leads"
- "Set up client onboarding after payment"

## Install

### From ClawHub

```bash
clawhub install ghl-manager
```

### Manual

Copy the `SKILL.md` file into your OpenClaw skills directory:

```bash
cp SKILL.md ~/.openclaw/skills/ghl-manager/SKILL.md
```

## Requirements

- An OpenClaw instance with access to your GHL account (via browser control or direct login)

## Systems covered

| System | Flow |
|---|---|
| Lead Capture | Lead form → book call |
| Sales | Call booking → reminders |
| Client Onboarding | Payment → onboarding form |
| Client Engagement | Weekly check-ins |
| Retention | Inactivity detection |
| Cancellation Save | Exit call offer |
| Reactivation | Return offer after 30 days |

## Publishing to ClawHub

```bash
clawhub login
clawhub publish ./ghl-manager --slug ghl-manager --name "GHL Manager" --version 1.0.0 --changelog "Initial release"
```

## License

MIT
