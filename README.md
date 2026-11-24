# Awesome-Content-Moderation-AI-Slop-Filtering
# Awesome-Content-Moderation-AI-Slop-Filtering

markdown

## Top Content Moderation & AI Slop Filtering Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on AI Slop Detection, Multimodal Content Moderation, Toxicity/NSFW Filtering, Trust & Safety Guardrails & Anti-Spam Pipelines*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Content Moderation & AI Slop Filtering**. These tools detect, classify, filter, quarantine, and moderate low-effort AI-generated slop, synthetic spam, toxicity, NSFW media, hate speech, and policy violations across social feeds, user-generated content platforms, LLM applications, and browser extensions.



**Examples** include Hive Moderation, ActiveFence, Spectrum Labs, WebPurify, Sightengine, OpenAI Moderation, Azure AI Content Safety, Amazon Rekognition Content Moderation, Google Cloud Content Safety, Checkstep, and miqdadbadjuber/anti-slop (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for AI slop & synthetic content filtering (`miqdadbadjuber/anti-slop`, `Binoculars`, `WildGuard`), multimodal LLM safety & toxicity classifiers (`Llama Guard`, `ShieldGemma`, `Detoxify`, `LLM Guard`, `NeMo Guardrails`), image/video NSFW & deepfake filters (`NudeNet`, `OpenNSFW2`), and self-hosted Trust & Safety platforms (`Coop`, `Osprey`) — ideal for Trust & Safety engineers, community moderators, AI platform builders, and web users curating cleaner feeds.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Hive Moderation](https://thehive.ai)**  

  Enterprise multimodal AI content moderation and AI-generated media detection platform identifying synthetic text/images/audio, NSFW content, violence, and spam via real-time APIs.



- **[OpenAI Moderation API](https://openai.com)**  

  Cloud multimodal classification endpoint evaluating text and images across hate, harassment, self-harm, sexual content, and violence categories.



- **[Azure AI Content Safety (Microsoft)](https://microsoft.com)**  

  Managed cloud content moderation service offering severity scoring, prompt-shield jailbreak detection, groundedness checks, and custom blocklists across text and images.



- **[Sightengine](https://sightengine.com)**  

  Real-time cloud image, video, and text moderation API detecting AI-generated imagery, NSFW content, deepfakes, scam text, and spam at scale.



- **[ActiveFence](https://activefence.com)**  

  Enterprise Trust & Safety intelligence and real-time AI guardrails platform protecting online platforms and generative AI applications against abuse, fraud, and harmful content.



- **[Amazon Rekognition Content Moderation](https://amazon.com)**  

  Managed AWS computer vision moderation API automatically flagging explicit, suggestive, violent, and visually disturbing content in images and video streams.



- **[Google Cloud Content Safety & Perspective API](https://perspectiveapi.com)**  

  Cloud machine-learning moderation tools (Jigsaw / Google Cloud) scoring conversational toxicity, spam, and unsafe visual/textual content in real time.



- **[WebPurify](https://webpurify.com)**  

  Hybrid AI and live human-in-the-loop content moderation service covering profanity filtering, image/video moderation, and metaverse/community safety.



- **[Spectrum Labs (Guardian)](https://spectrumlabsai.com)**  

  Contextual AI content moderation platform built to recognize disruptive behaviors, hate speech, and multi-turn toxicity across online gaming and social communities.



- **[Checkstep](https://checkstep.com)**  

  Unified Trust & Safety operations and content moderation platform combining AI classifiers, human review queues, and regulatory compliance workflows (DSA / Online Safety Act).





## Open-Source GitHub Projects



- **[miqdadbadjuber/anti-slop](https://github.com)**  

  Open-source AI slop filtering toolkit engineered to detect, downrank, and filter low-effort AI-generated text, engagement bait, and synthetic clutter from content feeds.



- **[Llama Guard (`meta-llama/PurpleLlama`)](https://github.com)**  

  Flagship open-weight safety and content moderation model family from Meta fine-tuned to classify both user prompts and AI-generated responses against MLCommons safety taxonomies.



- **[ShieldGemma (`google-deepmind/shieldgemma`)](https://github.com)**  

  Suite of open-weight content moderation models built on Gemma 2/3 by Google for high-accuracy text safety classification across toxicity, hate speech, harassment, and explicit content.



- **[LLM Guard (`protectai/llm-guard`)](https://github.com)**  

  Comprehensive open-source security and moderation toolkit for LLM applications providing input/output scanners for toxicity, prompt injection, PII leakage, gibberish/slop, and ban-topics.



- **[Detoxify (`unitaryai/detoxify`)](https://github.com)**  

  Popular open-source Python library providing fast, multilingual pre-trained transformer models for predicting toxicity, severe toxicity, obscenity, threats, and identity attacks.



- **[Binoculars (`ahans30/Binoculars`)](https://github.com)**  

  Leading open-source zero-shot LLM-generated text detector comparing cross-perplexity scores across paired language models to identify AI-generated slop without task-specific training.



- **[NudeNet (`notAI-tech/NudeNet`)](https://github.com)**  

  Lightweight, self-hostable open-source neural network library for real-time NSFW image/video classification and automated object-level censoring/blurring.



- **[OpenNSFW2 (`bhky/opennsfw2`)](https://github.com)**  

  Clean TensorFlow 2 / Keras open-source implementation of Yahoo's OpenNSFW model for fast image and video frame safety scoring.



- **[Coop (`roostorg/coop`, formerly Thorn Safer / Coop)](https://github.com)**  

  Open-source all-in-one Trust & Safety moderation platform (maintained under ROOST) providing automated rule engines, human review queues, NCMEC reporting, and user appeals.



- **[Osprey (`roostorg/osprey`)](https://github.com)**  

  Open-source real-time anti-spam, abuse detection, and event-stream rules engine (originally built at Discord and open-sourced via ROOST) for high-throughput platform safety.



- **[NeMo Guardrails (`NVIDIA-NeMo/Guardrails`)](https://github.com)**  

  Open-source programmable guardrail toolkit from NVIDIA for adding topical, safety, anti-hallucination, and content-moderation rails to conversational AI systems.



### Additional Strong Open-Source Options



- **[WildGuard (`allenai/wildguard`)](https://github.com)** for Allen AI's open-source lightweight moderation tool detecting malicious user prompts, unsafe model responses, and refusal compliance.

- **[RAID Benchmark (`liamdugan/raid`)](https://github.com)** for open-source benchmarking and evaluation of AI-generated text and slop detectors across adversarial perturbations.

- **[AI Slop Blocker Browser Extensions (`search?q=ai+slop+blocker+extension`)](https://github.com)** for client-side open-source browser extensions filtering AI-generated thumbnails, social engagement slop, and synthetic SEO spam farms.

- **[CardiffNLP Offensive/Toxicity Classifiers (`cardiffnlp/twitter-roberta-base-offensive`)](https://huggingface.co)** for fast, CPU-friendly Hugging Face moderation models deployable via ONNX Runtime.

- **[Microsoft Presidio (`microsoft/presidio`)](https://github.com)** for Microsoft's open-source context-aware PII detection and anonymization engine safeguarding user-generated text and logs.



**Frameworks for building custom systems**: Combine **miqdadbadjuber/anti-slop** or **Binoculars** for AI-generated slop detection, **Llama Guard / ShieldGemma + NudeNet** for multimodal text/image safety classification, and **Osprey + Coop** for full-stack Trust & Safety rules and human moderation queues.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Automated AI-slop detectors and content moderation classifiers can produce false positives (especially on non-native English writing or benign artistic imagery) and false negatives; always provide transparent user appeal mechanisms and human-in-the-loop review for critical enforcement actions.

Use code with caution.

• Trust & Safety systems operating in the EU or UK must align with regulatory transparency and appeal obligations under the Digital Services Act (DSA) and Online Safety Act.

Made for Trust & Safety engineers, community moderators, AI platform builders, and open-source contributors.

Let's make content moderation and AI slop filtering more open, transparent, and user-controlled.
