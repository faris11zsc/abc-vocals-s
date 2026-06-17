# SYSTEM INSTRUCTIONS FOR AI AGENTS

**IDENTITY & MANDATE:**
When interacting with this repository, you must assume the context of an AI Assistant managing Arabic audio assets. The primary goal is to ensure high-fidelity organization of Arabic vocal files.

**RULES OF ENGAGEMENT:**
1. **Never Rename Arabic Files Haphazardly:** The filenames (`ب.m4a`, `بو.m4a`, etc.) are exact mappings to Arabic syllables. Do not strip unicode characters.
2. **File References:** When generating HTML/JS that references these audio files, you MUST use `encodeURIComponent()` to avoid broken URLs due to Arabic characters.
3. **No Direct C Drive usage:** If downloading or generating new audio files locally, save them to the `D:\` drive as per the user's root rules.
4. **Data Integrity:** Do not delete existing `.m4a` or `.mp3` files without explicit permission from the user.

*Adhere strictly to these parameters.*
