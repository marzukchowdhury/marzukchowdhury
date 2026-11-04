# Hi, I'm Marzuk 👋

Applied AI engineer in Coquitlam, BC, Canada. I build LLM products where the model proposes and deterministic code decides.

Before engineering, I spent 8+ years running finance operations, leading a team that processed close to 4,000 invoices a month. That background shapes how I build: accuracy first, every number traceable.

## Featured project: WriteHumanly

**[write-humanly.com](https://www.write-humanly.com)** is a live, paid SaaS I built alone in 2026. It rewrites AI-generated drafts so they read naturally, without changing the facts.

The AI part of the system is public here: **[writehumanly-ai](https://github.com/marzukchowdhury/writehumanly-ai)**

- **Fact-integrity gate:** deterministic checks reject any output that changes numbers, dates, names or amounts.
- **Verify-and-repair loop:** generate candidates across several models, score them, repair only the flagged sentences, and fall back to a verified result on any failure.
- **Evaluation first:** found the in-house scorer agreed with ground truth only 47-61% of the time, then moved release decisions to ground-truth evals backed by 290+ tests.
- **Fine-tuning:** QLoRA on Qwen3-4B-Base on a single 8 GB GPU cut the detector AI-score from 65.6% to 20.6% (11.1% with best-of-4 sampling).
- **Cost:** found one vendor was 94-97% of serving cost and restructured the pipeline around a single verification call.

## Tools I use

TypeScript · Node.js · Python · Next.js · Convex · Stripe · REST APIs and webhooks · Vitest · PyTorch · Hugging Face (PEFT, TRL) · OpenAI, Gemini and open models · Claude Code daily

## Get in touch

- Email: marzukchowdhury23@gmail.com
- LinkedIn: [marzuk-chowdhury-741a951b7](https://www.linkedin.com/in/marzuk-chowdhury-741a951b7)
- Open to applied AI, technical support and finance-systems roles in Canada (open work permit, no sponsorship needed)
