# Data Classification Model

This page outlines a simple data classification model for Microsoft Purview planning.

## Classification Levels

| Level | Description | Example Handling |
|---|---|---|
| Public | Approved for public release | No special restriction |
| Internal | Internal business information | Keep within organization |
| Confidential | Sensitive business or personal data | Restrict sharing and apply stronger controls |
| Restricted | Highly sensitive or regulated data | Limit access, monitor sharing, and require approval |

## Design Questions

- What data types require protection?
- Which departments handle sensitive information?
- What labels should users understand easily?
- Which labels should apply encryption or access restrictions?
- Where should DLP policies apply: Exchange, SharePoint, OneDrive, Teams, or endpoint?

## Evidence to Capture

- Classification model
- Label list
- Label settings
- DLP policy test results
- User notification examples
