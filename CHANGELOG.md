# Changelog

All notable changes to this project are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

When the schema for a canonical primitive changes in a backwards-incompatible way, that's a **major** bump. New optional fields or new primitives are **minor**. Tooling and documentation fixes are **patch**.

---

## [Unreleased]

### Added

- Initial seed repository.
- Canonical specification at `docs/spec/company-as-code-spec.md`.
- JSON Schemas for canonical primitives: manifest, task, agent, workflow, initiative, goal, metric, event, audit-record, interface, organization, person, integration.
- Canonical `/company` directory structure across three domains (finance-ops, product-operations, sales-marketing) plus executive and top-level support directories.
- Authoring templates for manifests, agents, workflows, tasks, initiatives, goals, metrics, playbooks, plans, and ADRs.
- Worked examples in finance, platform, and growth modules.
- Reference TypeScript CLI with manifest validation and deterministic generators (agent catalogue, flow registry).
- CI workflows for schema validation and drift detection.
- Architecture documentation, getting-started guide, codified standards, and glossary.

[Unreleased]: https://github.com/your-org/company-as-code/compare/HEAD...HEAD
