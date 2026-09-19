# optima-history

A cross-course History lesson library for Optima Academy Online, organized by **topic and era**, not by
state course.

## Why this repo exists

Optima teaches several different History courses across different states (Texas History, Mississippi
History, Florida-standards World History, and more), each governed by that state's own standards and
pacing. Those courses overlap heavily in content — a lesson on the Crusades, the Alamo, or the causes of
the Civil War is real historical content that more than one state's course could reasonably draw on, even
though each course cites it against different standards codes.

Rather than write and maintain a near-duplicate lesson per state course, this repo holds lesson content
once, organized by what it's actually about. Which state standards a lesson satisfies is recorded as
**metadata on the lesson itself**, not as the folder it lives in. A course is then something a teacher
assembles — using an editor tool, in the same spirit as `optima-ela-encyclopedia`'s editor — by pulling
whichever topic lessons satisfy that course's standards, in whatever order that course's pacing needs.

## Writing philosophy: narrative first, standards downstream

Each topic folder should be intelligible as its own historical narrative — a good telling of the story of
the American West, or World War II, or Archaic and Classical Greece — written on its own terms as good
history. Standards and courses are downstream consumers of that narrative, not its author: a course
assembles the lessons it needs (per its own standards, pacing, and its teacher's preferences) from
whatever narrative folders already exist, but which standards a lesson happens to satisfy must never be
what shapes how that narrative gets written or what it includes. Write the history first; let courses draw
from it after.

## Design goal: avoid 1:1 folder-to-course mapping

A deliberate goal of this taxonomy is that few, if any, topic folders map cleanly onto a single existing
course. If a folder happened to hold exactly one course's lessons and nothing else, sorting that course's
existing content into this repo would just be a rename — no real reuse would be happening, and the whole
point of the repo would be undermined. Folders that cut across course boundaries (the cross-cutting
narrative folders like `american-west/`, `world-war-ii/`, and `industrial-revolution/`, but also
chronological folders sized so that no single state course owns one exactly) are preferred for this
reason, even when a narrower, course-shaped folder would be simpler to name and scope.

## Status

**Early / experimental.** The topic folders below are a first pass, seeded from lessons already discussed
for Optima's Texas History and World History builds. Expect this taxonomy to be reorganized as real content
gets ported in. The lesson-level metadata schema (standards codes, topic tags, etc.) is not finalized yet
either — see the discussion this repo grew out of before assuming any field name here is final.

## How standards tagging is meant to work (not yet implemented)

The plan is for each lesson to carry frontmatter recording which state standards it could reasonably
satisfy (e.g. Florida B.E.S.T., Texas TEKS, Mississippi standards), re-audited on a recurring basis (the
current idea is annually, each time a state's standards are revised) rather than hand-maintained
indefinitely. That audit is not built yet — this repo currently holds only the folder structure.

## Folder boundaries are guidance, not rules

Each topic folder's README describes its scope and, where two folders could plausibly hold the same
lesson, names a default and a tiebreaker (see `american-civil-war/` and `american-texas/` for an example).
These are meant to alert a writer to the best-fit home and keep placement consistent, not to be inviolable.
Real content will surface edge cases the current wording doesn't anticipate — use judgment, and treat the
boundary language as something to refine over time rather than a rule to satisfy exactly.

## Two kinds of folder: chronological eras and cross-cutting narratives

Most folders are chronological eras with clean, sequential bookends (e.g.
`american-colonial-period/` → `american-revolution-founding/` → `american-early-republic/` →
`jacksonian-westward-expansion/` → `american-civil-war/` → `gilded-progressive/`). A few are
cross-cutting narratives that legitimately span several eras at once, telling one continuous story
regardless of which era-folder's timeframe it crosses — `american-west/` (Lewis and Clark through the
closing of the frontier) is the clearest example, overlapping in time with everything from
`jacksonian-westward-expansion/` through `gilded-progressive/`. `world-war-ii/` and `industrial-revolution/` are further examples, but of a different shape: rather than
overlapping a fixed time range, they're scoped by relevance to a single event or phenomenon, so a lesson
can reach back into whatever decade it needs (Weimar Germany, Japanese imperialism, the Depression; or
Britain's textile mills spreading to America) as long as the lesson is actually about explaining that
event or phenomenon. This overlap is expected, not a flaw in the taxonomy; where it creates a real
placement question, the relevant folders' READMEs name a default and a tiebreaker (see `american-west/`'s
note on the Texas folders, `american-civil-war/`'s note on `american-texas/`, `world-war-ii/`'s note on
`roaring-20s-great-depression/`, or `industrial-revolution/`'s note on `gilded-progressive/`).

## Topic folders

- `spanish-republic-texas/`
- `american-texas/`
- `american-colonial-period/`
- `american-revolution-founding/`
- `american-early-republic/`
- `jacksonian-westward-expansion/`
- `american-west/`
- `archaic-classical-greece/`
- `roman-founding-republic/`
- `roman-empire/`
- `hellenistic-world/`
- `persian-near-east/`
- `age-of-exploration/`
- `american-civil-war/`
- `gilded-progressive/`
- `roaring-20s-great-depression/`
- `world-war-ii/`
- `industrial-revolution/`

Each is a placeholder for now (a short README describing its scope). None contain real lesson content yet.
