# Patch policy

Base: SagerNet/sing-box v1.14.4 (`c005f35300ce76427dc285481ec5695f5b179cd2`).

The `hotaru` branch accepts changes in three areas:

- Build tags and feature selection for supported client targets.
- Product identification and source provenance.
- libbox platform integration.

Protocol implementations, route selection and DNS decisions follow the pinned upstream version.
Subscription loading, configuration conversion, diagnostics and presentation are implemented in the
Hotaru client's Dart/Rust layers. A change outside these boundaries requires a separate architecture review.

Follow upstream 1.14.x fixes through reviewed commits. Do not advance to a new major/minor line merely
because the upstream default branch changes. Preserve the upstream license and record the exact source
revision in distributed artifacts.

`v1.14.4-hotaru.1` establishes the source baseline and repository documentation. It contains no runtime
changes relative to upstream v1.14.4.
