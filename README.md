# Discovery Day plugin marketplace

Two Discovery Day plugins maintained by calstate-co. The original plugin contents and versions are preserved from the supplied September 16, 2026 ZIP archives.

| Plugin | Purpose | Version |
| --- | --- | --- |
| `discovery-day-web-adventure` | Adventure A: Build a Site with Sites | `0.1.3+codex.local-20260916072657` |
| `discovery-day-adventure-b` | Adventure B: Build a recurring weekly preparation task | `0.1.0+codex.local-20260916072657` |

## Install in Codex

This repository has internal visibility. Authenticate Git with an account that has repository access first.

```sh
codex plugin marketplace add calstate-co/discovery-day
codex plugin add discovery-day-web-adventure@calstate-discovery-day
codex plugin add discovery-day-adventure-b@calstate-discovery-day
```

Start a new task after installation to load the skills. Start Adventure A with `Use $discovery-day-web-adventure to start Adventure A.` or Adventure B with `Guide me through Discovery Day Adventure B.`

Adventure A uses Sites. Adventure B uses scheduling and the connected sources selected during preparation. These plugins provide guidance; participants need access to the corresponding capabilities.

## Repository layout

- `.agents/plugins/marketplace.json`: marketplace catalog with two separately installable entries.
- `plugins/discovery-day-web-adventure/`: Adventure A manifest, skill, and references.
- `plugins/discovery-day-adventure-b/`: Adventure B manifest, skill, and references.

Original ZIPs remain local and are excluded from Git. Edit the extracted plugin sources for future updates.

## Refresh the marketplace

```sh
codex plugin marketplace upgrade calstate-discovery-day
```

Then reinstall the desired plugin and start a new task.
