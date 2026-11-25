# DP_Hackathons_Gemini

Gemini hackathon work.

## Read this first
- `README.md`: project overview
- `xprize-signals.zip`: do not unzip at start

## Usage rules (apply every session)
1. **Plan first**: beyond a quick answer, show a short plan (goal, steps, cost low/med/high) and wait for "go". If scope/cost changes, stop and re-plan that part only. Vague request -> ask one sharp question.
2. **Short output**: answer, deliver, stop. No recaps, no "next steps" files, no README unless asked. Tables/bullets only when they help.
3. **Small context**: read only needed files/parts; never re-read a file just edited; do not re-list folders. Load skills/tools only when triggered. Large tool output -> file, read summary. Subagents only for parallel/wide searches, reports <=300 words.
4. **Session discipline**: one session = one phase of one task. End at ~150 turns or phase done; first write `HANDOFF_<task>_<date>.md` (state, decisions, open items, exact next step, files to read first). Start new sessions from the newest handoff. Cheaper model for lookups/mechanical work; strongest only on request.
5. **Structure**: `CLAUDE.md` (rules + map), `HANDOFF_*.md` (newest = start), `LESSONS.md`, `CHANGELOG.md`. Scratch in `scratch/` (gitignored). Never load `archive/`, backups or old dated copies at start.
6. **Small verified batches**: batches of 3; one quick check per change; read the actual result before claiming success. Smallest fix first: setting, then config, then code.
7. **Lessons**: when corrected or an approach is confirmed, add a short lesson + reason to `LESSONS.md` (update existing note, do not duplicate); check it before similar work.
8. **Timing**: flag heavy jobs once if started at a busy time, then carry on.
