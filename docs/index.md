# OrbitFabric F Prime Adapter

The OrbitFabric F Prime Adapter projects selected OrbitFabric mission-contract entities into native FPP declaration fragments through explicit target bindings.

The current published release is [`v0.1.3`](https://github.com/OrbitFabric/orbitfabric-fprime-adapter/releases/tag/v0.1.3) (2026-09-25), indexed in the canonical Adapter Catalog. The post-migration patch changes release identity and active metadata, not projection behavior or the exact F Prime 4.2.2 / FPP 3.2.0 compatibility lane. The Core-owned adapter lifecycle and integration contracts retain candidate maturity.

## Choose your path

### I want to use the adapter

Start with [Getting Started](getting-started.md) for the published-release and Adapter Manager consumer flow.

### I want to try the adapter

Start with the [Reference Examples](reference-example.md).

The first example demonstrates one stable OrbitFabric mission contract projected into two different native F Prime placements. The second reconciles that explicit projected intent against the provider-native FPP semantic model.

Both examples include a local reproduction path over the exact supported lane.

### I want to develop or contribute

Start with [Development and verification](development.md).

## Current product boundary

The operation is `fpp_contract_projection`. Its semantic scope covers telemetry, commands, events and telemetry packet specifiers while leaving F Prime component architecture, topology, scheduling and runtime behavior under F Prime project ownership.

The adapter does not infer F Prime architecture from OrbitFabric structure. Target placement is explicit Profile intent, and the generated FPP fragments are composed by an existing F Prime project.

## Repository orientation

```text
src/
    adapter product

examples/
    public executable integration stories

native_acceptance/
    concrete F Prime materialization and downstream acceptance

docs/
    user, architecture and contributor documentation
```

## Documentation

- [Getting Started](getting-started.md)
- [Reference Examples](reference-example.md)
- [Product contract](product-contract.md)
- [F Prime Projection Profile](projection-profile.md)
- [Core input and result boundary](core-input-and-result.md)
- [Architecture and ownership](architecture-and-ownership.md)
- [Target compatibility](target-compatibility.md)
- [Integration Coverage](integration-coverage.md)
- [Development and verification](development.md)
- [0.1.3 release notes](releases/0.1.3.md)
- [0.1.2 release notes](releases/0.1.2.md)
- [0.1.1 release notes](releases/0.1.1.md)
- [0.1.0 release notes](releases/0.1.0.md)
