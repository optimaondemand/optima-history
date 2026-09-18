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

## Topic folders

- `spanish-republic-texas/`
- `archaic-classical-greece/`
- `roman-founding-republic/`
- `roman-empire/`
- `hellenistic-world/`
- `persian-near-east/`
- `age-of-exploration/`
- `american-civil-war/`

Each is a placeholder for now (a short README describing its scope). None contain real lesson content yet.
