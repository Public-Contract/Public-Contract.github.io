Public Contract Licensing

artifact_id: PUBLIC_CONTRACT_LICENSING_INDEX_V1
license_ref: LicenseRef-Public-Contract-Public-Inspection-Commercial-Boundary-1.0
status: RELEASED
public_inspection: allowed_under_root_license
open_source: false
commercial_runtime: separate_signed_agreement_required
production_use: separate_signed_agreement_required
academic_commercial_conversion: required
internal_systems_excluded: true

Purpose

This directory defines the public licensing architecture for the Public Contract browser laboratory and related public technical artifacts.

The controlling public rights boundary is the repository root:

"LICENSE"

This licensing index does not independently grant additional rights.

Licensing Architecture

PUBLIC INSPECTION / PRIOR-ART LANE
                |
                | separate boundary
                v
COMMERCIAL RUNTIME / PRODUCTION LANE
                |
                | separate boundary
                v
CERTIFICATION / MARKS LANE
                |
                | separate boundary
                v
NON-PUBLIC PRODUCTION INTERNALS

These layers must not be silently collapsed into one another.

Public availability is not a commercial runtime grant.

A successful public fixture is not a production authorization.

A receipt is not certification.

A DOI is not a commercial license.

Academic access is not academic commercialization authority.

Repository Licensing Files

The repository uses the following public rights surfaces:

"/LICENSE"

Controlling Public Contract Public Inspection / Commercial Boundary License Notice.

"/NOTICE.md"

Human-readable rights and attribution summary.

"/.spdx.json"

Machine-readable custom license metadata.

"/COMMERCIAL_INQUIRY.md"

Public commercial-conversion and licensing contact surface.

"/docs/licensing/README.md"

This licensing architecture and index.

Public Inspection Lane

Subject to the root "LICENSE", bounded public rights include noncommercial inspection, evaluation, citation, archival review, scholarly review, teaching, reproducibility review, interoperability analysis, procurement review, regulatory review, security review, and prior-art review.

These rights do not create a general right to commercialize the Protected Materials.

Commercial Conversion Lane

Separate written authorization is required for commercial or production uses including hosted execution, hosted validation, SDKs, APIs, connectors, validator services, managed services, certification, enterprise deployment, OEM, white-label, resale, sublicense, marketplace distribution, customer-facing deployment, sponsor-controlled production deployment, and academic commercialization.

Evidence Boundary

The Public Contract browser may generate:

OPEN
REVIEW_REQUIRED
HALT

and associated:

receipts
evidence archives
Pixel Witness artifacts
hashes
validation checks

Those artifacts are bounded technical evidence.

They do not independently constitute:

legal permission
regulatory approval
certification
deployment authorization
commercial licensing
partnership
endorsement

Third-Party Boundary

Third-party mathematics, facts, methods, public standards, laws, publications, and architectures remain attributed to their respective authors and authorities.

In particular, architectural and source facts attributed to Vaswani et al., "Attention Is All You Need" (2017), remain attributed to their original authors.

Public Contract licensing applies to original protectable Flint / Latent Studios expression and implementation where applicable. It does not convert third-party facts, mathematical principles, methods of operation, or public source material into proprietary subject matter.

Non-Public Technology Boundary

Public release does not publish or license non-public production technology, including unreleased:

lowering
normalization
compiler construction
validator internals
routing
proof binding
certificate generation
production regulatory kernels
commercial-control systems
pricing automation
dealdesk systems
approval workflows
classification engines
SBS internals
Omega internals
private datasets
credentials
secrets

Public disclosure of one layer does not disclose or waive another.

Relationship to Other Flint / Latent Studios Licensing

Public Contract may interoperate with or reference separately licensed MC, Omega-SBS, validator, enterprise, academic-conversion, support, certification, royalty, or commercial technology.

This repository license does not replace a separately executed agreement governing those systems.

Likewise, a separate commercial agreement does not alter this public repository's attribution or evidence boundaries except where that written agreement expressly states otherwise.

Stability Rule

Licensing changes must not silently modify the mathematical or validation meaning of PC01-PC10.

Where license identity becomes part of a generated receipt or evidence object, the runtime version and evidence hash must change accordingly.

The expected validation semantics remain:

same declared input
+
same declared runtime
+
same declared evidence body
=
same deterministic result

Copyright (c) 2026 Kevin Flint / Latent Studios.

All rights reserved except as expressly stated in the repository root "LICENSE".
