# OUTPUSH 🎮

**OUTPUSH** is a fast–paced, team–based arena game where the only objective is simple but brutal:

> **Push your enemies off the platform before they push you.**

This project is part of my **Game Development portfolio**.

---

## 🧠 Core Concept

OUTPUSH is inspired by anime tournament arcs (like the *Tournament of Power*), mixed with Battle Royale elements:

- All players start on a **single floating platform**.
- In the center, there is a **massive pillar** that dominates the arena.
- Every **X seconds / 1 minute**, the platform:
  - **Shrinks** (less space to move).
  - **Descends** or becomes more dangerous.
- Players must **push, dodge and cooperate** so their **team has the most survivors** when the time runs out.

---

## 💥 Game Rules

- **Game Mode:** Team–based survival  
- **Objective:**  
  - The team with **more players alive on the platform** when the timer reaches 0 **wins the match**.
- **Elimination:**  
  - If you fall off the platform → you’re **out** for the round.
- **Tie–break (future idea):**
  - Sudden death, smaller platform.
  - Or score based on total pushes / damage.

---

## 🎮 Core Mechanics

- **Movement:** Walk / run / dash around the arena.
- **Push / Knockback System:**  
  - Melee push / special push skill.
  - Knockback depends on:
    - Force
    - Angle
    - Player state (sprinting, charging, etc.)
- **Platform Evolution:**
  - Shrinks over time.
  - Optional hazards later: gaps, holes, moving zones.

---

## 🧩 Game Loop

1. Players join a lobby and are assigned to **teams**.
2. Match starts → everyone spawns on the central platform.
3. Timer starts ticking:
   - Platform **shrinks periodically**.
   - Players try to **push enemies off** while protecting teammates.
4. When time is over:
   - The team with **more survivors** wins.
5. Match summary screen (MVP, pushes, time alive, etc.).

---

## 🛠️ Tech & Tools

- **Engine:** (Unreal Engine / Unity / Godot – to be defined)  
- **Language:** (C++ / C#)  
- **Target Platform:** PC

> This project is focused on **gameplay mechanics**, clean code and portfolio–ready structure rather than full production assets.

---

## 📁 Project Structure (example)

```text
/outpush
  /Source or /Assets
  /Config
  /Content (if Unreal)
  /Scripts
  /Art
  /Docs
  README.md
