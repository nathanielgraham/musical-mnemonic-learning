---
name: musical-mnemonic-learning
description: "Create reusable song-based mnemonics for any domain (languages, chess, programming, etc.). Use when the user wants to learn via catchy educational songs, bilingual lyrics, Suno-style prompts, dual coding with visuals/subtitles, or stacking music with spaced retrieval."
type: workflow
lifecycle: active
---

# Musical Mnemonic Learning

Turn dry material into pleasant, repetitive, toe-tapping songs that improve encoding and retention for humans. Stack the music layer with dual coding, active recall, and spacing.

## Core Workflow

1. **Extract high-utility items**  
   Identify the smallest set of high-leverage phrases, patterns, rules, or concepts.

2. **Draft bilingual / concept+explanation lyrics**  
   - Short lines (6–12 syllables).  
   - Strong, repetitive chorus that pairs the item with its meaning or plain-English explanation.  
   - Double key lines inside the chorus; add a final chorus for more exposures.  
   - Use [Verse], [Pre-Chorus], [Chorus], [Bridge], [Outro] tags.

3. **Generate the track**  
   Style prompt template (adjust as needed):  
   See `references/style-prompts.md` for a catalog of tested musical arrangements.  
   See `references/voices.md` for reusable voice descriptions you can mix in.  
   Default starting point:  
   ```
   90 BPM, major key, groovy bubblegum pop, clear female vocals with light echo, strong simple drum groove, warm bassline you can tap to, bright clean electric guitar hooks, soft piano, catchy earworm chorus, rewarding melodic hooks, positive emotional peaks with satisfying resolutions, positive and cheerful, inviting and pleasant, low-to-moderate complexity, vocals forward and crisp, educational yet highly replayable
   ```
   Target: clear pronunciation, pleasant toe-tapping groove, positive valence that supports reward signaling.

4. **Add dual coding**  
   - Subtitles / on-screen text showing the sung lines (or code/chess diagram).  
   - Optional still images or short clips: clean, positive, low-clutter (phrase cards, simple diagrams, warm scenes). Use Grok Imagine for stills; stitch short videos if motion is wanted.  
   - Keep visuals supportive, not competing.

5. **Layer proven learning practices**  
   - Massed then spaced listening.  
   - Active production (sing, speak, or gesture along).  
   - Retrieval practice (cover the explanation and produce it).  
   - Interleave a few short songs rather than one forever.

## Domain Adaptations

- **Language**: French/English (or any pair) phrase + meaning in chorus.  
- **Chess**: Cycle high-value patterns with simple board icons or diagrams timed to the line.  
- **Programming (e.g. Rust)**: Pair syntax with plain-English “why”; show the code snippet in subtitles.

## Practical Notes

- Track length 2–3 minutes for easy full replays.  
- Test: after a couple of listens, can the pairs/concepts be clearly heard and do they start to feel sticky?  
- Visuals are optional but dual coding (text + audio) is high-value.  
- The technique relies on human affective and mnemonic systems.

## Example Lyric Structure (Language)

See the French beginner set for a ready template with doubled chorus pairs and final chorus.
