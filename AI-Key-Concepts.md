## 🧠 Key Concepts — Expanded

### AI is not magic — it’s patterns in numbers
**What it means:** Computers turn everything into numbers (pixels, words, audio samples, sensor values), then spot patterns in those numbers.
**Everyday feel:** Your phone “recognizes” a face by comparing numeric patterns of pixels; translation maps word-vectors (numbers) from one language to another.
**Mini-exercise:** Take any object (e.g., a photo). Ask: “How would I turn this into numbers?” (RGB values per pixel; height×width×3 array.)
**Takeaway:** If you can represent it as numbers, you can apply AI to it.

---

### Machine Learning (ML) — learning from examples
**What it means:** Instead of writing rules by hand, we feed examples and let the model learn the rule.
**Main flavors:**
* Supervised: labeled examples (email → spam/not spam).
* Unsupervised: find structure without labels (clustering students by study patterns).
* Self-supervised: learn from the data itself (predict the next word in a sentence).
* Reinforcement learning: learn by trial and reward (robot learns to walk).
**Mini-exercise:** Use Teachable Machine to train a 2-class image classifier in minutes (webcam).

---

### Generative AI — create new content from patterns
**What it means:** Models learn the distribution of data (text, images, music) and sample from it to produce new text, pictures, audio, or video.
**Everyday feel:** Chat replies that sound human; images “in the style of …”; music that matches a mood.
**Tip:** Good outputs come from clear instructions + constraints (style, length, audience).
**Try it:** Text (ChatGPT/Claude), Images (DALL·E/Midjourney), Music (Suno/Udio), Video (Veo/Kling).

---

### Prompting — talking to AI so it helps you better
**Core skills:**
* Role: “Act as a math tutor for a 12-year-old.”
* Task: “Explain fractions with a pizza analogy in 5 bullets.”
* Constraints: “Keep it under 120 words; include 1 example.”
* Iterate: Refine with “make it simpler,” “now give me a quiz.”
**Framework:** RATC → Role, Audience, Task, Constraints.
**Pro move:** Give context (input data, examples, style guide) and ask for checklists or rubrics to self-evaluate.

---

### Hallucinations — fluent but wrong answers
**What it is:** The model “fills in” likely words, not guaranteed facts, so it can sound confident yet be incorrect or make up sources.
**How to reduce risk:**
* Ask for sources / citations.
* Provide trusted context (docs, data).
* Use retrieval (RAG) or tools with real data.
* Verify critical claims with a second tool (e.g., Perplexity for citations).
**Good prompt add-on:** “If unsure, say you don’t know.”

---

### RAG (Retrieval-Augmented Generation)
**What it means:** Before answering, the system searches your knowledge base (PDFs, sites, DBs), pulls relevant passages, then the model writes using those snippets.
**Why it’s powerful:** Fewer hallucinations, answers grounded in your data, and easy updates (change the docs, not the model).
**Mental model:** Search → Select → Synthesize.
**Starter idea:** Build a Q&A bot over your policies or class notes; compare answers with/without retrieval.

---

### AI Agents — goal-driven, tool-using assistants
**What they do:** Break goals into steps, call tools (web, code, spreadsheets, APIs), check results, and continue until done.
**Example:** “Plan a 2-day Kinshasa workshop, draft slides, and email a checklist.” The agent searches venues, generates outlines, and composes emails (with human approval).
**Caution:** Great for workflow automation but still needs oversight (guardrails, budgets, and review).

---

### Using AI: “Super Google” vs. “Operating System”
**Super Google (answer engine):** Ask questions, get synthesized, cited answers (chat + search hybrid). Great for research and explanations. (Try Perplexity/Copilot.)
**Operating System (copilot layer):** AI embedded everywhere—docs, slides, IDEs, browsers—drafting, checking, summarizing, automating. Think of AI as a universal helper app that sits atop your tools.

---

### Exponential progress — why it feels shocking
**Intuition:** Capabilities compound: small monthly improvements stack fast. What seemed “impossible” last year becomes normal.
**Stadium analogy (forward-looking):** If water doubles every minute, you see a few puddles for a long time, then—suddenly—the stadium floods near the end. With tech, most of the impact arrives late and fast.
**How to cope:** Learn fundamentals, keep experimenting, and track updates rhythmically (e.g., monthly). Small, regular practice beats big, rare catch-ups.

---

### Ethics & safety — power with responsibility
**Disclosure:** Say when AI helped (“Drafted with AI”).
**Privacy:** Minimize or anonymize PII; don’t paste secrets into public tools.
**Legal:** Respect copyright, licenses, and local regulations.
**Bias & fairness:** Test outputs on diverse cases; avoid harmful stereotypes.
**Attribution:** When using sources or training on your data, cite/credit appropriately.
**Rule of thumb:** If it would embarrass you on a projector, don’t do it.

---

### Quick practice menu (do-it-now)
* **Pattern demo (Concept 1):** Load a photo and list 3 ways to represent it numerically (pixels, embeddings, edge maps).
* **ML in minutes (Concept 2):** Train a webcam classifier with Teachable Machine and test with different objects.
* **Prompt ladder (Concept 4):** Write a weak-looking prompt → improve it with Role/Audience/Task/Constraints → add examples → add a rubric.
* **RAG taste test (Concept 6):** Ask an AI about your own doc with and without retrieval; compare specificity and citations.
* **Safety check (Concept 10):** Take any generated output and run a quick ethics checklist: disclosure? privacy? rights? harmful bias?

---

### Handy tools from your quick reference
Text/chat (ChatGPT, Claude, Gemini, Copilot, Perplexity), image (DALL·E, Midjourney, OpenArt), music (Suno, Udio), video (Veo, Kling), 3D (Meshy, Zoo), and Teachable Machine for fast demos—all in your one-pager.
