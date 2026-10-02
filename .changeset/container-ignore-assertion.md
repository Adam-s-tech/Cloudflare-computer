---
"@cloudflare/computer": patch
---

Keep configured paths local to the container instead of syncing them with the Durable Object using `ContainerBackend.ignore`; see [local-only path documentation](https://github.com/cloudflare/computer/blob/main/docs/19_performance.md#local-only-paths-mount_ignore).
