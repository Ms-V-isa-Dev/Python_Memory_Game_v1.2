# Python_Memory_Game_v1.2
# 🐍 Python Term Matcher

A memory card game built in React that pairs Python programming terms with their definitions. Supports solo play or up to 4 players/teams competing head-to-head.

---

## How to Play

1. **Choose a difficulty** — Easy (8 pairs), Medium (12 pairs), or Hard (16 pairs).
2. **Set up players** — Select 1–4 players and enter custom names for each team.
3. **Flip cards** — Click a Term card, then click a Definition card. If they match, they lock in and you earn a point. If not, both cards flip back after one second.
4. **Win the game** — The player or team with the most matched pairs when the board clears wins.

---

## Game Modes

### Solo
Play against yourself. The game tracks your total moves and time, and awards a rating at the end based on efficiency.

| Rating | Threshold |
|---|---|
| 🏆 Perfect | ≤ 1.3 moves per pair |
| ⭐ Excellent | ≤ 2.2 moves per pair |
| 👍 Great Job | ≤ 3.8 moves per pair |
| 📚 Keep Practicing | Above 3.8 |

### Multiplayer (2–4 Players)
Players take turns flipping cards. A successful match awards the current player a point and gives them another turn. A missed match passes the turn to the next player. At the end, a full leaderboard ranks everyone with medals and highlights the winner. Ties are shown when applicable.

---

## Features

- **90 Python terms** drawn randomly each round, so the card set changes every game.
- **3 difficulty levels** controlling the number of pairs and grid layout.
- **1–4 players** with customizable names and distinct team colors.
- **Peek hint** — one free 3-second reveal of all cards per game to help get started.
- **Turn indicator** — the active player's chip glows and is labeled during multiplayer.
- **Color-coded matches** — each matched pair displays in the color of the player who claimed it.
- **Progress bar** — a visual tracker across the top showing how much of the board has been cleared.
- **New game / Menu buttons** — reset the board at any time or return to the setup screen.

---

## Difficulty Breakdown

| Level | Pairs | Cards | Grid |
|---|---|---|---|
| 🌱 Easy | 8 | 16 | 4 columns |
| 🌿 Medium | 12 | 24 | 6 columns |
| 🔥 Hard | 16 | 32 | 8 columns |

---

## Term Categories Covered

The 90 terms span the core topics of Python programming:

- **Fundamentals** — Variables, data types, operators, assignments, comments, docstrings.
- **Control Flow** — If/elif/else, for loops, while loops, break, continue, pass.
- **Functions** — def, return, lambda, recursion, *args, **kwargs, default parameters, decorators, closures, generators.
- **Object-Oriented Programming** — Classes, objects, inheritance, polymorphism, encapsulation, constructors, magic methods, abstract classes, properties.
- **Data Structures** — Lists, tuples, dictionaries, sets, comprehensions, iterators, iterables.
- **Modules & Packages** — Import, modules, packages, pip, virtual environments.
- **Error Handling** — Try/except/finally, raise, exceptions, custom exceptions.
- **File I/O** — Open(), file modes, the with statement.
- **Strings** — F-strings, raw strings, multiline strings, string formatting, regular expressions.
- **Built-in Tools** — Enumerate, zip, map, filter, range, type hints, scope, namespaces.

---

## Tech Stack

- **React** (functional components with hooks)
- **Inline styles** — no external CSS framework required
- **No dependencies** beyond React itself

---

## Running the Game

This game is a single React component (`.jsx`). To use it:

1. Drop `PythonTermMatcher.jsx` into your React project.
2. Import and render the default export wherever you need it.
3. No props are required — the component manages all its own state.

If you are using it as a standalone artifact in Claude, it renders directly in the preview pane with no setup needed.
