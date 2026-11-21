# AlphaRender Shaders

**AlphaRender** is a high-performance, highly customizable shaderpack for **Minecraft + Iris Shaders** (OpenGL 3.3+ & Vulkan 1.4), combining vanilla-faithful aesthetics with modern post-processing, pixel-locked cool shadows, 4-mode water rendering, 12 signature color palettes, and hardware-accelerated half-resolution Bloom & Optical Glare.

---

## Key Features

- **5-Tier Performance Profiles**: `LOW`, `MEDIUM`, `HIGH`, `ULTRA`, and `EXTREME`, with granular sliders for every visual and performance option.
- **12 Color Palette Styles**: Including **Classic Color**, **Nostalgia Color**, and **Legacy Color**, plus Natural, Vibrant, Warm Sunset, Cool Nordic, Filmic Teal-Orange, Pastel Dream, Monochrome Noir, Cyberpunk Neon, and Autumn Gold.
- **Full RGB Color Grading**: Global RGB tone multipliers plus 3-way **Shadow / Midtone / Highlight RGB** grading, exposure, contrast, saturation, vibrance, and 6 selectable tonemappers.
- **Hybrid Real-Time + Vanilla Shadows**: Combines accurate real-time pixel-locked shadows (`8 / 16 / 32 / 64` texel grid across terrain, entities, block entities, and water) with cool default shadow tinting and vanilla lightmap / directional shading.
- **4-Mode Water Engine**:
  - `0` — Vanilla
  - `1` — Vanilla Tinted
  - `2` — Pure Non-Vanilla
  - `3` — Realistic PBR (analytic waves, refraction, depth absorption, caustics, foam, SSR)
- **Hardware Half-Res Bloom & Optical Glare**: Multi-octave HDR Bloom and selectable Optical Glare/Scatter running on hardware `0.5x0.5` buffers (`colortex4` / `colortex6`) with conditional pass skipping.
- **Multi-Mode Bokeh Depth of Field (DoF)**: Default DoF, Focus Blur, Reverse Focus Blur, Manual Focus, and Tilt-Shift.
- **Complete Anti-Aliasing Suite**: Off, FXAA, MSAA, SMAA, TAA (with far-view anti-blur velocity reprojection), TAA+FXAA, TAA+MSAA, and CAS Sharpening.
- **Block Selection Box RGB + Bloom/Glare**: Customize the block outline color with RGB sliders; any non-black (`!Black`) outline automatically feeds into the Bloom and Optical Glare/Scatter pipeline.
- **Bilingual Localization**: Complete English (`en_US`) and Simplified Chinese (`zh_CN`) shader menus.

---

## Compatibility

| Environment | Support |
| :--- | :--- |
| **Iris 1.7.x – 1.12.x** (MC 1.20.1 – 26.3+) | Full native support (OpenGL & Vulkan) |
| **Iris 1.6.x** (MC 1.19.4 – 1.20.1) | Supported |
| **Iris 1.4.x – 1.5.x** (MC 1.18.2 – 1.19.2) | Basic compatibility (full-res bloom buffers) |

---

## Installation

1. Install **Fabric** or **NeoForge** with **Iris Shaders** (and **Sodium**).
2. Download `AlphaRender.zip` — **do not extract it**.
3. Place `AlphaRender.zip` into your Minecraft `.minecraft/shaderpacks/` folder.
4. Open **Options → Video Settings → Shader Packs**, select **AlphaRender**, and click **Apply**.

---

## License

Licensed under the [MIT License](LICENSE).
