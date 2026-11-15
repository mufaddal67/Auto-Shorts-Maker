# Auto Shorts Maker

A free Google Colab notebook that turns a long video into short vertical (9:16) clips for TikTok, Reels and YouTube Shorts. Gemini finds the most clip-worthy moments, and ffmpeg cuts and reformats them.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/auto-shorts-maker/blob/main/Auto_Shorts_Maker.ipynb)

## Requirements

- A **Google Colab account** (any free Google account works)
- A **free Gemini API key** from [Google AI Studio](https://aistudio.google.com/apikey)
- The **URL of a video** whose creator has given permission for it to be clipped

## How to use

1. Click **Open in Colab** above.
2. Save your Gemini API key as a Colab secret named `GEMINI_API_KEY` (🔑 icon in the left sidebar) and turn on notebook access. Never share or commit your key.
3. Paste the video URL into the settings cell.
4. Run the cells in order and download your clips.

## Responsible use

Only clip videos you own or have explicit permission to use, and follow each platform's terms of service.

## License

MIT
