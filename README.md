# Hotaru Core

A lightweight sing-box fork used by [Hotaru](https://github.com/kurumiZafkiel12/Hotaru).

The `hotaru` branch is based on **sing-box v1.14.4**, upstream commit
`c005f35300ce76427dc285481ec5695f5b179cd2`. It is the stable integration branch;
the upstream `testing` branch is retained separately.

Routing policy, subscription conversion, diagnostics and user interface logic belong to the Hotaru client.
This fork preserves the upstream protocol and routing behavior. Its patch policy permits build tag
selection, product identification and libbox platform integration only.

See [the patch policy](HOTARU-PATCH-POLICY.md), [upstream documentation](https://sing-box.sagernet.org/)
and [the original README](README.upstream.md).

The source remains licensed under [GPL-3.0-or-later](LICENSE). Upstream copyright and attribution are retained.
