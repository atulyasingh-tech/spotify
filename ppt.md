---
title: "Ship It With Specs"
author: "Workshop Presenter"
---

# Welcome to "Ship It With Specs" 🎧
Today, you are going to build your own Spotify-style music player from scratch — without writing a single line of code yourself.

---

# 1. Introduction

### *About Me*
- (Add your brief introduction here)
- Why I'm excited to build with you today!

---

# 2. What is Programming, Really? 💻
It's just giving instructions to a computer.
**Input → Logic → Output**. That's it.

- *Input:* You click "play" on a song.
- *Logic:* The app figures out what to do.
- *Output:* The music plays.

---

# 3. What is AI-Assisted Coding? 🤖
**You are the Architect. The AI is the Builder.**
- You don't need to memorize syntax.
- You describe what you want in plain English.
- The AI writes the code — and asks for your approval at each step.

---

# 4. Introduction to the AI Coding Tool 🛠️
How we will build today, using **Google Antigravity** (Gemini built in):
- **Sign in with Google** — the agent already has Gemini. No key to paste, nothing to install.
- **Plan first:** the agent writes a plan you review — *nothing is built yet.*
- **Then it builds:** changes appear on screen; you review each one as it lands.
- **The loop:** describe → review the plan → approve → build. That loop *is* the lesson.

---

# 5. Beyond "Vibe Coding" 🧠
*Why just typing words isn't enough to build something you keep.*

- **Vibe Coding:** Throwing prompts at the AI until it works. Great for a throwaway — but the only record of what you wanted is a chat log that scrolls away.
- **Systems Thinking:** Understanding how the pieces connect (the library, the player, the data).
- **Spec-Driven Thinking:** Write down *what* and *why* first — the code just follows.
- *To build something you can keep and change, you need the spec, not just the prompt!*

---

# 6. The Benchmark: What are we building?
### *Demo: Our Target Application*
- A custom, browser-based music player in a single `index.html`.
- Built entirely from a spec, using Google Gemini as the AI builder.

---

# 7. How Does the App Get Built? 🚦
It all happens across five simple gates:

```
AGENTS.md → REQUIREMENTS → DESIGN → TASKS → IMPLEMENT
 the rules    what & why      how     the steps   the code
```

1. **Rules:** the guardrails, written once.
2. **Requirements:** what it must do, in plain testable statements.
3. **Design:** how it will be structured.
4. **Tasks:** the ordered steps.
5. **Implement:** the AI writes the code — from the spec.

Today, we focus heavily on writing the **Requirements**.

---

# 8. What is a Spec? 📋
**Spec = Specification = the source of truth.**
Think of it as the blueprint. The code is just the most recent *build* of the blueprint.

- Change the app → change the spec first.
- Six months later, the spec tells the next person *why* it works that way.
- *The spec is yours. The AI is just the one typing.*

---

# 9. Testable Requirements: EARS 🎯

Not every sentence is a good requirement.
- ❌ "The player should be intuitive." → can't be tested.
- ✅ **WHEN** the user clicks play **THE SYSTEM SHALL** begin playback and switch the button to a pause icon. → testable.

**The EARS shape:**
`WHEN <trigger> THE SYSTEM SHALL <behaviour>`

---

# 10. The Guardrails: `AGENTS.md` 🚧

Before the AI writes anything, we give it a permanent rulebook (`AGENTS.md`) that Antigravity reads every time.

*Example rules for today:*
- One single `index.html` — no frameworks, no build step.
- Runs on a local live server (Antigravity's built-in preview).
- Song data hardcoded; likes saved with `localStorage`.

*These rules are the reason the app will actually run on the projector later.*

---

# 11. Design & Tasks: From What to How 🧩

- **Design** names the parts of the single file, the shape of the song list, and how likes are saved.
- **Tasks** break the work into 3 phases — and *every task points back to a requirement number.*
- *Nothing is in there because the AI felt like it. Everything traces to something we asked for.*

---

# 12. Time to Build! (Live Demo) 💻

Let's open **Google Antigravity** and walk the five gates live.

**What we will do:**
1. Write `AGENTS.md` — the guardrails.
2. Write `requirements.md` — *you* call out what it must do.
3. Write `design.md` and `tasks.md`.
4. Watch the code get built from the spec — then play a song!

---

# 13. Change the Spec, Not the Code 🔁

*"Product just asked for Shuffle. Where do we make the change?"*

- We add **one new requirement** to `requirements.md`, in your words.
- The AI updates the design, the tasks, and the code — automatically.
- *A product change without touching code — and the reason is written down forever, beside the code.*

---

# 14. Your Turn: Spec-It Challenges 🚀

The app has a "Practice — spec these next" panel. Pick one and write its requirement:

### 📝 Challenge 1: Liked Songs View
WHEN the user opens Liked Songs THE SYSTEM SHALL show only the tracks they've liked.

### 🕘 Challenge 2: Recently Played
WHEN a track is played THE SYSTEM SHALL remember it and show the most recent ones first.

---

# 15. Your Turn: Spec-It Challenges (cont.) 🎭

### ☰ Challenge 3: Play Queue
WHEN the user adds a track to the queue THE SYSTEM SHALL play queued tracks next.

### 🌗 Challenge 4: Light / Dark Theme
WHEN the user toggles the theme THE SYSTEM SHALL switch appearance and remember it on reload.

*Write the requirement first — then let the AI build it.*

---

# 16. Key Takeaway 🔑

**The app isn't magic — it's a few understandable pieces, written down first.**

Today you wrote the spec and watched the code follow. The code changed; the thinking didn't.

*If you can write down what you want, you can build it — and the idea matters more than the tool.*

---

# Let's Build! 🛠️
