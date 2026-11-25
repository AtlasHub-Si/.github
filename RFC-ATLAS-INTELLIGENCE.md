# RFC — Atlas Intelligence Library

**Status: proposed architecture; no new repository, migration or deployment authorized by this RFC alone.**

## Purpose

Atlas Intelligence is the umbrella for reusable, runtime-neutral business and operational knowledge. It is a library and catalog, not an agent runtime, database, commercial product or organizational authority.

## Source ownership

| Source | Canonical responsibility |
|---|---|
| Proposed private Atlas-Intelligence repository | Generic venture blueprints, comparative business research, reusable playbooks, catalog manifest and cross-library references |
| Atlas-Workforce | Canonical reusable agent definitions, team packages and approved reusable skills; preserve upstream attribution |
| Skills-Radar | Candidate discovery, evaluations, license/security checks; not approved skills by default |
| Atlas-Operational-Knowledge | Approved operational documents and publishing rules; review later consolidation, no duplicate content |
| Atlas-Cortex | Authorized retrieval, indexing, provenance and access governance, not original document ownership |
| Atlas-Memory-Fabric | GBrain engine reference; not an additional library or data authority |
| Each venture | Its mandates, private operating data, customers, decisions, finances and execution records |

Generic venture patterns are not approved business mandates. Existing ventures retain ownership of their records and prior authorizations. No cross-organization movement, disclosure or indexing without explicit scope and access review.

## Proposed catalog layout

    Atlas-Intelligence/
      README.md
      catalog.yaml
      ventures/
        blueprints/
        studies/
      playbooks/
      research/
      schemas/
      templates/
      references/
        workforce.yaml
        skills-radar.yaml
        operational-knowledge.yaml

Agent and team source files remain in Atlas-Workforce. The catalog references versioned identifiers and source commit URLs rather than copying files. Skills-Radar discovers candidates; approved skills are maintained in Workforce with evidence and provenance. A separate distribution/export artifact is allowed only when generated from a pinned source and clearly labeled.

## Portability

Evaluate the [OpenMausBot Teams format](https://github.com/milind-soni/openmausbot-teams/blob/main/FORMAT.md) as a team export target; keep internal metadata runtime-neutral. Validate generated bundles before importing. Routines disabled by default; no credentials, inherited permissions, memory or private transcripts in templates. Each runtime must enforce its own tool grants and approvals.

## Lifecycle

Discovery -> research -> evaluated -> validated -> approved for reuse -> deprecated. A business opportunity is separately authorized by its owner. A template is not an authorization to execute, spend, publish or access another organization's data.

## Implementation sequence

1. Confirm the private catalog scope and ownership.
2. Inventory existing reusable sources; reference rather than copy.
3. Prototype one generic business blueprint and one portable team.
4. Validate imports on AtlasBot and AtlasHQ in isolation.
5. Index authorized sources through AtlasCortex only after access and provenance tests.
6. Review whether any existing documentation repository should be consolidated; preserve history.

No live operational data, confidential venture records or secrets in public documents.
