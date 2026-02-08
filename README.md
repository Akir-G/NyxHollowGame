# Nyx Hollow's Quest - The Mind Flayer's Curse

A fully voice-acted Dungeons & Dragons text adventure game featuring over 100 AI-generated narrations and dynamic background music.

**UGAHacks 2026 | Tier 2 (Intermediate)**

---

##  Play the Game

### Download Audio Files First
**[Download Audio Package from Google Drive](https://drive.google.com/drive/folders/1hdzQKahOEYH35fGw3CKVmp0GSJoP173r?usp=drive_link)** (121 MP3 files, ~150MB)

### How to Play
1. Download `NyxHollowGameOfficial.html` from this repo
2. Download all audio files from Google Drive link above
3. Place the HTML file and ALL MP3 files in the same folder
4. Open `NyxHollowGameOfficial.html` in your browser (Chrome, Firefox, Safari, Edge)
5. Click the music button to start
6. Enjoy the adventure!

**Note:** The game will still work without audio files using browser text-to-speech, but downloading the audio is highly recommended for the full experience.

---

##  About

You play as **Nyx Hollow**, a half-elf warlock on a mission to find the Absolute Prism and stop a mind flayer curse. 

- **7 Locations** to explore
- **6 Sidequests** to complete
- **110 Voice Files** for narration
- **11 Music Tracks** for atmosphere
- **3 Unique Endings** based on your choices

---

##  Built With

- HTML5, CSS3, JavaScript ES6+
- ElevenLabs API (voice generation)
- Web Audio API (music system)
- Web Speech API (fallback narration)

---

##  Project Stats

- **2,726 lines of code**
- **45 functions**
- **26 progression flags**
- **Development time:** 36 hours
- **Team:** Solo project

---

##  Project Log Summary

### Goals
1. Create fully playable D&D text adventure
2. Integrate 110+ AI voice narrations
3. Implement dynamic background music system
4. Build branching narrative with multiple endings
5. Deploy as single-file web application

### Key Challenges & Solutions

**Challenge 1: Sequential Voice Playback**
- Problem: Multiple voices needed to play in sequence for complex scenes
- Solution: Implemented voice queue system with audio event listeners

**Challenge 2: Voice File Mapping**
- Problem: 110 voice files needed reliable context-based lookup
- Solution: Created ELEVENLABS_VOICES object with context keys

**Challenge 3: Browser Autoplay Blocking**
- Problem: Music wouldn't auto-start due to browser policies
- Solution: Added visual prompt and user interaction trigger

**Challenge 4: GitHub File Size Limits**
- Problem: 150MB of audio exceeded GitHub's limits
- Solution: Hosted audio on Google Drive, maintained code on GitHub

### Technologies Learned
- Web Audio API (playback, crossfading, volume control)
- State Management (custom system with 26 flags)
- API Integration (ElevenLabs voice generation)
- Event-driven programming (audio events, dynamic UI)

### AI Usage
- **ElevenLabs API:** Generated all 110 voice narrations
- **Claude AI:** Debugging assistance, code optimization, documentation
- **Manual work:** 100% game design, 80% core logic, all creative content
- **Critical thinking:** System architecture, problem-solving, feature decisions

---

##  Links

- **Audio Files:** [Google Drive](https://drive.google.com/drive/folders/1hdzQKahOEYH35fGw3CKVmp0GSJoP173r?usp=drive_link)
- **Full Documentation:** [CODE_DOCUMENTATION.md](CODE_DOCUMENTATION.md)

---

**Developer:** Akir Goode | **UGAHacks 2026**
