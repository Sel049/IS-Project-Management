# Project Plan: Online Course Registration System

## Project Name
Student Course Registration System  
**Start Date:** [Insert actual start date, e.g., 2026-04-15]  
**End Date:** [Insert actual end date, e.g., 2026-06-10] (8 weeks total)

## Work Breakdown Structure (WBS) - UPDATED with dates

### Phase 1: Initiation (Week 1: April 15-21)
- [x] Kickoff meeting with stakeholders (April 16)
- [x] Finalize requirements document (April 18)
- [x] Set up GitHub repository (April 15)
- **[NEW] Create GitHub Project Board with Kanban columns (April 19)**
- **[NEW] Define branch protection rules for main branch (April 20)**

### Phase 2: Design (Weeks 2-3: April 22 - May 5)
- [ ] Create wireframes (login, dashboard, course catalog) - Due May 1
- [ ] Design database schema (students, courses, enrollments) - Due May 3
- [ ] Review design with advisor - Due May 5
- **[NEW] Create mock UI in Figma for stakeholder review**

### Phase 3: Development (Weeks 4-6: May 6 - May 23) - UPDATED (2.5 weeks)
- [ ] Set up frontend (React.js) - Due May 10
- [ ] Implement backend (Node.js/Express) - Due May 16
- [ ] Connect to database (PostgreSQL) - Due May 20
- [ ] Add authentication (login/logout) - Due May 23
- **[NEW] Daily commit requirement: Each team member must push code daily by 6 PM**

### Phase 4: Testing (Weeks 7: May 24-30) - UPDATED (1.5 weeks)
- [ ] Unit testing for each module - Due May 26
- [ ] Integration testing (frontend + backend) - Due May 28
- [ ] Load testing with 500 concurrent users - Due May 29 (NEW)
- [ ] User acceptance testing with 10 volunteer students - Due May 30

### Phase 5: Deployment & Closure (Week 8: May 31 - June 10)
- [ ] Deploy to Render (free tier) - Due June 3
- [ ] Create user manual - Due June 6
- [ ] Final presentation - Due June 9
- [ ] Final report submission - Due June 10

## Resource Allocation (UPDATED with GitHub roles)
| Role | Person | GitHub Responsibility |
|------|--------|----------------------|
| Project Manager | [Name] | Manage Issues, create milestones |
| Lead Developer | [Name] | Review pull requests, merge code |
| Frontend Developer | [Name] | Push daily commits, create branches |
| Tester | [Name] | Create bug issues, verify fixes |

## Milestones & Deadlines (UPDATED with actual dates)
| Milestone | Due Date | Status |
|-----------|----------|--------|
| Requirements approved | April 21 | ✅ Done |
| Design approved | May 5 | 🔄 In Progress |
| Development complete | May 23 | ⏳ Not Started |
| Testing passed | May 30 | ⏳ Not Started |
| Final delivery | June 10 | ⏳ Not Started |

## Daily Commit Requirement (NEW)
- **Minimum 1 commit per team member per day**
- Commit message format: `[Component] Description - Issue #Number`
- Example: `[Login] Fixed password validation - Issue #4`
- **No commit by 6 PM?** Post in team chat with reason

## GitHub Branch Strategy (NEW)
| Branch | Purpose | Protection |
|--------|---------|-------------|
| `main` | Production-ready code | Requires PR approval |
| `develop` | Integration branch | Auto-deploys to staging |
| `feature/*` | Individual features | No restrictions |

## Communication Plan (UPDATED)
- Daily standup: 10 AM (GitHub Discussions or chat)
- Weekly progress report: Every Friday via GitHub Issue (label: `weekly-report`)
- Advisor meeting: Every alternate Wednesday at 2 PM
- **NEW: GitHub Issue assignment:** Every task must have an assignee by Monday 9 AM