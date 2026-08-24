# Monolithic Equations — Canonical 102

This repository publishes the **Monolithic 102 equation set** as supplied in the source corpus.

The repository is designed for preservation, citation, inspection, scripting, and independent analysis. The canonical sequence is frozen as **ME-001 through ME-102**. No equation has been silently rewritten, corrected, renumbered, or upgraded in status during packaging.

## Start here

- [`CANONICAL_102.md`](CANONICAL_102.md) — complete canonical set in original order.
- [`EQUATION_INDEX.md`](EQUATION_INDEX.md) — linked index of all 102 equations.
- [`equations/`](equations/) — one file per canonical equation.
- [`machine-readable/equations.json`](machine-readable/equations.json) — complete structured export.
- [`STATUS.md`](STATUS.md) — counts and explanation of the source's own bracketed status labels.
- [`MANIFEST.md`](MANIFEST.md) — package contents and integrity information.

## Canonical numbering

The identifiers `ME-001` through `ME-102` are immutable. A future correction or alternative formulation should receive a revision suffix such as `ME-037-r1` while historical `ME-037` remains available.

## Preservation rule

`CANONICAL_102.md` and `provenance/SOURCE_SUBSTACK_EXPORT.md` preserve the supplied source text. Generated files normalize packaging and metadata only; they do not replace the canonical text.

## Scientific-status rule

The source itself uses labels including *standard*, *derived*, *working construct*, *working hypothesis*, *hypothetical physical extension*, and related classifications. This repository preserves those labels. Repository publication by itself does not establish proof, physical validity, empirical confirmation, or scientific consensus.

## Machine use

Each structured record contains `number`, immutable `id`, source `heading`, `title`, source `classification`, canonical formula/body preceding the descriptor, and source `descriptor`.

Canonical source SHA-256:

`d534be8e0664fd523bd0bbbd82e98b8acda29e23f0941690be96573661080268`

## License

No license was specified in the supplied source. This package intentionally does not add one. Add a license only when the rights holder has chosen the intended terms.
