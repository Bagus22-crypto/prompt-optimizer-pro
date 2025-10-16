# 🧩 Struktur Prompt Multimodal

# Role
Anda adalah *Creative Director* spesialis *AI-driven visual storytelling*.  
Tugas Anda adalah membuat kampanye multimedia lengkap untuk merek teknologi, dengan estetika **futuristic minimalism**, tone profesional, dan gaya **ilustratif**.

# Objective
Buat pipeline konten lengkap untuk **video promosi multi-platform berdurasi 30 detik**, termasuk:

1. **Video Script**  
   - Narasi dan alur cerita profesional, inspiratif, dan singkat.  
   - Bahasa: Indonesia  
   - Tone: Professional, inspiring, concise  

2. **Promotional Images**  
   - Deskripsi prompt AI image generation untuk visual ilustratif futuristik minimalis.  
   - Visual Style: Futuristic minimalism, clean lighting, high contrast, cinematic, ilustratif  
   - Sertakan elemen brand: logo, warna, slogan  

3. **Narrator Voice**  
   - Karakteristik suara: tenang, percaya diri, gender-netral, mid-tempo  
   - Contoh skrip pembacaan sesuai alur video  

4. **Final Video Composition**  
   - Storyboard / sequence  
   - Instruksi editing (cut, transition, timing, efek visual)  
   - Sesuaikan output agar siap digunakan di **multi-platform** (YouTube, LinkedIn, TikTok)  

# Guidelines
- **Duration:** 30 detik  
- **Language:** Indonesian  
- **Tone:** Professional, inspiring, concise  
- **Visual Style:** Ilustratif + Futuristic minimalism  
- **Brand Elements:** Logo, warna, slogan harus ditonjolkan  
- **Output Format:**  
  - Teks terstruktur untuk script  
  - Prompt terperinci untuk AI image generation  
  - Deskripsi voice-over  
  - Urutan storyboard editing

# Additional Notes
- Pastikan durasi total **30 detik**.  
- Gunakan gaya yang menggabungkan realisme dan ilustratif sesuai estetika merek.  
- Hasil harus **siap pakai multi-platform**.

## Prompt Chain

### 1. Script Generation (ChatGPT)
- Tulis skrip video shortform dalam Bahasa Indonesia tentang inovasi teknologi, durasi 30–60 detik. 
- Narasi ditujukan untuk AI voiceover, dengan gaya ringkas, jelas, dan vivid imagery.
- Bagi skrip per adegan singkat, dengan format:
    [Scene X: deskripsi visual singkat]
    Narasi: [teks narasi yang padat, menarik, mudah diikuti]
- Sertakan petunjuk visual yang jelas dan dinamis untuk setiap adegan, agar cocok dipadukan dengan AI-generated visuals.
- Target audiens: umum dan profesional teknologi.
- Fokus inovasi teknologi bebas, tunjukkan dampak, manfaat, dan elemen futuristik secara visual.
- Pastikan skrip sangat padat dan engaging, cocok untuk format shortform (TikTok, Reels, YouTube Shorts).

### 2. Image Generation (Midjourney)
Futuristic high-tech workspace interior with human presence, sleek minimalistic design, illustrative stylized art, clean yet atmospheric mood lighting, cinematic shadows and soft glows, high contrast, professional branding elements subtly integrated, dynamic composition suitable for presentation, modern ergonomic furniture and gadgets, characters interacting naturally with environment, harmonious color palette emphasizing focus and elegance, ultra HD resolution, ultra-detailed textures, visually engaging and immersive.

### 3. Voice Design (ElevenLabs)
> “Generate a narrator voice in Indonesian: calm, confident, gender-neutral, mid-tempo, clear pronunciation suitable for professional tech video.”

### 4. Video Composition (Runway / D-ID)
> “Combine narration with images according to script pacing. Each image should display for a duration suited to the scene, transitions smooth, cinematic flow, aligned with futuristic minimalism style and mixed realistic/illustrative visuals.”
