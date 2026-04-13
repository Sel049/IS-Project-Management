# Risk Management Plan

## Project: Online Course Registration System

| Risk ID | Risk Description | Probability (1-5) | Impact (1-5) | Risk Score (P×I) | Mitigation Strategy | Contingency Plan | Owner | Status (NEW) |
|---------|----------------|------------------|--------------|------------------|---------------------|------------------|-------|--------------|
| R1 | Team member drops course | 3 | 5 | 15 | Cross-train all members on each module | Redistribute tasks; hire a backup from another team | PM | **Active - being monitored** |
| R2 | GitHub merge conflicts due to simultaneous edits | 4 | 3 | 12 | Use branch protection rules; daily pull before coding | Revert to last stable commit; use diff tool | Lead Developer | Active |
| R3 | Server downtime during testing | 2 | 4 | 8 | Use local development environment first | Switch to backup cloud server (AWS free tier) | Developer | Low |
| R4 | Students reject UI as difficult | 3 | 4 | 12 | Conduct early prototype demo in Week 2 | Redesign based on feedback; add tooltips | Designer | Active |
| R5 | Database corruption | 1 | 5 | 5 | Daily automated backups | Restore from previous night's backup | Developer | Low |
| R6 | Registration peak load (1000+ students) | 4 | 4 | 16 | Load testing with JMeter; optimize queries | Queue system + auto-scaling | Tester | **Active - High priority** |
| **R7 (NEW)** | **GitHub issue tracking ignored by team** | **3** | **4** | **12** | **Daily 5-min issue review in standup** | **Send reminders via WhatsApp/Teams** | **PM** | **New - Needs attention** |
| **R8 (NEW)** | **Advisor provides late feedback on deliverables** | **3** | **3** | **9** | **Submit drafts 3 days before deadline** | **Use peer review as fallback** | **PM** | **New** |

## Risk Response Summary (UPDATED)
- **High risks (score > 12):** R1, R6 → Immediate mitigation plan in place
- **Medium risks (score 8-12):** R2, R4, R7 → Review every Monday and Thursday
- **Low risks (score < 8):** R3, R5 → Accept, but have contingency

## Risk Monitoring (UPDATED with dates)
- ~~Review every Friday~~ → **NEW: Review every Monday and Thursday**
- Update this document with new risks via GitHub Issues (label: `risk`)
- **Next risk review meeting:** [Insert next Monday's date]
- **Risk audit completed by:** [Name] on [Date]

## Recent Risk Updates (NEW SECTION)
| Date | Risk ID | Update |
|------|---------|--------|
| [Today's Date] | R7 | Created after team missed 2 issue updates |
| [Today's Date] | R6 | Load test scheduled for next Friday |
| [Yesterday's Date] | R1 | Team member confirmed attendance for full semester |

## Tools for Risk Tracking
- GitHub Issues for individual risks
- Excel/Google Sheets backup for history
- **NEW:** Slack/Teams channel #risk-alerts for real-time notifications