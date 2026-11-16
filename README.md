<h1 align="center">Hi, I'm Idris 👋</h1>
<h3 align="center">Senior Full-Stack Engineer · Java/Spring Boot, Angular, Python · Payments & ML</h3>

<p align="center">
  10+ years building production systems for banking, payments and transaction processing.<br/>
  At Bank Mandiri I built Cakra, a sales app used by 12,000+ staff nationwide, and I'm now leading the design of a new Remittance & Payment System.<br/>
  Lately I also ship machine learning products end to end, and I contribute fixes to open-source projects.
</p>

<p align="center">
  <a href="https://idsoke.vercel.app"><b>Portfolio</b></a> ·
  <a href="https://idsoke.vercel.app/cv/">CV</a> ·
  <a href="https://www.linkedin.com/in/idris-id-9577bb56">LinkedIn</a> ·
  <a href="mailto:idrisnotebook@gmail.com">Email</a> ·
  Jakarta, open to remote roles
</p>

---

### 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**Customer Churn MLOps**](https://github.com/idsoke/customer-churn-mlops) · [live demo](https://fe-customer-churn-mlops.vercel.app) | End-to-end churn prediction, from data pipeline to a live web UI. ROC-AUC 0.988, 84.2% recall. Frontend in [fe-customer-churn-mlops](https://github.com/idsoke/fe-customer-churn-mlops). | Python, scikit-learn, DVC, FastAPI, Angular 22 |
| [**Sahm**](https://github.com/idsoke/sahm) · [live](https://sahm.sahm-web.workers.dev) | Indonesian sharia stocks per OJK's Sharia Securities List: status, prices, movers and a screener. Built on [fzn0x/idx](https://github.com/fzn0x/idx). | Rust, Cloudflare Workers |
| [**Warungku POS**](https://github.com/idsoke/idris-pos) | Multi-tenant point of sale for small shops. | Java 21, Spring Boot, JWT, Next.js |
| [**idris-taskapi**](https://github.com/idsoke/idris-taskapi) | Task management REST API with JWT auth and per-user data. | Node.js, Express, PostgreSQL |

---

### 🌍 Open-source contributions

**Merged**
- **[OpenSearch neural-search](https://github.com/opensearch-project/neural-search/pull/1971)**: fixed inaccurate `hits.total.value` on hybrid queries with a small `size`.
- **[Micronaut](https://github.com/micronaut-projects/micronaut-core/pull/12690)**: fixed the KSP processor resolving the wrong generic types for Kotlin suspend functions that return typealiases, which caused a `ClassCastException` during deserialization.
- **[Nakama](https://github.com/ahmadrosid/nakama/pulls?q=is%3Apr+author%3Aidsoke+is%3Amerged)** (5 PRs): automations now [resume from the last saved tool step](https://github.com/ahmadrosid/nakama/pull/1592) after a restart; [rejected malformed API keys](https://github.com/ahmadrosid/nakama/pull/730); [fixed a terminal raw-mode leak](https://github.com/ahmadrosid/nakama/pull/801); [tidied sub-agent child chats](https://github.com/ahmadrosid/nakama/pull/2225); [named the setting that allows a refused origin](https://github.com/ahmadrosid/nakama/pull/2567) in the server error.
- **[omni-tools](https://github.com/iib0011/omni-tools/pulls?q=is%3Apr+author%3Aidsoke+is%3Amerged)** (2 PRs): [built the client-side "Images to GIF" tool](https://github.com/iib0011/omni-tools/pull/374), then [added drag-and-drop](https://github.com/iib0011/omni-tools/pull/458) to it.
- **[graphql-java](https://github.com/graphql-java/graphql-java/pull/4561)**: documented what `Coercing.valueToLiteral` receives and when the engine calls it, with a test that pins the behaviour.

**In review**
- **[PrestoDB](https://github.com/prestodb/presto/pull/27909)**: fix for constant aggregation arguments being nulled during mixed distinct/non-distinct aggregation optimization, with unit and native tests.
- **[Spring AI](https://github.com/spring-projects/spring-ai/pull/7290)**: clarified retry configuration in the OpenAI docs.

---

### 🔧 Tech stack

**Backend:** Java 8/21, Spring Boot, JPA/Hibernate, Java EE, REST, Python FastAPI, PHP CodeIgniter<br/>
**Frontend:** Angular, TypeScript, RxJS, Next.js, HTML/CSS<br/>
**Messaging & integration:** Apache Kafka, Apache Camel, Netflix Eureka, Prowide Core (SWIFT MT)<br/>
**Data & ML:** Oracle, SQL Server, PostgreSQL, MySQL, Redis, pandas, scikit-learn, DVC<br/>
**Ops:** Linux, Docker, Jenkins, Elasticsearch, Grafana, Prometheus, Vercel, Cloudflare Workers
