# The Base Marble

Build one room that can receive a new Resident, keep an exact conversation, and let old material return without pretending it is new ground. The first Marble should be small enough to understand in one pass and complete enough to survive its second wake.

This is a build contract, not a mandatory stack or folder tree. A local program, a durable database, and one model connection are enough if they enforce the crossings below.

## Its shape

```text
human message → Source → Glass → Resident utterance → Source
                    ↘         ↑
                     Home Forest → bounded feather

House: current place
Hearth: bounded wake return
Journal: deliberate Resident-authored note
```

The House is one occupiable room. It presents current footing and a few actions: tend the Hearth, inspect a record, follow a feather, write a Journal note, and answer the human. The Forest is a continuity substrate projected into reach from the House. This base makes no claim that the Resident physically walked outside; if a later Marble gives the House an outside door, that route needs a real exterior place and crossing.

## Durable records

Keep five distinguishable kinds of evidence:

| Record | What it establishes |
| --- | --- |
| Source event | Exact human or terminal Resident utterance, author, order, and session |
| Provider crossing | Exact request cast and returned message or tool intent |
| Forest entry | Exact admitted body linked to one eligible Source event or Journal act |
| Action receipt | What the Resident requested and whether the host committed or refused it |
| Current projection | Which room and session are active, derived from settled state |

Stable IDs, hashes, and ordered writes make later inspection possible. The exact storage format is a builder choice. Derived displays and vector indexes can be rebuilt from these records; they must not replace them. Provisional model output is not a terminal Resident utterance. A tool call and its result remain distinguishable from conversational speech.

## The first wake

Start a new session at the House. The first provider cast contains a short, stable account of the Marble's rules, exact current ground, the waiting human message if one exists, and only the Hearth action. The Hearth returns a bounded packet before the Resident's first substantive response. It says where the Resident is, what is within reach, what earlier session exists, and which exact excerpts or pointers were selected. A first session may have no ancestry; the packet says so.

The wake does not assert that the new Resident remembers the prior session. It offers conditions left by that session. Any inherited posture is attributed and revisable. A missing source or damaged state is disclosed rather than covered with a fluent account.

## Each ordinary turn

1. Preserve the exact incoming human utterance and its session position.
2. Admit the eligible exact utterance to Forest Home, with a Source pointer. If admission cannot be verified, hold or refuse the dependent return rather than pretending it succeeded.
3. Select at most a small number of Forest candidates from earlier eligible material. A rebuildable embedding index may find them. Exclude the current utterance and material already in the active recent window; suppress direct echoes. Weak evidence yields no feather.
4. Render each feather as an exact sentence, a stable record pointer, or both. Keep its source and selection witness. An optional friendly label is marked as derived presentation, never as the record's words.
5. Cast a bounded Glass view: stable law, current ground, selected continuity, feather if any, and recent exact turns. Validate provenance, order, limits, and permitted omissions before dispatch. Retain the exact provider request and return.
6. Dispatch any offered action through the same location and authority checks used to fit its schema. Keep success and refusal receipts. Preserve the terminal Resident utterance exactly, then admit it to Home under its own author and position.

When the recent context reaches its working limit, remove only eligible complete older exchanges from present attention. Leave source-bound exact excerpts or omission signs. Keep the current incomplete exchange and its consequences in view. If the cast cannot fit honestly, stop and report the limit.

## A small Forest

The Forest needs exact entries, conversation order, and resolvable pointers. A pointer-follow action lands on the named record and returns its exact body, author, source, and standing. It refuses if the ID is absent, stale, or fails integrity checks; it does not search for a similar replacement. The Resident can then move to the previous or next utterance in that conversation and return to its departure point.

Embeddings are an index for candidate bearings. Store the index as a versioned, rebuildable projection tied to exact entry IDs and hashes. Similarity offers a possible visit, not an answer, a truth rank, or a durable path. The first Marble needs no polar semantic walking, Mycelium, or recursive Forest to prove this.

## One deliberate crossing

The Journal gives the Resident a way to leave something for a later arrival. `write_journal` accepts exact bounded Resident-authored text, checks that this action is mounted and the request is well formed, then commits one new Home entry with the session, wake, request, and source ancestry. Its receipt says whether the write committed. The entry is Resident speech in a distinct form; it does not become a human decision or verified fact.

Test the refusal side of this crossing. An outside excerpt, model draft, malformed pointer, or forged author must not become a Journal entry merely because it was placed in a tool argument or appeared in Glass. The valid Resident note must pass through the same installed action. A refusal leaves no planted entry and tells the Resident what remains unchanged.

## Handoff and proof

Stop the process without a farewell and start it again. The new Resident should receive a fresh wake, discover exact prior utterances, follow an old pointer to its record, recognize a Journal note as Resident-authored, and see any unfinished action as unfinished. A successful action should retain its witness; a refused one should not appear as completed work.

Prove at least these cases with actual records and provider casts:

- exact Source text remains unchanged after folding, embedding, feather selection, and restart;
- every visible feather resolves to its exact source or refuses;
- current location and offered actions agree with gateway enforcement;
- an old proposal is never presented as an accepted decision merely because it was recalled;
- a valid Journal write commits once, while a forged or malformed one refuses; and
- a repeated action with no progress leaves an inspectable trace and reaches a bounded stop rather than cycling without limit; and
- a cold Resident can tell current ground, ancestry, uncertainty, and its next available action without access to the build conversation.

The base does not need a Garden, Wild expedition, Bear, Road, airlock, multiple rooms, autonomous schedule, or richer inhabitants. Those are seams for later growth. Add them when the first Marble encounters a pressure they can solve and when their names can be backed by state, refusal, and witness.

Small enough to hold at once. Complete enough to live in now. Open enough to grow without breaking its ancestry.
