# Awesome AI Music Generation & Songwriting

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-AI-Music-Generation-Songwriting/pulls)
[![Last Updated](https://img.shields.io/badge/Updated-November_2026-blue.svg)](https://github.com/ishandutta2007/Awesome-AI-Music-Generation-Songwriting)

> An SEO-indexed, curated directory of the best **AI Music Generation tools**, **AI Songwriting platforms**, and **open-source audio machine learning foundation models**. Covers text-to-music models, AI singing voice synthesis (SVS), stem separation, neural audio workstations, MIDI composition, and local inference pipelines.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS / Hosted AI Music Platforms](#saas--hosted-ai-music-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Recommended Custom Studio Pipelines](#recommended-custom-studio-pipelines)
- [How to Contribute](#how-to-contribute)
- [License & Disclaimer](#license--disclaimer)

---

## Sector Overview & Market Dynamics

The global AI music and audio generation market is currently valued between **$450 million and $2.9 billion** (with the broader AI music sector surpassing **$5.5 billion**), rapidly expanding at a compound annual growth rate (**CAGR**) of **22% – 31%** toward an estimated **$14B – $22B+** by the mid-2030s. The sector is characterized by **moderate fragmentation**: while early-stage platforms, boutique composition tools, and specialized stem/VST plugins compete across diverse creator workflows, category leaders like Suno and Udio increasingly capture dominant consumer mindshare and multi-billion dollar valuations alongside major music labels setting licensing terms.

## SaaS / Hosted AI Music Platforms

| Platform | Estimated Scale / Valuation / Revenue | Starting Paid Price | Free Tier / Trial Limit | Key Highlights & Songwriting Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Suno AI](https://suno.com)** | **$5.4B** Valuation (Series D, June 2026; ~$300M ARR) | $10/mo ($8/mo billed annually) | 50 credits/day (~10 song parts/day, non-commercial only) | Flagship cloud studio for generating complete multi-minute vocal songs, custom lyrics, stem splits, and audio-to-song remixes. |
| **[Udio](https://udio.com)** | **~$40M - $100M** Valuation (~$10M seed funding, a16z) | $10/mo ($8/mo billed annually) | 10 credits/day + 100 backup pool/mo (max 3 long tracks/day, personal use) | High-fidelity vocal and musical generation with section extension, audio inpainting, lyric timing, and stem separation. |
| **[Boomy](https://boomy.com)** | **$80M** Valuation ($5.4M+ funding; $1M-$10M ARR) | $9.99/mo | Free forever: Create & edit up to 25 saved tracks (no downloads or commercial releases) | Accessible generator for instant genre beats, vocal arrangements, and direct streaming distribution. |
| **[Splash Pro](https://splashmusic.com)** | **$20M - $27M** Funding ($10M-$50M est. revenue) | $10/mo (Starter tier) | Free forever: Text-to-song experimentation with standard length & basic vocalists (no WAV/stems, personal use) | AI vocals and beat generation toolkit combining text-to-music, custom lyric vocalists, and Roblox/gaming integration. |
| **[Soundraw](https://soundraw.io)** | **$5.01M** Funding (Series A; est. <$5M revenue) | $16.99/mo ($12.99/mo billed annually) | Free forever: Unlimited track generation & preview customization (0 downloads allowed without paid plan) | Dynamic creator tool for real-time arrangement, tempo manipulation, instrument muting, and video background music. |
| **[Beatoven.ai](https://beatoven.ai)** | **$2.5M - $15.5M** Funding (~$2.5M ARR) | $9/mo (Creator tier) | Free forever: Unlimited composition & previewing, with ~15 mins monthly download allocation (attribution required) | Mood-based soundtrack generator for video editors and indie game devs with section-by-section emotion and cut controls. |
| **[Soundful](https://soundful.com)** | **$3.8M** Funding (~$1.6M ARR) | $9.99/mo ($4.99/mo billed annually) | Free forever: Unlimited generations from 25+ templates, restricted to 1 MP3 download/month (personal use, credit required) | Studio-grade loops and royalty-free instrumental generation customized by musical scale, key, and BPM. |
| **[Mubert](https://mubert.com)** | **$2.6M - $3.6M** Funding (~$1.6M ARR) | $21/mo ($11.69/mo billed annually for Creator) | Free forever (Ambassador Plan): 25 generated tracks/month (watermarked, personal use with attribution) | Generative streaming music engine and B2B API delivering adaptive, infinite soundscapes for games, live streams, and apps. |
| **[AIVA](https://aiva.ai)** | **$1.5M - $2.5M** Funding (~$1M-$2.3M ARR) | €15/mo (~$16/mo; €11/mo billed annually) | Free forever: 3 downloads/month, max 3 min track length, MP3/MIDI only (non-commercial, AIVA owns copyright) | AI virtual composer specialized in classical, cinematic symphonies, and game tracks with full MIDI/sheet-music export. |
| **[Loudly](https://loudly.com)** | Early-stage venture (<$2M est. funding / ARR) | $9.99/mo ($5.99/mo billed annually) | Free forever: 30-second generations and 1 song download/month for testing and personal evaluation | AI music creator combining text prompts, 100% royalty-free loop blends, stem export, and genre crossovers. |





## Open-Source GitHub Projects

Curated collection of open-source AI music generation models, vocal synthesis tools, stem separators, and symbolic composition frameworks, sorted by GitHub stargazers count:

- **[Bark (`suno-ai/bark`)](https://github.com/suno-ai/bark)** [![GitHub stars](https://img.shields.io/github/stars/suno-ai/bark?style=social&color=white)](https://github.com/suno-ai/bark/stargazers)  
  Open-source (`MIT`) transformer-based text-to-audio model from Suno capable of generating realistic speech, singing vocals, background acoustics, and musical cues.

- **[RVC — Retrieval-based Voice Conversion (`RVC-Project/Retrieval-based-Voice-Conversion-WebUI`)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)** [![GitHub stars](https://img.shields.io/github/stars/RVC-Project/Retrieval-based-Voice-Conversion-WebUI?style=social&color=white)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI/stargazers)  
  High-performance, easy-to-use voice conversion framework popular for converting vocal tracks into diverse singing voices and timbre styles using VITS neural networks.

- **[Fish Speech (`fishaudio/fish-speech`)](https://github.com/fishaudio/fish-speech)** [![GitHub stars](https://img.shields.io/github/stars/fishaudio/fish-speech?style=social&color=white)](https://github.com/fishaudio/fish-speech/stargazers)  
  Leading open-source multilingual neural voice and vocal synthesis system built on dual-autoregressive and VQ-GAN architectures with zero-shot voice cloning capabilities.

- **[UVR — Ultimate Vocal Remover (`Anjok07/ultimatevocalremovergui`)](https://github.com/Anjok07/ultimatevocalremovergui)** [![GitHub stars](https://img.shields.io/github/stars/Anjok07/ultimatevocalremovergui?style=social&color=white)](https://github.com/Anjok07/ultimatevocalremovergui/stargazers)  
  Core open-source (`MIT`) desktop GUI application bundling leading deep-learning vocal and instrument separation models (`MDX-Net`, `Demucs v4`, `VR Arch`) for clean remixing and stem extraction.

- **[AudioCraft / MusicGen (`facebookresearch/audiocraft`)](https://github.com/facebookresearch/audiocraft)** [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/audiocraft?style=social&color=white)](https://github.com/facebookresearch/audiocraft/stargazers)  
  Foundational open-source (`MIT` code / `CC-BY-NC` weights) PyTorch library from Meta featuring `MusicGen` (text- and melody-conditioned music generation), `AudioGen`, and `EnCodec`.

- **[Magenta (`magenta/magenta`)](https://github.com/magenta/magenta)** [![GitHub stars](https://img.shields.io/github/stars/magenta/magenta?style=social&color=white)](https://github.com/magenta/magenta/stargazers)  
  Foundational open-source (`Apache-2.0`) research suite from Google exploring deep learning for symbolic MIDI songwriting, chord progression modeling, and drum groove humanization.

- **[Audacity (`audacity/audacity`)](https://github.com/audacity/audacity)** [![GitHub stars](https://img.shields.io/github/stars/audacity/audacity?style=social&color=white)](https://github.com/audacity/audacity/stargazers)  
  Iconic open-source (`GPL-3.0`) multitrack audio workstation enhanced with Intel OpenVINO deep learning AI plugins for local MusicGen generation, stem separation, and noise suppression.

- **[MuseScore Studio (`musescore/MuseScore`)](https://github.com/musescore/MuseScore)** [![GitHub stars](https://img.shields.io/github/stars/musescore/MuseScore?style=social&color=white)](https://github.com/musescore/MuseScore/stargazers)  
  World-leading open-source (`GPL-3.0`) musical score notation and engraving application for composing, arranging, and rendering orchestral sheet music and multi-instrument arrangements.

- **[YuE (`multimodal-art-projection/YuE`)](https://github.com/multimodal-art-projection/YuE)** [![GitHub stars](https://img.shields.io/github/stars/multimodal-art-projection/YuE?style=social&color=white)](https://github.com/multimodal-art-projection/YuE/stargazers)  
  Breakthrough open-source (`Apache-2.0`) lyrics-to-song foundation model family capable of synthesizing multi-minute full songs with rich accompaniment and lead/backing vocals from text prompts.

- **[LMMS (`LMMS/lmms`)](https://github.com/LMMS/lmms)** [![GitHub stars](https://img.shields.io/github/stars/LMMS/lmms?style=social&color=white)](https://github.com/LMMS/lmms/stargazers)  
  Free, cross-platform open-source (`GPL-2.0`) digital audio workstation for beatmaking, MIDI sequencing, sound design, and assembling AI-generated stems into finished songs.

- **[Demucs (`facebookresearch/demucs`)](https://github.com/facebookresearch/demucs)** [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/demucs?style=social&color=white)](https://github.com/facebookresearch/demucs/stargazers)  
  Industry-standard open-source (`MIT`) Hybrid Transformer music source separation toolkit that cleanly separates mixed audio into drums, bass, vocals, and other stems.

- **[Pedalboard (`spotify/pedalboard`)](https://github.com/spotify/pedalboard)** [![GitHub stars](https://img.shields.io/github/stars/spotify/pedalboard?style=social&color=white)](https://github.com/spotify/pedalboard/stargazers)  
  Spotify's open-source (`GPL-3.0`) high-speed Python audio effects processing library supporting VST3/AU plugins, spatial reverb, delays, and mastering chains for generated stems.

- **[Basic Pitch (`spotify/basic-pitch`)](https://github.com/spotify/basic-pitch)** [![GitHub stars](https://img.shields.io/github/stars/spotify/basic-pitch?style=social&color=white)](https://github.com/spotify/basic-pitch/stargazers)  
  Lightweight, fast neural network library from Spotify for polyphonic audio-to-MIDI transcription with note pitch-bend detection.

- **[Ardour (`Ardour/ardour`)](https://github.com/Ardour/ardour)** [![GitHub stars](https://img.shields.io/github/stars/Ardour/ardour?style=social&color=white)](https://github.com/Ardour/ardour/stargazers)  
  Professional-grade open-source (`GPL-2.0`) digital audio workstation for audio engineers, multi-track recording, MIDI arranging, and advanced mixing/mastering of synthetic tracks.

- **[ACE-Step (`ace-step/ACE-Step`)](https://github.com/ace-step/ACE-Step)** [![GitHub stars](https://img.shields.io/github/stars/ace-step/ACE-Step?style=social&color=white)](https://github.com/ace-step/ACE-Step/stargazers)  
  Accelerated linear Transformer and diffusion song generation foundation model with localized lyric editing, infilling, and extension.

- **[OpenUtau (`openutau/OpenUtau`)](https://github.com/openutau/OpenUtau)** [![GitHub stars](https://img.shields.io/github/stars/openutau/OpenUtau?style=social&color=white)](https://github.com/openutau/OpenUtau/stargazers)  
  Modern open-source (`MIT`) singing synthesizer DAW and vocal editor supporting DiffSinger, ENUNU, and traditional UTAU voicebanks with pitch-curve editing.

- **[Stable Audio Open (`Stability-AI/stable-audio-tools`)](https://github.com/Stability-AI/stable-audio-tools)** [![GitHub stars](https://img.shields.io/github/stars/Stability-AI/stable-audio-tools?style=social&color=white)](https://github.com/Stability-AI/stable-audio-tools/stargazers)  
  Latent diffusion model from Stability AI producing high-resolution 44.1kHz stereo audio samples, instrument riffs, drum patterns, and ambient soundscapes up to 47 seconds long.

- **[Riffusion (`riffusion/riffusion-hobby`)](https://github.com/riffusion/riffusion-hobby)** [![GitHub stars](https://img.shields.io/github/stars/riffusion/riffusion-hobby?style=social&color=white)](https://github.com/riffusion/riffusion-hobby/stargazers)  
  Real-time music generation technique utilizing Stable Diffusion fine-tuned on audio spectrograms to generate looping grooves and continuous audio transitions.

- **[DiffSinger (`openvpi/DiffSinger`)](https://github.com/openvpi/DiffSinger)** [![GitHub stars](https://img.shields.io/github/stars/openvpi/DiffSinger?style=social&color=white)](https://github.com/openvpi/DiffSinger/stargazers)  
  Acoustic singing-voice synthesis framework converting musical scores and lyrics into natural, expressive singing vocals via score-conditioned diffusion models.

- **[Matchering (`sergree/matchering`)](https://github.com/sergree/matchering)** [![GitHub stars](https://img.shields.io/github/stars/sergree/matchering?style=social&color=white)](https://github.com/sergree/matchering/stargazers)  
  Automated audio mastering container using target reference tracks to match frequency spectrum, loudness, and dynamics across AI tracks.

- **[AudioLDM 2 (`haoheliu/AudioLDM2`)](https://github.com/haoheliu/AudioLDM2)** [![GitHub stars](https://img.shields.io/github/stars/haoheliu/AudioLDM2?style=social&color=white)](https://github.com/haoheliu/AudioLDM2/stargazers)  
  Versatile latent text-to-audio and text-to-music diffusion architecture conditioned on Language of Audio (LOA) representations.

- **[DiffRhythm (`ASLP-lab/DiffRhythm`)](https://github.com/ASLP-lab/DiffRhythm)** [![GitHub stars](https://img.shields.io/github/stars/ASLP-lab/DiffRhythm?style=social&color=white)](https://github.com/ASLP-lab/DiffRhythm/stargazers)  
  Ultra-fast latent diffusion full-song generation model synthesizing full 4-minute songs with lyrics and backing tracks in seconds on consumer GPUs.

- **[MMAudio (`hkchengrex/MMAudio`)](https://github.com/hkchengrex/MMAudio)** [![GitHub stars](https://img.shields.io/github/stars/hkchengrex/MMAudio?style=social&color=white)](https://github.com/hkchengrex/MMAudio/stargazers)  
  Multimodal generative model for synchronized soundtrack and ambient audio generation driven by video frames and textual guidance.

- **[MT3 (`magenta/mt3`)](https://github.com/magenta/mt3)** [![GitHub stars](https://img.shields.io/github/stars/magenta/mt3?style=social&color=white)](https://github.com/magenta/mt3/stargazers)  
  Multi-task multitrack music transcription framework converting polyphonic and multi-instrument audio mixes into expressive symbolic MIDI.

- **[TTS-Audio-Suite / ComfyUI-Audio (`diodiogod/TTS-Audio-Suite`)](https://github.com/diodiogod/TTS-Audio-Suite)** [![GitHub stars](https://img.shields.io/github/stars/diodiogod/TTS-Audio-Suite?style=social&color=white)](https://github.com/diodiogod/TTS-Audio-Suite/stargazers)  
  Modular node-based audio workstation extension for ComfyUI enabling end-to-end visual pipelines with ACE-Step, MusicGen, Bark, and Demucs.

- **[MidiTok (`Natooz/MidiTok`)](https://github.com/Natooz/MidiTok)** [![GitHub stars](https://img.shields.io/github/stars/Natooz/MidiTok?style=social&color=white)](https://github.com/Natooz/MidiTok/stargazers)  
  Fast Python tokenization library for MIDI scores and symbolic music composition with Transformer and LLM tokenizers (REMI, Octuple, MuMIDI).

- **[SongGen (`LiuZH-19/SongGen`)](https://github.com/LiuZH-19/SongGen)** [![GitHub stars](https://img.shields.io/github/stars/LiuZH-19/SongGen?style=social&color=white)](https://github.com/LiuZH-19/SongGen/stargazers)  
  Single-stage autoregressive transformer architecture for full-track song generation incorporating conditioned lyrics and rhythm controls.

- **[Anticipatory Music Transformer (`jthickstun/anticipation`)](https://github.com/jthickstun/anticipation)** [![GitHub stars](https://img.shields.io/github/stars/jthickstun/anticipation?style=social&color=white)](https://github.com/jthickstun/anticipation/stargazers)  
  Symbolic music generation model implementing the Anticipation architecture for real-time interactive accompaniments and musical filling.



## Recommended Custom Studio Pipelines

Build a complete, royalty-free, locally runnable AI music workstation by pairing open-source models across each phase of production:

1. **Full-Song Generation & Lyrics-to-Music**: Use [YuE](https://github.com/multimodal-art-projection/YuE), [ACE-Step](https://github.com/ace-step/ACE-Step), or [DiffRhythm](https://github.com/ASLP-lab/DiffRhythm) for full song compositions with vocal arrangements.
2. **Singing Voice Synthesis & Timbre Conversion**: Use [Fish Speech](https://github.com/fishaudio/fish-speech), [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI), or [DiffSinger](https://github.com/openvpi/DiffSinger) inside [OpenUtau](https://github.com/openutau/OpenUtau).
3. **Loops, Ambient & Sound FX**: Generate high-fidelity instrumentals via [Stable Audio Open](https://github.com/Stability-AI/stable-audio-tools), [AudioCraft / MusicGen](https://github.com/facebookresearch/audiocraft), or [AudioLDM 2](https://github.com/haoheliu/AudioLDM2).
4. **Stem Separation**: Deconstruct tracks into pristine acapella, drums, bass, and synth stems via [Ultimate Vocal Remover (UVR)](https://github.com/Anjok07/ultimatevocalremovergui) or [Demucs](https://github.com/facebookresearch/demucs).
5. **Audio-to-MIDI & Sheet Music**: Transcribe melodies into editable notation via [Basic Pitch](https://github.com/spotify/basic-pitch) and arrange in [MuseScore Studio](https://github.com/musescore/MuseScore).
6. **DAW Sequencing, Mixing & Mastering**: Arrange in [LMMS](https://github.com/LMMS/lmms) or [Audacity](https://github.com/audacity/audacity) / [Ardour](https://github.com/Ardour/ardour), polish with [Spotify Pedalboard](https://github.com/spotify/pedalboard), and perform automated reference-mastering with [Matchering](https://github.com/sergree/matchering).

---

## How to Contribute

Contributions are warmly welcomed! To contribute:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/add-new-tool`.
3. Add the SaaS platform or open-source repository (ensuring accurate pricing/limits for SaaS and correct stargazer badges for open-source repos).
4. Commit your changes: `git commit -m "Add [Tool Name]"`.
5. Push to your fork and submit a Pull Request.

---

## License & Disclaimer

- **License**: Distributed under the [MIT License](file:///C:/Users/ishan/Documents/Projects/Awesome-AI-Music-Generation-Songwriting/LICENSE).
- **Disclaimer**: Trademarks and brand logos belong to their respective copyright holders. Listed pricing and free tier allowances reflect publicly available information as of late 2026 and are subject to change by each service provider.
