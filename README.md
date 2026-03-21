# MCTsummit.eu

This repo is the source of  **MCTSummit.EU**, website meant to be a central hub and an archive for **M**icrosoft **C**ertified **T**rainers.

Since Microsoft introduced the MCT program in the 1990s, a lot of passionate lecturers, trainers, consultants engaged in educating IT pros all around the world. What started as a mix of certification and partner program, became a vivid community of people - sharing knowledge, meeting all over the places, simply enjoyed having a drink together.

Most summits have been organized on a strictly private basis. This website is meant as a wiki, documenting talks, collecting pictures, to indulge in memories.

You are very welcome to add content to this website. Provide information, links, pictures, etcetera. I will provide detailed information on this when the time is right. Please contact me any time with questions and proposals.

Although this site focuses primarily on (past and future) European events - we also love to link and advertise MCT summits all over the globe.

## Documentation (contributors & agents)

- **[IMPLEMENTATION.md](IMPLEMENTATION.md)** — Site structure, navigation (desktop vs mobile header, search), summit content rules, front matter (including optional `date` / **Created** line), agenda tables.
- **[VISION.md](VISION.md)** — Project purpose, goals, and scope.
- **`.cursor/rules/`** — Cursor memory-bank rules (e.g. `summit-structure.mdc`, `agenda-tables.mdc`, `header-navigation.mdc`); keep them aligned when changing layout or conventions.

**Build:** Hugo; config **`hugo.toml`**. Production **`baseURL`** is set there; `hugo server` uses localhost for preview. Client search needs **`enableSearch`** and home output **`JSON`** (see IMPLEMENTATION.md §4.3).