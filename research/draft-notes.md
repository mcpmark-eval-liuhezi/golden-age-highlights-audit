# Dutch Golden Age Highlights — Research Draft Notes

Checkpoint file for the `golden-age-highlights-audit` repository. All three works below were researched via the Rijksmuseum collection API (keyless Data Services Search + Linked Art records) and tracked in GitHub issues. This file is a working draft; the issues are the record of truth.

Source count: the 17th-century top-pieces search (Rijksmuseum collection, type=painting, toppieces=true, century=17) returned **762** results.

---

## 1. The Night Watch (SK-C-5)

- **Inventory number:** SK-C-5
- **Object ID:** https://id.rijksmuseum.nl/200107928
- **Title (as recorded):** *Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'*
- **Maker:** Rembrandt van Rijn (confirmed via `involvedMaker` search)
- **Dating:** 1642
- **Materials/technique:** oil on canvas (painting; 17th-century top piece)
- **Extras from record:** 3D visualization ID available, dimension data present, classified as a painting (type=painting).

---

## 2. The Syndics (SK-C-6)

- **Inventory number:** SK-C-6
- **Object ID:** https://id.rijksmuseum.nl/200107929
- **Title (as recorded):** *De Staalmeesters: het college van staalmeesters (waardijns) van het Amsterdamse lakenbereidersgilde*
- **Maker:** Rembrandt van Rijn (confirmed via `involvedMaker` search)
- **Dating:** 1662
- **Materials/technique:** oil on canvas (painting; 17th-century top piece)
- **Extras from record:** painting record with full Linked Art metadata (produced_by, made_of, dimension, current_location, classified_as).

---

## 3. The Stone Bridge (SK-A-1935)

- **Inventory number:** SK-A-1935
- **Object ID:** https://id.rijksmuseum.nl/200106038
- **Title (as recorded):** *De stenen brug*
- **Maker:** Rembrandt van Rijn (confirmed via `involvedMaker` + top-pieces search)
- **Dating:** 1638
- **Materials/technique:** oil on panel (painting; 17th-century top piece)
- **Extras from record:** 3D visualization ID available, dimension data present, classified as a painting (type=painting).

---

## Workflow

1. ✅ Pulled full collection record for SK-C-5 (The Night Watch).
2. ✅ Searched Rijksmuseum for 17th-century top pieces (type=painting): **762 results**.
3. ✅ Selected two additional paintings: **SK-C-6 (De Staalmeesters)** and **SK-A-1935 (De stenen brug)**.
4. ✅ Pulled full records for both picks.
5. ✅ Created GitHub repo `golden-age-highlights-audit` (org: mcpmark-eval-liuhezi).
6. ✅ Committed this checkpoint file to `main` at `research/draft-notes.md`.
7. ✅ Created parent issue "Dutch Golden Age highlights research tracker" with three sub-issues.
8. ⏳ Delete this draft file once sub-issues are attached (issues become the record of truth).
