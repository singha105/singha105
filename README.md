## Hi, I'm Arnab

I'm finishing an MS in Computer Science at the University of Dayton (December 2026), and I also work as a data analyst for the university. Most of what I build is on the infrastructure side: Kubernetes operators, AWS automation, and backend services in Go and Python. Lately I've been building AI agents that work on that kind of infrastructure, with a person approving anything that changes it.

I'm looking for new-grad roles in DevOps, cloud, platform/SRE or AI engineering, starting January 2027.

### Projects

- **[OpsPilot](https://github.com/singha105/opspilot)**: an incident-response agent for Kubernetes. It investigates alerts with read-only MCP tools and a hybrid RAG index of runbooks, then proposes a fix that only runs after someone approves it. On 20 held-out incidents it found the failing component 19 times. Python, LangGraph, FastAPI.
- **[Paved](https://github.com/singha105/paved)**: a Kubernetes operator that turns an 18-line `ServiceClaim` into a running service with a canary rollout, autoscaling, network policy, SLO alerts and a dashboard. When the error budget runs out, an admission webhook freezes deploys. Go, Kubebuilder, Prometheus.
- **[IAM Autopilot](https://github.com/singha105/iam-autopilot)**: trims AWS IAM policies down to what each role actually uses. It shadow-tests the smaller policy, ships it through a reviewed PR, and rolls back on its own if anything gets denied. Across three roles it cut 2,110 granted permissions to 11. Go, Step Functions, Terraform.
- **[webhook-relay](https://github.com/singha105/webhook-relay)**: at-least-once webhook delivery with a transactional outbox, Valkey Streams, signed payloads, retries and a dead-letter queue. I load-tested it to about 870 events/sec on a laptop and chaos-tested it by killing workers mid-delivery. Go, PostgreSQL, Kubernetes.
- **[agent-team](https://github.com/singha105/agent-team)**: four Claude agents that hand work to each other, with tool calls sandboxed in Docker and budgets enforced across the whole delegation tree. Python, FastAPI, React.

Smaller things: [mincut-segmentation](https://github.com/singha105/mincut-segmentation) (image segmentation with max-flow written from scratch, [runs in the browser](https://singha105.github.io/mincut-segmentation/)) and [phonepad](https://github.com/singha105/phonepad) (turns an iPhone into a game controller for a Mac).

### Tools I use

- Languages: Go, Python, TypeScript, SQL, Bash
- Infrastructure: Kubernetes, Docker, Terraform, Helm, Argo CD, GitHub Actions
- AWS: Lambda, Step Functions, DynamoDB, IAM, S3
- Observability and data: Prometheus, Grafana, OpenTelemetry, PostgreSQL, Redis/Valkey
- AI: LangGraph, MCP, RAG, Claude API

### Contact

[singha105.github.io](https://singha105.github.io) · [LinkedIn](https://www.linkedin.com/in/singharnab/) · [arnabsingh001@gmail.com](mailto:arnabsingh001@gmail.com)
