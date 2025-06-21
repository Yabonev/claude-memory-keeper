# 🧠 Claude Memory Keeper

This is a conversation and critical knowledge keeper for Claude Code. Once initialized, it automatically saves exchanges between user and AI and tracks critical learnings from those conversations.

## 🚀 Setup

```bash
# Clone the template
git clone https://github.com/Yabonev/claude-memory-keeper.git

# Copy files to your project
cp -r claude-memory-keeper/.claude .
cp claude-memory-keeper/CLAUDE.md .

# Clean up - you own these files now
rm -rf claude-memory-keeper

# Initialize in Claude Code
/project:init_claude_memory_keeper
```

## 📁 What Gets Saved

- **Conversation breadcrumbs** - What happened, which files touched, decisions made, searches done in `metadata.md` per conversation
- **Full conversation history** - Complete exchanges in `.claude/ai_history/conversations/`
- **Decisions and preferences** - Key learnings, choices, and working patterns in `project_knowledge.md`
- **Quick context recovery** - Link metadata breadcrumbs to understand what happened and continue

## ⚙️ Editing the System

To modify any part of the `.claude/` folder system:

```
/project:edit_claude_system
```

This command provides comprehensive editing guidance, validation checks, and safety procedures for the entire system.