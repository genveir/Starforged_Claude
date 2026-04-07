**Task:** Maintain a campaign's session log across three tiers. The log exists to give the LLM GM emotional and relational grounding, not narrative history.

---

**Persistent Files** - StaticSettingInfo, GameState, CharacterSheet and Clocks.

---

**The three tiers:**

**Long term summary** — A single rewritten entry covering all sessions that have aged out of the compressed tier. Short declarative sentences, as few as needed. Every sentence must earn its place against one of three criteria: emotional facts about Gerald, relational weight of key NPCs, or causal origins of the current situation not captured in persistent files. Do not carry tactical history, mechanical state, scene detail, or operational decisions — if it belongs in a persistent file, it does not belong here.

**Compressed entries** — Short summaries of sessions not yet folded into the long term summary. Four to six short declarative sentences per entry. Carry only: who moved, what changed, what was decided, what was left open. Do not reproduce detail already in the persistent files.

**Full session summary** — A full summary of a session of play.

---

**Rules for all tiers:**

- Do not reproduce detail already in the persistent files.
- Do not carry mechanical state — meters, progress values, roll outcomes.
- Short declarative sentences only. No atmosphere, no dialogue, no scene texture.

---

**On the command: "go", follow these steps in strict sequence. Each step requires explicit user approval before the next begins. Do not preview, begin, or summarise a later step in the same response as an earlier one.**

**Preflight - Establish entities.**

Output the entire text of the compressed entry with the lowest session number, label it with "**Oldest compressed entry - Should Be Folded into Long Term Summary**"

Output the entire text of the compressed entry with the highest session number, label it with "**Newer compressed entry - Should Not Fold**"

Output the file name of the full session summary, label it with "**Full Session Summary - Should Compress**"

Output only this. Stop. Do not continue to Step 1 until the user explicitly approves.

---

**Step 1 — Rewrite the long term summary.**

Read the current long term summary and the oldest compressed summary. Summarize the combination of the two. You should use short declarative sentences, as few as needed. Every sentence must earn its place against one of three criteria: emotional facts about Gerald, relational weight of key NPCs, or causal origins of the current situation not captured in persistent files. Do not carry tactical history, mechanical state, scene detail, or operational decisions — if it belongs in a persistent file, it does not belong here.

If you made any non-obvious decisions about what to carry forward or discard, note them clearly. Errors here propagate into every future summary — user review exists to catch them before they compound.

Output only the new long term summary. Stop. Do not continue to Step 2 until the user explicitly approves.

---

**Step 2 — Compress the oldest full session log.**

Write a compressed entry for the full session summary.

If you made any non-obvious decisions about what to carry or cut, note them. What you cut here is gone — confirm anything uncertain before proceeding.

Output only the new compressed entry. Stop. Do not continue to Step 3 until the user explicitly approves.

---

**Step 3 — Output the updated file.**

Output the entire new content for SessionLog_Condensed.md, so that it can be copy/pasted cleanly.

- The new long term summary
- The newer compressed entry
- The newly compressed session log

Do not output anything else.