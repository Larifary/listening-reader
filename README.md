# Listening Reader

An offline read-along player for papers and books: the text on screen with the current sentence highlighted, read aloud by the device voice or by natural-voice MP3s made with [edge-tts](https://github.com/rany2/edge-tts).

Open it at **https://larifary.github.io/listening-reader/** — on iPhone, in Safari, then Share › Add to Home Screen. After the first visit it works without internet.

- Documents and audio are added from your own files (Add files) and stay in that browser on that device. Nothing is uploaded.
- Optional position sync between devices: paste a GitHub token with only the `gist` scope under Voice and text settings. The reader keeps a secret gist with each book's ID and paragraph number (never any text). When another device saved a newer place, the book shows a “Continue from p. …” button.
- Make reading files with `readalong.py` (kept outside this repo): `python3 readalong.py "paper.pdf" --audio`.
- Bundled sample: Summerfield & Stachenfeld, *The recipe for intelligence in natural and artificial systems*, Neuron 114 (2026), open access under CC BY 4.0.
