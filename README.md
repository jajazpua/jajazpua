# ChangeProof Developer

### MCP & OpenAPI compatibility reviews for teams shipping API and AI-agent integrations

**Find potentially breaking contract changes before they become an integration problem.**

I build **[ChangeProof](https://github.com/jajazpua/ChangeProof)**, an owner-operated compatibility analysis service for API teams, AI-agent developers and MCP maintainers. We compare two public or sanitized contract revisions and deliver **reviewed, evidence-backed findings** with the scope and uncertainties stated clearly.

**[Request a paid review & quote](https://github.com/jajazpua/ChangeProof/issues/new?template=quote-request.yml)** · **[See a report preview](https://github.com/jajazpua/ChangeProof/blob/main/demo/README.md)** · [Request a focused free pilot](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/#/pilot)

> **Available now:** manually supervised MCP/OpenAPI contract reviews. Pricing, turnaround and deliverables are agreed before paid work. No automatic checkout or unattended hosted analysis API.

---

## What ChangeProof helps you decide

| Before a release or migration | What we inspect |
| --- | --- |
| **Will existing agents still call my MCP tool?** | Added/removed tools, newly required arguments, changes to input/output schemas, enums and metadata. |
| **Could this OpenAPI revision affect existing clients?** | Operations, required parameters, response/request shapes, referenced schemas and potential compatibility risks. |
| **Where should engineers test first?** | Before/after evidence, source locations, prioritized findings and targeted integration-test recommendations. |

**Typical deliverable:** a reviewed compatibility summary, traceable contract findings, relevant hashes where inputs are available and actionable verification steps. Structured JSON and an HTML report are available when supported and agreed for the engagement.

## See what the report looks like

[![Synthetic ChangeProof report preview](https://raw.githubusercontent.com/jajazpua/ChangeProof/main/docs/assets/compatibility-demo-preview.svg)](https://github.com/jajazpua/ChangeProof/blob/main/demo/README.md)

**[Explore the HTML demo](https://github.com/jajazpua/ChangeProof/blob/main/demo/README.md)** · [View public technical evidence](https://github.com/jajazpua/ChangeProof/blob/main/docs/PUBLIC_EVIDENCE.md)

*The preview uses synthetic MCP/OpenAPI fixtures. It illustrates report presentation, not a paying customer case, independent accuracy certification or a production runtime test.*

## Selected public work

- **[UniFi Network API compatibility review](https://github.com/jajazpua/ChangeProof/blob/main/ChangeProof_UniFi_68_Validated_Pilot_Report.md)** — static comparison of two published API contract versions and a documented migration risk; no confirmed runtime client failure.
- **[Apache ShenYu MCP regression contribution](https://github.com/apache/shenyu/pull/8309)** — synthetic schema evolution fixtures and focused tests submitted upstream; not presented as a merged production integration or endorsement.
- **[Denkeeper MCP synthetic case](https://github.com/jajazpua/ChangeProof/blob/main/pilots/denkeeper-583/README.md)** — independently checked offline fixture examining tool and annotation drift; not an actual Denkeeper runtime test.

## Work with ChangeProof

**For teams:** Request a **scoped paid review** when you have an upcoming migration, release or multiple contract changes to assess. Explain the decision you need to make and link public/sanitized BEFORE and AFTER specifications. We will agree the analysis scope, format, timing and price before any work.

**For a focused evaluation:** Start with a **limited free pilot** covering one clearly defined compatibility question, subject to suitability and capacity.

**[Get a scoped quote](https://github.com/jajazpua/ChangeProof/issues/new?template=quote-request.yml)** · [Request the free pilot](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/#/pilot) · [Visit the ChangeProof website](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/)

<sub>Contract findings are not proof of an actual production failure or a security vulnerability. Generated-SDK compile compatibility and live system behavior require separate tests. Do not post credentials, confidential specifications or personal information in public GitHub issues.</sub>
