# Risk Management Plan

## Project: Online Course Registration System

| Risk ID | Risk Description | Probability (1-5) | Impact (1-5) | Risk Score (P×I) | Mitigation Strategy | Contingency Plan | Owner |
|---------|----------------|------------------|--------------|------------------|---------------------|------------------|-------|
| R1 | Team member drops course | 3 | 5 | 15 | Cross-train all members on each module | Redistribute tasks; hire a backup from another team | PM |
| R2 | GitHub merge conflicts due to simultaneous edits | 4 | 3 | 12 | Use branch protection rules; daily pull before coding | Revert to last stable commit; use diff tool | Lead Developer |
| R3 | Server downtime during testing | 2 | 4 | 8 | Use local development environment first | Switch to backup cloud server (AWS free tier) | Developer |
| R4 | Students reject UI as difficult | 3 | 4 | 12 | Conduct early prototype demo in Week 2 | Redesign based on feedback; add tooltips | Designer |
| R5 | Database corruption | 1 | 5 | 5 | Daily automated backups | Restore from previous night's backup | Developer |
| R6 | Registration peak load (1000+ students) | 4 | 4 | 16 | Load testing with JMeter; optimize queries | Queue system + auto-scaling | Tester |

## Risk Response Summary
- **High risks (score > 12):** R1, R6 → Need immediate mitigation
- **Medium risks (score 8-12):** R2, R4 → Monitor weekly
- **Low risks (score < 8):** R3, R5 → Accept, but have contingency

## Risk Monitoring
- Review all risks every **Friday** during team meeting
- Update this document with new risks via GitHub Issues (label: `risk`)
- Risk status reported in weekly progress report

## Tools for Risk Tracking
- GitHub Issues for individual risks
- Excel/Google Sheets backup for history