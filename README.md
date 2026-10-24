# mlx-metallib-build

Builds `mlx.metallib` (plus its fingerprint sidecar) for a given commit of the public
[Layr-Labs/mlxfast-nemotron35-30b-a3b-engine](https://github.com/Layr-Labs/mlxfast-nemotron35-30b-a3b-engine)
on a GitHub-hosted macOS runner, for use on a Mac that has Command Line Tools but no full Xcode.
The workflow only fetches and builds the public engine source; this repository contains nothing else.
