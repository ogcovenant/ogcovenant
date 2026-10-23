<h1 align="center">Covenant Ogowale</h1>

<p align="center">
  <a href="https://x.com/ogowalec"><img src="https://img.shields.io/badge/@ogowalec-000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://github.com/ogcovenant"><img src="https://img.shields.io/badge/ogcovenant-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://huggingface.co/justcovenant"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <img src="https://img.shields.io/badge/Remote-Worldwide-000?style=flat-square" alt="Remote, worldwide" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1000&color=00C2A8&center=true&vCenter=true&width=580&lines=Building+what+comes+next.;Software+engineer.+Product+builder.;Engineering+fintech+and+payments.;AI+engineer.+From+models+to+products.;Building+across+chains+and+systems.;From+idea+to+production." alt="Building what comes next: software engineering, fintech, AI, and multichain systems" />
</p>

---

### `whoami`

```ts
const covenant = {
  role: ["Software Engineer", "Product Engineer"],
  focus: ["fintech & payment systems", "onchain infrastructure", "applied AI"],
  chains: ["Solana", "Base", "Ethereum L2s"],
  languages: ["TypeScript", "Go", "Python", "Rust", "Solidity"],
  ai: ["LLM fine-tuning", "RAG", "context engineering", "model deployment"],
  philosophy: "the right tool and chain for the problem",
};
```

I build production systems end to end, with experience spanning **fintech and payments, backend infrastructure, multichain applications, and applied AI**. My work ranges from transaction and ledger workflows to cross-chain asset management, LLM fine-tuning, retrieval pipelines, and model deployment. I care about correctness, reliability, and choosing the right technology for the problem.

---

### 💳 Fintech & payments engineering

I've worked on **financial systems where correctness matters as much as shipping**: wallet balances, transaction flows, ledger accounting, and the integrations that move value between services and networks.

**Areas I've worked on:**

- **Ledgers and wallet accounting:** Debit/credit flows, wallet balance integrity, transaction records, and corrective ledger entries. I've debugged a production payment issue caused by reversed debit/credit semantics in coupled code, rolled back the change, audited transactions within the incident window, and corrected balances with **new ledger entries rather than rewriting history**.
- **Payments and integrations:** Backend payment flows, provider integrations, transaction state management, webhook processing, and reconciliation concerns, with attention to idempotency and failure recovery.
- **Onchain financial infrastructure:** Cross-chain asset management involving **LayerZero and LI.FI**, working across Solana and EVM ecosystems and integrating DeFi primitives into application workflows.
- **Wallet and account architecture:** Designing flows that connect user accounts, custodial or provider-managed wallets, fiat payment rails, and onchain settlement while keeping blockchain complexity out of the user experience.

I approach payments as a **systems-engineering problem**, not just an API integration: money movement needs auditable state transitions, predictable failure handling, and a ledger that can be trusted.

---

### 🤖 AI engineering

I work across the AI engineering workflow: **dataset preparation, supervised fine-tuning, evaluation, retrieval, inference deployment, and product integration**.

**Selected work:**

- **Gemma 3 4B (E2B) fine-tuning:** Successfully fine-tuned the model after **38 failed attempts**, using AWS SageMaker, Unsloth, and LoRA adapters. Prepared a custom **203k-row reasoning dataset** ([`justcovenant/rag-reasoning-sft`](https://huggingface.co/datasets/justcovenant/rag-reasoning-sft)) covering four reasoning types, including chain-of-thought examples with `<thinking>` tags.
- **Model serving:** Deployed a fine-tuned Llama model to an **AWS SageMaker real-time endpoint**, using inference components and scale-to-zero autoscaling.
- **Retrieval and product AI:** Built RAG pipelines with embeddings, ChromaDB, hybrid retrieval, and reranking, alongside structured outputs, tool-using agents, and LLM-powered application flows.

| Area | Tools and techniques |
| --- | --- |
| **Fine-tuning** | SFT, LoRA, Unsloth, SageMaker, custom dataset curation |
| **RAG** | OpenAI embeddings, ChromaDB, hybrid retrieval, reranking |
| **Context engineering** | Prompt design, tool-use agents, structured outputs, evaluation loops |
| **Deployment** | SageMaker endpoints, inference components, autoscaling, scale-to-zero |
| **Product AI** | OpenAI and Claude integrations, agent workflows, retrieval-augmented apps |

---

### ⚙️ Engineering stack

Rather than a wall of badges, here's how I group the tools I use:

| Domain | Stack |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Go, Python, Rust, Solidity |
| **Backend & frontend** | Node.js, NestJS, Next.js, React, Tailwind CSS |
| **Data & financial systems** | PostgreSQL, Prisma, Redis, transaction ledgers, reconciliation |
| **Infrastructure** | Docker, Kubernetes, AWS, Terraform |
| **Web3** | Solana, Base, Ethereum L2s, Anchor, Foundry, Hardhat |
| **AI/ML** | PyTorch, Hugging Face, Unsloth, SageMaker, LangChain, ChromaDB |

---

### ⛓ Multichain by design

I build across **Solana and EVM networks**, without treating any one chain as the default answer to every problem. For me, blockchain is an infrastructure decision: the product's requirements come first, then the network, execution model, and integrations.

That means weighing **cost, confirmation times, security assumptions, developer tooling, and liquidity** before choosing where a transaction should run. Sometimes the right approach is to stay on one chain. Other times, users need to move assets or interact with applications across networks without dealing with the complexity themselves.

| Ecosystem | Where it fits into my work |
| --- | --- |
| **Solana** | Low-cost, fast-moving transaction flows, SPL tokens, and programs built with Anchor |
| **Base & Ethereum L2s** | EVM smart contracts, wallet integrations, and applications built around existing DeFi protocols |
| **Cross-chain** | Connecting liquidity and user flows across networks using messaging and routing infrastructure such as **LayerZero and LI.FI** |

I've worked on **cross-chain asset management** and the application layer around it: smart contract interactions, wallet connectivity, token standards, and transaction routing. The goal is to make the underlying chain a deliberate architectural choice, not an extra decision the user has to make.

**Tooling:** Anchor, Solana Web3.js, SPL tokens, Solidity, viem, ethers, wagmi, RainbowKit, Privy, Foundry, Hardhat, ERC-20/721/1155, and account abstraction.

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ogcovenant&show_icons=true&theme=transparent&hide_border=true&title_color=00C2A8&icon_color=00C2A8&text_color=8B949E" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ogcovenant&layout=compact&theme=transparent&hide_border=true&title_color=00C2A8&text_color=8B949E&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ogcovenant&theme=transparent&hide_border=true&ring=00C2A8&fire=00C2A8&currStreakLabel=00C2A8" alt="GitHub contribution streak" />
</p>

---

<p align="center">
  <i>Open to founding engineer roles, technical collaborations, and hard problems in fintech, infrastructure, and applied AI.</i>
</p>
