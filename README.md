# Nido — Scoop bucket

Scoop bucket for [Nido](https://github.com/Josepavese/nido): fast, local
QEMU/KVM VM sandboxes for AI agents, with a native MCP server.

```powershell
scoop bucket add nido https://github.com/Josepavese/scoop-nido
scoop install nido
nido version
```

QEMU is required to run VMs: `scoop install qemu`.

`bucket/nido.json` is refreshed automatically by the Excavator workflow
(`.github/workflows/excavator.yml`, every 4 hours) from Nido GitHub Releases.
