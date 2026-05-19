# Agentic Security Related Work Hub

This repository is a lightweight reading hub for papers and technical material around agentic security, especially LLM-agent prompt injection, tool-use safety, privilege escalation, runtime enforcement, information-flow control, authorization, and capability-style defenses.

Each sub-folder is a focused sub-hub. The table below links to the folder, summarizes the article cluster it currently tracks, and records the latest known update.

| Folder | Folder summary | Last update |
|---|---|---|
| [stage-privilege-verification](./stage-privilege-verification/) | Related work for verified staged authorization in LLM-agent systems. This sub-hub collects prompt-injection threat papers, agent security benchmarks, memory/RAG poisoning work, action hijacking, prompt/model-level defenses, runtime policy enforcement, information-flow-control defenses, capability and authorization foundations, verified-system analogies, and recent agent privilege-escalation work. Its current center of gravity is provenance-aware authorization for staged agent execution: how low-integrity observations, retrieved content, memory, tool metadata, and model-generated plans can be prevented from laundering authority into unsafe tool calls. | 2026-05-19 |

## Current Contents

- [stage-privilege-verification/related-work-summary.md](./stage-privilege-verification/related-work-summary.md): a structured literature table for Verified Staged Authorization, including paper status, abstract-level takeaways, and why each work matters for the project.
- [related-work-summary-template.md](./related-work-summary-template.md): a reusable Markdown template for creating new sub-hub literature tables in the same format.

## Scope

The repository is intended for organized, shareable notes rather than a complete bibliography dump. A good sub-hub should usually include:

- a focused research question or system idea,
- a curated related-work table,
- links to primary paper pages or project pages,
- short notes about why each work matters,
- a shortlist of closest competitors or baselines.

For a new sub-hub, copy [related-work-summary-template.md](./related-work-summary-template.md) into the new folder as `related-work-summary.md`, then fill in the paper table and closest-competitor table.

## Update Convention

When adding a new sub-folder, add a row to the table with:

1. the folder link,
2. a short summary of the paper cluster,
3. the latest update date in `YYYY-MM-DD` format.
