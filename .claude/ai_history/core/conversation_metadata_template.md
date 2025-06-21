# Conversation Metadata Template

## Overview
This template creates a metadata file for each conversation folder that tracks all relevant files, links, and knowledge referenced during the conversation. This enables quick context loading in future sessions.

## Purpose
- **Quick Context Loading**: Link this file to Claude to auto-load all relevant files
- **File Change Tracking**: Document how files evolved during the conversation
- **Knowledge Mapping**: Connect conversation to specific project knowledge
- **Session Continuity**: Enable easy pickup where conversation left off

## Template Structure

```markdown
# Conversation [XXX] Metadata

## Quick Start
*For new Claude sessions: "Read this metadata file and load all referenced files and knowledge."*

## Conversation Summary
**Purpose**: [Brief description of what this conversation accomplished]
**Duration**: [Start date - End date or ongoing]
**Status**: [Completed/Ongoing/Paused]

## Files Referenced
*All files that were read, modified, or created during this conversation*

### Modified Files
- **`path/to/file.ext`**
  - **Changes**: [Brief description of what changed]
  - **Why**: [Reason for changes]
  - **Status**: [Completed/In Progress/Needs Review]

### Read Files
- **`path/to/file.ext`**: [Why this file was relevant]
- **`path/to/file.ext`**: [Context for reading this file]

### Created Files
- **`path/to/file.ext`**: [Purpose of new file]
- **`path/to/file.ext`**: [What this file does]

## Knowledge Applied
*Reference codes from project_knowledge.md that were used*

- **[KNOWLEDGE_CODE_01]**: [How it was applied in this conversation]
- **[KNOWLEDGE_CODE_02]**: [Context for using this knowledge]

## New Knowledge Created
*Knowledge discovered during this conversation - also add to project_knowledge.md*

### [NEW_KNOWLEDGE_CODE]: [Knowledge Title]
- **When was this created**: [Context of discovery during this conversation]
- **Use case**: [USE_CASE_TAG]
- **Content**: [Brief knowledge summary]
- **Applied to**: [Which files or decisions this knowledge affected]

## External References
*Links, documentation, or resources referenced*

- **[URL/Resource]**: [Why this was referenced]
- **[Documentation link]**: [How this helped the conversation]

## Key Decisions
*Important decisions made during this conversation*

1. **[Decision]**: [Rationale and impact]
2. **[Decision]**: [Context and alternatives considered]

## Next Steps
*What should happen next or what was left incomplete*

- [ ] [Task or follow-up item]
- [ ] [Pending decision or work]

## Context for Future Sessions
*Critical information for continuing this work*

**Current State**: [Where things stand now]
**Key Files to Load**: [Most important files for context]
**Active Concerns**: [Issues or challenges to keep in mind]
```

## Usage Instructions

1. **Create for each conversation**: Copy this template to `conversations/conversation_XXX/metadata.md`
2. **Update throughout conversation**: Keep metadata current as work progresses
3. **Use for session continuity**: Link this file when starting new sessions
4. **Reference for knowledge**: Connect to specific project knowledge codes
5. **Track file evolution**: Document how files changed and why