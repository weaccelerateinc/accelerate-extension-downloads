# Accelerate extension downloads

The approved extension archive is [Accelerate extension 0.0.0.1](https://github.com/weaccelerateinc/accelerate-extension-downloads/releases/tag/extension-v0.0.0.1). Its ZIP is 29,397,270 bytes and has SHA-256 `65574cbb27ab344687963f72a136f2653551b57458b284e486946b27699099c8`. Verify the downloaded ZIP against the release's existing `SHA256SUMS` before installation. Retain the trusted provider installation record and pin the installed extension and runtime in your backend.

## SDK compatibility metadata

The [SDK 0.12.0 compatibility manifest](compatibility/accelerate-extension-0.0.0.1.sdk-0.12.0.release.json) describes the same approved ZIP and the `accelerate_manual_checkout_v1` executor and `accelerate_extension_bridge_v1` bridge protocols. Its [checksum](compatibility/accelerate-extension-0.0.0.1.sdk-0.12.0.SHA256SUMS) covers this manifest only. SDK 0.12.0 publication is pending. Use the approved release manifest bundled with the SDK as the authoritative trusted backend configuration for that SDK version. The original release manifest and its `SHA256SUMS` remain available for existing integrations; they list SDK 0.10.0 and 0.10.1 only.

Protocol compatibility does not qualify a provider, browser configuration, or checkout. The recorded qualification is Browser Use sandbox demo fill, masked review, and cancel. It does not establish qualification for run-created Browser Use browsers, purchase submission, other providers, or arbitrary merchant checkouts. These require separate acceptance evidence. The extension does not submit payments automatically.

Metadata is an operator-controlled compatibility record, not a cryptographic publisher signature. Never accept extension pins or approval metadata from agent or model input. Install the approved extension when creating a browser; do not replace it in an active checkout.
