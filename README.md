# 🧠 Claude Memory Keeper

I got tired of losing context every time Claude hit token limits. Critical decisions, working patterns, conversation history - all gone. Had to re-explain my entire project every new session.

So I built this `.claude/` folder system to fix it.

## 🚀 Quick Start

```bash
# Add to your project
git clone https://github.com/Yabonev/claude-memory-keeper.git
cp -r claude-memory-keeper/.claude .

# Initialize in Claude Code
/project:init_claude_memory_keeper
```

## 📁 What I Save

- **Critical decisions** - Architecture choices, what worked/failed and why
- **Full conversation logs** - Every prompt exchange, searchable and referenceable
- **My working patterns** - Coding style, preferences, workflow quirks Claude learns
- **Project context** - New sessions auto-load relevant knowledge

## 🔧 Problems This Actually Solves

- **"What did we decide about that API structure?"** → It's in the knowledge base
- **"That optimization we tried - did it work?"** → Check the conversation history  
- **"New session, time to explain everything again..."** → Nope, auto-loads context
- **"Which prompt worked best for this type of task?"** → Searchable logs

## 📋 How It Works

I set it up so Claude automatically:
- Saves important conversations in `.claude/ai_history/conversations/`
- Updates `.claude/ai_history/project_knowledge.md` with key decisions
- Loads relevant context when starting new sessions
- Lets me reference specific conversations that went well

## ⚙️ Usage

Just work normally. When context runs out or you start fresh, run `/project:init_claude_memory_keeper` and Claude picks up where you left off.

---

No more explaining the same project over and over.