# Voice Design guidance_scale A/B samples

Listening samples for sierra-research/tau2-bench#636. This branch holds audio only and is not meant to be merged.

Persona: `priya_patil`. Prompt, sample text, seed 42, `eleven_ttv_v3` and loudness 0.5 are identical; only `guidance_scale` differs (38 = current script, 5 = proposed fix).

- `synth_*_u1.mp3`, `synth_*_u2.mp3`: two user-simulator lines spoken by the saved voice with tau2's synthesis settings (`eleven_v3`, stability 0.5, similarity 0.75).
- `preview_*_p0.mp3`: the Voice Design preview the script saves as the voice (`previews[0]`).
