## About this fork

This fork works toward running VIctory on GPUs **without mesh shader support**
(for example AMD RX 5000 and older, Nvidia GTX 10-series and older, and
integrated graphics). The game's world is drawn almost entirely by mesh
shaders, so this means translating them to compute shaders and drawing from
buffers.

**Status:** experimental, work in progress. Without mesh shaders the world is
not drawn at all (menus and videos only).

**Performance warning:** even on a Radeon RX 7900 XTX the upstream project runs
the world at roughly 6-22 fps and uses 40-46 GB of RAM. GPUs without mesh
shaders are slower, and emulating mesh shaders costs more. **This fork may
never be playable on low-end or integrated hardware.** It is a compatibility
and correctness effort, not a promise of playable speed.

This repository contains no game files. Bring your own legally obtained dump.
Not affiliated with or endorsed by the game's developer or publisher.

Currently, nothing has been done yet.
