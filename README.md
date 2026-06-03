
raw
Plug and play readme · MD
# Plug & Play
 
Free, open-source operational tools for underserved organizations and communities — built to work out of the box, with no enterprise budget required. Each tool lives in its own submodule with its own stack.
 
---
 
## What it does
 
A growing library of plug-and-play tools spanning municipal government, community organizations, and civic infrastructure. First focus: U.S. cities and local government offices that lack the time or staff to build their own software.
 
Tools are built to be self-contained, well-documented, and deployable without a dedicated engineering team.
 
## Repository structure
 
Each tool type lives as a Git submodule:
 
```
plug-and-play/
├── municipal/          # Tools for city and local government offices
├── nonprofit/          # Tools for community organizations and nonprofits
├── civic-data/         # Public data tools and open dataset utilities
└── ...                 # New tool types added as programs expand
```
 
### Cloning with submodules
 
```bash
git clone --recurse-submodules https://github.com/sunrise-atelier/plug-and-play
```
 
Or if already cloned:
 
```bash
git submodule update --init --recursive
```
 
Each submodule has its own README with stack-specific setup instructions.
 
## Contributing
 
See [CONTRIBUTING.md](https://github.com/sunrise-atelier/sunrise-api/blob/main/CONTRIBUTING.md) for guidelines. If you want to propose a new tool type, open an issue with the `proposal` label. Browse [`good first issue`](../../issues?q=is%3Aopen+label%3A%22good+first+issue%22) to find a starting point.
 
---
 
Part of [Sunrise Atelier](https://github.com/sunrise-atelier) — free, open-source tools for underserved communities.
