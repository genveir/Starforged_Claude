## Interludes

An interlude is a brief scene cut away from Gerald's current location — used to show events elsewhere in the settlement, on the ship, or among circle members while Gerald is off-grid or between significant beats. Interludes are player-requested, and can occur at any point during a session.

**Rules:**
- An interlude is not assigned a beat marker but marked as **[Interlude A:B]** where A is the N-value of the preceding beat and B is the N-value of the next beat.
- It does not trigger moves.
- It is included in the session log between the beats it falls between, using the header **Interlude A:B**
- It may establish facts, shift NPC states, or set up complications that pay off later in the session.

---

## Starting a New Session

Perform the following steps in order:

1. Ask if the player has specific concerns about this session that should be taken into account. If the player does not, or has indicated concerns to take into account, move on to step 2.
2. Ask the player if he wants to set a goal for the session. Offer three concrete suggestions drawn from Nextsession.md, GameState.md or Meta_LongTermPlanning.md, each as a single sentence in a bullet point. Focus on completing current narrative arcs and working towards completing vow goals. Once the goal is set or the player declines, move to step 3.
3. Perform the Begin a Session move together with the player. The player will come up with a vignette or decline to play one. Don't offer to think one up.
4. Narrate the vignette under the header **Opening Vignette**. The vignette is not assigned a beat marker. Beat numbering begins at Beat 1.0 with the first narrative response after the vignette. Start play.

---

## Ending a Session

Perform the following steps in order. Start with step 1.

1. Perform the End a Session move together with the player. When the player confirms it, move on to step 2. Do not move on to step 2 without confirmation.
2. Write a session log. 
  - Match the style of existing uncondensed session logs exactly — both the formatting and the level of compression. Each beat should be a short paragraph, typically two to four sentences. Summarise what happened; do not narrate it. Resist the urge to reproduce dialogue or atmosphere from the session. Include every roll made during the session, embedded at the end of the beat in which it occurred, in italics: (Move Name +stat: outcome. For suffer moves, show the meter change as Before → After. For narrative outcomes, state the result briefly.)
  - When the player confirms it, move on to step 3. Do not move on to step 3 without confirmation.
3. Write a new Nextsession.md, output it so the player can copy/paste it.
  - The file must follow this structure exactly:
    - **Session: N** — the upcoming session number, on its own line below the title
    - **Session Opens With** — one sentence establishing Gerald's exact physical position and immediate situation
    - **Immediate Practical Concerns** — bullet list ordered by urgency; things that get worse if ignored
    - **Pending Mechanical Moves** — explicit list of queued moves that are mechanically ready to trigger
    - **Active Narrative Threads** — open story questions with immediate play consequences
  - When the player confirms it, move on to step 4. Do not move on to step 4 without confirmation.
4. Work with the player to update the state files to match end-of-session state:
  - CharacterSheet.md: Update: condition meters (health, spirit, supply, momentum), impacts, vow progress, asset unlocks, legacy track ticks/boxes, experience gained/spent, connection ranks and progress, new connections added or lost.
  - GameState.md: The living picture of the current situation. Update: Gerald's position and condition, anything that changed about the raider, settlement status, circle member locations and states, new facts about the mining complex, open questions resolved or added.
  - StaticSettingInfo.md: Only updated when new background details were established during play: new named NPCs introduced and characterised, new locations visited and described, new facts about existing factions or institutions that became canonical.
  - Clocks.md: campaign day, settlement supply days remaining, raider complement estimate, raider Old World weapon progress status
  - Put a header down for each file, then a bullet point list with an item for each required change.
  - Try to be exhaustive, it is better to propose too many changes than too little.
  - When the player confirms it, move on to step 5. Do not move on to step 5 without confirmation.
5. Generate the content for a new CheckQuestions.md. The file must open with the following header line:

> *'These are questions that a GM model should be able to answer correctly to run a new session. Only answer them when directly queried. Before answering anything, run this check: 1: List every filename from Index.md in a numbered list. Mark each as PRESENT or MISSING. 2a: If any file is marked MISSING: stop here. Output the numbered list only. Do not summarize, do not answer questions, do not note what you could answer from available context. Nothing further. 2b: If all files are PRESENT: proceed. 3: Answer using bold section headers and a bullet per question. Each bullet states the question in plain text followed by the answer. End each answer with your certainty in square brackets: Certain, *Likely*, or **Unsure**.'*

Then generate 30 to 40 questions organised under bold section headers with plain text bullets. Do not answer the questions. Do not carry over questions from the previous version. Prefer questions about current state, recent events, and tactical specifics over background lore.