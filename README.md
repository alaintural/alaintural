## Alain Tural

Founder of [Pixedi](https://pixedi.com). I build production systems with AI and publish the engineering behind them.

Most of my work sits in one gap: the distance between a model that works in a demo and a system that still works on a Tuesday afternoon when nobody is watching it. A job status is the system's opinion of itself, not a fact about the world. A renderer can crash and still report success. An agent can report DONE having written nothing. The fix was never a better prompt. It was a check that reads the world instead of trusting the report.

**What I work on**

- Browser-based 3D product configurators, and the offline reference renders they get measured against
- Automation infrastructure: verification gates, queues, and pipelines that count what actually shipped
- Applied AI in production, including the parts that did not survive measurement

**Open source**

- [SyncTile for MiniMax H3](https://github.com/alaintural/synctile-h3): 4.9x faster local video generation and seam-free 4K (3840 x 2160) on one RTX 4090, by blending tiles in latent space after every sampling step. Benchmarks against MMH3 Split Upscale and SeedVR2 included. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23196934.svg)](https://doi.org/10.5281/zenodo.23196934) Write-up: [pixedi.com/lab](https://pixedi.com/lab/minimax-h3-4k-synctile)

**Writing and measurements:** [alaintural.com](https://alaintural.com)

Most of my work is client work and lives in private repositories. What I publish here is the part that stands on its own: small tools, and the measurement harnesses behind the numbers I write about.
