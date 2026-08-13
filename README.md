# FUTURE-AIGC-JSON-prompter-skills
aigc, prompt-engineering, json-prompting, text-to-video, text-to-image, stable-diffusion, runwayml
# Specialized JSON Prompter Skills for AIGC Creators 🚀

A curated collection of production-ready JSON schemas optimized for AI visual artists and video creators. These schemas eliminate prompt drift, enforce strict camera physics, and separate aesthetic styling from foreground subjects.

## 📦 What's Inside

- **`static-design/`**: Schemas prioritizing spatial composition, textures, color hex arrays, and framing for midjourney, Stable Diffusion, and Gemini.
- **`video-generation/`**: Templates built to isolate camera physics, temporal settings, and fluid/particle dynamics for Runway, Sora, LTX Studio, and Veo.

---

## 🎨 1. Static Visual Design Skill
Use this schema to isolate asset textures and lighting choices from the main foreground subject to prevent color blending.

```json
{
  "project_type": "static_visual_design",
  "composition": {
    "subject": "A futuristic sleek mechanical hummingbird hovering over a glowing cybernetic orchid",
    "framing": "Extreme close-up shot, macro photography lens",
    "placement": "Subject centered, shallow depth of field with heavy bokeh"
  },
  "aesthetic_style": {
    "art_direction": "Cyberpunk mixed with high-end luxury tech product design",
    "color_palette": ["#00FFCC", "#FF007F", "#1A1A24"],
    "lighting": "Biomechanical rim lighting, neon key light, soft volumetric fog reflection",
    "surface_textures": "Polished chrome, matte carbon fiber, iridescent glass wings"
  },
  "technical_render": {
    "aspect_ratio": "16:9",
    "engine_modifiers": "Octane Render style, Unreal Engine 5 nanite detail, 8k textures"
  }
}
```

---

## 🎬 2. AIGC Video Generation Skill
Use this schema to enforce strict camera movements and environmental simulation boundaries to prevent the AI from warping objects over time.

```json
{
  "project_type": "video_generation",
  "temporal_settings": {
    "duration_seconds": 4.0,
    "target_fps": 24
  },
  "scene_setup": {
    "environment": "A rainy cyberpunk Tokyo alleyway at night",
    "atmosphere": "Moody, dense neon reflection on wet asphalt, rising steam",
    "key_actors": "A lone cybernetic traveler walking away down the center path"
  },
  "camera_physics": {
    "movement_vector": "Continuous slow push-in, low-angle tracking shot",
    "lens_type": "Anamorphic 35mm, high distortion on edges",
    "pacing": "Linear, no abrupt cuts or sudden dynamic motion spikes"
  },
  "particle_dynamics": {
    "fluid_simulation": "Rain hitting puddles creating concentric ripples",
    "gaseous_simulation": "Slow-moving neon steam rising from street grates"
  }
}
```

---

## 🛠️ Credits & Inspired By
This repository incorporates principles and structures derived from:
- [JSON Prompter by Afzal7](https://github.com) - Interface layout inspiration.
- [JSON Prompt Gen by SolvingTools](https://github.com) - Parameter mapping and physics vectors.

## 📄 License
This project is licensed under the MIT License - feel free to use, modify, and distribute these schemas for commercial or personal AIGC workflows.
