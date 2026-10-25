# edna_primer_designer

A Chinese-language AI skill for evidence-aware eDNA metabarcoding primer selection and design.

[中文说明](README.md) · [SKILL.md](SKILL.md) · [Method cases](references/method-cases.md) · [Bibliography](references/bibliography.md)

## Scope

- Explain published design choices and compare assays for a specified community and environment.
- Trace original designs, modifications, applications, and quantitative/library workflows.
- Plan reference datasets, computational screening, decision metrics, and staged validation.

This is a guide and template package, not an executable design pipeline, exhaustive primer database, or catalog of order-ready sequences. Published results, predictions, and experimental validation remain distinct.

## Use

Start with `SKILL.md`; open supporting references only as needed. In a client that supports this format, load the complete directory according to that client's instructions. Keep `references/` and `templates/` with the entry point. If discovery uses the folder name, use `edna-primer-design`; explicit invocation, where supported, is `$edna-primer-design`.

The optional `agents/openai.yaml` contains interface metadata. YAML and TSV templates record project decisions rather than run analyses.

Cases are organized around design decisions, including lineage compensation, background exclusion, length versus resolution, and complementary assays. The literature record is dated 2026-10-24; verify original sequences and versions for each application.

Cite the original studies when using their primers or findings. Inclusion does not imply endorsement or change the terms of source publications, data, or software. For corrections, provide the DOI and precise source location.
