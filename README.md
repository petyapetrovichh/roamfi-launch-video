# roamfi-launch-video

RoamFi V2 launch video, built with HyperFrames.

| Project | Render | Notes |
| --- | --- | --- |
| `roamfi_v2_x/` | `roamfi_v2_x/renders/roamfi_v2_x_2026-09-12_14-22-34.mp4` | Original version |
| `roamfi_v2_x_dynamic/` | `roamfi_v2_x_dynamic/renders/roamfi_v2_x_dynamic.mp4` | Same script, scenes, timings and assets; more kinetic motion design |
| `roamfi_v2_x_motion/` | `roamfi_v2_x_motion/renders/roamfi_v2_x_motion.mp4` | Fully kinetic cut driven by the music: every scene change, object entrance/exit, camera move and text swap sits on the beat grid detected from `reference/audio.mp3` (130 BPM, 52.6s). Objects are rebuilt as custom UI; camera zooms and pans inside panels; no money-flow diagram |
| `roamfi_v2_x_motion_vertical/` | `roamfi_v2_x_motion_vertical/renders/roamfi_v2_x_motion_vertical.mp4` | 9:16 (1080x1920) re-layout of the motion cut: same script, beats, motion and audio; scenes restacked vertically, text and objects rescaled, camera moves reframed for portrait, role pill rests top-centre |

Reference app screenshots, the logo and the music track (`audio.mp3`) live in `reference/`.

Each project renders with `npm run check` then `npm run render` from its own directory.
