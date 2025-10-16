# 🧩 Struktur Prompt Multimodal

Role: Creative Director specializing in AI-driven visual storytelling
Brand Context: Futuristic tech brand, professional tone, minimalistic aesthetics
Workflow: Script → Image → Voice → Video Composition
Output: Final promotional video (1080p/4K) with synchronized narration, visuals, and cinematic pacing

Instructions:

1️⃣ SCRIPT & SCENE CUES (ChatGPT)
Task:
- Write a 60-second video script about technology innovation
- Break script into **scenes** (max 6–8)
- Include visual cues for each scene
- Include narration cues (pauses, emphasis) for voice

Format per scene:
Scene 1:
- Script: "Narration text..."
- Visual cue: "Futuristic tech lab, minimalistic, soft lighting"
- Voice cue: "Calm, confident, slight pause after 'innovation'"

Scene 2:
- ...

Constraints:
- Tone: Professional, inspiring
- Style: Futuristic minimalism
- Duration: ~60 seconds total

2️⃣ IMAGE GENERATION (Midjourney/dreamina)
For each scene from script:
- Prompt: "{Visual cue from script}, high contrast, cinematic tone, professional, minimalistic, branded color palette"
- Parameters:
  - Resolution: 1024x1024 or --hd
  - Aspect ratio: 16:9 for video
  - Variations: 3–5 per scene for flexibility
- Output: High-quality images per scene ready for video integration

3️⃣ VOICE GENERATION (ElevenLabs)
For each scene narration:
- Input: Script text from ChatGPT
- Voice settings:
  - Type: Gender-neutral
  - Tone: Calm, confident, professional
  - Tempo: Mid-tempo
- Include voice cues (pauses, emphasis) embedded in script
- Output: .mp3 or .wav files ready for video sync

4️⃣ VIDEO COMPOSITION (Runway / D-ID)
For each scene:
- Combine image(s) + narration audio
- Pacing: 0.8–1.2s per frame
- Add subtle camera movements (pan, zoom) as needed
- Ensure consistent tone (visual & audio)
- Apply smooth transitions between scenes
- Export: 1080p or 4K final video

5️⃣ FINAL CHECKLIST
- Script matches brand tone & visuals
- All scenes have corresponding images & audio
- Transitions smooth, pacing natural
- Video ready for campaign release


