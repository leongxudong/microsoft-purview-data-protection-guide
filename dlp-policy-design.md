# DLP Policy Design

Data Loss Prevention policies help detect and control risky handling of sensitive information.

## Policy Design Areas

| Area | Design Question |
|---|---|
| Location | Should the policy apply to Exchange, SharePoint, OneDrive, Teams, endpoint, or all supported locations? |
| Data type | Which sensitive information types should be monitored? |
| Condition | What activity should trigger the policy? |
| Action | Should the policy audit, warn, block, or allow override? |
| User notification | What should the user see when the policy triggers? |
| Incident report | Who should receive alerts or reports? |

## Rollout Approach

1. Start in test mode.
2. Review policy matches.
3. Tune conditions and exceptions.
4. Enable user notifications.
5. Move to enforcement in phases.
6. Review impact and false positives.

## Screenshot Placeholder

Add screenshots later:

```text
screenshots/purview-dlp-policy-list.png
screenshots/purview-dlp-test-mode-policy.png
screenshots/purview-activity-explorer-sample.png
```
