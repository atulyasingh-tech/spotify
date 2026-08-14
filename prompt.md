
## Agent.md (a senior person) -> 
Create a file AGENTS.md with the permanent rules for this project. Do not
write app code yet. Product: a single-page music player. HARD CONSTRAINTS:
one index.html (inline CSS + vanilla JS); no frameworks; no npm/build/CDN;
runs on a local live server (Antigravity preview), not double-clicked;
tracks hardcoded from TRACKS.md; state in localStorage; specs go in spec/.
Then stop.


## Requirement.MD
Read AGENTS.md and follow it. Write spec/requirements.md only — no design,
no code. Users can: see a library grid, play a track, use a player bar
(play/pause/next/prev, seek + time, volume), search, like a track that
persists on reload, and auto-play the next track. Write every requirement
in EARS: WHEN <trigger> THE SYSTEM SHALL <behaviour>. Number them. Then stop.

## Design.md
requirements.md is approved. Write spec/design.md: the structure of the single
index.html, the shape of the track array, and how liked state is stored and
restored. Obey AGENTS.md. No code. Then stop.


## Task.md
Design approved. Write spec/tasks.md in EXACTLY 3 phases. Each task references
the requirement number it implements. Each phase ends in something I can verify
by opening index.html. Phase 1 must be visible. Then stop.
