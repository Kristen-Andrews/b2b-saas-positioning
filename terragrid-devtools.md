# Terragrid Positioning Canvas (Example)

**Fictional company. Illustrative only.**

**Last updated:** July 2026
**Owner:** CMO
**Status:** Locked

---

## 1. Category

**What game are you playing?**
- [x] Owned category

**Category name:** Platform Engineering Observability

**One-sentence category definition:**
Platform Engineering Observability is the way internal developer platform teams measure developer experience and platform reliability as a single system, because DX and SRE metrics are the same problem viewed from opposite ends.

---

## 2. ICP

**Firmographic profile:**
- Industry: Software, fintech, e-commerce with 100+ engineers
- Company size: 500 to 5,000 employees
- Geography: North America and EU
- GTM motion: Bottom-up adoption, VP Engineering or Head of Platform closes

**Champion buyer:**
- Title: Head of Platform Engineering, Director of Developer Experience
- Reports to: VP Engineering or CTO
- Team size: 6 to 30 platform engineers
- Scorecard: Deploy frequency, change failure rate, developer NPS, MTTR

**Economic buyer:**
- Title: VP Engineering or CTO
- Board exposure: Engineering efficiency is a board-level metric post-2024
- Fired for: Slow shipping velocity, high-profile outages

**Trigger event:**
Internal developer platform team hits 12+ engineers and can no longer answer "is the platform actually helping developers ship faster?" with data.

---

## 3. Primary alternative

**Their current workflow:**
Custom Grafana dashboards stitched together by a platform engineer as a side project, plus quarterly developer surveys run in Google Forms.

**Why it persists:**
Every platform team believes they can build observability better than they can buy it. The Grafana instance already exists. Nobody has budget for a meta-tool that observes the tools.

**What breaks first when they scale:**
The platform engineer who built the dashboards leaves. Nobody else understands the queries. The team spends 3 weeks reverse-engineering their own metrics before the next board update.

---

## 4. Unique attributes

| # | Attribute | Swap test |
|---|-----------|-----------|
| 1 | The only observability platform that unifies DORA metrics, SPACE metrics, and platform reliability in one view | Pass |
| 2 | Ships with 40+ pre-built dashboards specific to internal developer platforms, not generic infrastructure | Pass |
| 3 | Built by the former platform team at Stripe | Pass |
| 4 | Native integrations with Backstage, ArgoCD, and Buildkite on day one | Pass |
| 5 | No custom query language. Reads OpenTelemetry natively. | Pass |

---

## 5. Value proof

| Attribute | Proof point |
|-----------|-------------|
| 1 | Cardinal Data cut platform metrics reporting from 12 hours per week to 20 minutes |
| 2 | Average time-to-first-insight after install: 4 hours |
| 3 | Founding team includes 4 former Stripe platform engineers, 2 former Netflix SREs |
| 4 | Public integration docs at terragrid.dev/integrations |
| 5 | OpenTelemetry Collector distribution certified by CNCF |

---

## 6. Enemy

**The old way:**
Platform teams measure their own success with the same tools they use to monitor production infrastructure, which means they can't tell you whether the platform is working for developers.

**Why it's broken now:**
Post-2023, every board wants engineering efficiency metrics. Custom Grafana dashboards don't survive board scrutiny and can't be maintained by teams that turn over every 18 months.

**The cost of staying stuck:**
Platform teams get cut in cost-optimization cycles because they can't prove ROI in the language the CFO speaks.

**The new way:**
Platform Engineering Observability treats developer experience and platform reliability as one measurement problem, with dashboards built for the CFO's question, not the SRE's console.

---

## 7. Message map

**Headline:** Prove your platform is working.

**Subhead:** Terragrid is the observability platform built for internal developer platform teams, unifying developer experience and reliability in dashboards your CFO will actually read.

**Three pillars:**

| Pillar | Claim | Proof |
|--------|-------|-------|
| Purpose-built for platform teams | 40+ pre-built platform dashboards, not generic infra | Time-to-first-insight: 4 hours |
| Unified DX and reliability | DORA + SPACE + SRE metrics in one view | Cardinal Data cut reporting from 12 hrs/wk to 20 min |
| Built by platform practitioners | Founding team from Stripe and Netflix | Team page, engineering blog |

**Elevator pitch:**
Terragrid is Platform Engineering Observability. We built it for internal developer platform teams past 100 engineers, because every platform team we know is running reporting on a Grafana instance one engineer built as a side project, and it breaks the second that engineer leaves. We ship 40+ pre-built dashboards on day one that unify DORA, SPACE, and reliability metrics. Cardinal Data cut their platform reporting from 12 hours a week to 20 minutes. Want to see what your platform metrics would look like tomorrow morning?

**Boilerplate:**
Terragrid is the Platform Engineering Observability platform for internal developer platform teams at companies with 100+ engineers. Founded by former platform engineers from Stripe and Netflix, Terragrid unifies DORA, SPACE, and reliability metrics in a single view, with 40+ pre-built dashboards that install in hours.

---

## 8. Anti-positioning

**Not for:**
- Engineering teams under 100 engineers (no internal platform team yet)
- Companies without a designated Head of Platform or DX
- Application-level observability use cases (Datadog, Honeycomb, New Relic territory)

**Not doing:**
- APM. Ever.
- Log management at scale.
- On-call and incident response tooling.

**When we lose:**
Usually to "we'll build it ourselves in Grafana." That customer comes back in 18 months when the engineer leaves.
