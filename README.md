<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:FF3D9A,100:0B1119&height=180&section=header&text=Edgaze&fontSize=72&fontColor=EAF2F8&fontAlignY=34&desc=Edge%20Platforms,%20Inc.&descSize=14&descAlignY=54&animation=twinkling" width="100%" />

<strong>Infrastructure for publishing, running, and monetizing AI workflows.</strong>

<br><br>

[Website](https://edgaze.ai) · [REST API](https://api.edgaze.ai/v1/openapi) · [MCP server](https://github.com/edgaze-ai/mcp)

</div>

<br>

## About

Edgaze is a marketplace and execution platform for AI workflows. Creators publish reusable workflows with their implementation details protected. Buyers run them through the web app, REST API, or MCP server and pay per execution.

<br>

## Workflow lifecycle

```
  BUILD  ──▶  PUBLISH  ──▶  RUN  ──▶  PAY OUT
```

**01 · Build** Create a graph in Workflow Studio or draft one with Composer.

**02 · Publish** Set a margin and keep prompts, keys, and node logic private.

**03 · Run** Execute the workflow through the web app, REST API, or MCP server.

**04 · Pay out** Completed runs are recorded and creator earnings are paid through Stripe Connect.

<br>

## Product guarantees

| | |
|:--|:--|
| Guarantee | Detail |
|:--|:--|
| Failed runs are free | Buyers are not charged when the platform cannot deliver output. |
| Demo runs are free | Demos use the same quality as paid runs. |
| Creator IP stays sealed | Publishing does not expose workflow internals. |
| Creators keep 80% | Compute is billed separately as part of the buyer's price. |

<br>

## Developer access

Run workflows programmatically over HTTP or MCP.

```bash
# Full machine-readable specification
curl https://api.edgaze.ai/v1/openapi
```

The hosted MCP server supports OAuth, five tools, and one resource for compatible clients.

Manifests and setup: [`edgaze-ai/mcp`](https://github.com/edgaze-ai/mcp)

<br>

## Platform components

| Layer | What runs there |
|:--|:--|
| Component | Description |
|:--|:--|
| Execution | Durable DAG engine on self-hosted Temporal, resumable per node. |
| Studio | Visual graph authoring and natural-language workflow drafting. |
| Billing | Append-only ledgers for buyers, creators, and platform revenue. |
| Payouts | Stripe Connect with recipient onboarding in 90+ eligible countries. |
| Interfaces | Web app, REST API, MCP server, and embeddable run cards. |

<br>

## Repositories

| Repository | Description |
|:--|:--|
| [`mcp`](https://github.com/edgaze-ai/mcp) | Public MCP server manifests and client setup |

<br>

---

<div align="center">
<sub>Edge Platforms, Inc. · [Website](https://edgaze.ai) · [API documentation](https://api.edgaze.ai/v1/openapi)</sub>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1119,50:FF3D9A,100:00E5FF&height=100&section=footer&animation=twinkling" width="100%" />

</div>