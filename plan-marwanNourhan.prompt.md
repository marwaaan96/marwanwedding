## Plan: Lifetime Contract Invitation

Build a single-page, print-ready English wedding invitation as a premium “lifetime contract” between Marwan and Nourhan. The recommended approach is a static HTML/CSS deliverable with a strong legal-document structure, luxury styling accents, subtle playful copy, and a swappable photo slot so the final output exports cleanly to PDF and still works on screen.

**Steps**
1. Phase 1 — Content architecture. Draft the invitation copy and section order around the contract concept: title, contracting parties, effective date and time, venue, short Marwan profile clause, agreement language, and signatures. This step defines the exact tone balance: formal/legal at the structure level, with a few smart playful lines and polished luxury phrasing.
2. Phase 1 — Information design. Translate the brief into a one-page layout with these blocks: contract header, declaration paragraph, Marwan journey clause, event details panel, signatory/photo area, and signature footer. Keep the page scannable enough for guests while preserving the “document” illusion.
3. Phase 2 — Base markup. Create the main HTML page with semantic sections, clear text placeholders, and a dedicated image slot that can be hidden or replaced without affecting layout. This depends on steps 1 and 2.
4. Phase 2 — Visual system. Build the CSS design language: refined serif headline styling, supporting document-style body typography, controlled gold/ink palette, paper-like background treatment, clause dividers, and signature-line styling. Add responsive rules for phone viewing and print rules for clean PDF export. This depends on step 3.
5. Phase 2 — Concept polish. Layer in brief-specific identity cues without making the page busy: a subtle football-era reference, a media/campaign metaphor for the wedding launch, and a premium contract seal feel around the date, time, and venue. This runs in parallel with step 4 once the core layout exists.
6. Phase 3 — Asset integration. Add the final couple photo into the prepared frame/slot, tune cropping and contrast, and verify the design still reads well if the image is removed for a text-only fallback. This depends on step 3 and on receiving the replacement photo.
7. Phase 3 — Export support. Add a minimal README with how to preview locally, replace the image asset, and export to PDF from the browser while preserving margins and colors. This depends on steps 4 and 6.
8. Phase 3 — Final QA. Verify the invitation at desktop width, phone width, and browser print preview; check hierarchy, spacing, legibility, and whether the tone lands as “formal + smart + luxury” rather than overly corporate or overly playful. This depends on steps 4 through 7.

**Relevant files**
- d:\Projects\Wedding Contract\index.html — main invitation document, content sections, text placeholders, and image slot.
- d:\Projects\Wedding Contract\styles.css — layout, visual tokens, luxury/contract styling, responsive rules, and print stylesheet behavior.
- d:\Projects\Wedding Contract\assets\ — final couple photo and any lightweight decorative assets if needed.
- d:\Projects\Wedding Contract\README.md — local preview, photo replacement, and PDF export instructions.

**Verification**
1. Open the HTML in a browser and confirm all required details are present exactly: Marwan, Nourhan, June 6 2026, 6:00 PM, Holiday Inn Hotel Maadi.
2. Use browser print preview and confirm the full invitation fits cleanly on one page with preserved spacing and readable typography.
3. Check the mobile viewport to ensure the layout stacks cleanly and the photo does not break text flow.
4. Swap in the final photo and confirm the composition still feels balanced; if not, fall back to text-only mode without breaking the layout.

**Decisions**
- Language: English only.
- Deliverable: static print-ready HTML that can be exported to PDF.
- Tone: hybrid of elegant legal-contract structure, smart playful copy, and bold modern luxury styling.
- Photo handling: prepare the design for a later replacement image rather than using the current attachment.
- Included scope: one premium invitation page optimized for screen and PDF.
- Excluded scope unless later requested: RSVP flow, guest-name personalization, animations, multi-page booklet, or social-story variants.

**Further Considerations**
1. Recommended copy strategy: keep the body mostly elegant and formal, then place the more playful “lifetime contract” lines in clause headings or benefit statements so the concept feels intentional, not gimmicky.
2. Recommended photo guidance: use a clean portrait or half-body couple image with good contrast and enough empty margin around the faces for flexible cropping.
3. Recommended page goal: design first for an A4/Letter-compatible one-page print layout, then adapt down for mobile rather than the reverse.