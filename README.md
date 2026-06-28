# lookout-mirror

Builds and publishes container images from [hackclub/lookout](https://github.com/hackclub/lookout) to GitHub Container Registry.

## Images

- `ghcr.io/lordbagel42/lookout-server:latest`
- `ghcr.io/lordbagel42/lookout-worker:latest`

Rebuilt daily at 04:00 UTC. Also triggerable manually via Actions → workflow_dispatch.

## Setup

After the first workflow run, set both packages to **Public**:
- GitHub → Packages → `lookout-server` → Package settings → Change visibility → Public
- GitHub → Packages → `lookout-worker` → Package settings → Change visibility → Public
