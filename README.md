# OpenMobile2-Sim

Static build of the MobileGym++ simulator for the OpenMobile-2 project page
(https://os-copilot.github.io/OpenMobile2-Home/), served by GitHub Pages at
`/OpenMobile2-Sim/` and embedded there as a same-origin iframe.

Built from the MobileGym++ repository with `VITE_BASE=/OpenMobile2-Sim/` and
`VITE_CDN_BASE=https://cdn.mobilegym.dev`, then assembled by
`tools/assemble_sim.py` in the page repository, which re-encodes the large
images as WebP so the site fits the Pages size limit.

Code is Apache-2.0 (see LICENSE, NOTICE); bundled app data is CC BY-NC 4.0
(see LICENSE-DATA, DISCLAIMER.md). Every rebuild replaces the whole tree.
