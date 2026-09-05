# XBSTACK

**Reproducible AI engineering labs for real-world Agent, MCP, LangGraph, n8n, OpenAI and AI SDK problems.**

> **在高处看世界，在底层堆资产。**

XBSTACK turns real engineering failures into public, verifiable assets:

`real problem → minimal reproduction → version matrix → tested workaround → upstream issue → deep dive`

**[Problem Labs](https://github.com/xbstack/problem-labs)** · **[MCP & Agent Tools](https://www.xbstack.com/en/tools/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=tools_entry&ref=github)** · **[XBSTACK.com](https://www.xbstack.com/github/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=website_entry&ref=github)**

## Featured Problem Labs

| Problem | Repro / Lab | Upstream / Analysis |
| --- | --- | --- |
| MCP `StreamableHTTPClientTransport` stays pending after request-scoped SSE EOF/error | [mcp-streamable-http-sse-pending-repro](https://github.com/xbstack/mcp-streamable-http-sse-pending-repro) | [typescript-sdk#2739](https://github.com/modelcontextprotocol/typescript-sdk/issues/2739) · [analysis](https://www.xbstack.com/en/ai/mcp-streamable-http-sse-pending-timeout/?utm_source=github&utm_medium=referral&utm_campaign=mcp_streamable_http_sse_pending&utm_content=github_profile&ref=github) |
| LangGraph `Command(resume=dict)` can misclassify ordinary dictionaries as interrupt maps | [langgraph-command-resume-dict-misclassification-repro](https://github.com/xbstack/langgraph-command-resume-dict-misclassification-repro) | [langgraph#8693](https://github.com/langchain-ai/langgraph/issues/8693) · [tracker](https://www.xbstack.com/en/tools/mcp-radar/?utm_source=github&utm_medium=referral&utm_campaign=langgraph_resume_dict_8693&utm_content=github_profile&ref=github) |
| AI SDK `WorkflowAgent` signed approval: unsupported baseline → opt-in signed replay enforcement | [ai-sdk-workflowagent-signed-approval-repro](https://github.com/xbstack/ai-sdk-workflowagent-signed-approval-repro) | [vercel/ai#19964](https://github.com/vercel/ai/issues/19964) · [analysis](https://www.xbstack.com/en/ai/vercel-ai-sdk-7-migration-production/?utm_source=github&utm_medium=referral&utm_campaign=ai_sdk_workflowagent_approval&utm_content=github_profile&ref=github) |
| LangGraph async `aupdate_state` raises `Ambiguous update` where sync succeeds | [langgraph-aupdate-state-ambiguous-update-repro](https://github.com/xbstack/langgraph-aupdate-state-ambiguous-update-repro) | [langgraph#8714](https://github.com/langchain-ai/langgraph/issues/8714) · [analysis](https://www.xbstack.com/en/ai/langgraph-aupdate-state-ambiguous-update/?utm_source=github&utm_medium=referral&utm_campaign=langgraph_aupdate_state_ambiguous_update&utm_content=github_profile&ref=github) |
| Accepted LangGraph run can disappear before the first durable checkpoint; fresh recovery raises `EmptyInputError` | [langgraph-first-checkpoint-acceptance-ledger-repro](https://github.com/xbstack/langgraph-first-checkpoint-acceptance-ledger-repro) | [langgraph#8764](https://github.com/langchain-ai/langgraph/issues/8764) · [Problem Labs](https://www.xbstack.com/github/?utm_source=github&utm_medium=referral&utm_campaign=langgraph_first_checkpoint_acceptance_ledger&utm_content=github_profile&ref=github) |
| n8n Raw body + explicit JSON response returns stream internals | [n8n-http-request-raw-body-stream-repro](https://github.com/xbstack/n8n-http-request-raw-body-stream-repro) | [n8n#36402](https://github.com/n8n-io/n8n/issues/36402) · [analysis](https://www.xbstack.com/en/ai/n8n-http-request-raw-body-response-stream/?utm_source=github&utm_medium=referral&utm_campaign=n8n_http_raw_response_stream&utm_content=github_profile&ref=github) |
| OpenAI Agents SDK RunState approval/resume across processes and redelivery | [openai-agents-runstate-approval-resume-lab](https://github.com/xbstack/openai-agents-runstate-approval-resume-lab) | [analysis](https://www.xbstack.com/en/ai/openai-agents-sdk-runstate-approval-resume/?utm_source=github&utm_medium=referral&utm_campaign=openai_agents_runstate&utm_content=github_profile&ref=github) |

## Tools & Trackers

- **[MCP Inspector](https://www.xbstack.com/en/tools/mcp-inspector/?utm_source=github&utm_medium=referral&utm_campaign=mcp_inspector&utm_content=github_profile&ref=github)** — read-only MCP endpoint preflight and compatibility inspection.
- **[Agent Readiness Auditor](https://www.xbstack.com/en/tools/agent-readiness-auditor/?utm_source=github&utm_medium=referral&utm_campaign=agent_readiness_auditor&utm_content=github_profile&ref=github)** — website discovery/readiness checks for AI agents.
- **[MCP / Agent Compatibility Tracker](https://www.xbstack.com/en/tools/mcp-radar/?utm_source=github&utm_medium=referral&utm_campaign=compatibility_tracker&utm_content=github_profile&ref=github)** — issue/version observations across MCP, AI SDK, LangGraph and OpenAI Agents.
- **[Agent Security Auditor](https://www.xbstack.com/en/tools/agent-security-auditor/?utm_source=github&utm_medium=referral&utm_campaign=agent_security_auditor&utm_content=github_profile&ref=github)** — configuration-level review with secret redaction and least-privilege checks.

## What XBSTACK Covers

AI Agent engineering · MCP protocol · LangGraph production state · n8n workflows · OpenAI APIs / Agents SDK · Vercel AI SDK · reproducible debugging · evaluation · security · deployment

## Maintenance Rules

- Reproduction evidence is separated from inference and vendor claims.
- Workarounds remain labeled as workarounds until a fixed release is independently verified.
- Version matrices are rerun when candidate releases appear.
- GitHub Issue / Discussion replies include an XBSTACK link only when it directly helps solve the thread's problem.
- No generic promotional replies or unrelated backlinks.

**Browse all reproducible engineering assets → [XBSTACK Problem Labs](https://github.com/xbstack/problem-labs)**

## Latest from XBSTACK

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->
