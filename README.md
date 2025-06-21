# 🧠 Claude Memory Keeper

This is a conversation and critical knowledge keeper for Claude Code. Once initialized, it automatically saves exchanges between user and AI and tracks critical learnings from those conversations.

## 🚀 Setup

```bash
# Add to your project
git clone https://github.com/Yabonev/claude-memory-keeper.git
cp -r claude-memory-keeper/.claude .

# Initialize in Claude Code
/project:init_claude_memory_keeper
```

## 📁 What Gets Saved

- **Conversation history** - Full exchanges saved in `.claude/ai_history/conversations/`
- **Critical decisions** - Key learnings tracked in `project_knowledge.md`
- **Working patterns** - Your preferences Claude learns over time
- **Context continuity** - New sessions auto-load relevant knowledge

## ⚙️ Editing the System

To modify any part of the `.claude/` folder system:

```
/project:edit_claude_system
```

This command provides comprehensive editing guidance, validation checks, and safety procedures for the entire system.