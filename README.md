# Every Other Token (original 1.0 snapshot)

This repository is the original July 2025 version (1.0.0) of **[Mattbusel/Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token)**, which is the maintained project (web UI, Anthropic support, research mode, attribution export and much more). Use that one.

What this snapshot contains: a single-file Rust CLI (`src/main.rs`) that streams a completion from the OpenAI API and transforms every other token as it arrives (`reverse`, `uppercase`, `mock`, `noise`), with optional color-coded visual and heatmap modes.

![Terminal output with heatmap](Screenshot%202025-07-12%20161852.png)

```bash
export OPENAI_API_KEY=sk-...
cargo run -- "tell me about a robot" noise gpt-3.5-turbo --visual --heatmap
```

Kept for history only; it receives no updates.
