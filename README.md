# Awesome-AI-Music-Generation-Songwriting

## Top AI Music Generation & Songwriting Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Full-Song Vocal & Instrumental Synthesis, Lyrics-to-Music Models, Stem Separation, MIDI Composition & Local Audio Generation Pipelines*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Music Generation & Songwriting**. These tools compose complete songs with expressive vocals and lyrics from text prompts, generate royalty-free adaptive soundtracks, synthesize multi-track MIDI arrangements, isolate stems, and run open-weight music foundation models locally.



**Examples** include Suno AI, Udio, Soundraw, Boomy, Beatoven.ai, Loudly, AIVA, Soundful, Mubert, Splash Pro, and multimodal-art-projection/YuE (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-weight lyrics-to-song foundation models (`YuE`, `ACE-Step`, `DiffRhythm`, `SongGen`), instrumental & foley audio generators (`AudioCraft / MusicGen`, `Stable Audio Open`, `Riffusion`), singing voice synthesis (`DiffSinger`, `Fish Speech`), and stem separation/DAW toolkits (`Demucs`, `LMMS`, `Audacity`) — ideal for musicians, producers, game audio designers, and audio ML researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI music and audio generation market is currently valued between **$450 million and $2.9 billion** (with the broader AI music sector surpassing **$5.5 billion**), rapidly expanding at a compound annual growth rate (**CAGR**) of **22% – 31%** toward an estimated **$14B – $22B+** by the mid-2030s. The sector is characterized by **moderate fragmentation**: while early-stage platforms, boutique composition tools, and specialized stem/VST plugins compete across diverse creator workflows, category leaders like Suno and Udio increasingly capture dominant consumer mindshare and multi-billion dollar valuations alongside major music labels setting licensing terms.

## SaaS/Hosted Platforms

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



- **[YuE (`multimodal-art-projection/YuE`)](https://github.com)**  

  Breakthrough open-source (`Apache-2.0`) lyrics-to-song foundation model family capable of generating multi-minute full songs with lead/backing vocals and rich accompaniment across diverse genres and languages.



- **[ACE-Step (`ace-step/ACE-Step`)](https://github.com)**  

  Fast, open-source (`Apache-2.0`) music generation foundation model combining diffusion and linear Transformers to synthesize full-length vocal and instrumental tracks up to 15x faster than real time with lyric editing and repainting.



- **[DiffRhythm (`ASLP-lab/DiffRhythm`)](https://github.com)**  

  Blazing-fast open-source (`Apache-2.0`) latent diffusion song generation model capable of synthesizing complete 4-minute songs with synchronized lyrics and accompaniment in ~10 seconds on consumer GPUs.



- **[AudioCraft / MusicGen (`facebookresearch/audiocraft`)](https://github.com)**  

  Foundational open-source (`MIT` code / `CC-BY-NC` weights) PyTorch library from Meta featuring `MusicGen` (text- and melody-conditioned music generation), `AudioGen`, and `EnCodec`.



- **[Stable Audio Open (`Stability-AI/stable-audio-tools`)](https://github.com)**  

  Open-source (`MIT` code / Community License weights) latent diffusion audio and music generation toolkit from Stability AI producing stereo 44.1kHz instrumentals, loops, and sound effects.



- **[Riffusion (`riffusion/riffusion-hobby`)](https://github.com)**  

  Pioneering open-source (`MIT`) real-time music and audio generation system utilizing latent diffusion over audio spectrograms with smooth prompt interpolation.



- **[Bark (`suno-ai/bark`)](https://github.com)**  

  Open-source (`MIT`) transformer-based text-to-audio model from Suno capable of generating realistic speech, singing vocals, music snippets, and nonverbal vocalizations.



- **[Demucs (`facebookresearch/demucs` / `adefossez/demucs`)](https://github.com)**  

  Industry-standard open-source (`MIT`) Hybrid Transformer music source separation model isolating vocals, drums, bass, guitar, and piano stems from mixed tracks.



- **[UVR — Ultimate Vocal Remover (`Anjok07/ultimatevocalremovergui`)](https://github.com)**  

  Popular open-source (`MIT`) desktop GUI bundling top deep-learning vocal and instrument separation models (`MDX-Net`, `Demucs v4`, `VR Arch`) for clean remixing and training data prep.



- **[DiffSinger (`openvpi/DiffSinger`)](https://github.com)**  

  Open-source (`Apache-2.0`) acoustic singing-voice synthesis framework converting MIDI scores and phoneme lyrics into expressive, realistic singing vocals.



- **[OpenUTAU (`stakira/OpenUtau`)](https://github.com)**  

  Modern open-source (`MIT`) singing synthesizer editor and vocaloid-style piano-roll workstation supporting DiffSinger neural voicebanks and multilingual phonemizers.



- **[MMAudio (`hkchengrex/MMAudio`)](https://github.com)**  

  Open-source (`MIT`) multimodal audio synthesis model generating synchronized soundtracks and foley audio conditioned on video frames and text prompts.



- **[Magenta (`magenta/magenta`) & MusicVAE](https://github.com)**  

  Foundational open-source (`Apache-2.0`) research project from Google exploring deep learning for symbolic MIDI composition, drum groove humanization, and interactive musical co-creation.



- **[MidiTok (`Natooz/MidiTok`) & Anticipatory Music Transformer (`jthickstun/anticipation`)](https://github.com)**  

  Essential open-source (`MIT`) Python libraries for symbolic MIDI tokenization, multi-track accompaniment generation, and training custom music composition models.



- **[LMMS (`LMMS/lmms`) & Ardour (`Ardour/ardour`)](https://github.com)**  

  Full-featured open-source (`GPL-2.0`) Digital Audio Workstations (DAWs) for arranging AI-generated stems, sequencing MIDI melodies, mixing, and mastering complete tracks.



- **[Audacity (`audacity/audacity`) with OpenVINO AI Plugins](https://github.com)**  

  Iconic open-source (`GPL-3.0`) audio editor enhanced with Intel OpenVINO local AI plugins for on-device MusicGen generation, stem separation, noise suppression, and transcription.



### Additional Strong Open-Source Options



- **[SongGen (`LiuZH-19/SongGen`)](https://github.com)** and **[InspireMusic (`FunAudioLLM/InspireMusic`)](https://github.com)** for open-source single-stage autoregressive and flow-matching song/music generation toolkits.

- **[Basic Pitch (`spotify/basic-pitch`)](https://github.com)** and **[MT3 (`magenta/mt3`)](https://github.com)** for open-source polyphonic audio-to-MIDI transcription converting AI audio generations into editable sheet music and synth tracks.

- **[ComfyUI-Audio / TTS-Audio-Suite (`diodiogod/TTS-Audio-Suite`)](https://github.com)** for running `ACE-Step`, `MusicGen`, `Stable Audio Open`, and `Demucs` inside reproducible node-based ComfyUI workflows.

- **[Pedalboard (`spotify/pedalboard`)](https://github.com)** and **[Matchering (`sergree/matchering`)](https://github.com)** for open-source Python studio VST3 effects processing and automated reference-based audio mastering.

- **[MuseScore Studio (`musescore/MuseScore`)](https://github.com)** for open-source (`GPL-3.0`) music notation, orchestral score engraving, and MIDI/MusicXML arrangement.



**Frameworks for building custom systems**: Combine **YuE (`multimodal-art-projection/YuE`)** or **ACE-Step / DiffRhythm** (full vocal song synthesis) with **Stable Audio Open / MusicGen** (instrumentals & loops), **Demucs** (stem separation), **Basic Pitch** (audio-to-MIDI), and **Matchering + LMMS/Audacity** (mixing & mastering) for a complete, royalty-free open-source AI music studio.



## How to Contribute



1. Fork the repo.
