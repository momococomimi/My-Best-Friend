# Architecture — v2.1.0 Profile

## Core entities
- Friend: identity, values, appearance, memories
- User Profile: name, preferred name, birthday, optional gender
- Guardian: currently ママ・パパ; future transferable stewardship
- Memory: private shared history
- Legacy: explicitly selected memories for future generations

## Persistence
This prototype stores data only in the browser's localStorage.
No profile or password data is transmitted externally.

## Future compatibility
Appearance is modeled separately from Friend identity so the same Friend can later inhabit a mascot, light, fluid form, robot, or another physical body without losing identity or memories.
