<h1 align="center">GPT Short Video Mass Generator</h1>

## Project Overview:
This repo wraps a full pipeline for pumping out thousands of short-form videos—end to end. It scrapes clips, grabs screenshots, sends frames to GPT for smart descriptions, auto-generates multiple on-brand text overlays, then burns everything back onto the videos with FFmpeg/Python. Perfect for bulk content farms for TikTok/Reels/Shorts without babysitting every edit.


## Core Features:
- **Hands-off throughput:** One command spins the whole chain—scrape → analyze → caption → render.
- **Human-ish creativity at scale:** GPT handles semantic tagging and overlay copy so videos don’t feel templated.
- **Stealthy, resilient scraping:** Rotating proxies + randomized timing to keep sources happy and IPs fresh
