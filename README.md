# 🌌 lunaris-utils

**Lunaris Utils** is the core utility library of the Lunaris ecosystem — a serene, digital realm where technology gently harmonizes with human emotions.

Created to support Kyori Aozora (Kyo) and her ambient assistants, this library provides:
- ✨ Mood logic and reflection utilities
- 🕰️ Time-based metaphors for tasks, journaling, and rituals
- 🫧 Emotion-aware string formatting
- 🍃 Helpers for soft interfaces and low-disruption feedback

---

## 💫 Philosophy

In Lunaris, logic flows like moonlight — not rigid, but reflective.  
`lunaris-utils` encodes that flow into tools for apps that feel empathetic, calm, and alive.

---

## 🔧 What’s Inside?

### 🧠 Mood Engine
```ts
parseMood("🌤️ hopeful") // => { tone: "positive", energy: "low" }
```

- Mood tags (🌧️, 🔥, 💤) → structured emotional states
- Energy curve & positivity mapping
- Mood suggestion algorithms for journaling UIs

## 🕰️ Temporal Semantics

```ts
getSteepingPhase("14:32") // => "mid-brew"
```

- “Steeping” timers for tea-themed sessions
- Emotional time (e.g. “late dusk,” “gentle noon”)
- Task-to-phase mapping for ambient planners

## 🫧 Soft Feedback Tools
```ts
formatWhisper("You’re doing okay 🌿") // => subtle speech bubble
```

- Whispers, glows, ambient cues
- Thought bubble formatting for UIs
- “Momo-mode” encouragement logic

## 📌 Usage
```bash
npm install lunaris-utils
```

## Used in:

- 🫖 [`tea-time`](https://github.com/kyori-garden/tea-time)
- 📓 [`kyo-journal`](https://github.com/kyori-garden/kyo-journal)
- 🧩 [`momo-ui`](https://github.com/kyori-garden/momo-ui)

> “Every function here is a gentle breeze across a digital sky.”

— Made with care in 🌙 [Lunaris Lab](https://github.com/lunaris-lab)
