# aurora-routing-agent

AI agent that computes optimal delivery routes and dispatch decisions for
**Aurora Logistics** (fictitious company used as a Backstage reference
example). Speaks the [Agent2Agent (A2A) protocol](https://a2a-protocol.org/)
and calls internal systems through `aurora-mcp-gateway`.

Mockup only — no real agent runtime, just an Agent Card and
`catalog-info.yaml` to demonstrate Backstage cataloging an AI agent.

- Owner: `team-ai-agents`
- System: `fleet-tracking`
- Agent Card: [`.well-known/agent.json`](./.well-known/agent.json)
