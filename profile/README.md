# open-he-mchose

**Unofficial open documentation and tools for MCHOSE Hall-effect (magnetic switch) keyboards.**
Not affiliated with or endorsed by MCHOSE.

> **⚠️ AI-generated content.** The reverse engineering, documentation and code in this organization were
> produced almost entirely by an AI assistant (Claude, by Anthropic). The maintainer directed the work and
> tested the results on real hardware, but did not write the analysis or code by hand. Facts are labelled by
> how they were confirmed (hardware test, firmware analysis, or the vendor's web driver). Verify before
> relying on anything here, and please report mistakes.

📖 **Website: https://open-he-mchose.github.io/**

| Repository | What it is |
|---|---|
| [docs](https://github.com/open-he-mchose/docs) | Protocol (`glw` family, 30 models), per-model pages, firmware internals, known bugs |
| [re-tools](https://github.com/open-he-mchose/re-tools) | Tools for researching new models: Ghidra language for WCH QingKe RISC-V, firmware → ELF, web-driver and USB helpers |
| [open-he-mchose.github.io](https://github.com/open-he-mchose/open-he-mchose.github.io) | The website, built from `docs` |

**Status:** Jet75-II fully documented and tested (protocol, key-depth stream, lighting, advanced keys,
NKRO/Snap Tap firmware bug with a Linux fix). Other models: listed, not yet researched — owners of other
MCHOSE magnetic keyboards are very welcome to help.

## Roadmap

1. 🚧 **Complete reverse engineering of the Jet75-II** — protocol, lighting, depth stream, advanced keys,
   macros and profiles are done; Fn-layer codes and the remaining fields are next.
2. 📋 **Open driver** — C++ library and CLI for Linux and Windows.
3. 📋 **Desktop GUI** — a Qt configurator for Windows and Linux on top of the driver, an open alternative to
   the official web driver. macOS is not planned for now.

Full roadmap: https://open-he-mchose.github.io/roadmap/

No vendor firmware, software or code is distributed here.
