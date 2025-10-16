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
> "Ultra-detailed futuristic high-tech workspace interior in stylized illustrative art, human characters actively working and interacting naturally with modern ergonomic furniture and gadgets, sleek minimalistic design, cinematic soft glows and atmospheric shadows, harmonious color palette emphasizing focus, elegance, and productivity, subtle integration of professional branding elements, dynamic composition suitable for presentation, visually immersive and engaging, ultra HD resolution, ultra-detailed textures, high contrast, realistic materials with precise reflections and ambient occlusion, cinematic mood lighting, perfect for concept art or presentation render."

### 3. Voice Design (ElevenLabs)
- Buat narasi suara berbahasa Indonesia untuk klip video pendek (30–60 detik) dengan karakteristik berikut:
- Gaya: tenang, percaya diri, netral gender
- Tempo: sedang (mid-tempo), nyaman didengar
- Artikulasi: jelas dan mudah dimengerti
- Nada & Ekspresi: ekspresif, menekankan poin penting secara natural tanpa terdengar berlebihan
- Audiens: profesional teknologi atau edukasi tech
- Platform: ElevenLabs TTS
- Parameter tambahan (opsional): pitch natural, volume seimbang, intonasi halus untuk penekanan kata penting, penekanan emosional ringan sesuai konteks
- Output: file audio berkualitas tinggi siap pakai untuk video pendek.

### 4. Video Composition (Runway / D-ID)
- Buat animasi berdasarkan skrip berikut, dengan setiap adegan digabungkan antara narasi dan gambar.

- Durasi tiap adegan: Estimasi otomatis sesuai pacing narasi dan intensitas scene.

- Transisi antar gambar: Smooth cinematic, natural dan seamless antar adegan.

- Gaya visual: Futuristik minimalis, campuran realistis dan ilustratif, dengan fokus estetika clean, modern, dan sinematik.

- Output: Deskripsi visual per adegan untuk generasi di Runway, termasuk komposisi, warna, lighting, angle, dan elemen kunci yang mendukung storytelling.

- Catatan: Pertahankan flow narasi agar visual mendukung cerita, jangan ada ketidaksesuaian antara pacing narasi dan visual.

