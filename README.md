# Awesome-3D-Lighting-Relighting-Tools

## Top 3D Lighting & Relighting Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Physically Based 3D Lighting, Neural & 3DGS Scene Relighting, HDRI Studio Illumination & Cloud GPU Rendering*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Lighting & Relighting Tools**. These tools enable look-development artists, VFX supervisors, virtual production teams, and AI researchers to light 3D scenes with physically accurate HDRIs, relight captured 3D Gaussian Splats and NeRFs, bake real-time illumination, and scale path-traced rendering across local or cloud GPUs.



**Examples** include Spline 3D, Luma AI, Jawset Postshot, Adobe Substance 3D, Marmoset Toolbag, Chaos Cloud, V-Ray, OctaneRender Cloud, Redshift, Blender Studio, and storytold/lightcraft (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local neural 3D/multi-view relighting, relightable 3D Gaussian Splatting, Houdini/Blender HDRI studio lighting tools, physically based path tracers, and scene-referred 32-bit color/lighting pipelines — ideal for look-dev artists, lighting TDs, and graphics researchers building transparent pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Spline 3D](https://spline.design)**  

  Collaborative browser-based 3D design and real-time lighting studio offering physical/matcap shaders, interactive spotlights, environment maps, and instant WebGL embeds.



- **[Luma AI](https://lumalabs.ai)**  

  Cloud AI 3D capture and radiance field platform supporting interactive WebGL lighting adjustments, shader integration, and photorealistic 3D asset generation.



- **[Jawset Postshot](https://jawset.com)**  

  High-speed 3D Gaussian Splatting and radiance field workstation featuring live training previews, ACES color pipelines, and Unreal Engine / After Effects relighting workflows.



- **[Adobe Substance 3D Stager & Sampler](https://adobe.com)**  

  Commercial look-development and virtual photography suite featuring real-time ray-traced studio lighting, parametric HDRI light editors, and IBL environment generation.



- **[Marmoset Toolbag](https://marmoset.co)**  

  Industry-standard real-time ray-traced look-development, baking, and sky/HDRI lighting suite with interactive WebGL viewer export for game and film assets.



- **[Chaos Cloud & V-Ray](https://www.chaos.com/)**  

  Production-proven physically based rendering and cloud render-farm ecosystem featuring Adaptive Dome Light, Light Mix post-render relighting, and global illumination.



- **[OTOY OctaneRender & RNDR Cloud](https://otoy.com)**  

  Unbiased spectral GPU path-tracing engine backed by decentralized cloud GPU rendering for real-time volumetric lighting, caustics, and look development.



- **[Maxon Redshift](https://maxon.net)**  

  Biased GPU-accelerated production renderer offering interactive IPR lighting previews, physical sun/sky systems, volumetric fog, and cloud rendering integrations.



- **[Blender Studio (Cloud)](https://studio.blender.org/)**  

  Cloud production platform, open-movie asset library, and collaborative pipeline hub built around Blender's Cycles and EEVEE lighting workflows.



- **[Lightmap HDR Light Studio](https://www.lightmap.co.uk/)**  

  Dedicated real-time 3D lighting application that lets artists paint and position HDRI studio softboxes, rims, and area lights live across Blender, Maya, Houdini, and Cinema 4D.





## Open-Source GitHub Projects



- **[Stability-AI/ReLi3D](https://github.com/Stability-AI/ReLi3D)**  

  Open-source relightable multi-view 3D reconstruction model (`ICLR 2026`) that predicts UV-unwrapped textured meshes with disentangled illumination and spatially varying PBR materials.



- **[RelightFormer (`vLAR-group/RelightFormer`)](https://github.com/vLAR-group/RelightFormer)**  

  SIGGRAPH Asia 2026 open-source feed-forward generative Transformer for multi-view consistent 3D scene relighting without slow iterative inverse rendering.



- **[IC-Light (`lllyasviel/IC-Light`)](https://github.com/lllyasviel/ic-light)**  

  Popular open-source (`Apache-2.0`) illumination-manipulation diffusion framework supporting text-conditioned and background-conditioned consistent relighting for 3D renders and portraits.



- **[DDS-Relight (`tarhanefe/dds-relight`)](https://github.com/tarhanefe/dds-relight)**  

  Open-source 3D NeRF and radiance field relighting framework integrating wavelet-based gradient filtering and diffusion guidance to preserve reflections and scene geometry.



- **[GR3EN (`gr3en-relight`)](https://gr3en-relight.github.io/)**  

  Open-source generative 3D environment relighting system that distills video-to-video relighting diffusion into 3D reconstructions with realistic cast shadows, reflections, and neon/lamp insertion.



- **[grabanton/lighter](https://github.com/grabanton/lighter)**  

  Open-source Houdini package for fast HDRI studio lighting editing, highlight detection, and extracting bright HDR regions into separate native Houdini/Karma lights.



- **[SkyRig Studio (`lamer486/SkyRigStudio`)](https://github.com)**  

  Free, open-source (`MIT`) HDRI and sun-alignment lighting script for 3ds Max featuring Poly Haven HDRI downloads, automatic sun detection, and exposure/EV overrides.



- **[Blender (Cycles & EEVEE Next)](https://github.com)**  

  Flagship open-source (`GPL-2.0+`) 3D creation suite featuring Light Linking, Cycles spectral/path-traced global illumination, Nishita physical sky, and real-time EEVEE lighting.



- **[LuxCoreRender](https://github.com)**  

  Open-source (`Apache-2.0`) physically based, unbiased spectral path-tracing render engine specialized in complex light transport, caustics, and architectural daylighting.



- **[Mitsuba 3](https://github.com)**  

  Research-grade open-source (`BSD-3-Clause`) retargetable forward and inverse rendering system built for differentiable 3D lighting, material optimization, and light transport simulation.



- **[Appleseed](https://github.com)**  

  Open-source (`MIT`) physically based global illumination rendering engine designed for film look-development, realistic area lighting, and animation.



- **[storytold/lightcraft](https://github.com/storytold/lightcraft)**  

  Open-source (`Apache-2.0`) pure-Rust, scene-referred 32-bit float non-destructive photo and EXR/HDR raw developer with WebAssembly support and AI agent MCP control.



- **[MakeHDR (`sosoyan/make-hdr`)](https://github.com/sosoyan/make-hdr)**  

  Cross-platform open-source (`BSD-3-Clause`) OpenFX plug-in for Nuke, Fusion, and Natron that merges multi-exposure LDR brackets into calibrated 32-bit HDRI environment maps.



- **[HDRI-lighting-Shortcut (`Nikos-Prinios`)](https://github.com/Nikos-Prinios/HDRI-lighting-Shortcut)**  

  Open-source Blender add-on providing one-click HDRI world shader node setups, rotation/elevation gizmos, and strength controls for rapid look-dev lighting.



- **[NeRF-OSR (`r00tman/NeRF-OSR`)](https://github.com)**  

  Open-source PyTorch framework for outdoor 3D scene relighting using neural radiance fields with disentangled illumination and surface reflectance.



### Additional Strong Open-Source Options



- **[houyuanchen111/Awesome-Relight](https://github.com/houyuanchen111/Awesome-Relight)** and **[tandaily/Awesome-Relighting](https://github.com/tandaily/Awesome-Relighting)** for comprehensive research maps covering `LuxRemix`, `SSD-GS` (Relightable 3DGS), `COREA`, `IllumiNeRF`, and inverse rendering datasets.

- **[Poly Haven HDRIs](https://github.com)** for 100% free, CC0-licensed up to 16K/24K unclipped 32-bit EXR/HDR studio, indoor, and outdoor lighting environments.

- **[Radiance](https://github.com)** for validated physically based architectural lighting simulation and luminance/illuminance engineering analysis.

- **[Cycles Standalone](https://github.com)** and **[Embree (Intel)](https://github.com)** / **[OpenImageDenoise](https://github.com)** for high-performance CPU/GPU ray-tracing kernels and AI path-trace denoising.

- **[Three.js PMREMGenerator & Lightformers](https://github.com)** and **[Drei `<Environment>` / `<Lightformer>`](https://github.com)** for building custom real-time WebGL HDRI studio lighting rigs in browsers.



**Frameworks for building custom systems**: Combine **Blender Cycles** or **Mitsuba 3** with **Stability-AI/ReLi3D**, **IC-Light**, **Poly Haven HDRIs**, and **storytold/lightcraft** (for 32-bit float tone mapping) for end-to-end open-source 3D lighting and relighting pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Neural 3D relighting models (such as `ReLi3D`, `RelightFormer`, and `DDS-Relight`) require compatible CUDA GPUs and calibrated multi-view camera poses for optimal inverse rendering quality.

- Verify individual software and model weight licenses (`MIT`, `Apache-2.0`, `GPL-2.0+`, `BSD-3-Clause`, or community research terms) before deploying relighting pipelines in commercial productions.



---
