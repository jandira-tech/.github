# Jandira Tech

The engineering vehicle behind **[Arthur Souza Rodrigues](https://github.com/arthrod)** — a lawyer who ships code.

We build the tooling under legal work — NER models, document pipelines, contract evals, redlining services — instead of describing it in a memo.

Based in **New York** and **São Paulo**. Building **[Cicero](https://arthur.law)** — a legal workbench that turns messy inputs (email threads, third-party paper, drafts, quick requests) into structured outputs.

---

## What we work on

- **GLiNER for legal NER** — training, fine-tuning, ONNX export, Rust inference, benchmarking. End-to-end pipeline from FlashDeBERTa-based architectures down to runtime.
- **PII detection & synthesis for pt-BR** — Brazilian Portuguese is under-served in privacy tooling; we build both detectors and realistic synthetic generators.
- **Contract extraction & redlining** — clause extraction, docx round-trips, HTML↔DOCX conversion, diff-aware n8n nodes.
- **SEC / EDGAR data infrastructure** — bulk pullers, parsers, doc-to-dict utilities.
- **Legal-AI evaluation** — benchmark of contract-drafting AI vs. human lawyers (450 outputs, 72 surveyed lawyers).

## Stack we reach for

`PyTorch` · `Transformers` · `ONNX` · `Rust` (inference) · `FastAPI` · `pydantic-ai` · `TypeScript` · `Astro` · `Cloudflare Workers` · `pt-BR NLP` · `docx / OOXML internals`

---

## Featured projects

### GLiNER ecosystem
- **[gliner-onnx-benchmark](https://github.com/arthrod/gliner-onnx-benchmark)** — benchmarks across ONNX runtimes
- **[gliner-training-utils](https://github.com/arthrod/gliner-training-utils)** — training tooling
- **[gliner2_finetune](https://github.com/arthrod/gliner2_finetune)** — fine-tuning recipes
- **[ptbr_gliner_showcase](https://github.com/arthrod/ptbr_gliner_showcase)** — pt-BR demos
- **[gliner-looong](https://github.com/arthrod/gliner-looong)** — long-context experiments

### Legal / SEC / PII
- **[clause-extract](https://github.com/arthrod/clause-extract)** — clause-level extraction
- **[sec-edgar-bulker](https://github.com/arthrod/sec-edgar-bulker)** — SEC EDGAR bulk fetching
- **[sec-parser-2](https://github.com/arthrod/sec-parser-2)** · **[secdoctodict](https://github.com/arthrod/secdoctodict)** — parsing & structuring
- **[amd_pii_generator](https://github.com/arthrod/amd_pii_generator)** · **[pii_showcase](https://github.com/arthrod/pii_showcase)** — pt-BR PII synthesis & detection
- **[planalto_dot2dict](https://github.com/arthrod/planalto_dot2dict)** — Brazilian gov data utilities
- **[contractrec](https://github.com/arthrod/contractrec)** · **[contract_translator](https://github.com/arthrod/contract_translator)** — contract tooling
- **[Legal-Eaze](https://github.com/arthrod/Legal-Eaze)** · **[Tourcicero](https://github.com/arthrod/Tourcicero)**
- **[tabajara-stemmer](https://github.com/arthrod/tabajara-stemmer)** — classic pt-BR stemmer

### Docx & document conversion
- **[html-to-docx](https://github.com/arthrod/html-to-docx)** · **[html-to-docx2](https://github.com/arthrod/html-to-docx2)**
- **[docx-validate](https://github.com/jandira-tech/docx-validate)** — DOCX validation
- **[n8n-nodes-docx-diff](https://github.com/arthrod/n8n-nodes-docx-diff)** — diff nodes for n8n
- **[redline-endpoint](https://github.com/arthrod/redline-endpoint)** — redlining as a service

### Dev tooling
- **[claude-code-system-prompts](https://github.com/arthrod/claude-code-system-prompts)**
- **[ai-pr-reviewer](https://github.com/arthrod/ai-pr-reviewer)**
- **[modal-for-noobs](https://github.com/arthrod/modal-for-noobs)** — Modal helpers

### Practice management
- **[app-gestao-advocacia](https://github.com/arthrod/app-gestao-advocacia)** — law-firm ops app

---

## Beyond code

12+ years in BigLaw and in-house. Cross-border US/Brazil practice — contracts, governance, privacy (LGPD), compliance, AI adoption, legal operations. Trilingual: English · Português · Español.

---

## Find us

[arthur.law](https://arthur.law) · [LinkedIn](https://linkedin.com/in/arthrod) · [Hugging Face](https://huggingface.co/arthrod) · `contact@arthur.law`
