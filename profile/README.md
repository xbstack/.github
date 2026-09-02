# XBSTACK

**Independent AI engineering lab for reproducible Agent, LangGraph, n8n, MCP, OpenAI and AI SDK problems.**

> 在高处看世界，在底层堆资产。

## Start with a problem

### LangGraph
- [`aupdate_state` → `InvalidUpdateError: Ambiguous update`](https://github.com/xbstack/langgraph-aupdate-state-ambiguous-update-repro) · [full analysis](https://www.xbstack.com/en/ai/langgraph-aupdate-state-ambiguous-update/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=langgraph_aupdate_state)
- [`Command(resume=dict)` can misclassify ordinary dictionaries as interrupt maps](https://github.com/xbstack/langgraph-command-resume-dict-misclassification-repro) · [upstream #8693](https://github.com/langchain-ai/langgraph/issues/8693)
- [ToolNode async `max_concurrency` ignored](https://github.com/xbstack/langgraph-toolnode-max-concurrency-repro) · [full analysis](https://www.xbstack.com/en/ai/langgraph-toolnode-max-concurrency-ignored/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=langgraph_concurrency)
- [SQLite failed batch partially commits state](https://github.com/xbstack/langgraph-sqlite-partial-commit-repro) · [full analysis](https://www.xbstack.com/en/ai/langgraph-checkpointer-memory-sqlite-redis/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=langgraph_sqlite)

### n8n
- [2.35.3 `$json` mutating Array methods return `null`](https://github.com/xbstack/n8n-2353-json-array-null-repro) · [full analysis](https://www.xbstack.com/en/ai/n8n-2353-json-array-methods-return-null/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=n8n_array_null)
- [HTTP Request Raw body returns stream internals](https://github.com/xbstack/n8n-http-request-raw-body-stream-repro) · [full analysis](https://www.xbstack.com/en/ai/n8n-http-request-raw-body-response-stream/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=n8n_raw_stream)
- [ARM64 distroless `GLIBC_PRIVATE` failure](https://github.com/xbstack/n8n-distroless-arm64-glibc-repro) · [full analysis](https://www.xbstack.com/en/ai/n8n-distroless-arm64-glibc-error/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=n8n_arm64_glibc)

### OpenAI
- [Responses API stream abort / `No tool call found`](https://github.com/xbstack/openai-responses-stream-abort-tool-call-loss) · [full analysis](https://www.xbstack.com/en/ai/openai-responses-api-stream-abort-tool-call-lost/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=openai_stream_abort)
- [Agents SDK RunState approval/resume lab](https://github.com/xbstack/openai-agents-runstate-approval-resume-lab) · [full analysis](https://www.xbstack.com/en/ai/openai-agents-sdk-runstate-approval-resume/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=openai_runstate)

### MCP and AI SDK
- [`StreamableHTTPClientTransport` SSE disconnect leaves POST pending until timeout](https://github.com/xbstack/mcp-streamable-http-sse-pending-repro) · [upstream #2739](https://github.com/modelcontextprotocol/typescript-sdk/issues/2739) · [full analysis](https://www.xbstack.com/en/ai/mcp-streamable-http-sse-pending-timeout/?utm_source=github&utm_medium=referral&utm_campaign=mcp_streamable_http_sse_pending&utm_content=github_profile)
- [`WorkflowAgent` signed tool-approval before/after fixture](https://github.com/xbstack/ai-sdk-workflowagent-signed-approval-repro) · [upstream #19964](https://github.com/vercel/ai/issues/19964)
- [MCP stdio / `-32700 Parse Error` diagnostics](https://github.com/xbstack/mcp-stdio-diagnostics) · [full analysis](https://www.xbstack.com/en/ai/mcp-json-rpc-parse-error/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=mcp_parse_error)
- [AI SDK 7 migration demo](https://github.com/xbstack/xbstack-ai-sdk-7-migration-demo) · [full analysis](https://www.xbstack.com/en/ai/vercel-ai-sdk-7-migration-production/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=ai_sdk_7)

## Problem Labs

**[Browse the XBSTACK Problem Labs index →](https://github.com/xbstack/problem-labs)**

Every lab aims to preserve this chain:

`real problem → minimal reproduction → version matrix → tested workaround → upstream thread → XBSTACK deep dive`

Website: https://www.xbstack.com/github/?utm_source=github&utm_medium=referral&utm_campaign=github_profile&utm_content=problem_labs

## Latest MCP & Web Agent Updates

- [MCP StreamableHTTPClientTransport POST Stays Pending After SSE Disconnect: Issue #2739 Reproduced](https://www.xbstack.com/en/ai/mcp-streamable-http-sse-pending-timeout/?utm_source=github&utm_medium=referral&utm_campaign=mcp_streamable_http_sse_pending&utm_content=profile_latest) (2026-09-01)
- [How to Configure llms.txt v2: alternate, describedby, and Markdown Discovery](https://www.xbstack.com/en/ai/llms-txt-v2-agent-readiness/?utm_source=github&utm_medium=referral&utm_campaign=llms_txt_v2&utm_content=latest_article&ref=github) (2026-08-31)
- [How to Add WebMCP to a Website: Chrome 149, Tool Schemas, and registerTool](https://www.xbstack.com/en/ai/webmcp-chrome-149-website-tools/?utm_source=github&utm_medium=referral&utm_campaign=webmcp_chrome149&utm_content=latest_article&ref=github) (2026-08-31)
- [How to Test an MCP Server Before Production: Read-Only Inspector Preflight](https://www.xbstack.com/en/ai/mcp-server-read-only-preflight-inspector/?utm_source=github&utm_medium=referral&utm_campaign=mcp_readonly_preflight&utm_content=latest_article&ref=github) (2026-08-31)
- [How to Security Check an MCP Configuration: Secrets, Shell, Remote MCP, and Permissions](https://www.xbstack.com/en/ai/mcp-config-secret-permission-security-audit/?utm_source=github&utm_medium=referral&utm_campaign=mcp_config_security&utm_content=latest_article&ref=github) (2026-08-31)

## MCP & Agent Tooling

- [Agent Readiness Auditor](https://www.xbstack.com/en/tools/agent-readiness-auditor/?utm_source=github&utm_medium=referral&utm_campaign=agent_readiness_auditor&utm_content=profile_tool&ref=github) — public website discovery/readiness checks.
- [MCP Inspector](https://www.xbstack.com/en/tools/mcp-inspector/?utm_source=github&utm_medium=referral&utm_campaign=mcp_inspector&utm_content=profile_tool&ref=github) — read-only MCP endpoint preflight and compatibility inspection.
- [MCP / Agent Compatibility Tracker](https://www.xbstack.com/en/tools/mcp-radar/?utm_source=github&utm_medium=referral&utm_campaign=compatibility_tracker&utm_content=profile_tool&ref=github) — live MCP server observations plus MCP, AI SDK, LangGraph and OpenAI Agents issue/version tracking.
- [Agent Security Auditor](https://www.xbstack.com/en/tools/agent-security-auditor/?utm_source=github&utm_medium=referral&utm_campaign=agent_security_auditor&utm_content=profile_tool&ref=github) — configuration-level security review with secret redaction and least-privilege checks.

## What XBSTACK builds

AI Agent engineering · MCP protocol · LangGraph production state · n8n workflows · OpenAI APIs/Agents SDK · AI SDK · reproducible debugging · evaluation · security · deployment
