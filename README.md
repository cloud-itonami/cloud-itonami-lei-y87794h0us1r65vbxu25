# cloud-itonami-lei-y87794h0us1r65vbxu25

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Walmart Inc.**

This repository archives publicly published policy text of **Walmart Inc.**, with
source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.md)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Walmart Inc.
- **LEI (ISO 17442)**: [Y87794H0US1R65VBXU25](https://search.gleif.org/#/record/Y87794H0US1R65VBXU25) (GLEIF-verified)
- **Jurisdiction**: US-DE
- **Website**: https://corporate.walmart.com
- **Ticker**: WMT (NYSE)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived policy documents,
  each entry carrying `:tos/full-text`, `:tos/source-url`, `:tos/retrieved-at`,
  `:tos/sha256`, `:tos/doc-type`, and a `:tos/supersedes` chain for future revisions.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Note on document type

The source page (`corporate.walmart.com/policies`) is Walmart's published "Policies
and Guidelines" hub, not a single canonical Terms-of-Use contract page (Walmart's
consumer-facing `walmart.com` terms pages returned bot-detection challenges to this
archive's fetch, undocumented as a fabricated substitute). The captured text is real,
verbatim, currently-published Walmart policy content, honestly labeled
`:policies-and-guidelines` rather than `:terms-of-service`.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`) for why this repo exists,
the LEI-keyed naming convention, and the full-text-with-provenance data schema.
