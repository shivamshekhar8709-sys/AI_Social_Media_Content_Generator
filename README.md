# 🚀 AI Social Media Content Generator

An AI-powered tool that generates ready-to-post social media content — posts, hashtags, CTAs, content ideas, and even AI image prompts — using the **Google Gemini API**.

Just tell it your **topic, platform, tone, and audience**, and it instantly creates platform-optimized content you can refine, improve, and pair with AI-generated visuals.

---

## ✨ Features

- 📝 **AI-Generated Posts** — Create engaging, platform-specific social media posts in seconds
- 🏷️ **Trending Hashtags** — Automatically generates 5 relevant hashtags for your content
- 📣 **Call-to-Action (CTA)** — Adds a compelling CTA to boost engagement
- 💡 **Next Content Idea** — Suggests a related content idea to keep your calendar full
- 🔁 **Content Improvement** — Rewrites and polishes generated content (more engaging, concise, and emoji-rich)
- 🎨 **AI Image Prompt Generator** — Generates a detailed prompt you can use with any AI image tool to create matching visuals
- 🖼️ **Image Analysis** — Uses Gemini's multimodal capabilities to analyze how well a generated image matches your content and audience

---

## 🧠 How It Works

```
            👤 User Input (Topic, Platform, Tone, Audience)
                          │
                          ▼
                🧠 Prompt Engineering
                          │
                          ▼
                  🤖 Google Gemini
                          │
              ┌───────────┴───────────┐
              ▼           ▼           ▼
         📝 Content   🏷️ Hashtags   📣 CTA
                          │
                          ▼
               🎨 AI Image Prompt
                          │
                          ▼
              🖼️ Final Creative + Analysis
```

---

## 🛠️ Tech Stack

- **Python**
- **Google Gemini API** (`google-genai` SDK)
- **Pillow (PIL)** — for image handling and analysis
- **Jupyter Notebook** — interactive, step-by-step workflow

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/ai-social-media-content-generator.git
   cd ai-social-media-content-generator
   ```

2. **Install dependencies**
   ```bash
   pip install -q google-genai pillow
   ```

3. **Add your Gemini API key**

   Create a file named `gemini api key.txt` in the project root and paste your [Google Gemini API key](https://aistudio.google.com/apikey) inside it.

   > ⚠️ **Never commit your API key file to GitHub.** Make sure `gemini api key.txt` is listed in your `.gitignore`.

---

## ▶️ Usage

1. Open `AI_Social_Media_Content_generator.ipynb` in Jupyter Notebook / JupyterLab / Google Colab.
2. Run the cells in order. You'll be prompted to enter:
   - **Topic** — what the post is about
   - **Platform** — LinkedIn / Instagram / X
   - **Tone** — Professional / Friendly / Funny
   - **Target Audience** — who the content is for
   - **Content Type** — Post / Caption / Carousel
3. The AI generates:
   - A social media post
   - 5 hashtags
   - A call-to-action
   - A related content idea
4. (Optional) Run the improvement step to refine the generated content further.
5. (Optional) Generate an AI image prompt, add your own generated/uploaded image, and let Gemini analyze how well it fits your post.

---

## 📁 Project Structure

```
ai-social-media-content-generator/
│
├── AI_Social_Media_Content_generator.ipynb   # Main notebook
├── gemini api key.txt                        # Your API key (not committed)
└── README.md
```

---

## 🔑 Getting a Gemini API Key

1. Go to [Google AI Studio](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Generate a new API key
4. Paste it into `gemini api key.txt`

---

## 🚧 Roadmap

- [ ] Add a simple web UI (Streamlit/Gradio)
- [ ] Support scheduling/exporting a weekly content calendar
- [ ] Multi-platform batch generation
- [ ] Direct AI image generation (not just prompts)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) or open a pull request.

---

## 🙌 Acknowledgements

Built using the [Google Gemini API](https://ai.google.dev/) for generative AI capabilities.
