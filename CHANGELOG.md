# Inverna hosting changes

## 0.1.0-dev.12 — 2026-10-20

- Bundle the matching revision 6 backend with the standalone Inverna profile.
- Include corrected city movement, trainer name and appearance propagation.
- Support optional community friend codes and native owned PTTR delivery.
- Keep local owner enrollment, configuration checks and persistent hosting setup.

Both wrapper checks pass, including disposable real startup and signed shutdown.
Native battles/trades were confirmed on the combined backend with prepared
0.1.7 clients; this city-only role does not allocate player worlds or federate
identities with separate world deployments. The independent source client and
complete custom-art rendering verification remain unfinished.

Extract both sibling folders, use Node.js 24.12+, and preserve existing data,
owner keys and configuration when upgrading.
