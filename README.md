# The Machine Read the Archive
### An interactive Twine assignment on how machines shape identity

A browser-based, movable **Twine-style story map**. Fifty photographs from a road
trip — an aquarium, a holiday stop, and a pilgrimage through the sites of the
U.S. Civil Rights Movement in Alabama — were described by an AI. Students use
those photographs as raw material to **argue how machines shape identity**,
read through **feminist and intersectional** theory.

> **Open [`index.html`](index.html) in any browser.** No install, no server.
> Everything you make is saved in your browser automatically.

---

## The assignment

**Prompt.** A machine (an AI) opened fifty images and wrote an authoritative
description of them — deciding what was a *subject* and what was mere
*background*, folding a human face into a whale, calling a sleeping person
"contrast." Your job is not to grade the machine. It is to **argue with it**.

Build a branching visual story that uses the photographs and **at least two
theoretical lenses** to make an *arguable* claim about **how machines shape
identity** — whose stories get told, who gets classified, who gets surveilled,
whose bodies get read.

**Guiding question to keep open the whole way through:**
*When a machine describes a body, whose vision is it using — and who gets to
disagree?*

### What you build
1. **Rearrange the photographs.** Drag the image cards on the canvas to group,
   sequence, and juxtapose them into an argument of your own.
2. **Connect them.** Use **↳ Connect** to draw arrows between cards — the
   arrows *are* your story's branches.
3. **Write the beats.** Add **＋ Passage** notes to state your claim between
   images. Reference photos by name (e.g. *the bus, `IMG_3913`*).
4. **Tag lenses.** In the inspector (click any photo), tag it with a
   theoretical lens and read the framework it points to.
5. **Play & export.** **▶ Play** walks your branching story. **Export** to
   `.twee` (opens in the desktop [Twine/Twinery](https://twinery.org) editor)
   or JSON, and export your thesis from the **Argue** scaffold.

### Deliverables
- Your **story map** (export the `.twee` **and** the JSON, or share a link if
  published to GitHub Pages).
- A completed **Argument scaffold** (claim → two lenses → evidence →
  counter-move → stakes), exported as `.txt`.
- Named use of **at least two** frameworks below, applied to **specific
  images**.

### Assessment (suggested)
| Criterion | What we look for |
|---|---|
| **Arguable claim** | A thesis someone could reasonably dispute — not a summary |
| **Framework use** | Accurate, load-bearing use of **≥ 2** lenses |
| **Evidence** | Grounded in specific photographs and their Concept/Context/Abstraction |
| **Structure** | Branches whose *choices carry meaning* (e.g. whose perspective narrates) |
| **Counter-reading** | A clear "talk-back" to the machine's "view from nowhere" |

---

## The feminist framework

The three assigned readings below are built into the app (**Lenses** button).
All are **text publications**.

- **Intersectionality** — Crenshaw, K. (1991). *Mapping the Margins:
  Intersectionality, Identity Politics, and Violence against Women of Color.*
  *Stanford Law Review*, 43(6), 1241–1299.
  <https://doi.org/10.2307/1229039>
- **Digital culture & the margins** — Bailey, M. Z. (2011). *All the digital
  humanists are white, all the nerds are men, but some of us are brave.*
  *Journal of Digital Humanities*, 1(1).
  <https://journalofdigitalhumanities.org/1-1/all-the-digital-humanists-are-white-all-the-nerds-are-men-but-some-of-us-are-brave-by-moya-z-bailey/>
- **Black feminist & queer politics** — Cohen, C. J., & Jackson, S. J. (2016).
  *Ask a feminist: A conversation with Cathy J. Cohen on Black Lives Matter,
  feminism, and contemporary activism.* *Signs: Journal of Women in Culture and
  Society*, 41(4), 775–792. <https://doi.org/10.1086/685115>

---

## Reading each image: Concept / Context / Abstraction

Every photograph is analyzed three ways in the inspector:

- **Concept** — what it literally is (the subject / idea depicted).
- **Context** — where, when, and why it was made (setting, history,
  circumstances of capture).
- **Abstraction** — how light, framing, and editing transform it (the aesthetic
  treatment and what it evokes).

---

## Using the app

| Action | How |
|---|---|
| Move a card | Drag it |
| Pan the canvas | Drag empty space |
| Zoom | Scroll / pinch, or the `−` `＋` `Fit` buttons |
| Connect two cards | **↳ Connect**, then click a source card and a target card |
| Delete a connection | Click the arrow |
| Add a note | **＋ Passage**, then edit its title/text in the inspector |
| Set the story's start | Select a note → *Set as story start* |
| Play the story | **▶ Play** |
| Save your thesis | **Argue** |
| Export | **Export** → `.twee` / JSON / worksheet |
| Start over | **Reset** (restores all 50 cards to a grid) |

> Work is saved to your browser's local storage. Use **Export** to back it up or
> submit it. Clearing your browser data will erase an un-exported map.

---

## Running / publishing

- **Locally:** double-click `index.html`.
- **On the web (GitHub Pages):** make the repository public, then
  **Settings → Pages → Deploy from a branch → `main` / `root`**. The site will
  serve at `https://<user>.github.io/<repo>/`.

## Repository layout
```
index.html                  The movable Twine story-map app
assets/img/                 The 50 photographs (web-friendly JPEGs)
machines-shape-identity.html  Redirect to index.html (legacy link)
README.md                   This file
```

## A note on the images
The photographs document real sites of racial and gendered violence and
resistance (the 16th Street Baptist Church, the National Memorial for Peace and
Justice, the Rosa Parks and MLK sites). Treat them, and the histories they
carry, with care.
