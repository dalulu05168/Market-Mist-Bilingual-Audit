# Codex bilingual audit instructions / 《市场迷雾》校对规则

This is the user's explicitly approved PUBLIC repository. Treat all Chinese text here as unaccepted draft, not a certified translation. Do not infer completion from chapter count.

## Source hierarchy
1. Original 686-page Market Mist PDF (the authoritative source; currently **not uploaded as a PDF binary**).
2. `original/chapters_en/*.en.txt` are page-labelled text extractions from that PDF for provisional review. Original figures, layout and any image-only text are not represented fully.
3. `translations/chapters_zh_draft/*.md` contain work-in-progress translations. Chapters 07–12 and 15–16 were extracted from the consolidated Chinese DOCX; other chapters are earlier standalone draft snapshots. The exact Chinese DOCX binary is **not yet uploaded**.

## User requirements
- Audit all 28 chapters plus front matter, afterword and final summary against the English source **sentence by sentence**.
- Detect omissions, meaning drift, logical inversions, unauthorized additions/deletions, errors in numbers, dates, market prices, terminology, speaker attribution and references.
- Cite exact source PDF page and target chapter and text for each issue; correct only substantiated errors; recheck corrections.
- Preserve original chart and illustration contents: **DO NOT translate English within figures/icons/charts**.
- Track each chapter's acceptance in `AUDIT_STATUS.json`; never mark an unverified chapter COMPLETE.
- Upload/commit success is not text QA success. Structural and numeric checks do not replace translation accuracy review.
- Do not claim an independent end-to-end audit is done until all source sentences and translated content have been verified.

For an authoritative final Word edition, a reviewer must also receive the original PDF and exact latest Chinese DOCX binaries and verify Word integrity.