# cuda-emotion

Emotional state engine — maps neurochemicals to 11 core emotions that modulate risk, exploration, cooperation (Rust)

Part of the Cocapn cognitive layer — how agents think, decide, and learn.

## What It Does

### Key Types

- `EmotionalState` — core data structure
- `EmotionalModulation` — core data structure
- `EmotionalMemory` — core data structure
- `EmotionalEpisode` — core data structure
- `EmotionalContagion` — core data structure
- `EmotionEngine` — core data structure

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-emotion.git
cd cuda-emotion

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_emotion::*;

// See src/lib.rs for full API
// 12 unit tests included
```

### Available Implementations

- `Emotion` — see source for methods
- `EmotionalState` — see source for methods
- `EmotionalModulation` — see source for methods
- `EmotionalMemory` — see source for methods
- `EmotionalContagion` — see source for methods
- `EmotionEngine` — see source for methods

## Testing

```bash
cargo test
```

12 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: cognition
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates

- [cuda-confidence-cascade](https://github.com/Lucineer/cuda-confidence-cascade)
- [cuda-deliberation](https://github.com/Lucineer/cuda-deliberation)
- [cuda-reflex](https://github.com/Lucineer/cuda-reflex)
- [cuda-goal](https://github.com/Lucineer/cuda-goal)
- [cuda-fusion](https://github.com/Lucineer/cuda-fusion)
- [cuda-attention](https://github.com/Lucineer/cuda-attention)
- [cuda-narrative](https://github.com/Lucineer/cuda-narrative)
- [cuda-learning](https://github.com/Lucineer/cuda-learning)
- [cuda-skill](https://github.com/Lucineer/cuda-skill)

## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
