# Conversation Metadata Template

## Overview
This template captures ALL context relevant to the current conversation - files, decisions, searches, links, knowledge, insights, and any information critical to understanding and continuing this discussion.

## Purpose
- **Complete Context Capture**: Everything relevant to this conversation in one place
- **Quick Context Loading**: Link this file to Claude to instantly understand current state
- **Decision Preservation**: Track why choices were made and alternatives considered
- **Session Continuity**: Enable seamless pickup where conversation left off
- **Context Recovery**: Never lose important information when context runs out

## Template Structure

```markdown
# Conversation [XXX] Metadata

## Quick Start
*For new Claude sessions: "Read this metadata file to understand complete context and continue this conversation seamlessly."*

## Conversation Summary
**Purpose**: [What this conversation is trying to accomplish]
**Current Focus**: [What we're working on right now]
**Duration**: [Start date - End date or ongoing]
**Status**: [Active/Paused/Completed/Blocked]

## Critical Context
*The most important information to understand this conversation*

**Main Problem**: [Core issue being solved]
**Current Approach**: [How we're tackling it]
**Key Constraints**: [Important limitations or requirements]
**Success Criteria**: [How we'll know we're done]

## Files & Code
*Everything file-related in this conversation*

### Modified Files
- **`path/to/file.ext`**
  - **Changes**: [What changed and why]
  - **Impact**: [How this affects the overall goal]
  - **Status**: [Done/In Progress/Needs Review]

### Read/Analyzed Files
- **`path/to/file.ext`**: [Why we looked at this and what we learned]
- **`path/to/file.ext`**: [Context and insights gained]

### Created Files
- **`path/to/file.ext`**: [Purpose and how it fits the solution]

## Knowledge & Insights
*All knowledge applied and discovered*

### Applied Knowledge
- **[KNOWLEDGE_CODE]**: [How existing knowledge was used]
- **[KNOWLEDGE_CODE]**: [Context for applying this knowledge]

### New Discoveries
- **[NEW_INSIGHT]**: [What we learned and why it matters]
- **[PATTERN_FOUND]**: [New pattern discovered and its implications]
- **[SOLUTION_APPROACH]**: [New approach that worked/didn't work]

## Searches & Research
*Web searches, documentation lookups, investigations*

- **"[search query]"**: [What we were looking for and what we found]
- **[Documentation URL]**: [Why we checked this and key takeaways]
- **[Investigation topic]**: [What we researched and conclusions]

## External Resources
*Links, tools, references used*

- **[URL/Tool]**: [Purpose and key information gained]
- **[Documentation/Guide]**: [How this helped solve the problem]
- **[Reference Material]**: [Why this was relevant]

## Decisions Made
*All important choices and their rationale*

1. **[Decision]**: 
   - **Rationale**: [Why we chose this]
   - **Alternatives**: [What else we considered]
   - **Impact**: [How this affects the project]

2. **[Decision]**:
   - **Context**: [Situation that required this choice]
   - **Trade-offs**: [What we gained/lost with this decision]

## Problems & Solutions
*Issues encountered and how they were resolved*

### Solved Problems
- **[Problem]**: [How we fixed it and lessons learned]
- **[Error/Issue]**: [Root cause and solution applied]

### Current Blockers
- **[Blocker]**: [Why this is blocking progress and potential solutions]
- **[Uncertainty]**: [What we need to figure out]

## Current State
*Where things stand right now*

**What's Working**: [Progress made and successful approaches]
**What's Not Working**: [Current challenges or failed attempts]
**Next Critical Step**: [Most important thing to do next]
**Open Questions**: [Things we need to resolve]

## Context for Continuation
*Everything needed to pick up where we left off*

**Mental Model**: [How to think about this problem]
**Current Strategy**: [Our approach and why]
**Key Files to Load**: [Most important files for immediate context]
**Background Context**: [Important history or context to remember]
**Watch Out For**: [Pitfalls or issues to be aware of]
```

## Usage Instructions

1. **Create for each conversation**: Copy this template to `conversations/conversation_XXX/metadata.md`
2. **Update continuously**: Add context as it becomes relevant - don't wait until the end
3. **Capture everything**: Searches, insights, failed attempts, decisions, alternatives considered
4. **Focus on "why"**: Not just what happened, but why it matters and how it affects the goal
5. **Enable quick continuation**: Write so future Claude can instantly understand and continue
6. **Be comprehensive**: Better to over-document than lose critical context