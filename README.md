# cuda-emotion

**11 emotional states as computational modulators of agent behavior.**

> Emotions aren't decorative. They change how the agent thinks, decides, and acts.

## The Model

Emotions exist in a 2D valence-arousal space:
- **Valence**: positive (approach) to negative (avoid)
- **Arousal**: calm (deliberate) to excited (reactive)

### 11 Emotions

| Emotion | Valence | Arousal | Effect on Agent |
|---------|---------|---------|-----------------|
| Joy | + | + | Faster decisions, broader exploration |
| Trust | + | - | Cooperation, information sharing |
| Surprise | 0 | + | Attention spike, context reset |
| Anticipation | + | + | Planning, preparation |
| Fear | - | + | Rapid avoidance, deliberation suppression |
| Anger | - | + | Aggressive action, risk tolerance |
| Disgust | - | - | Rejection, avoidance |
| Sadness | - | - | Reduced activity, conservative choices |
| Curiosity | + | + | Increased exploration |
| Calm | + | - | Deep deliberation, thorough analysis |
| Frustration | - | + | Strategy switching, escalation |

## Key Mechanics

- **Emotional contagion**: States spread to nearby agents via A2A messages
- **Behavioral modulation**: Emotion affects attention breadth, decision speed, and risk tolerance
- **Emotional memory**: Events tagged with emotional valence; emotional events persist longer in episodic memory
- **Return to baseline**: Emotions decay exponentially toward neutral state

## Ecosystem Integration

- [cuda-neurotransmitter](https://github.com/Lucineer/cuda-neurotransmitter) -- Neurochemical foundation
- [cuda-attention](https://github.com/Lucineer/cuda-attention) -- Arousal modulates attention scope
- [cuda-deliberation](https://github.com/Lucineer/cuda-deliberation) -- Emotion affects deliberation depth
- [cuda-memory-fabric](https://github.com/Lucineer/cuda-memory-fabric) -- Emotional valence strengthens encoding
- [cuda-communication](https://github.com/Lucineer/cuda-communication) -- Emotional state in messages
- [cuda-narrative](https://github.com/Lucineer/cuda-narrative) -- Stories carry emotional arcs

## License

MIT OR Apache-2.0