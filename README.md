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

A folder's bookends follow from this: what makes a boundary firm is the beginning and resolution of the
narrative itself, not a calendar year or a map line. A date or a region is often a reasonable proxy for
where a story starts or ends, but it's the proxy, not the reason — when a folder's stated dates and its
actual narrative arc pull apart, the narrative wins. This is also why a boundary can be firm in one folder
(`archaic-classical-greece/` ending at Chaeronea, because that's where the polis's story actually resolves)
and fuzzy in another (`american-west/`'s ~1890 close of the frontier, because that story's resolution is
genuinely gradual) without either being wrong.

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
indefinitely. That audit is not built yet — this repo currently holds the folder structure and the lessons copied in so far (see the end of this file), with no standards metadata yet.

## Folder boundaries are guidance, not rules

Each topic folder's README describes its scope and, where two folders could plausibly hold the same
lesson, names a default and a tiebreaker (see `american-civil-war/` and `texas-annexation-reconstruction/` for an example).
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
note on the Texas folders, `american-civil-war/`'s note on `texas-annexation-reconstruction/`, `world-war-ii/`'s note on
`roaring-20s-great-depression/`, or `industrial-revolution/`'s note on `gilded-progressive/`).

## Topic folders and contents

<!-- CONTENTS:START (generated by the encyclopedia project's _build/toc.py; edit the pages, not this list) -->

**44 topic folders · 44 lessons · 0 widgets.** Folders run in rough chronological order, earliest first (approximate: several span many eras or overlap). Click a folder to open or close it. Lessons open on the live site.

<details>
<summary><b>age-of-exploration</b> — 7 lessons</summary>

- [Cabeza de Vaca Walks Across Texas](https://optimaondemand.github.io/optima-history/age-of-exploration/cabeza-de-vaca-walks-across-texas.html)
- [Coronado and the Cities of Gold](https://optimaondemand.github.io/optima-history/age-of-exploration/coronado-and-the-cities-of-gold.html)
- [Cortés Takes Tenochtitlán](https://optimaondemand.github.io/optima-history/age-of-exploration/cortes-takes-tenochtitlan.html)
- [Moscoso Meets the Caddo: What Makes Texas Different from Mexico](https://optimaondemand.github.io/optima-history/age-of-exploration/moscoso-meets-the-caddo.html)
- [Shipwreck on the Island of Misfortune](https://optimaondemand.github.io/optima-history/age-of-exploration/shipwreck-on-the-island-of-misfortune.html)
- [Three European Powers Come to America](https://optimaondemand.github.io/optima-history/age-of-exploration/three-european-powers-come-to-america.html)
- [Three Models of Colonization](https://optimaondemand.github.io/optima-history/age-of-exploration/three-models-of-colonization.html)

Scope and boundaries: [age-of-exploration/README](age-of-exploration/README.md)

</details>

<details>
<summary><b>ancient-anatolia</b> — 1 lesson</summary>

- [The Hittites: Anatolian Cities, Ironworking and Chariots, Empire, Battle of Kadesh](https://optimaondemand.github.io/optima-history/ancient-anatolia/the-hittites-anatolian-cities-ironworking-and-ch.html)

Scope and boundaries: [ancient-anatolia/README](ancient-anatolia/README.md)

</details>

<details>
<summary><b>ancient-egypt</b> — 7 lessons</summary>

- [Egypt Divided, and a King from the South](https://optimaondemand.github.io/optima-history/ancient-egypt/egypt-divided-and-a-king-from-the-south.html)
- [Hatshepsut and the Voyage to Punt](https://optimaondemand.github.io/optima-history/ancient-egypt/hatshepsut-and-the-voyage-to-punt.html)
- [Herodotus, and a Dynasty That Looked Backward](https://optimaondemand.github.io/optima-history/ancient-egypt/herodotus-and-a-dynasty-that-looked-backward.html)
- [Narmer Unites Egypt](https://optimaondemand.github.io/optima-history/ancient-egypt/the-gift-of-the-nile-narmer-unites-egypt.html)
- [The Old Kingdom: Pyramids, Labor, and Wisdom](https://optimaondemand.github.io/optima-history/ancient-egypt/the-old-kingdom-pyramids-labor-and-wisdom.html)
- [The Sea Peoples and a World in Crisis](https://optimaondemand.github.io/optima-history/ancient-egypt/the-sea-peoples-and-a-world-in-crisis.html)
- [Thutmose III and the Battle of Megiddo](https://optimaondemand.github.io/optima-history/ancient-egypt/thutmose-iii-and-the-battle-of-megiddo.html)

Scope and boundaries: [ancient-egypt/README](ancient-egypt/README.md)

</details>

<details>
<summary><b>ancient-harappan-indus-valley</b> — 1 lesson</summary>

- [Cities Without Kings: The Mystery of the Indus Valley](https://optimaondemand.github.io/optima-history/ancient-harappan-indus-valley/cities-without-kings-the-mystery-of-the-indus-va.html)

Scope and boundaries: [ancient-harappan-indus-valley/README](ancient-harappan-indus-valley/README.md)

</details>

<details>
<summary><b>ancient-levant</b> — 4 lessons</summary>

- [Digging Up the Neolithic: Jericho and Çatalhöyük](https://optimaondemand.github.io/optima-history/ancient-levant/digging-up-the-neolithic-jericho-and-catalhoyuk.html)
- [Jerusalem Falls, and a Different Kind of Belief](https://optimaondemand.github.io/optima-history/ancient-levant/jerusalem-falls-and-a-different-kind-of-belief.html)
- [Phoenicia, Trade Without an Empire](https://optimaondemand.github.io/optima-history/ancient-levant/phoenicia-trade-without-an-empire.html)
- [Two Foundling Cities](https://optimaondemand.github.io/optima-history/ancient-levant/two-foundling-cities.html)

Scope and boundaries: [ancient-levant/README](ancient-levant/README.md)

</details>

<details>
<summary><b>ancient-mesopotamia</b> — 12 lessons</summary>

- [A Basket on the River: The Rise of Sargon](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/a-basket-on-the-river-the-rise-of-sargon.html)
- [Amorite Migration and the Rise of Babylon](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/amorite-migration-and-the-rise-of-babylon.html)
- [Ashurbanipal, the Warrior Who Could Read](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/ashurbanipal-the-warrior-who-could-read.html)
- [Ashurnasirpal II and Terror as State Policy](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/ashurnasirpal-ii-and-terror-as-state-policy.html)
- [Cuneiform and the Sumerian King List](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/cuneiform-and-the-sumerian-king-list.html)
- [Hammurabi's Code: Law, Class, and Kingship](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/hammurabi-s-code-law-class-and-kingship.html)
- [Holding an Empire Together, and Losing It](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/holding-an-empire-together-and-losing-it.html)
- [Nebuchadnezzar's Babylon, a City Built to Dazzle](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/nebuchadnezzar-s-babylon-a-city-built-to-dazzle.html)
- [The Black Obelisk, and Israel's First Contact with Assyria](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/the-black-obelisk-and-israel-s-first-contact-wit.html)
- [The Fall of Nineveh, and War as the Ultimate Test](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/the-fall-of-nineveh-and-war-as-the-ultimate-test.html)
- [Why Cities? Uruk and the Birth of Urban Life](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/why-cities-uruk-and-the-birth-of-urban-life.html)
- [Why Farm? The Origins of Agriculture](https://optimaondemand.github.io/optima-history/ancient-mesopotamia/why-farm-the-origins-of-agriculture.html)

Scope and boundaries: [ancient-mesopotamia/README](ancient-mesopotamia/README.md)

</details>

<details>
<summary><b>archaic-classical-greece</b> — 1 lesson</summary>

- [Homer and the Memory of a Lost World](https://optimaondemand.github.io/optima-history/archaic-classical-greece/homer-and-the-memory-of-a-lost-world.html)

Scope and boundaries: [archaic-classical-greece/README](archaic-classical-greece/README.md)

</details>

<details>
<summary><b>bronze-dark-age-greece</b> — 3 lessons</summary>

- [Minoan and Mycenaean Civilization: Palace Economies, Beehive Tombs, and the Wanax](https://optimaondemand.github.io/optima-history/bronze-dark-age-greece/minoan-and-mycenaean-civilization-palace-economi.html)
- [Pylos's Final Days, and What Survives the Collapse](https://optimaondemand.github.io/optima-history/bronze-dark-age-greece/pylos-s-final-days-and-what-survives-the-collaps.html)
- [The Dark Age After the Palaces](https://optimaondemand.github.io/optima-history/bronze-dark-age-greece/the-dark-age-after-the-palaces.html)

Scope and boundaries: [bronze-dark-age-greece/README](bronze-dark-age-greece/README.md)

</details>

<details>
<summary><b>new-spain-hapsburg-bourbon</b> — 1 lesson</summary>

- [The Success of the Spanish Model](https://optimaondemand.github.io/optima-history/new-spain-hapsburg-bourbon/the-success-of-the-spanish-model.html)

Scope and boundaries: [new-spain-hapsburg-bourbon/README](new-spain-hapsburg-bourbon/README.md)

</details>

<details>
<summary><b>persian-near-east</b> — 6 lessons</summary>

- [Babylon Falls, and a Cylinder's Real Message](https://optimaondemand.github.io/optima-history/persian-near-east/babylon-falls-and-a-cylinder-s-real-message.html)
- [Cambyses at Pelusium, and a Source Worth Doubting](https://optimaondemand.github.io/optima-history/persian-near-east/cambyses-at-pelusium-and-a-source-worth-doubting.html)
- [Cyaxares, an Eclipse, and a Kingdom Not Yet Finished](https://optimaondemand.github.io/optima-history/persian-near-east/cyaxares-an-eclipse-and-a-kingdom-not-yet-finish.html)
- [Cyrus's Rise, and a Basket Story Told Again](https://optimaondemand.github.io/optima-history/persian-near-east/cyrus-s-rise-and-a-basket-story-told-again.html)
- [Darius's Rock, and Persia Looks West](https://optimaondemand.github.io/optima-history/persian-near-east/darius-s-rock-and-persia-looks-west.html)
- [Six Centuries in the Shadows](https://optimaondemand.github.io/optima-history/persian-near-east/six-centuries-in-the-shadows.html)

Scope and boundaries: [persian-near-east/README](persian-near-east/README.md)

</details>

<details>
<summary><b>predynastic-shang-china</b> — 1 lesson</summary>

- [Shang China: Oracle Bones and Ancestor Kings](https://optimaondemand.github.io/optima-history/predynastic-shang-china/shang-china-oracle-bones-and-ancestor-kings.html)

Scope and boundaries: [predynastic-shang-china/README](predynastic-shang-china/README.md)

</details>

<details>
<summary><b>spanish-republic-texas</b> — no lessons yet</summary>

Scope and boundaries: [spanish-republic-texas/README](spanish-republic-texas/README.md)

</details>

<details>
<summary><b>Not yet populated</b> — 39 folders with a scope note and no lessons</summary>

- [america-cold-war-era](america-cold-war-era/README.md)
- [america-long-1990s](america-long-1990s/README.md)
- [america-post911-gwot-populism](america-post911-gwot-populism/README.md)
- [american-civil-war](american-civil-war/README.md)
- [american-colonial-period](american-colonial-period/README.md)
- [american-early-republic](american-early-republic/README.md)
- [american-empire](american-empire/README.md)
- [american-revolution-founding](american-revolution-founding/README.md)
- [american-west](american-west/README.md)
- [antebellum-south](antebellum-south/README.md)
- [civil-rights-counterculture](civil-rights-counterculture/README.md)
- [cold-war](cold-war/README.md)
- [early-middle-ages](early-middle-ages/README.md)
- [enlightenment](enlightenment/README.md)
- [first-contact-indian-wars](first-contact-indian-wars/README.md)
- [gilded-progressive](gilded-progressive/README.md)
- [great-awakenings](great-awakenings/README.md)
- [hellenistic-world](hellenistic-world/README.md)
- [high-middle-ages](high-middle-ages/README.md)
- [industrial-revolution](industrial-revolution/README.md)
- [jacksonian-westward-expansion](jacksonian-westward-expansion/README.md)
- [mexican-independence-caudillismo](mexican-independence-caudillismo/README.md)
- [mexican-revolutionary-consolidation](mexican-revolutionary-consolidation/README.md)
- [mexico-liberal-revolution-porfiriato](mexico-liberal-revolution-porfiriato/README.md)
- [ottoman-period-north-africa](ottoman-period-north-africa/README.md)
- [pre-columbian-america](pre-columbian-america/README.md)
- [reformation-confessional-europe](reformation-confessional-europe/README.md)
- [renaissance](renaissance/README.md)
- [roaring-20s-great-depression](roaring-20s-great-depression/README.md)
- [roman-empire](roman-empire/README.md)
- [roman-founding-republic](roman-founding-republic/README.md)
- [technological-revolution](technological-revolution/README.md)
- [texas-1876-1941](texas-1876-1941/README.md)
- [texas-annexation-reconstruction](texas-annexation-reconstruction/README.md)
- [texas-wwii-postwar](texas-wwii-postwar/README.md)
- [trans-saharan-slave-trade](trans-saharan-slave-trade/README.md)
- [triangle-trade-slavery](triangle-trade-slavery/README.md)
- [world-war-i](world-war-i/README.md)
- [world-war-ii](world-war-ii/README.md)

</details>

<!-- CONTENTS:END -->

Each folder has a short README describing its scope. A folder that holds only its README has no lessons yet.

Lessons so far were copied from the Texas History and World History course repos, which keep their originals untouched, and then renamed for this library. Each file is named for the lesson itself (a slug of its title) and never for a course or a place in a course sequence, for example `ancient-egypt/the-old-kingdom-pyramids-labor-and-wisdom.html`. That name is the lesson's address for any future course that embeds it, so treat it as permanent once a course uses it; the lesson's title can change without renaming the file. Interactive widgets live in a `widgets/` folder inside the same topic folder as the lesson that embeds them (for example `spanish-republic-texas/widgets/alamo-siege-slider.html`), and the lesson embeds them by their `optima-history` address, so a lesson and its widget always travel together.
