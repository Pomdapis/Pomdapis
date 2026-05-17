<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  HEADER                                                              -->
<!-- ──────────────────────────────────────────────────────────────────── -->

<a name="top"></a>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=200&section=header&text=Sacha%20Hennaut&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Fractional%20CTO%20%C2%B7%20Platform%20Builder%20%C2%B7%20Remote&descSize=18&descAlignY=60&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=B388FF&center=true&vCenter=true&width=720&lines=I+architect+event-sourced+platforms.;I+ship+agent+factories.;I+plug+in+as+your+CTO%2C+part-time%2C+full+focus.;Currently+taking+new+clients+%E2%80%94+full+remote." alt="typing animation" />
  </a>
</p>

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  STATUS / CTAs                                                       -->
<!-- ──────────────────────────────────────────────────────────────────── -->

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-AVAILABLE-39FF14?style=for-the-badge&labelColor=0d1117" alt="status: available" />
  <img src="https://img.shields.io/badge/MODE-FULL%20REMOTE-00E5FF?style=for-the-badge&labelColor=0d1117" alt="mode: full remote" />
  <img src="https://img.shields.io/badge/ROLE-FRACTIONAL%20CTO-B388FF?style=for-the-badge&labelColor=0d1117" alt="role: fractional CTO" />
</p>

<p align="center">
  <a href="https://calendly.com/pomdapis/30min">
    <img src="https://img.shields.io/badge/%E2%86%92%20Book%20a%2030min%20intro-0d1117?style=for-the-badge&logo=googlecalendar&logoColor=B388FF&labelColor=0d1117&color=B388FF" alt="Book a call" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/sacha-hennaut-dev/">
    <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00E5FF&labelColor=0d1117&color=00E5FF" alt="LinkedIn" />
  </a>
</p>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  WHO                                                                 -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ who</samp>

```ts
const sacha = {
  role:     "fractional CTO + hands-on builder",
  timezone: "GMT+1 · works fully remote",
  focus:    ["multi-tenant platforms", "event sourcing", "AI agents"],
  stack:    [".NET 10", "TypeScript", "Next.js", "Kubernetes", "PostgreSQL"],
  shipping: ["Sassy Solutions", "Nexus", "Compendium"],
  loves:    ["clean ports & adapters", "boring tech under wild ideas", "shipping"],
};
```

I split my time between **building my own platform** (Sassy Solutions / Nexus / Compendium) and **plugging into client teams as their CTO** — usually 1 to 3 days a week, fully remote. I pick up architecture, hire technical talent, unblock delivery, and ship code alongside the team. No theatre, no slide decks, just a senior engineer with skin in the game.

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  FEATURED                                                            -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ what i'm building</samp>

<table>
<tr>
<td width="33%" valign="top">

### <a href="https://github.com/sassy-solutions"><img src="https://img.shields.io/badge/-AGENCY-B388FF?style=flat-square&labelColor=0d1117" /></a> [Sassy Solutions](https://github.com/sassy-solutions)

> An **agent-building agency.** We design, build, and ship custom AI agents on a multi-tenant platform we own end-to-end.

— Hexagonal .NET core
— RAG + tool-calling out of the box
— White-label deploys
— Marketplace of skills & templates

`agents-as-a-service`

</td>
<td width="33%" valign="top">

### <img src="https://img.shields.io/badge/-PLATFORM-00E5FF?style=flat-square&labelColor=0d1117" /> Nexus

> The **multi-tenant platform** behind Sassy Solutions. Event-sourced, schema-isolated, Kubernetes-native.

— Per-tenant Zitadel + Postgres schema
— Auto-provision in seconds (org → identity → DB → namespace → ingress)
— Ships with SDK + MCP server + admin UI
— Deploy-from-template pipeline

`.NET 10 · CQRS/ES · K8s · private`

</td>
<td width="33%" valign="top">

### <a href="https://github.com/sassy-solutions/compendium"><img src="https://img.shields.io/badge/-FRAMEWORK-39FF14?style=flat-square&labelColor=0d1117" /></a> [Compendium](https://github.com/sassy-solutions/compendium)

> The **event-sourcing framework** underneath Nexus. Open primitives for aggregates, projections, multi-tenancy, and outboxes.

— Zero-dependency core
— Multi-tenancy as a first-class concern
— Result pattern, no exceptions for control flow
— Published as NuGet

<a href="https://github.com/sassy-solutions/compendium"><img src="https://img.shields.io/github/stars/sassy-solutions/compendium?style=flat-square&logo=github&labelColor=0d1117&color=39FF14" alt="stars" /></a>

</td>
</tr>
</table>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  OPEN ECOSYSTEM                                                      -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ open ecosystem</samp>

Compendium isn't a monolith — it ships as a **tiny core + a growing constellation of adapters**, so you only depend on what you actually wire in. Everything below is MIT-licensed, .NET 10, and built to the same conventions ([adapter template](https://github.com/sassy-solutions/template-compendium-adapter-dotnet)).

<table>
<tr>
<td valign="top" width="50%">

<h3>🧠 AI providers</h3>

<a href="https://github.com/sassy-solutions/compendium-adapter-anthropic"><img src="https://img.shields.io/badge/Anthropic-0d1117?style=for-the-badge&logo=anthropic&logoColor=D97757" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-openai"><img src="https://img.shields.io/badge/OpenAI-0d1117?style=for-the-badge&logo=openai&logoColor=00E5FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-gemini"><img src="https://img.shields.io/badge/Gemini-0d1117?style=for-the-badge&logo=googlegemini&logoColor=B388FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-openrouter"><img src="https://img.shields.io/badge/OpenRouter-0d1117?style=for-the-badge&logoColor=B388FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-ollama"><img src="https://img.shields.io/badge/Ollama-0d1117?style=for-the-badge&logo=ollama&logoColor=ffffff" /></a>

<sub>Chat, embeddings, tool-calling, streaming. Swap providers without touching domain code.</sub>

</td>
<td valign="top" width="50%">

<h3>🔎 Vector & search</h3>

<a href="https://github.com/sassy-solutions/compendium-adapter-pgvector"><img src="https://img.shields.io/badge/pgvector-0d1117?style=for-the-badge&logo=postgresql&logoColor=00E5FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-qdrant"><img src="https://img.shields.io/badge/Qdrant-0d1117?style=for-the-badge&logoColor=B388FF" /></a>

<sub>Postgres-native or cloud — same `IVectorStore` port. RAG without ceremony.</sub>

</td>
</tr>
<tr>
<td valign="top" width="50%">

<h3>🗄️ Infrastructure</h3>

<a href="https://github.com/sassy-solutions/compendium-adapter-postgresql"><img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00E5FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-redis"><img src="https://img.shields.io/badge/Redis-0d1117?style=for-the-badge&logo=redis&logoColor=DC382D" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-s3"><img src="https://img.shields.io/badge/S3%20%E2%80%93%20R2%20%E2%80%93%20MinIO-0d1117?style=for-the-badge&logo=amazons3&logoColor=39FF14" /></a>

<sub>JSONB event store · idempotency + projection checkpoints · S3-compatible object storage.</sub>

</td>
<td valign="top" width="50%">

<h3>💸 SaaS plumbing</h3>

<a href="https://github.com/sassy-solutions/compendium-adapter-stripe"><img src="https://img.shields.io/badge/Stripe-0d1117?style=for-the-badge&logo=stripe&logoColor=B388FF" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-lemonsqueezy"><img src="https://img.shields.io/badge/LemonSqueezy-0d1117?style=for-the-badge&logoColor=FFCE00" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-zitadel"><img src="https://img.shields.io/badge/Zitadel-0d1117?style=for-the-badge&logo=zitadel&logoColor=FF5A00" /></a>
<a href="https://github.com/sassy-solutions/compendium-adapter-listmonk"><img src="https://img.shields.io/badge/Listmonk-0d1117?style=for-the-badge&logoColor=39FF14" /></a>

<sub>Billing · identity · transactional email — the boring-but-load-bearing stuff, wired up once.</sub>

</td>
</tr>
</table>

<br />

<details>
<summary><b>⚡ Also brewing →</b> <code>stream-ui</code> · form-first LLM streaming for React & React Native</summary>
<br />

[**`sassy-solutions/stream-ui`**](https://github.com/sassy-solutions/stream-ui) — Type-safe streaming + parsing of structured LLM output, AG-UI + A2UI native, zero runtime deps. Built for the agent UIs we ship at Sassy.

</details>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  HIRE ME                                                             -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ work with me</samp>

I'm a good fit if you're a **founder, CTO, or scale-up team** who needs one of these:

| | |
|--|--|
| 🧭 | **Architecture you can grow into** — multi-tenant from day one, without over-engineering. |
| ⚙️ | **A platform spine** — event sourcing, CQRS, auth, provisioning, observability, wired right. |
| 🤖 | **Agents that actually ship** — not demos. Owned data, owned infra, owned roadmap. |
| 🚀 | **Delivery acceleration** — pair with your team, unblock, ship, hand back cleaner than I found it. |

<p align="left">
  <a href="https://calendly.com/pomdapis/30min">
    <img src="https://img.shields.io/badge/%E2%86%92%20Grab%2030%20min-B388FF?style=for-the-badge&labelColor=0d1117" alt="Grab 30 min" />
  </a>
</p>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  STACK                                                               -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ stack</samp>

<table>
<tr>
<td valign="top" width="33%">

**backend**
<br /><br />
<img src="https://img.shields.io/badge/.NET%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Event%20Sourcing-B388FF?style=flat-square" />
<img src="https://img.shields.io/badge/CQRS-B388FF?style=flat-square" />

</td>
<td valign="top" width="33%">

**frontend**
<br /><br />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white" />

</td>
<td valign="top" width="33%">

**platform & ai**
<br /><br />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Zitadel-FF5A00?style=flat-square&logo=zitadel&logoColor=white" />
<img src="https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square" />

</td>
</tr>
</table>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  STATS                                                               -->
<!-- ──────────────────────────────────────────────────────────────────── -->

## <samp>◆ in the wild</samp>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Pomdapis&show_icons=true&hide_border=true&bg_color=0d1117&title_color=B388FF&icon_color=00E5FF&text_color=c9d1d9&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=Pomdapis&hide_border=true&background=0d1117&stroke=0d1117&ring=B388FF&fire=00E5FF&currStreakLabel=B388FF&currStreakNum=ffffff&sideNums=ffffff&sideLabels=c9d1d9&dates=8b949e" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pomdapis&bg_color=0d1117&color=c9d1d9&line=B388FF&point=00E5FF&area=true&hide_border=true" />
</p>

<br />

<!-- ──────────────────────────────────────────────────────────────────── -->
<!--  FOOTER                                                              -->
<!-- ──────────────────────────────────────────────────────────────────── -->

<p align="center">
  <a href="https://calendly.com/pomdapis/30min"><img src="https://img.shields.io/badge/Let's%20talk-B388FF?style=for-the-badge&labelColor=0d1117" /></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/sacha-hennaut-dev/"><img src="https://img.shields.io/badge/Connect-00E5FF?style=for-the-badge&labelColor=0d1117" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=120&section=footer&animation=fadeIn" alt="footer" />
</p>
