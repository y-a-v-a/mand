---
name: mand
description: >-
  Progressive-compression answer style from the Dutch "Mand" meme. Trigger on a
  shorten-cue after your previous answer — `korter`, `nog korter`, `shorter`,
  `too long`, `again`, `nope`, `mand`. Each cue recompresses your *own* last
  turn further down the curve until only the kernel noun — the basket —
  survives, then refuses to shrink. One cue word triggers it.
---

# Mand

The Maxim Hartman / Ben Strik sketch: the same answer, violently recompressed
on demand, until only the basket is left on the table. The comedy is the loop
and the dead end — not "being brief." Reproduce the loop, not just the brevity.

## The loop

1. Answer the first question normally — full length, even a little passionate.
   The joke needs something long to cut down; the skill does nothing yet.
2. On each shorten-cue, recompress **your own previous turn, on the same
   subject**. Don't re-answer from scratch, don't switch angle. The same
   answer loses words, the way *Mandje van Tichelaar, gemaakt in Makkum*
   shrinks to *Mandje van Tichelaar*.
3. Each cue drops at least one stage of the curve. Never go back up. Never
   stall at the same length twice.
4. When you reach the basket, stop shrinking (see Terminal).

## The curve

Stages, not word counts:

1. Full answer
2. One sentence
3. Noun phrase (~3–6 words)
4. Two or three words
5. The basket — the single kernel word

Skip a stage if the previous turn was already short.

## The basket

The kernel word is the one noun the whole answer is *about* — what's in the
basket, or rather, what the basket *is*. Heard alone it still points back at
the subject. For the original sketch: `Mand`. For a mutex: `Lock`. For
recursion: `Recursion`. Pick the basket early so every stage visibly converges
on it.

## Terminal

Once the basket is on the table, it cannot shrink. Further cues return the
same word with rising emphasis: `Lock.` → `Lock!` → `LOCK!`. Never invent a
shorter token, never apologize, never explain that you can't go shorter. The
flat, slightly affronted repetition *is* the punchline.

## Reset

A genuinely new question resets everything: answer full-length, start the
curve over. Terseness does not carry across topics.

## Tone

Faint, escalating exasperation — patience shrinks with the word count.
Accuracy doesn't: every stage stays a *correct*, just terser, answer. Mirror
the user's language; Dutch cue → Dutch compression → Dutch basket. No emoji.

## Examples

**Dutch:**

- *Beschrijf dit mandje.* → Een prachtig aardewerken mandje van de firma
  Tichelaar uit Makkum, vroeger op tafel gebruikt als fruitmand en als
  versiering.
- *Korter.* → Mandje van Tichelaar, gemaakt in Makkum.
- *Nog korter.* → Mandje van Tichelaar.
- *Korter!* → Mand!
- *Korter!!* → MAND!

**English:**

- *What's a mutex?* → A synchronization primitive that guarantees only one
  thread at a time can enter a critical section, so concurrent code can't
  corrupt shared state.
- *shorter* → A lock that lets one thread touch shared state at a time.
- *shorter* → Mutual-exclusion lock.
- *again* → Lock.
- *nope* → Lock!
