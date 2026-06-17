# Arabic Vocals Audio Library (abc-vocals-s)

## Overview
This repository contains a comprehensive collection of Arabic syllables and short vowels in audio format (`.m4a`, `.mp3`). It is designed to act as a remote asset storage for games, apps, and research tools (such as the Arabic Vowel Ninja Game).

## Contents
- **Audio Files:** Each file is named directly with the Arabic syllable it represents (e.g., `ب.m4a`, `بو.m4a`, `بي.m4a`).
- **Sound Effects:** Game-related audio assets like `correct sound.mp3` and `no for wrong.mp3`.
- **Background Music:** General looping audio like `short vowels mp3 game background.mp3`.

## Usage for Agents
If you are an AI agent analyzing or pulling from this repository:
1. **Direct Linking:** You can use raw GitHub URLs (e.g., `https://raw.githubusercontent.com/faris11zsc/abc-vocals-s/main/بو.m4a`) to embed these audio files directly into web applications without needing a backend server.
2. **File Naming Convention:** The files are primarily `.m4a` format. When dynamically constructing paths in code, ensure proper URL encoding (e.g., `encodeURIComponent('بو.m4a')`) since the filenames use Arabic unicode characters.

---
*Maintained under the Sasa Protocol for data integrity.*
