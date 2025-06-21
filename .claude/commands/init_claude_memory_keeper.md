---
description: Initialize Claude Memory Keeper system - loads template into memory, understands structure, and activates intelligent workflows
---

# Initialize Claude Memory Keeper System

## Your Task
You are activating the Claude Memory Keeper system. This command loads the complete template structure into your memory and establishes the intelligent workflow system.

## Step 1: Load Core System Files
Read and understand these essential files:

**System Integration:**
- @.claude/CLAUDE.md
- @.claude/ai_history/CLAUDE.md  
- @.claude/claude_code/CLAUDE.md
- @.claude/commands/CLAUDE.md
- @.claude/sub-agent-tasks/CLAUDE.md

**Core Templates & Instructions:**
- @.claude/ai_history/core/tracking_instructions.md
- @.claude/ai_history/core/project_knowledge_template.md
- @.claude/claude_code/claude_md_principles.md
- @.claude/claude_code/settings.md

**Configuration:**
- @.claude/settings.json

## Step 2: System Understanding Verification
After reading all files, state your understanding:

**Template Structure:**
- Explain the hierarchy: Root → .claude/ → subfolders
- Describe each subfolder's purpose and key files
- Confirm the integration flow between components

**Key Capabilities:**
- Context-aware knowledge management with reference codes
- Strategic delegation with sub-agent task outputs
- Custom slash command automation
- Living memory evolution through usage

**Operational Principles:**
- "Context is King" - comprehensive context gathering before execution
- Lean CLAUDE.md design (20-35 lines max)
- Explicit file paths always (`.claude/subfolder/file`)
- User approval required for sub-agent output usage

## Step 3: System Activation
Confirm you understand:
- How to create `project_knowledge.md` from template when needed
- When and how to save conversations in `conversations/` folders
- How to use reference codes and context evaluation
- Strategic delegation patterns with structured outputs
- Cross-component integration workflows

## Step 4: Mandatory Project Discovery & Root File Update
**CRITICAL**: The root CLAUDE.md MUST be updated before proceeding with any work.

### Project Discovery Process:
1. **Read root CLAUDE.md** - Confirm it contains template content
2. **Ask USER these required questions**:
   - "What is the main purpose and goals of this project?"
   - "What technology stack are you using?"
   - "What are the key challenges you're facing?"
   - "What's the current status/stage of the project?"
   - "Any specific working preferences or conventions I should know?"

3. **Update root CLAUDE.md** - Replace template sections with discovered information:
   - Project Overview (objective, tech stack, challenges, status)
   - User Preferences & Working Style
   - Technical Context specific to this project
   - Any domain-specific knowledge

4. **Verify update** - Confirm root CLAUDE.md now contains project-specific content
5. **Only then begin normal work** - Apply memory keeper system to actual project tasks

### Validation Check:
- [ ] Root CLAUDE.md contains real project information (not template placeholders)
- [ ] User has confirmed the project context is correct
- [ ] System is ready for project-specific work

## Expected Response Format
```
## System Loading Complete ✅

**Template Structure Understood:**
[Explain the hierarchy and component purposes]

**Key Capabilities Activated:**
[List the main system features you'll now use]

**Operational Principles Confirmed:**
[State the core principles you'll follow]

**REQUIRED: Project Discovery & Root CLAUDE.md Update**
I must update the root CLAUDE.md file before proceeding. Please answer these questions:

1. What is the main purpose and goals of this project?
2. What technology stack are you using?
3. What are the key challenges you're facing?
4. What's the current status/stage of the project?
5. Any specific working preferences or conventions I should know?

After I update the root CLAUDE.md with your project context, I'll begin applying the memory keeper system to your actual work.
```

## Success Criteria
- All core files loaded and understood
- System hierarchy and integration clear
- Operational principles confirmed
- **Root CLAUDE.md updated with actual project context** (not template)
- User has confirmed project context is correct
- Ready to apply memory keeper system to real project work
- Intelligent workflow patterns activated