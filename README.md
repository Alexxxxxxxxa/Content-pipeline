# OmniContent AI Forge 🤖🎬

A powerful, end-to-end automated pipeline designed to transform simple form inputs into high-quality video content and automatically distribute it across all major social media platforms.

## 🌟 Vision
The goal of this project is to eliminate the manual grind of content creation. By combining LLMs with video generation APIs and multi-platform publishing tools, this workflow handles everything from scripting to final posting.

## 🚀 Multi-Channel Workflow
The system follows a sophisticated linear logic:

1.  **Input (On Form Submission):** User provides a topic, niche, or raw script.
2.  **Orchestration (AI Agent):** OpenAI's model analyzes the input, optimizes it for the target platform (e.g., SEO for YouTube, hooks for TikTok, professional tone for LinkedIn).
3.  **Creative Refinement:** A secondary LLM layer generates specific visual prompts and scene descriptions.
4.  **Generation (HTTP Requests):** Sends data to a video-gen API (like Kie.ai, HeyGen, or Runway) and retrieves the rendered media.
5.  **Multi-Platform Distribution:**
    * **YouTube:** Automated upload with optimized titles and descriptions.
    * **Instagram/TikTok:** Vertical video formatting and trending hashtag generation.
    * **LinkedIn/Twitter (X):** Professional post generation with embedded video links.

## 🛠️ Tech Stack
* **Workflow Engine:** ActivePieces / Flowise (Visual Automation)
* **Intelligence:** OpenAI GPT-4o
* **Integration:** HTTP Webhooks & REST APIs
* **Destinations:** YouTube Data API, LinkedIn API, Meta Graph API (Instagram), and TikTok for Developers.

## ✨ Key Features
* ✅ **Cross-Platform Optimization:** Automatically adjusts the script style based on the destination.
* ✅ **Zero-Touch Publishing:** No manual rendering or uploading required.
* ✅ **Scalable Architecture:** Easily add more "HTTP Request" nodes to support any new platform.
* ✅ **Dynamic Metadata:** AI generates custom captions, hashtags, and thumbnails for each post.

## ⚙️ Setup
1. **Clone & Import:** Download the `.json` workflow file and import it into your automation builder.
2. **API Credentials:** Add your OpenAI key and the respective API tokens for the social platforms you wish to use.
3. **Customize:** Adjust the "Message a Model" node to define your specific brand voice.

---
*Built to help creators and businesses dominate the digital space with AI.*
Maine kya badla hai?
Name: OmniContent ka matlab hai "all channels," jo LinkedIn aur TikTok ko bhi cover karta hai.

Platform Flexibility: Maine "YouTube" ke bajaye "Multi-Platform Distribution" ka section daal diya hai.

Professional Tone: Ismein maine "Hooks," "SEO," aur "Brand Voice" jaise words use kiye hain jo kisi professional developer ya creator ki nishani hoti hai.
