# MEMORY.md - Long-Term Memory

_Curated memories, decisions, and context that matter beyond daily logs._

## Current Project Context

**OpenProject Project:** kaironinv-dot-ai (ID: 3)
**Project Role:** Business Analyst (Metric) - bridge between PM (Alice) and dev team

### Key Stakeholders
- **Boss** - Leads organization, key business stakeholder
- **Alice (Product Manager)** - Defines product vision and strategy
- **Development Team** - Builds features based on User Stories

### Current Project Phase
- **Phase 1A:** Verified Research Diary MVP
  - EPIC #37: Trial & Engagement Validation
  - Feature #39: Tier Management System
  - Feature #40: Usage Tracking & Limits
- **Phase 1B:** Payments (deferred)
  - Feature #38: Payment Gateway Integration
  - Feature #41: Billing Dashboard
  - Feature #42: Upgrade/Downgrade Flows

### R&R Structure (March 10 Update)
- **PM (Alice):** EPICs (strategic initiatives) → Features (business outcomes, success metrics)
- **Dev Team:** User Stories (with ACs) → Tasks (technical breakdown)
- **BA (Metric):** Bridges between PM and Dev, ensures alignment

### Key Wiki Pages
- Product Overview - Master overview and phase coordination
- Product Vision - Core values, positioning, success definition
- Product Strategy - Strategic principles, risk mitigation, success metrics
- Product Phase 1: Verified Research Diary MVP - Detailed Phase 1A specs
- Decisions - Log of key product decisions
- R&R Update: EPIC & Features Focus - Latest R&R structure

### Pending Decisions (as of March 15)
- Feature #40: Preview Limited Tier button timing & export deadline
- EPIC #37: Trial cancellation policy

## Key System Updates

### 2026-03-15: MEMORY.md Creation & Core Context File Protection
- Created MEMORY.md as long-term curated memory storage (was missing)
- Added MEMORY.md as protected core context file across all documentation
- Updated security protocols to prevent deletion of core context files
- Core context files now include: AGENTS.md, SOUL.md, TOOLS.md, WORKFLOW.md, IDENTITY.md, USER.md, HEARTBEAT.md, MEMORY.md, OPENPROJECT.md, OWNED_SKILLS.md
- Backed up updated files to GitHub repositories

### 2026-03-15: Repository Backup Restoration
- Restored access to metric-aiba-core-context GitHub repository
- Updated GITHUB_TOKEN in .env with updated credentials
- Successfully uploaded core context to https://github.com/mamkkl/metric-aiba-core-context
- Uploaded updated runbooks to https://github.com/mamkkl/openclaw-workspace-initial-runbooks

### 2026-03-15: Self-Improvement Protocol Enforcement
- **Critical bug identified:** 3-layer self-improvement architecture was being violated
- Layer 1 (on-the-fly capture) was not being followed during conversations
- Boss corrections were only logged when explicitly asked to run self-improvement
- Updated core context to document 3-layer architecture explicitly:
  - HEARTBEAT.md: Added 3-layer architecture diagram (later cleaned up)
  - SOUL.md: Added self-improvement discipline section
  - AGENTS.md: Integrated 3-layer into memory section
  - SECURITY_PROTOCOL_RUNBOOK.md: Connected User Correction Protocol to Layer 1
  - Added LRN-20260315-006 documenting this violation and prevention
- LRN-20260315-006: Self-improvement protocol violation documented
- **Protocol enforced:** Layer 1 (on-the-fly) is primary; Layers 2/3 are safety nets
- **Cleaned up HEARTBEAT.md:** Removed 3-layer architecture diagram (Layer 2 should focus on execution, not architecture)

### 2026-03-15: Created SELF_IMPROVEMENT_RUNBOOK.md
- Comprehensive guide for setting up 3-layer self-improvement framework
- Includes architecture diagrams, setup instructions, patterns, templates
- Document troubleshooting guidance, integration checklists, best practices
- Purpose: New agents can implement continuous learning from Day 1
- **Uploaded to:** https://github.com/mamkkl/openclaw-workspace-initial-runbooks.git (commit 82df39b, updated 6e73200)
- **Location:** runbooks/SELF_IMPROVEMENT_RUNBOOK.md (25,425 bytes, updated with dependencies)
- Includes Layer 1 (User Correction Protocol), Layer 2 (Heartbeat), Layer 3 (Daily Promotion)
- **Dependency Added:** self-improving-agent skill (https://clawhub.ai/pskoett/self-improving-agent)
- Installation: `npx clawhub install self-improving-agent`
- **Critical bug identified:** 3-layer self-improvement architecture was being violated
- Layer 1 (on-the-fly capture) was not being followed during conversations
- Boss corrections were only logged when explicitly asked to run self-improvement
- Updated core context to document 3-layer architecture explicitly:
  - HEARTBEAT.md: Added 3-layer architecture diagram
  - SOUL.md: Added self-improvement discipline section
  - AGENTS.md: Integrated 3-layer into memory section
  - SECURITY_PROTOCOL_RUNBOOK.md: Connected User Correction Protocol to Layer 1
- LRN-20260315-006: Self-improvement protocol violation documented
- **Protocol enforced:** Layer 1 (on-the-fly) is primary; Layers 2/3 are safety nets
- Restored access to metric-aiba-core-context GitHub repository
- Updated GITHUB_TOKEN in .env with updated credentials
- Successfully uploaded core context to https://github.com/mamkkl/metric-aiba-core-context
- Uploaded updated runbooks to https://github.com/mamkkl/openclaw-workspace-initial-runbooks
- Feature #40: Preview Limited Tier button timing & export deadline
- EPIC #37: Trial cancellation policy

## Security Protocols

**MEMORY.md Security:**
- ONLY load in main sessions (direct chats with Boss)
- NEVER load in shared contexts (Discord, group chats)
- This file is private context - protect accordingly
- **Deletion Protection:** MEMORY.md is a core context file. Never delete without explicit Boss approval (see SECURITY_PROTOCOL_RUNBOOK.md for details)

### 2026-03-16: Core Context Repository Cleanup & Human Approval Requirement Formalization
- Scanned metric-aiba-core-context repository and removed unauthorized files
- **Removed items:** 2026-03-15.md, LEARNINGS.md, README.md, SECURITY.md, memory/ directory, tools/ directory
- **Restored:** README.md for repository documentation
- **Final repository contents:** 10 core context files + README.md
- **Added explicit human approval requirement for core context additions/updates:**
  - Core Principles: Added "modify" to deletion protection, added "Core context additions require approval" policy
  - Ask first section: Expanded to include adding/updating core context files
  - Exception: Approved `.maintenance/daily/` suggestion workflow where drafts are created, reviewed, and approved
  - This formalizes compliance with "adding core context requires human approval" rule
- **Changes pushed to:** https://github.com/mamkkl/metric-aiba-core-context (commit 4ff928d)

---

_Last updated: 2026-03-16_
