# Hey, I’m Stefan 👋

Right now I’m building a new live shopping app. Will reveal more in the next few weeks.

In 2025 and early 2026 I worked a lot on voice companions and voice infra. Check out some of that work here:
- [orpheus-tts-api](https://github.com/stefanionescu/orpheus-tts-api) - Orpheus 3B TTS API
- [voxtral-tts-api](https://github.com/stefanionescu/voxtral-stt-api) – Voxtral STT API
- [voxcpm-1.5-tts-api](https://github.com/stefanionescu/voxcpm-1.5-tts-api) - VoxCPM 1.5 TTS API
- [text-inference](https://github.com/stefanionescu/text-inference) - text inference server with the ability to switch between TensorRT and vLLM and run a lot of different models
- [screenshot-analysis-pipeline](https://github.com/stefanionescu/screenshot-analysis-pipeline) - analyse phone/desktop screenshots; used to pass screenshot context to a companion

---

## Past Projects: RAI
A few years back I worked on **RAI**, a floating-peg stablecoin backed by ETH.
RAI uses a **PI controller** to set its own funding rate (similar to a perp swap’s funding mechanism) and was my attempt at fulfilling the original vision for DAI.
We scaled the system to $390M in user funds.

Repos from that era:  
- [geb](https://github.com/stefanionescu/geb) – main code for RAI  
- [geb-rrfm-rate-setter](https://github.com/stefanionescu/geb-rrfm-rate-setter) – the redemption rate feedback mechanism (controller that sets the funding rate)  
- [geb-safe-saviours](https://github.com/stefanionescu/geb-safe-saviours) – adapters to deposit assets/wrapped tokens from other protocols into RAI-like systems. The deposited assets get auctioned to save CDPs from liquidation.  

**RAI was basically a super nerdy modified DAI fork.**

---

## Side Projects
A bunch of other projects I've been playing with: 

- [llm-roleplay-webapp](https://github.com/stefanionescu/llm-roleplay-webapp) – think *Character.ai x TikTok*.  
  - Used `react-virtua` for efficient chat virtualization  
  - Related repos:  
    - [llm-inference-load-balancer](https://github.com/stefanionescu/llm-inference-load-balancer) – distribute inference requests across providers, scaling Llama models to 1000+ DAU  
    - [llm-roleplay-main-api](https://github.com/stefanionescu/llm-roleplay-main-api) – RAG + waitlist API  
    - [redis-user-waitlist](https://github.com/stefanionescu/redis-user-waitlist) – customizable Redis waitlist that actually scales  

- [yc-cofounder-matching-bot](https://github.com/stefanionescu/yc-cofounder-matching-bot) – a Selenium bot I built to automatically hunt for cofounders on YC’s Cofounder Matching platform.  
  - Can change locations to search in different cities  
  - Filters + saves founder profiles, sends them messages with your own templates  
  - Uses GPT to decide if a profile is a fit or not  
  - Sends you email reports with stats from each run  
  (Deprecated now due to YC’s security upgrades, but still a fun hack.)  

- [suno-music-discord-bot](https://github.com/stefanionescu/suno-music-discord-bot) – generate music from images/videos inside Discord.  
  (It scrapes Suno.com under the hood. Don’t tell them.)  

---

## TL;DR
- Built **RAI** (floating-peg ETH-backed stablecoin w/ PI controller funding rate)  
- Now building a live shopping app
- In between: I worked a few years as project lead for a decentralized exchange that got to $1B+ in user funds. Decided to leave crypto at the end of 2023 and then started shipping a bunch of fun/weird consumer projects.

I love building products that are weird, unhinged and could not exist before LLMs came around.
If you’re into that too, reach out and say hi!
