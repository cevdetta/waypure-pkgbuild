# waypure

**waypure** is a curated collection of Arch Linux PKGBUILDs built for modern, minimalist systems using the Wayland display server protocol, Vulkan graphics stack, and PipeWire as the single audio solution. Legacy components such as X11, PulseAudio, and JACK are excluded or replaced where possible.

This project is designed for users who value clean, fast, security-conscious systems that do not rely on outdated or bloated libraries.

---

## Goals

- **Wayland-native only** — No X11 dependencies
- **PipeWire-only audio** — Unified, no PulseAudio or JACK unless routed through PipeWire
- **Vulkan and EGL only** — No OpenGL-only or X11 GLX tools
- **Minimal and clean** — No optional bloat, stripped-down builds
- **Security-first** — Follows upstream closely, uses signed and hashed `.tar.gz` releases
- **No git clones** — Uses `.tar.gz` release archives for reproducibility and speed
