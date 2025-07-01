# TTS Audiobook Generator from Public Domain Books

This project builds an automated pipeline to turn any public domain book from [Project Gutenberg](https://www.gutenberg.org/) into a modern, listener-friendly audiobook using OpenAI's text generation and ElevenLabs' TTS engine. The final results are published on YouTube via the channel [Once Upon A Classic](https://www.youtube.com/@onceuponaclassic).

##  Project by
Shawn Wilson

##  What It Does
-  Fetches classic books from Project Gutenberg by Book ID
-  Uses OpenAI to generate modern retellings of the original text
-  Converts those retellings into high-quality speech with ElevenLabs API
-  Publishes narrated content on YouTube (Once Upon A Classic)

##  Technologies Used
- Python
- `gutenbergpy` for book fetching
- OpenAI API for narrative generation
- ElevenLabs API for TTS
- FFmpeg (optional, for audio processing)
- YouTube Studio (for publishing)

##  Note on API Keys
The code uses placeholder keys (`YOUR_OPENAI_API_KEY`, `YOUR_ELEVENLABS_API_KEY`) for safety. Replace them with your own to run the pipeline.

##  Book Examples
- **Macbeth** (used in `script_generator.ipynb`)
- **The Enchanted April** (used in `TTS_conversion.ipynb`)
- User can modify the book ID to fetch and convert *any* public domain book

##  Contents
- `script_generator.ipynb` – Fetches any Gutenberg book and converts it into modernized script via OpenAI
- `TTS_conversion.ipynb` – Takes the modernized script and converts it to audio using ElevenLabs


##  YouTube Channel
Watch the audiobooks: [Once Upon A Classic](https://www.youtube.com/@once_upon_a_classic)

---

This project bridges NLP and audio to bring forgotten literary works to new life. Ideal for education, accessibility, and storytelling at scale.
