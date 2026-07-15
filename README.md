<h1 align="center">Ethan Fox</h1>

<p align="center"><b>Cloud &amp; DevOps Engineer</b></p>

<p align="center">
  I ship real apps on real infrastructure — Terraform, containers, Kubernetes, and CI/CD —
  and I learn a platform by building on it.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ethan-fox03/"><img src="https://img.shields.io/badge/LinkedIn-ethan--fox03-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ethanfox03@gmail.com"><img src="https://img.shields.io/badge/Email-ethanfox03@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## Cloud & DevOps

A four-project arc where I rebuild the *same* class of app on progressively deeper
infrastructure — from a fully-managed edge platform up to a Kubernetes cluster I run
myself. The apps stay small on purpose; the platform around them is the point.

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| **[url-shortener-k8s](https://github.com/genkuroo/url-shortener-k8s)** | Running the orchestrator myself — GitOps delivery, autoscaling, and monitoring around a containerized service | Kubernetes · Helm · Argo CD · Prometheus/Grafana · HPA |
| **[url-shortener-aws](https://github.com/genkuroo/url-shortener-aws)** | Infrastructure-as-code from an empty account: network, containers, database, and an OIDC-authenticated CI/CD pipeline | Terraform · ECS Fargate · ALB · RDS · GitHub Actions |
| **[cloud-habit-tracker-aws](https://github.com/genkuroo/cloud-habit-tracker-aws)** | Serverless and event-driven — no servers to manage, shipped as one SAM template | AWS Lambda · DynamoDB · CloudFront · SAM |
| **[habit-tracker](https://github.com/genkuroo/habit-tracker)** | Where the arc started: an app on Cloudflare's edge with a serverless API and managed data | Cloudflare Pages · Workers · KV · D1 |

The progression is deliberate: each step hands me more of the stack to own — from
"the platform hides everything" (Cloudflare) to "I own the scheduler" (Kubernetes).

## Applications & Data

Full builds behind the infrastructure work — the kind of app I like putting *on* the platforms above.

| Project | What it does | Stack |
| --- | --- | --- |
| **[fitness-dashboard](https://github.com/genkuroo/fitness-dashboard)** | Unifies Strava (cardio), MyNetDiary (diet/weight), and Liftoff (strength) into one SQLite store to cross-reference training, diet, and weight on a shared timeline | Python · pandas · Flask · Chart.js |
| **[dnd-campaign-tracker](https://github.com/genkuroo/dnd-campaign-tracker)** | Multi-user, authenticated D&D 5e campaign tool — a ~3,700-line Flask app deployed on Fly.io in Docker | Flask · SQLite · Docker · Fly.io |
| **[stock-tracker](https://github.com/genkuroo/stock-tracker)** | Portfolio CLI + dashboard with live quotes, news, and a per-ticker AI TLDR | Python · Flask · Claude API |

## Tech I Work With

**Cloud & infrastructure** — AWS · Terraform · Kubernetes · Helm · Argo CD · Docker · Cloudflare

**Observability & CI/CD** — Prometheus · Grafana · GitHub Actions

**Languages & frameworks** — Python · FastAPI · Flask · PostgreSQL · SQLite

## Contact

I'm open to Cloud / DevOps roles. The fastest ways to reach me:

- **LinkedIn** — [ethan-fox03](https://www.linkedin.com/in/ethan-fox03/)
- **Email** — [ethanfox03@gmail.com](mailto:ethanfox03@gmail.com)
