# Maintenance Log

Append-only record of wiki operations.

## [2026-04-16] lint | Migration & .gitignore Audit
- Validated `.gitignore` after repository migration.
- Confirmed path-specific and pattern-based ignore rules are correctly implemented.

## [2026-04-15] ingest | Initial Repository Setup
- Initialized schema in `GEMINI.md`.
- Ingested `README.txt` into `readme.md`.
- Ingested `probability_lab` into `probability_lab.md`.
- Ingested `bankershotseat` into `bankershotseat.md`.
- Ingested `evolutionoftrust` into `evolutionoftrust.md`.
- Ingested `emojiworldsimulator` into `emojiworldsimulator.md`.
- Ingested `alchemyformula` into `alchemyformula.md`.
- Created `index.md` and `log.md`.

## [2026-04-15] lint | Structural Reorganization
- Restructured folders into `00_Meta/`, `10_Projects/`, and `20_Wiki/`.
- Renamed project folders with `1x_` numbering index.
- Created `Root_MOC.md`, `10_Projects/10_Projects_MOC.md`, and `20_Wiki/20_Wiki_MOC.md`.
- Updated `GEMINI.md` schema to reflect the new architecture.
- Updated all existing wiki markdown pages to point to their new raw source locations.

## [2026-04-15] lint | Backlinking and Indexing Review
- Appended `**Backlinks:**` sections to all leaf nodes in `00_Meta/` and `20_Wiki/`.
- Updated MOC files (`Root_MOC.md`, `10_Projects_MOC.md`, `20_Wiki_MOC.md`) to use robust internal linking syntax.
- Ensured no orphan files exist within the core structural directories.

## [2026-04-15] lint | Live Links & README Consolidation
- Corrected the GitHub Pages live URLs to use the special-adventure-4qqpnnn domain and 10_Projects/ path.       
- Merged and cleaned README.md to integrate "Su's Version" text, removing duplicated content and broken Google search links.

## [2026-04-15] lint | Thorough Repository Review & Validation
- Conducted comprehensive review of structure, internal links, and backlinks.
- Verified MOC integrity and resolved all internal paths.
- Confirmed backlink footers on all leaf nodes and removed legacy broken link from llm-wiki.md.
- Validated external GitHub Pages live links in README.md.

## [2026-04-15] lint | Legacy README Formatting
- Converted 0_Meta/README.txt to README_DLab.md with proper markdown formatting.
- Added explanatory context and updated URL patterns.
- Deleted the obsolete README.txt file.

## [2026-04-15] ingest | Merge README files
- Merged `readme.md` into `README_DLab.md`.
- Deleted `readme.md`.
- Updated MOC links.

## [2026-04-15] update | Probability Lab Integration
- Replaced all references to `heartapp` and Daphnia Lab Simulator with `probability_lab` and Probability Lab across the codebase, MOCs, and wiki pages.
- Deleted `heartapp.md` and generated `probability_lab.md` to document the new project.

## [2026-04-15] update | The Alchemy Formula Integration
- Replaced all references to `workloadestimator` and Course Workload Estimator with `alchemyformula` and The Alchemy Formula across the codebase, MOCs, and wiki pages.
- Deleted `workloadestimator.md` and generated `alchemyformula.md` to document the new project.

## [2026-04-15] update | Banker's Hot Seat Integration
- Replaced all references to `osmosisgame` and Membrane Master with `bankershotseat` and Banker's Hot Seat across the codebase, MOCs, and wiki pages.
- Deleted `osmosisgame.md` and generated `bankershotseat.md` to document the new project.

## [2026-04-15] update | Emoji World Simulator Integration
- Replaced all references to `smokeytrip` and Smokey's Trip with `emojiworldsimulator` and Emoji World Simulator across the codebase, MOCs, and wiki pages.
- Deleted `smokeytrip.md` and generated `emojiworldsimulator.md` to document the new project.

## [2026-04-15] update | Evolution of Trust Integration
- Replaced all references to `photosynth1` and Leaf Lab with `evolutionoftrust` and Evolution of Trust across the codebase, MOCs, and wiki pages.
- Deleted `photosynth1.md` and generated `evolutionoftrust.md` to document the new project.

## [2026-04-28] update | Repository Migration
- Updated README.md and documentation with the new base URL: https://jiansuphd.github.io/dlab_jsu1/
- Updated all MOC links and locations in 00_Meta/ to reflect the new repository structure and base URL.
- Verified internal links and backlinks across the entire wiki.

---
**Backlinks:** [[Root_MOC|Root MOC]]
