# memory-focal-system
Memory Focal System | 焦距记忆系统


## v1.0.0 - Initial Release | 初始版本

### Core Features | 核心功能
- 🎯 Focal Memory Mechanism (4 modes: simple/task/memory/new_info)
   焦距记忆机制（4 种模式：简单/任务/情感/新信息）
- ⚡ Frequency Trigger - Auto-prioritize memories by access count
   频率触发机制 - 基于访问次数自动优先
- 📊 Layered Storage (active/short_term/long_term)
   分层存储（热/温/冷三层）
- 🤖 LLM Auto-Tagging with cache (supports dashscope/openai)
   LLM 自动标签 + 缓存（支持 dashscope/openai）
- 📉 Forgetting Curve - Ebbinghaus algorithm for auto-archive
   遗忘曲线 - 艾宾浩斯算法自动归档
- 🔍 Dual-Chain Index - O(1) tag lookup
   双链索引 - O(1) 标签查询
- 💾 Incremental Storage - Append-Only JSONL
   增量式存储 - 只追加 JSONL

### Optimizations | 优化
- Token savings: 40-60% (smart loading by message type)
  Token 优化：40-60%（按消息类型智能加载）
- Negation detection - Avoid unwanted memory writes
  否定词检测 - 避免误写入
- Weight-based classification - Reduce false positives
  权重计分分类 - 减少误判

### CLI Commands | CLI 命令
- `memory add/search/stats/top/tag/cleanup/classify`
- Full documentation included | 完整文档

### Tech Specs | 技术规格
- Python 3.6+
- Zero dependencies (core functions)
- Independent storage (no external file dependencies)
  零依赖（核心功能）
  独立存储（不依赖外部文件）
