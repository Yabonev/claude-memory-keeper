# Claude Memory Keeper

**Enhanced context-aware memory management system** for Claude Code with intelligent conversation tracking and seamless AI agent collaboration.

## What This Does

This is a **template repository** that gives Claude Code agents persistent memory and intelligent workflow capabilities. Drop it into any project and Claude immediately gains:

- **Context-aware knowledge management** - Knows what's relevant for each task
- **Living documentation** that evolves with your project
- **Strategic delegation** with sub-agent task coordination
- **Custom slash commands** for workflow automation
- **Cross-session continuity** - Every new Claude agent starts with full project context

## Quick Start

### 1. Clone to Your Project
```bash
git clone https://github.com/Yabonev/claude-memory-keeper.git
cd your-project
cp -r claude-memory-keeper/.claude .
```

### 2. Initialize the System
Start any Claude Code session and run:
```
/project:init_claude_memory_keeper
```

### 3. Start Working
That's it. Claude now has persistent memory and will:
- Track important decisions and patterns
- Remember your preferences and working style
- Suggest automations for repetitive tasks
- Maintain context across sessions
- Coordinate complex multi-step work

## How It Works

### The `.claude/` Folder Structure
```
.claude/
├── CLAUDE.md                    # Integration hub - coordinates everything
├── ai_history/                  # Memory management
│   ├── CLAUDE.md               # Memory system overview
│   ├── core/                   # Templates and instructions
│   └── conversations/          # Conversation tracking
├── claude_code/                # Tool optimization
│   ├── CLAUDE.md               # Best practices overview
│   ├── settings.md             # Tool usage guidance
│   └── claude_md_principles.md # System design principles
├── commands/                   # Custom workflows
│   ├── CLAUDE.md               # Commands overview
│   ├── init_claude_memory_keeper.md
│   └── edit_claude_system.md
└── sub-agent-tasks/            # Parallel execution outputs
    └── CLAUDE.md               # Task coordination
```

### Key Features

**🧠 Context-Aware Knowledge**
- Claude evaluates what knowledge is relevant before applying it
- No information overload - only uses what matters for the current task

**🎯 Strategic Delegation**
- Complex tasks get broken down and executed in parallel
- Sub-agent outputs are saved and coordinated intelligently

**⚡ Custom Automation**
- Repetitive patterns become custom slash commands
- Workflows evolve and improve over time

**📚 Living Documentation**
- Knowledge base grows and adapts with your project
- Captures decisions, patterns, and lessons learned

## Usage Patterns

### Starting a New Session
```
/project:init_claude_memory_keeper
```
Claude loads the complete system and asks about your project goals.

### Continuing Previous Work
Claude automatically loads existing knowledge and picks up where you left off.

### Complex Multi-Step Tasks
Claude uses strategic delegation, breaking work into parallel sub-tasks and coordinating results.

### Repetitive Workflows
Claude suggests creating custom commands for patterns it notices.

## Advanced Usage

### Context Filtering
The system uses tags like `[RESEARCH]`, `[IMPLEMENT]`, `[REFACTOR]` to apply only relevant knowledge.

### Reference Coding
Knowledge gets organized with descriptive codes for easy retrieval and application.

### Cross-Component Integration
All system parts work together - memory informs tool usage, which creates automation opportunities.

## Template Philosophy

This is designed as a **universal template** that adapts to any project type:
- Software development
- Research projects  
- Content creation
- Data analysis
- System administration
- Any workflow that benefits from persistent AI memory

## System Maintenance

Use `/project:edit_claude_system` for comprehensive editing guidance when you need to modify or extend the system.

## Getting Started

1. **Copy the `.claude/` folder** to your project
2. **Run `/project:init_claude_memory_keeper`** in Claude Code
3. **Start working** - the system adapts to your project automatically

The memory keeper learns your patterns, remembers your decisions, and makes every Claude session more intelligent than the last.