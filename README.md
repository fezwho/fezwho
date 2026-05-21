
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/syne@5/700.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/plus-jakarta-sans@8/400.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/plus-jakarta-sans@8/500.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/dm-mono@5/400.min.css">

<h2 class="sr-only">Faizan — GitHub Profile README Preview</h2>

<style>
:root {
  --syne: 'Syne', var(--font-sans);
  --jakarta: 'Plus Jakarta Sans', var(--font-sans);
  --mono: 'DM Mono', var(--font-mono);
}
.rm-wrap {
  max-width: 660px;
  padding: 2rem 0 1rem;
  font-family: var(--jakarta);
  font-size: 15px;
  line-height: 1.75;
  color: var(--color-text-primary);
}
.rm-name {
  font-family: var(--syne);
  font-size: 42px;
  font-weight: 700;
  letter-spacing: -1.5px;
  line-height: 1;
  margin: 0 0 6px;
  color: var(--color-text-primary);
}
.rm-tagline {
  font-family: var(--mono);
  font-size: 13px;
  color: var(--color-text-secondary);
  margin: 0 0 2rem;
  letter-spacing: 0.01em;
}
.rm-tagline span {
  opacity: 0.45;
  margin: 0 6px;
}
.rm-section-label {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--color-text-tertiary);
  margin: 2rem 0 0.75rem;
  padding-bottom: 6px;
  border-bottom: 0.5px solid var(--color-border-tertiary);
}
.rm-hero {
  font-family: var(--syne);
  font-size: 20px;
  font-weight: 700;
  letter-spacing: -0.3px;
  margin: 0 0 6px;
  color: var(--color-text-primary);
}
.rm-hero em {
  font-style: normal;
  color: var(--color-text-secondary);
  font-weight: 700;
}
.rm-sub {
  font-size: 14px;
  color: var(--color-text-secondary);
  margin: 0 0 1.5rem;
}
.rm-list {
  list-style: none;
  padding: 0;
  margin: 0 0 0.5rem;
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.rm-list li {
  display: flex;
  align-items: baseline;
  gap: 10px;
  font-size: 14px;
  color: var(--color-text-secondary);
}
.rm-list li::before {
  content: '→';
  font-family: var(--mono);
  font-size: 12px;
  color: var(--color-text-tertiary);
  flex-shrink: 0;
}
.rm-list li strong {
  font-weight: 500;
  color: var(--color-text-primary);
}
.rm-chips {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin: 0;
}
.rm-chip {
  font-family: var(--mono);
  font-size: 12px;
  padding: 4px 10px;
  border-radius: 4px;
  background: var(--color-background-secondary);
  border: 0.5px solid var(--color-border-secondary);
  color: var(--color-text-secondary);
}
.rm-projects {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 10px;
  margin: 0;
}
.rm-project {
  padding: 14px 16px;
  border: 0.5px solid var(--color-border-tertiary);
  border-radius: var(--border-radius-lg);
  background: var(--color-background-primary);
}
.rm-project-title {
  font-family: var(--syne);
  font-size: 14px;
  font-weight: 700;
  color: var(--color-text-primary);
  margin: 0 0 4px;
}
.rm-project-desc {
  font-size: 12.5px;
  color: var(--color-text-secondary);
  margin: 0;
  line-height: 1.55;
}
.rm-origin {
  font-size: 14px;
  color: var(--color-text-secondary);
  margin: 0 0 1.5rem;
  line-height: 1.7;
}
.rm-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 1.5rem;
  margin-top: 0.5rem;
  border-top: 0.5px solid var(--color-border-tertiary);
}
.rm-footer-links {
  display: flex;
  gap: 16px;
}
.rm-footer-link {
  font-family: var(--mono);
  font-size: 12px;
  color: var(--color-text-secondary);
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 5px;
  cursor: pointer;
}
.rm-footer-link:hover {
  color: var(--color-text-primary);
}
.rm-footer-loc {
  font-family: var(--mono);
  font-size: 12px;
  color: var(--color-text-tertiary);
  display: flex;
  align-items: center;
  gap: 5px;
}
.rm-divider {
  height: 0.5px;
  background: var(--color-border-tertiary);
  margin: 0.25rem 0;
  border: none;
}
.rm-closing {
  font-size: 13.5px;
  font-style: italic;
  color: var(--color-text-tertiary);
  text-align: center;
  padding: 1.25rem 0 0;
  font-family: var(--jakarta);
}
</style>

<div class="rm-wrap">
  <p class="rm-name">Faizan</p>
  <p class="rm-tagline">React Dev <span>→</span> AI Engineer <span>→</span> Builder of Things That Think</p>

  <p class="rm-section-label">What I'm Building</p>
  <p class="rm-hero"><em>RAG Pipelines.</em> Voice Agents. Agentic Systems.</p>
  <p class="rm-sub">Breaking LLMs open to understand them — then shipping products with them.</p>

  <p class="rm-section-label">Current Focus</p>
  <ul class="rm-list">
    <li><strong>Production RAG</strong> — LangChain · ChromaDB · FastAPI · hybrid retrieval · reranking</li>
    <li><strong>Multi-provider AI</strong> — fan-out LLM architectures, parallel inference, cascading fallbacks</li>
    <li><strong>Voice AI agents</strong> — Twilio · LiveKit · OpenAI Realtime API</li>
    <li><strong>LLM fine-tuning</strong> — LoRA / QLoRA on Mistral, LLaMA, Gemma, Phi</li>
    <li><strong>AI Browser Automation</strong> — LLaMA 3.3 70B · Playwright · Docker</li>
  </ul>

  <p class="rm-section-label">Stack I Reach For</p>
  <div class="rm-chips">
    <span class="rm-chip">Python</span>
    <span class="rm-chip">FastAPI</span>
    <span class="rm-chip">LangChain</span>
    <span class="rm-chip">LlamaIndex</span>
    <span class="rm-chip">React</span>
    <span class="rm-chip">Next.js</span>
    <span class="rm-chip">ChromaDB</span>
    <span class="rm-chip">pgvector</span>
    <span class="rm-chip">Docker</span>
    <span class="rm-chip">Ollama</span>
  </div>

  <p class="rm-section-label">A Few Things I've Shipped</p>
  <div class="rm-projects">
    <div class="rm-project">
      <p class="rm-project-title">🧠 Mega Mind</p>
      <p class="rm-project-desc">RAG app with custom pipeline builder, observability dashboard, and quality metrics</p>
    </div>
    <div class="rm-project">
      <p class="rm-project-title">🎙 Voice Support Agent</p>
      <p class="rm-project-desc">Real-time voice AI using Twilio + LiveKit + OpenAI Realtime API</p>
    </div>
    <div class="rm-project">
      <p class="rm-project-title">🤖 AI Browser Bot</p>
      <p class="rm-project-desc">Autonomous web agent powered by LLaMA 3.3 70B + Playwright</p>
    </div>
    <div class="rm-project">
      <p class="rm-project-title">🏫 School AI Assistant</p>
      <p class="rm-project-desc">Multi-provider RAG (OpenAI / Gemini / HuggingFace) with Next.js voice UI</p>
    </div>
  </div>

  <p class="rm-section-label">Background</p>
  <p class="rm-origin">CS grad from University of Central Punjab. Started writing React. Got curious about the models behind the interfaces. Haven't looked back.</p>

  <div class="rm-footer">
    <div class="rm-footer-links">
      <span class="rm-footer-link" onclick="openLink('https://fezwho.github.io')">
        <i class="ti ti-world" aria-hidden="true"></i> fezwho.github.io
      </span>
      <span class="rm-footer-link" onclick="openLink('https://github.com/fezwho')">
        <i class="ti ti-brand-github" aria-hidden="true"></i> fezwho
      </span>
    </div>
    <span class="rm-footer-loc">
      <i class="ti ti-map-pin" aria-hidden="true"></i> Lahore, Pakistan
    </span>
  </div>

  <p class="rm-closing">I like systems. I like understanding why things work. Then making them work better.</p>
</div>
