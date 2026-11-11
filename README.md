# ci-smoke-lab-17
Throwaway sandbox for CI smoke test of the contribution+CI loop

## Build artifact

This repo's CI workflow (`.github/workflows/demo.yml`) uploads a build artifact
named **demo-build** on every manually triggered run. The workflow writes a short
text file (`build/artifact.txt`) and uploads it as the `demo-build` artifact,
which shows up under the "Artifacts" tab of the workflow run in the repo.
