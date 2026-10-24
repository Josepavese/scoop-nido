# Nido - Scoop bucket

Scoop bucket for [Nido](https://github.com/Josepavese/nido): a local VM manager for AI agents. Create, run and reuse QEMU virtual
machines through the CLI, terminal dashboard or native MCP server.

[Quickstart](https://github.com/Josepavese/nido#press-start) · [MCP guide](https://github.com/Josepavese/nido/blob/main/docs/mcp.md)

```powershell
scoop bucket add nido https://github.com/Josepavese/scoop-nido
scoop install nido
nido version
```

QEMU is required to run VMs: `scoop install qemu`.

`bucket/nido.json` is refreshed automatically by the Excavator workflow
(`.github/workflows/excavator.yml`, every 4 hours) from Nido GitHub Releases.
