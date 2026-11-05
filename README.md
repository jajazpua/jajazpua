# Building ChangeProof

Developer and owner of **ChangeProof** — a focused tool for reviewing compatibility changes in **MCP tool definitions** and **OpenAPI contracts**.

I build tools that help developers see what changed, identify potential breaking changes, and make integration decisions using inspectable evidence.

### ChangeProof

**[Website](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/)** · **[Explore the project](https://github.com/jajazpua/ChangeProof)** · **[Request a free compatibility pilot](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/#/pilot)**

- **MCP:** changes to `tools/list`, required inputs, schemas, types, enums, and metadata.
- **OpenAPI:** changes to paths, operations, request/response schemas, and referenced models.
- **Evidence:** structured findings, input hashes, and explicit uncertainty and validation limits.

### Public evidence

- **[UniFi OpenAPI case study](https://github.com/jajazpua/ChangeProof/blob/main/ChangeProof_UniFi_68_Validated_Pilot_Report.md)** — static review of supplied versioned specifications, with findings, hashes, and validation limits.
- **[Sample compatibility report](https://github.com/jajazpua/ChangeProof/blob/main/ChangeProof_Sample_Compatibility_Report.md)** — a clearly labelled synthetic MCP and OpenAPI example.

### Open-source contributions

- **[Apache ShenYu — MCP contract evolution regression fixtures (PR #8309)](https://github.com/apache/shenyu/pull/8309)** — submitted synthetic MCP `tools/list` snapshots, directional compatibility expectations, and focused JUnit regression tests for [issue #7935](https://github.com/apache/shenyu/issues/7935). The selected Maven test run passed **5 tests, 0 failures**. **Status: open for review, not merged** (November 2026); this is not an endorsement by Apache ShenYu or validation of runtime pinning.

**Current stage:** owner-supervised pilot. Reports are reviewed manually; static schema comparisons do not prove runtime behavior. A public unattended analysis API and production automated payments are not available.

### Work with me

Have two **public or sanitized** versions of an MCP or OpenAPI definition you want compared? **[Submit a focused free-pilot request](https://changeproof-agent-checks.russet-spark-1861.chatgpt.site/#/pilot)**.

No production access, private credentials, or payment information is needed for a free pilot. Please do not share secrets in public GitHub issues.
