<h1 align="center">GPT Short Video Mass Generator</h1>

## Project Overview:
This repo wraps a full pipeline for pumping out thousands of short-form videos—end to end. It scrapes clips, grabs screenshots, sends frames to GPT for smart descriptions, auto-generates multiple on-brand text overlays, then burns everything back onto the videos with FFmpeg/Python. Perfect for bulk content farms for TikTok/Reels/Shorts without babysitting every edit.


## Core Features:
- **Hands-off throughput:** One command spins the whole chain—scrape → analyze → caption → render.
- **Human-ish creativity at scale:** GPT handles semantic tagging and overlay copy so videos don’t feel templated.
- **Stealthy, resilient scraping:** Rotating proxies + randomized timing to keep sources happy and IPs fresh


<div align="center">
  <img
    src="https://github.com/user-attachments/assets/d200549d-7613-446f-a43b-19a4117ca360"
    alt="select device"
    width="600px"
  />
</div>


<div align="center">
  <a href="https://appilot.app/">
    <img
      alt="Website"
      width="25px"
      src="https://github.com/user-attachments/assets/8e5f3af3-b098-4c1d-980d-df9aebc680d0"
    />
    <code>Appilot Website</code>
  </a>
  &nbsp;&nbsp;
  <a href="https://discord.gg/3CZ5muJdF2">
    <img
      alt="Join Our Server"
      width="30px"
      src="https://github.com/Zeeshanahmad4/RealEstateMate-WhatsApp-Group-Management-Bot/blob/main/discord-icon-svgrepo-com.svg"
    />
    <code>Join Our Server</code>
  </a>
  &nbsp;&nbsp;
  <a href="https://t.me/devpilot1">
    <img
      alt="Contact us"
      width="30px"
      src="https://edent.github.io/SuperTinyIcons/images/svg/telegram.svg"
    />
    <code>Contact Us</code>
  </a>
</div>

<div align="center">
<strong> Have a Custom Project in Mind please Contact?</strong>

<div align="center">
  <a href="mailto:support@appilot.app">
  <img
    alt="Email"
    width="30px"
    src="https://github.com/user-attachments/assets/91c8d428-32b7-4be0-91fa-2e42c902b5b8"
  />
  <code>support@appilot.app</code>
</a>
  &nbsp;&nbsp;
  <a href="https://cal.com/app-pilot-m8i8oo/30min">
  <img
    alt="Book a 30-minute Call"
    width="30px"
    src="https://github.com/user-attachments/assets/cd3e5c7b-3e4e-4bb3-b242-bcc20ee78f13"
  />
  <code>Book a 30-minute Call</code>
</a>
<span>

<div align="left">

## Features List:
| Feature                | Description                                                                       |
| ---------------------- | --------------------------------------------------------------------------------- |
| Video Scraper          | Pulls thousands of niche-relevant clips from defined sources with proxy rotation. |
| Auto Screenshotter     | Extracts 3 representative frames per video for semantic analysis.                 |
| GPT Frame Describer    | Feeds frames to OpenAI API to generate context-aware summaries.                   |
| Overlay Text Generator | Produces 5 punchy overlay lines per clip, tuned to your niche.                    |
| FFmpeg Batch Renderer  | Stacks overlays onto videos in bulk with position/size randomization.             |
| Retry & Queue System   | Fault-tolerant jobs with resumable queues for long runs.                          |
| Config-First Design    | YAML/ENV driven: paths, API keys, model choices, overlay styles.                  |
| Proxy & Rate Control   | Rotates proxies, inserts jittered delays to mimic human traffic.                  |
| Audit Logs & Reports   | CSV/JSON logs of each step (scraped, processed, failed, rendered).                |
| Modular Pipeline       | Swap GPT provider, scraper, or renderer without gutting the code.                 |


## Key Stats:
- **Automation Accuracy:** 98% successful end-to-end runs
- **Session Stability:** 24/7 processing with auto-resume
- **Concurrent Account/Sources:** 200+ handled via queue shards
- **Action Randomization Effectiveness:** 99% pass rate in internal A/B tests

## Tech & Stack:
- **Python** (scraping, orchestration), FFmpeg (video ops)
- **OpenAI/LLM APIs** for descriptions & overlays
- **Playwright/Selenium** + **Rotating Proxies** for stealth grabs
- Optional: **Redis/RQ** for job queues, **Docker** for reproducible runs
