---
name: Generate Idynic Story
about: Generate a professional story from codebase contributions for your idynic profile
title: "[STORY] Generate story from [REPO NAME] contributions"
labels: story-generation
---

## Generate Idynic Story from Codebase

Use this template to have Claude Code analyze your contributions to a repository and generate a professional story suitable for your idynic profile.

### Instructions

1. Open Claude Code in the target repository
2. Copy the prompt below and paste it
3. Replace `<your-email>` with your git commit email
4. Review and refine the generated story
5. Upload to idynic

---

## Prompt

```
Analyze this codebase to write a professional story about my contributions.

**RESEARCH PHASE** (do this first):
1. Run `git log --author="<your-email>" --oneline -50` to see my commits
2. Look at significant PRs I authored (use GitHub MCP if available)
3. Identify the major features, fixes, or systems I built
4. Note the technologies used and architectural decisions made

**GENERATE A STORY** (500-800 words, first person) that includes:

### 1. The Challenge/Context
- What problem was being solved? Why did it matter?
- Business context, scale, constraints
- Company/project background

### 2. Measurable Accomplishments
Extract concrete metrics from commits/PRs:
- Features shipped, bugs fixed, performance improvements
- Systems built, integrations completed
- Timeline (when did this work happen?)

### 3. Technical Depth
What technologies did I use and HOW?
- Languages, frameworks, cloud services
- Architectural patterns (event-driven, microservices, etc.)
- Specific technical challenges overcome

### 4. Leadership/Collaboration (if visible)
- Code reviews given/received
- Cross-team coordination
- Documentation, mentoring, process improvements

### 5. Traits Demonstrated
Infer from the work itself:
- Initiative (started new projects?)
- Quality focus (test coverage, refactoring?)
- Problem-solving (debugging, incident response?)
- Resilience (difficult migrations, tight deadlines?)

**OUTPUT REQUIREMENTS**:
- First-person narrative voice
- Specific metrics, dates, and technologies
- Show skills through actions, don't just list them
- Include company/role context
- Suitable for uploading to idynic

**EXAMPLE OPENING**:
"At [Company] (2021-2023), I was brought in to tackle their struggling [system]. Within [timeframe], I had [specific accomplishment], using [technologies], which resulted in [measurable impact]..."
```

---

## Tips for Better Stories

**The idynic extraction system looks for:**
- ✅ Quantified impact (percentages, users, revenue, timeline)
- ✅ Technologies demonstrated in context (not just listed)
- ✅ Traits shown through behavior (not self-described)
- ✅ Role/company/date context

**Avoid:**
- ❌ Generic statements without evidence
- ❌ Listing skills without showing usage
- ❌ Vague accomplishments ("improved things")
- ❌ Self-praise without backing ("I'm a great leader")

---

## After Generation

1. Review the story for accuracy
2. Add any context Claude couldn't see (business impact, team dynamics)
3. Upload to [idynic.com](https://idynic.com)
4. Your story will be processed to extract skills, achievements, and attributes
