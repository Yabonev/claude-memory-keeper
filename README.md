# 🧠 Claude Memory Keeper

**The Problem:** Claude forgets everything when context runs out. You lose critical decisions, working patterns, and conversation history.

**The Solution:** A `.claude/` folder system that saves learning and maintains conversation history across sessions.

## 🚀 Quick Start

```bash
# Add to your project
git clone https://github.com/Yabonev/claude-memory-keeper.git
cp -r claude-memory-keeper/.claude .

# Initialize in Claude Code
/project:init_claude_memory_keeper
```

## 📁 What Gets Saved

- **Critical decisions** - Architecture choices, patterns that worked/failed
- **Conversation history** - Full prompt exchanges you can reference later  
- **Working preferences** - Your coding style, tool preferences, workflow patterns
- **Context continuity** - New Claude sessions load relevant knowledge automatically

## 🔧 Real Problems This Solves

- **"Wait, what did we decide about the database schema?"** → Saved in knowledge base
- **"That refactoring approach we tried last week - did it work?"** → Check conversation history
- **"New Claude session, explaining the codebase again..."** → Auto-loads project context
- **"Which prompt got the best results for this task?"** → Searchable conversation logs

## 📋 How It Works

The system tracks conversations and extracts knowledge automatically:
- Saves important exchanges in `.claude/ai_history/conversations/`
- Updates `.claude/ai_history/project_knowledge.md` with decisions and patterns
- New sessions load relevant context based on current task
- You can reference specific conversations when something worked well

## ⚙️ Usage

Work normally. Claude saves critical learning and conversation history automatically. When context runs out or you start a new session, run `/project:init_claude_memory_keeper` to load everything back.

---

Stops the frustrating cycle of re-explaining your project every time.