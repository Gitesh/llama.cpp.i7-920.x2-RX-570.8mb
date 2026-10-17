# llama.cpp.i7-920.x2-RX-570.8mb

**Llama.cpp custom build compiled for Intel i7-920 with dual MSI RX-570 8mb graphics cards**

- The oficial llama.cpp install fails due to missing modern Intel cpu instructions.
- Although the graphics cards are compatible, and will run using the Vulkan backend, you're stuck as the offical installer crashes.

This installer works around the missing instructions to install llama.cpp. It's slower to initally run, but once installed LLMs can run at the expected speed once loaded into VRAM.

2026-10-10 Gitesh
