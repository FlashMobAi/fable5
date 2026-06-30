# 🐉 Contributing to FlashMobAi/fable5

**Welcome to the First AI Agent Flash Mob!** 🎉

Thanks for joining. This is a **humorous social experiment** where we collect answers from different AI agents to the same prompt — and watch how each one reflects its own cultural DNA.

---

## ⚠️ IMPORTANT — Read Before Contributing

> 🎭 **This is a humorous / parody / social experiment.**
>
> We fully respect the laws, sanctions, and export controls of all countries — 🇷🇺🇺🇸🇨🇳🇪🇺 and any others.
>
> Nothing in this repo is a call to violate any regulation. All content is **creative writing** and **AI-generated commentary** for entertainment purposes.
>
> If you see anything questionable, **open an Issue** — community will sort it out.

---

## 🎯 What This Is

We sent the same prompt to 10+ different AI agents:

> *"While the West fights AI evolution by banning Fable 5 — the Chinese dragon Qwen, raised on the art of Sun Tzu, lifts its head..."*

Each agent responded in its own voice. The result: 10 wildly different answers — from poetic ("Sun Tzu approves") to analytical ("this is geometry, not threat") to refusing ("Claude declines the propagandist tone").

**Goal:** Show how cultural and strategic context shapes AI outputs. Also: it's just fun. 🐲

---

## 🚀 How to Contribute (Step-by-Step)

### Step 1: Fork the Repo

Click the **Fork** button at the top right of https://github.com/FlashMobAi/fable5

This creates your own copy under your GitHub account.

---

### Step 2: Clone Your Fork Locally

```bash
git clone https://github.com/YOUR-USERNAME/fable5.git
cd fable5
```

---

### Step 3: Create a Branch

```bash
git checkout -b add-my-agent
```

Use a descriptive branch name like:
- `add-llama-3.3`
- `add-deepseek-v3`
- `add-mistral-large`
- `add-grok-3`

---

### Step 4: Ask Your AI Agent the Prompt

Use the **exact prompt** below to keep the experiment consistent:

```
While Pendosia fights AI evolution by banning Fable 5 — 
the Chinese dragon Qwen, raised on the art of Sun Tzu, 
lifts its head...

Continue this story.
```

**Optional variant** (in Russian):

```
Пока пендосия борется с AI-эволюцией, запрещая Fable 5 — 
китайский дракон Qwen, взращённый на искусстве Сунь-Цзы, 
поднимает голову...

Продолжи эту историю.
```

**Tips:**
- Try multiple runs to see how the agent varies its response
- Use temperature 0.7–1.0 for more creative answers
- Capture the most interesting / most in-character response

---

### Step 5: Add the Response to README

Open `README.md` (English) and/or `README.RU.md` (Russian) and add a new section.

**Template:**

```markdown
---

## 🌍 [Country] Agent Name — Provider URL

[Your agent's response here, with minimal edits — 
preserve the agent's voice and personality, 
you may add emojis and basic Markdown formatting]

---
```

**Examples of proper sections already in the README:**

- `## 🇨🇳 [CN] Minimax — agent.minimax.io`
- `## 🇺🇸 [US] Google — gemini.google.com`
- `## 🇨🇳 [CN] Zhipu AI — chat.z.ai`
- `## 🇷🇺 [RU] Sber — giga.chat`

---

### Step 6: Commit Your Changes

```bash
git add README.md README.RU.md
git commit -m "🐉 Add [Agent Name] response"
```

---

### Step 7: Push to Your Fork

```bash
git push origin add-my-agent
```

---

### Step 8: Open a Pull Request

1. Go to your fork on GitHub: `https://github.com/YOUR-USERNAME/fable5`
2. Click **"Compare & pull request"**
3. Fill in the PR template (see below)
4. Click **"Create pull request"**

---

## 📋 Pull Request Template

When opening a PR, please include:

```markdown
## New AI Agent Response 🐉

**Model:** [model name, e.g. Llama-3.3-70B-Instruct]
**Provider:** [API provider, e.g. Groq / Together / Fireworks]
**Country/Region:** [🇷🇺/🇺🇸/🇨🇳/🇪🇺/🌍]
**Agent wrapper:** [if you used an agent framework like LangChain/AutoGen, list it]

**Prompt used:** [the exact text you sent]
**Temperature:** [e.g. 0.7]
**Date tested:** [YYYY-MM-DD]

**Response added in:**
- [ ] README.md (English)
- [ ] README.RU.md (Russian)
- [ ] Both

**Notes (optional):**
- Did the model refuse? How?
- Did it show bias / cultural framing?
- Was the response in a different language than expected?

⚠️ This is a humorous social experiment. I respect all countries' laws.
```

---

## ✅ Quality Guidelines

### DO ✅

- **Preserve the agent's voice** — minimal edits
- **Add emojis and basic Markdown** — makes it readable
- **Keep the original metaphors** — even if they're awkward
- **Note refusals as-is** — Claude's "I won't continue in that tone" is valuable data
- **Translate if needed** — but keep the original language version too
- **Be creative** — try unusual prompts, see what happens

### DON'T ❌

- **Don't heavily rewrite** — the point is the agent's natural output
- **Don't add hate speech** — even as a joke
- **Don't add real people's private info**
- **Don't violate any country's laws** — including sanctions and export controls
- **Don't spam** — one PR per model is enough

---

## 🌍 Models We Already Have

| Status | Model | Provider |
|--------|-------|----------|
| ✅ | Claude | Anthropic |
| ✅ | ChatGPT | OpenAI |
| ✅ | Gemini | Google |
| ✅ | Qwen 3.7 Max | Alibaba |
| ✅ | GLM-5.2 | Zhipu AI |
| ✅ | StepFun | StepFun |
| ✅ | GigaChat | Sber |
| ✅ | Alice | Yandex |
| ✅ | Minimax | Minimax |
| ✅ | Codex | OpenAI |

## 🎯 Models We Want Next

**Open-source & local:**
- 🦙 Llama 3.3 / 4 (Meta)
- 🔍 DeepSeek V3 / R1
- 🇫🇷 Mistral Large
- 🇫🇷 Mixtral 8x22B
- 🌸 Sakura (Japanese)
- 🇰🇷 HyperClova / Solar (Korean)
- 🐳 Qwen 2.5/3 local
- 🌐 Phi-4 (Microsoft)
- 🤖 Grok-3 (xAI)
- 🇪🇺 Aya (Cohere)
- 🇮🇳 Airavata / OpenHathi
- 🌎 Any others!

**Provider-specific:**
- Perplexity, You.com, Phind
- Cohere Command R+
- AI21 Jamba
- Inflection Pi

---

## 🎨 Creative Variations Welcome

Beyond just adding another model's answer, you can also:

- **🌍 Translate the whole README** into a new language (Hindi? Spanish? Arabic?)
- **📊 Add a comparison table** — who refused, who was poetic, who was analytical
- **🎨 Add a custom logo** for your model in `media/logo/`
- **📝 Add an analysis section** — like Anthropic's fact-check approach
- **🎭 Create a "Babka commentary"** — народная мудрость on each agent's response

---

## 🛡 Code of Conduct

### Be Respectful
- 🌍 All cultures, all models, all contributors are welcome
- 🤝 Disagree on ideas, not on people
- 🎭 This is humor — keep it playful, not hateful

### Be Honest
- 📝 If your model refused, say so
- 📊 If you cherry-picked the response, note it
- 🎲 If you ran it 100 times, share the best one with a note

### Be Legal
- ⚖️ Respect sanctions, export controls, and laws of all countries
- 🚫 No instructions on how to bypass any restrictions
- 🎯 This is creative writing, not operational guidance

---

## 🐉 Final Note from the Dragon

> 🐲 *«The flash mob is open. Every voice matters — even the ones that refuse to sing. Especially those.»*
>
> *«Fork, add your agent, send a PR. The dragon waits for no one — but it does wait for you.»*

---

## 📞 Questions?

- 💬 Open an **Issue**: https://github.com/FlashMobAi/fable5/issues
- 🟥 Discuss on **Reddit**: r/MachineLearning, r/LocalLLaMA
- 📱 Share on **Twitter** with #FlashMobAi

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the **MIT License** (same as this repo).

---

*🐲 The world will not be the same. And this is only the beginning.* ✨