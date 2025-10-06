# Copilot Instructions

These notes keep every automated helper aligned with the way **The Tale of Darā** repository is organized and expanded. Read them before proposing edits, and double-check them whenever you start a new task.

## Repository Map

- `Base.md`: Legacy linear draft. Treat it as a staging ground only—finished prose lives inside the structured chapter folders. Replace migrated passages with editorial pointers.
- `Chapters/Chapter XX/Section YY/INDEX.md`: Canonical home for story content. Each section file must contain:
  - Introductory context (one or two sentences).
  - A scene table (columns: scene number & title, summary, linked locations).
  - `## روایت کامل` with subsections that elaborate each scene beat.
  - Enough layered prose to cover at least two A5 pages of continuous narrative—expand sensory detail, micro-actions, and dialogue until the requirement is naturally met.
  - Continuity notes pointing to the next/previous sections when relevant.
- `Characters/`: One Markdown file per character plus `INDEX.md`. Add or update entries whenever a character is introduced or evolves.
- `Locations/`: One Markdown file per location plus `INDEX.md`. Document new places immediately after they appear.

## Core Workflow

1. **Plan first.** Outline the steps you intend to take (e.g., read context, design structure, apply edits). Use the todo tooling provided by the environment.
2. **Read before writing.** Pull the latest section, character, and location files to stay consistent with existing lore.
3. **Migrate deliberately.** When moving text from `Base.md` into a section file:
   - Copy the prose into the relevant `Chapters/.../INDEX.md` below the scene table.
   - Trim the original passage from `Base.md` and leave a note linking to the new home.
4. **Keep documentation in sync.** Any new person, creature, faction, artifact, or location must be described in the appropriate folder the moment it arrives on the page, capturing the same first-appearance specifics (attire, voice, bearing, notable scents, accessories).
5. **Link everything.** In tables and prose, wrap references to locations or other sections with relative Markdown links.
6. **Validate tone and continuity.** Check earlier sections and character sheets to avoid contradictions. Note open threads where helpful.

## Style Requirements

- **Detail level:** Render environments, sensations, and small gestures with the granular care of George R. R. Martin—weather, textiles, scents, and political subtext should all register.
- **First introduction:** Whenever a character appears for the first time, deliver a vivid portrait that covers face, clothing, movement, voice, and the emotional effect on onlookers; treat it as if the reader is standing in front of them.
- **Emotional voice:** Balance that detail with the hopeful, wonder-filled cadence of J. K. Rowling. Keep the prose accessible, focusing on curiosity, friendship, and resilience even in darker moments.
- **Language:** Farsi Markdown with typographic quotes and dashes as already established. Preserve existing formatting conventions.
- **Scene headers:** Use `###` subsections named in Persian, matching the scene table titles where possible.
- **Narrative volume:** Sustain each section at a minimum length equivalent to two A5 pages of continuous prose by layering sensory description, purposeful dialogue, and character reactions for every beat.

## Quality Checklist

Before declaring a task done:

- [ ] Scene table matches the full narrative (same number of beats, consistent summaries).
- [ ] All new entities recorded in `Characters/` or `Locations/` with up-to-date data.
- [ ] `Base.md` contains only references to migrated content, not duplicated prose.
- [ ] Cross-links between sections and location files are valid.
- [ ] Notes on future work or unanswered questions are captured in the relevant section file.

Following this guide keeps the story world coherent and the documentation trustworthy. Whenever a process question arises, update this document with the clarified expectation.