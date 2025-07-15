<div align="center">
  <img src="https://raw.githubusercontent.com/DivyamTalwar/Sarvam.ai-Assignment/main/SourceCode/Banner.png" alt="AI Marketing Swarm Banner" width="100%"/>
  <h1 style="font-weight: bold; margin-top: 20px; font-size: 64px; text-shadow: 4px 4px 20px #4A90E2;">
    AI Marketing Swarm
  </h1>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=4A90E2&width=600&lines=Your+Autonomous+Content+Engine.;Crafting+Viral+Campaigns%2C+24%2F7.;From+Idea+to+Market+in+Minutes." alt="Typing SVG" /></a>
</div>

<p align="center">
    <a href="https://github.com/DivyamTalwar/Sarvam.ai-Assignment" target="_blank"><img src="https://img.shields.io/github/stars/DivyamTalwar/Sarvam.ai-Assignment?style=for-the-badge&logo=github&color=gold" alt="Stars"/></a>
    <a href="https://github.com/DivyamTalwar/Sarvam.ai-Assignment/network/members" target="_blank"><img src="https://img.shields.io/github/forks/DivyamTalwar/Sarvam.ai-Assignment?style=for-the-badge&logo=github&color=blue" alt="Forks"/></a>
    <a href="https://github.com/DivyamTalwar/Sarvam.ai-Assignment/issues" target="_blank"><img src="https://img.shields.io/github/issues/DivyamTalwar/Sarvam.ai-Assignment?style=for-the-badge&logo=github&color=red" alt="Issues"/></a>
    <a href="https://github.com/DivyamTalwar/Sarvam.ai-Assignment/blob/main/LICENSE" target="_blank"><img src="https://img.shields.io/github/license/DivyamTalwar/Sarvam.ai-Assignment?style=for-the-badge&color=brightgreen" alt="License"/></a>
    <br>
    <img src="https://img.shields.io/badge/n8n-Workflow%20Core-blueviolet?style=for-the-badge&logo=n8n" alt="n8n Core"/>
    <img src="https://img.shields.io/badge/AI%20Stack-Multi--Modal-black?style=for-the-badge" alt="AI Stack"/>
    <img src="https://img.shields.io/badge/Status-Active-purple?style=for-the-badge" alt="Status"/>
    <img src="https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge" alt="Contributions Welcome"/>
</p>

---

> ### **📜 The Manifesto: The Agency is Dead. Long Live the Swarm.**
> The traditional marketing agency is a relic—slow, expensive, and bottlenecked by human limitations. **AI Marketing Swarm** is the response. It is a decentralized, autonomous content engine built on `n8n` that operationalizes a world-class marketing team as a set of interconnected, intelligent workflows. It doesn't just assist; it conceives, creates, and executes entire multi-channel campaigns—from insightful blog posts and professional LinkedIn updates to compelling, AI-generated videos with custom sound. We are not augmenting the marketing team. We are replacing it with a more efficient, scalable, and creative digital organism.

---

### **✨ Core Pillars of the Swarm**
<table width="100%">
  <tr>
    <td align="center" width="33%">
      <h3>🚀 Autonomous Campaigns</h3>
      <p>Generates multi-channel marketing content from a single prompt.</p>
    </td>
    <td align="center" width="33%">
      <h3>🧠 Multi-Modal AI Stack</h3>
      <p>Orchestrates Gemini, DALL-E 3, Runway, and ElevenLabs.</p>
    </td>
    <td align="center" width="33%">
      <h3>⚡ Radical Efficiency</h3>
      <p>Compresses days of marketing work into minutes of automated execution.</p>
    </td>
  </tr>
</table>

---

### **🎬 The Swarm in Motion: The Content Assembly Line**
<div align="center">
  <p>Visualizing the workflow—an idea enters the Swarm and emerges as a complete, multi-platform marketing campaign.</p>
  <img src="https://raw.githubusercontent.com/DivyamTalwar/Sarvam.ai-Assignment/main/SourceCode/Workflow.gif" alt="Workflow GIF" width="90%"/>
  <p><em>This GIF illustrates the flow from a single topic to a blog post, a LinkedIn update, and a faceless video, all orchestrated by n8n.</em></p>
</div>

---

### **🧠 The Digital Agency: Architecture & Blueprints**
AI Marketing Swarm is a collection of specialized, expert workflows orchestrated by `n8n`. Each workflow is a "specialist" in our digital agency, designed to perform a specific marketing function with peak efficiency. This modular architecture allows for infinite scalability and easy customization.

<details>
<summary><strong>🏛️ Click to Meet the Marketing Task Force: The Specialist Workflows</strong></summary>

| Workflow File | Specialist Role | Core AI Services |
| :--- | :--- | :--- |
| `AI_Marketing_Team.json` | **Campaign Strategist** | The central brain that delegates tasks to other specialists. |
| `Blog_Post.json` | **Content Writer & SEO** | `Gemini` for writing, `DALL-E 3` for header images. |
| `LinkedIn_Post.json` | **Social Media Manager** | `Gemini` for professional copy, `DALL-E 3` for visuals. |
| `Create_Image.json` | **Graphic Designer** | `DALL-E 3` for standalone, high-quality image generation. |
| `Edit_Image.json` | **Photo Editor** | `DALL-E 2` for in-painting, out-painting, and modifications. |
| `Faceless_Video.json`| **Video Producer** | `Gemini` (script), `DALL-E 3` (scenes), `Runway` (animation), `ElevenLabs` (audio). |
| `Search_Images.json` | **Stock Photo Researcher** | `Gemini` to find the best free-to-use images for any topic. |
| `Get_News.json` | **Market Researcher** | `News API` to inject real-time events into content strategy. |

</details>

#### **Workflow Spotlight: The Anatomy of a Blog Post**
This is not just JSON; it's a repeatable blueprint for perfect content. Here’s a glimpse into the "mind" of our Blog Post specialist, showcasing the sophisticated prompting that drives its output.

```json
// Blog_Post.json (Illustrative Snippet from an n8n Agent)
{
  "name": "Blog Post Agent",
  "type": "n8n-nodes-base.agent",
  "typeVersion": 1,
  "position": [1080, 520],
  "parameters": {
    "model": "gemini",
    "systemMessage": "You are a world-class SEO Content Writer and Marketing Expert. Your task is to write a comprehensive, engaging, and insightful blog post on the given topic. The tone should be authoritative yet accessible. Structure the article with clear headings, bullet points, and a compelling introduction and conclusion. Ensure the content is optimized for search engines by naturally including relevant keywords. You MUST generate a suitable, creative prompt for an AI image generator to create a header image for this blog post. Your final output must be a single JSON object containing two keys: 'blog_post' and 'image_prompt'."
  }
}
```

---

### **💻 The Arsenal: A Symphony of Elite Technology**
This project is forged with a no-compromise, best-in-class technology stack. Each service was chosen for its unique, market-leading capabilities.

| Category | Technology | Why We Chose It |
| :--- | :--- | :--- |
| 🚀 **Orchestration** | `n8n` | The central nervous system. For visual, robust, and infinitely scalable workflow automation. |
| 🧠 **Text AI** | `Google Gemini 1.5 Flash` | State-of-the-art reasoning, speed, and cost-efficiency for all text and script generation. |
| 🖼️ **Image AI** | `OpenAI DALL-E 3` | The gold standard for generating high-quality, creative, and context-aware visuals on demand. |
| 🎬 **Video AI** | `Runway` | A leader in programmatic, AI-driven video generation for creating dynamic content at scale. |
| 🔊 **Audio AI** | `ElevenLabs` | For creating hyper-realistic voiceovers and soundscapes, adding a layer of polish to video content. |
| 📈 **Data** | `News API` | To ground our content strategy in real-time, relevant world events. |

---

### **🗺️ Future Horizons: The Roadmap**
- ✅ **Phase 1:** Core Multi-Modal Content Workflows (Blog, LinkedIn, Image, Video)
- ⏳ **Phase 2:** Performance Analysis Loop (Workflows to track content engagement via APIs)
- 💡 **Phase 3:** Advanced Campaign Strategist (An agent to proactively suggest content based on news and trend analysis)
- 🚀 **Phase 4:** Self-Optimizing Prompts (Use engagement data to A/B test and refine prompts via Reinforcement Learning)
- 🌐 **Phase 5:** Interactive Web Dashboard (A UI for managing campaigns, viewing results, and triggering workflows)

---

### **🛠️ Activation Protocol: Setup & Deployment**

#### 1. **Set Up the Hive (n8n)**
- **Option A (Cloud):** Sign up for a free `n8n` cloud instance [here](https://n8n.io/pricing/).
- **Option B (Self-Host):** Deploy `n8n` using Docker.
  ```bash
  docker run -it --rm --name n8n -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n
  ```

#### 2. **Clone the DNA**
Clone this repository to get all the workflow `.json` files.
```bash
git clone https://github.com/DivyamTalwar/Sarvam.ai-Assignment.git
cd Sarvam.ai-Assignment
```

#### 3. **Import the Specialists**
In your n8n canvas, manually import each `.json` file from this repository. This will load the pre-built workflows into your instance.

#### 4. **Arm the System: Configure Credentials**
This is the most critical step. In your n8n instance, go to the "Credentials" section and add new credentials for each of the following services. The workflows will automatically use them.

- **Google AI:** For Gemini models.
- **OpenAI:** For DALL-E models.
- **Runway:** For your Runway API key.
- **ElevenLabs:** For your ElevenLabs API key.
- **News API:** For the `Get_News.json` workflow.

#### 5. **Execute**
Navigate to a workflow (e.g., `Blog_Post`) and hit "Execute Workflow". Provide a topic and watch the Swarm create. You can also activate workflows to run on schedules or via webhooks for full automation.

---

### **🤝 Join the Swarm: Call for Contributions**
This is more than a project; it's a new paradigm for content creation. If you are an engineer, a marketer, or a visionary, your contributions are mission-critical.
*   **⭐ Star the project** to signal your support for the future of automated marketing.
*   **🍴 Fork the repo** and submit a PR with your own specialist workflows (e.g., for TikTok, Instagram, or Reddit).
*   **💡 Open an issue** with new ideas, prompt enhancements, or bug reports.
*   **🤖 Integrate a new AI tool** and build a workflow around it.

---

<p align="center">
  <a href="https://github.com/DivyamTalwar">
    <img src="https://github-readme-stats.vercel.app/api?username=DivyamTalwar&theme=merko&hide_border=false&include_all_commits=true&count_private=true&bg_color=00000000&border_color=00000000" alt="Divyam's GitHub Stats"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DivyamTalwar&theme=merko&hide_border=false&include_all_commits=true&count_private=true&layout=compact&bg_color=00000000&border_color=00000000" alt="Divyam's Top Languages"/>
    <img src="https://nirzak-streak-stats.vercel.app/?user=DivyamTalwar&theme=merko&hide_border=false&background=00000000&border=00000000" alt="Divyam's GitHub Streak"/>
  </a>
</p>
