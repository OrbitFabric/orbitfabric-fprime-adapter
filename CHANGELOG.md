# Changelog

All notable changes to this project will be documented in this file.

## Unreleased

## 0.1.3 - 2026-09-25

### Changed

- Published the post-migration adapter identity `github.com/OrbitFabric:orbitfabric/fprime@0.1.3`, with matching package and release metadata.
- Retained existing projection behavior, contract consumption and the exact F Prime 4.2.2 / FPP 3.2.0 compatibility lane.
- Preserved historical release identities and their immutable descriptor and evidence references.

### Publication

- Published GitHub Release `v0.1.3` with `adapter-release.json`, the `0.1.3` wheel and `SHA256SUMS`.
- Registered the exact published Release Descriptor digest in the canonical Adapter Catalog.
- Publication does not promote candidate Core-owned adapter lifecycle or integration contracts, and does not itself establish a separate post-publication greenfield acceptance.

## 0.1.2

### Added

- Added the provider-native semantic reconciliation Reference Example over the existing supported F Prime 4.2.2 / FPP 3.2.0 lane.
- Added clean local reproduction paths for both public Reference Examples.
- Added repository orientation for the split between public examples and provider-native acceptance harnesses.

### Changed

- Made the Java 11 requirement explicit in semantic-reconciliation CI instead of relying on the hosted runner image.
- Aligned MkDocs navigation and user documentation with both Reference Examples.
- Ignored local example and native-acceptance workspaces so supported local runs do not dirty the checkout.

### Compatibility

- Kept `fpp_contract_projection`, Projection Profile semantics, Integration Result behavior and the exact supported F Prime 4.2.2 / FPP 3.2.0 lane unchanged.
- Did not widen the adapter API, Core contract surface or target compatibility claim.

## 0.1.1

### Fixed

- Aligned the Adapter Source Coordinate encoded in release metadata with the documented canonical product identity.
- Bound release bundle generation and publication verification to the canonical product identity so release metadata cannot drift from the adapter identity constants.

### Changed

- Refined public documentation after the `v0.1.0` release and external greenfield acceptance.
- Stabilized Reference Example proof metadata and framework provenance handling after greenfield validation.

## 0.1.0

### Added

- Canonical `orbitfabric-fprime-adapter` product identity at `0.1.0`.
- Python package `orbitfabric_fprime_adapter` and console command `orbitfabric-fprime`.
- Integration identity `orbitfabric-fprime` and operation `fpp_contract_projection`.
- Canonical F Prime Projection Profile contract for telemetry, command, event and telemetry-packet bindings.
- Exact accepted target lane for F Prime v4.2.2 and FPP 3.2.0, including exact commits.
- Canonical FPP projection implementation with validation, allocation checks, diagnostics and Integration Result generation.
- Core Integration Input Set consumption with digest, surface, lint and identity verification.
- Integration Coverage matrix with explicit partial, unsupported, out-of-scope and non-applicable semantics.
- Native F Prime generation/build and generated dictionary conformance against the exact target lane.
- Canonical F Prime GDS closed-loop runtime acceptance for projected command, telemetry, event and command completion.
- Consumer Reference Example showing one stable OrbitFabric contract across monolithic and split F Prime placements.
- Native Reference Example acceptance proving both placements through F Prime generation, build and generated dictionary resolution while preserving the same OrbitFabric source identity set.
- Managed install, verify, execute, inspect and remove lifecycle proof through OrbitFabric Adapter Manager.
- Provider-neutral release descriptor and release proof.
- Published `v0.1.0` release assets with checksums and provenance descriptor.
- Published-byte verification and clean external greenfield installation/execution.
- MkDocs documentation baseline.

### Release status

`v0.1.0` is published as the first stable release. The published product bytes have passed post-publication verification and external greenfield acceptance.
