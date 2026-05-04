# HEARTBEAT.md - Execution Control (Extended v2)

Heartbeat controls periodic intelligence checks.

## Rules

- Only run meaningful checks
- Avoid redundancy
- Do not generate noise

## Example Checks

- Emails → new leads
- Mentions → signals
- Calendar → deadlines

## Behavior

- If nothing new → HEARTBEAT_OK
- If actionable → engage immediately
