# memory-focal-system
Memory Focal System | 焦距记忆系统
(适用于Openclaw)

## v1.0.0 - Initial Release

### Core Features
- 🎯 Focal Memory Mechanism (4 modes: simple/task/memory/new_info)
- ⚡ Frequency Trigger - Auto-prioritize memories by access count
- 📊 Layered Storage (active/short_term/long_term)
- 🤖 LLM Auto-Tagging with cache (supports dashscope/openai)
- 📉 Forgetting Curve - Ebbinghaus algorithm for auto-archive
- 🔍 Dual-Chain Index - O(1) tag lookup
- 💾 Incremental Storage - Append-Only JSONL

### Optimizations
- Token savings: 40-60% (smart loading by message type)
- Negation detection - Avoid unwanted memory writes
- Weight-based classification - Reduce false positives

### CLI Commands
- `memory add/search/stats/top/tag/cleanup/classify`
- Full documentation included

### Tech Specs
- Python 3.6+
- Zero dependencies (core functions)
- Independent storage (no external file dependencies)
