# Phase 28Z Errata — QORE never “king” (LS hard rule)

## What changed
- **qore** is constrained to **crown prince / heir apparent / regional lord (non-sovereign)**.
- Any rendering of **qore** as **“king/monarch/sovereign ruler”** is a **mis-specification** under LS methodology.
- Sovereign kingship is encoded by **mlo** (e.g., `mlo kdi …`).

## Specific correction (Phase 28Z draft)
Original draft sentence glossed:
- `qore kdi Tanyidamani se Adikhalamani` as “King of Kush Tanyidamani …”

Correct LS gloss:
- `qore kdi Tanyidamani se Adikhalamani` → **“Crown prince/heir of Kush Tanyidamani, son of Adikhalamani”**

(We leave `mlo kdi …` as the “King of Kush …” formula.)

## Lexicon artifacts updated
- Updated master lexicon JSON: v12 (qore hard constraint + forbidden gloss list).
- Updated CSV export: v12 (qore definition/translation/notes aligned).

## Next audit target
- Run a full-text scan over all translation outputs to ensure **no qore → king** drift exists anywhere (including older phase gloss text).