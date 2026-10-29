# tonscan-mirror

A second copy of [tonscan.info](https://tonscan.info)'s static files, for readers whose networks
freeze connections to Cloudflare (Russian mobile lines, 2026). Readers never see this address:
tonscan.info's own pages load the code from here when the direct path is throttled.

Built and published by the `awesome-doge/tonscan-info` deploy workflow. Do not edit by hand.

- `net-check/blob.bin`: 100 KB of random bytes, read by tonscan.info's network check page to
  measure whether this host is reachable in full from a given network.
