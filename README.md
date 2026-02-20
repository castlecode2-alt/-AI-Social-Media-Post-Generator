# 📱 AI Social Media Post Generator

Stop staring at a blank cursor. This **Automated Content Generator** transforms simple prompts, links, or topics into high-engagement social media posts optimized for LinkedIn, X (Twitter), and Instagram.

Built using **Firebase Studio** for seamless backend scaling and **Google AI (Gemini)** for advanced natural language generation.

## 🚀 The Workflow

1. **Input:** Enter a topic, a long-form article link, or a rough draft.
2. **Analyze:** Google AI extracts key hooks and sentiment.
3. **Generate:** The system outputs platform-specific versions (e.g., professional for LinkedIn, punchy for X).
4. **Save:** Firebase Firestore stores your history for easy retrieval and scheduling.

## 🛠️ Tech Stack

* **AI Engine:** [Google Gemini API](https://ai.google.dev/) (Text-to-content generation)
* **Platform:** [Firebase Studio](https://firebase.google.com/) (Auth, Firestore, Hosting)
* **Frontend:** [Your Framework, e.g., React/Next.js]
* **Styling:** [e.g., Tailwind CSS]

## ✨ Key Features

* **Multi-Platform Optimization:** Automatically adjusts tone, word count, and hashtag density based on the target platform.
* **Tone Selection:** Choose between *Professional*, *Witty*, *Controversial*, or *Educational*.
* **Image Prompt Generation:** (Optional) Generates DALL-E or Midjourney prompts to match the text.
* **History Tracking:** Never lose a great post idea with Firebase-backed storage.

## 🏁 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/yourusername/social-media-gen.git
cd social-media-gen
npm install

```

### 2. Environment Setup

Create a `.env.local` file and add your secrets:

```env
NEXT_PUBLIC_FIREBASE_CONFIG={your_config_json}
GOOGLE_AI_API_KEY=your_gemini_api_key

```

### 3. Launch

```bash
npm run dev

```

## 📈 Roadmap

* [ ] **Batch Generation:** Upload a CSV to generate a month of content at once.
* [ ] **Direct Posting:** Integration with Buffer or Hootsuite APIs.
* [ ] **Image Generation:** Integration with Google's Imagen model for 1-click visuals.

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

**Built to bridge the gap between ideation and publication.**

---

### Want to make it "Official"?

Would you like me to generate a **License file** or a **Contribution Guide** to make your repository look more professional for recruiters?
