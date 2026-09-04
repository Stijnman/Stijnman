# Repository Audit & Analysis Prompt

## 🔍 Comprehensive Repository Investigation & Improvement Guide

This prompt is designed to systematically analyze each repository in the Stijnman GitHub profile and generate actionable improvement tasks with scheduling capabilities.

---

## 📋 AUDIT EXECUTION TEMPLATE

### Phase 1: Repository Discovery & Enumeration
```
TASK: Scan all repositories in github.com/Stijnman
- List repository names
- Identify project status (Active, Archived, In-Development)
- Note repository descriptions
- Track last commit dates
```

### Phase 2: Deep Repository Analysis

For each repository discovered, perform the following analysis:

#### 2.1 Project Structure Assessment
```
Analyze:
- README.md presence & quality
- Documentation completeness
- File organization & hierarchy
- Configuration files (.gitignore, .env.example, etc.)
- License file presence
- Contributing guidelines
```

#### 2.2 Code Quality Review
```
Evaluate:
- Code consistency
- Comment coverage
- Error handling implementation
- Testing infrastructure (unit tests, integration tests)
- Linting configuration (ESLint, Prettier, etc.)
- Type safety (TypeScript, JSDoc, etc.)
```

#### 2.3 Dependencies & Security
```
Check:
- package.json/requirements.txt currency
- Vulnerable dependencies
- Version pinning practices
- Dependency documentation
```

#### 2.4 Documentation Gaps
```
Identify Missing:
- Installation instructions
- Usage examples
- API documentation
- Environment setup guide
- Troubleshooting section
- Contribution guidelines
- Architecture/design documentation
```

#### 2.5 Project Metadata
```
Verify:
- Description clarity
- Topics/tags relevance
- Repository visibility settings
- Branch protection rules
- Issues template
- PR template
```

---

## 🎯 IMPROVEMENT INSTRUCTION GENERATION

### Output Format: Actionable Task Checklist

```markdown
## Repository: [REPO_NAME]
**Status**: [Active/In-Development/Needs-Work]
**Last Update**: [DATE]
**Priority Level**: [Critical/High/Medium/Low]

### 📝 Documentation Tasks
- [ ] Task 1: [Specific action needed]
  - Details: [What needs to be done]
  - Priority: [P1/P2/P3]
  - Est. Time: [Time estimate]

### 🛠️ Code Quality Tasks
- [ ] Task 2: [Specific action needed]
  - Details: [What needs to be done]
  - Priority: [P1/P2/P3]
  - Est. Time: [Time estimate]

### 🔒 Security & Dependencies Tasks
- [ ] Task 3: [Specific action needed]
  - Details: [What needs to be done]
  - Priority: [P1/P2/P3]
  - Est. Time: [Time estimate]

### 📚 Missing Features/Content
- [ ] Task 4: [Specific action needed]
  - Details: [What needs to be done]
  - Priority: [P1/P2/P3]
  - Est. Time: [Time estimate]

### 📅 Recommended Schedule
**Week 1**: [Priority P1 tasks]
**Week 2**: [Priority P2 tasks]
**Week 3-4**: [Priority P3 tasks]
**Ongoing**: [Maintenance tasks]
```

---

## 📅 SCHEDULED IMPROVEMENT CALENDAR

### Quick Reference Format:
```
REPOSITORY IMPROVEMENT SCHEDULE - Q4 2026

📦 Repository: [NAME]
├── Week 1 (Sept 4-10)
│   ├── ✅ Complete: [Task]
│   ├── ⏳ In-Progress: [Task]
│   └── 📋 Scheduled: [Task]
├── Week 2 (Sept 11-17)
│   └── [Tasks]
└── Week 3-4 (Sept 18-Oct 2)
    └── [Tasks]
```

---

## 🤖 AI-ASSISTED INSTRUCTION PROMPT

Use this prompt with LLMs to generate improvement instructions:

```
You are a technical documentation and code quality specialist. 

Analyze the following GitHub repository:
- Repository Name: [NAME]
- Repository URL: [URL]
- Description: [DESC]

Perform a comprehensive audit covering:
1. Documentation quality and completeness
2. Code organization and standards
3. Missing README sections
4. Broken links or outdated content
5. Missing tests or test documentation
6. Security vulnerabilities or dependency issues
7. Architecture documentation gaps
8. Contributing guidelines completeness

Generate a prioritized checklist of specific, actionable improvements with:
- Clear task descriptions
- Implementation steps
- Estimated time to complete
- Dependencies (if any)
- LLM assistance opportunities (where AI can help)

Format output as a scheduled roadmap for the next 4 weeks.
```

---

## 📊 AUDIT SUMMARY DASHBOARD

After running audits on all repositories, generate:

```
STIJNMAN GITHUB PORTFOLIO HEALTH REPORT
═══════════════════════════════════════

📈 Overall Status: [Excellent/Good/Needs-Work/Critical]

📦 Repositories Analyzed: [X]
├── ✅ Well-Maintained: [X]
├── ⚠️ Needs-Updates: [X]
└── 🔴 Critical-Issues: [X]

📋 Total Improvement Tasks: [X]
├── 🔴 Critical (P1): [X]
├── 🟠 High (P2): [X]
└── 🟡 Medium (P3): [X]

⏱️ Estimated Total Effort: [X hours]

📅 Recommended Focus Areas:
1. [Area 1]
2. [Area 2]
3. [Area 3]

🤖 AI-Ready Tasks (for LLM acceleration):
- [Task 1]
- [Task 2]
- [Task 3]
```

---

## 🚀 EXECUTION WORKFLOW

1. **Run Discovery**: Execute Phase 1 to find all repos
2. **Deep Dive**: Run Phase 2 analysis on each repo
3. **Generate Tasks**: Create specific improvement checklists
4. **Schedule**: Map tasks to calendar weeks
5. **Execute**: Work through prioritized tasks
6. **Track**: Update progress in scheduled checklist
7. **Review**: Monthly audit updates

---

## 📌 USAGE INSTRUCTIONS

To use this prompt with Copilot or other LLMs:

1. Copy the relevant section (Discovery, Analysis, or Generation)
2. Provide repository URL or name
3. Request specific output format (Checklist, Calendar, Dashboard)
4. Ask for LLM-assisted enhancements
5. Track completed tasks in the scheduled calendar

**Example Command**:
```
@copilot Analyze all my repositories and generate a 4-week improvement 
schedule with specific tasks, priorities, and time estimates. Include 
opportunities for AI-assisted completion.
```

---

*This prompt enables continuous portfolio improvement through systematic analysis and AI-powered enhancements.*
