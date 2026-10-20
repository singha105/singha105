<h2 align="center">Hi, I'm Arnab</h2>

<p align="center">
  MS Computer Science at the University of Dayton · DevOps, cloud and AI engineering
  <br>
  <a href="https://singha105.github.io">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/singharnab/">LinkedIn</a> ·
  <a href="mailto:arnabsingh001@gmail.com">Email</a>
</p>

<br>

I'm finishing my MS in December 2026, and I also work as a data analyst for the university. Most of what I build is on the infrastructure side: Kubernetes operators, AWS automation, and backend services in Go and Python. Lately I've been building AI agents that work on that kind of infrastructure, with a person approving anything that changes it.

I'm looking for new-grad roles in DevOps, cloud, platform/SRE or AI engineering, starting January 2027.

### Projects

<table>
<tr>
<td width="50%" valign="top">
<p><b><a href="https://github.com/singha105/opspilot">OpsPilot</a></b><br>
<code>Python</code> <code>LangGraph</code> <code>FastAPI</code></p>
<p>An incident-response agent for Kubernetes. It investigates alerts with read-only MCP tools and a hybrid RAG index of runbooks, then proposes a fix that only runs after someone approves it. It found the failing component in 19 of 20 held-out incidents.</p>
</td>
<td width="50%" valign="top">
<p><b><a href="https://github.com/singha105/paved">Paved</a></b><br>
<code>Go</code> <code>Kubebuilder</code> <code>Prometheus</code></p>
<p>A Kubernetes operator that turns an 18-line ServiceClaim into a running service with a canary rollout, autoscaling, network policy, SLO alerts and a dashboard. When the error budget runs out, it freezes deploys.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><b><a href="https://github.com/singha105/iam-autopilot">IAM Autopilot</a></b><br>
<code>Go</code> <code>Step Functions</code> <code>Terraform</code></p>
<p>Trims AWS IAM policies down to what each role actually uses. It shadow-tests the smaller policy, ships it through a reviewed PR, and rolls back on its own if anything gets denied. Across three roles it cut 2,110 granted permissions to 11.</p>
</td>
<td width="50%" valign="top">
<p><b><a href="https://github.com/singha105/webhook-relay">webhook-relay</a></b><br>
<code>Go</code> <code>PostgreSQL</code> <code>Kubernetes</code></p>
<p>At-least-once webhook delivery with a transactional outbox, Valkey Streams, signed payloads, retries and a dead-letter queue. Load-tested to about 870 events/sec on a laptop and chaos-tested by killing workers mid-delivery.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><b><a href="https://github.com/singha105/agent-team">agent-team</a></b><br>
<code>Python</code> <code>FastAPI</code> <code>React</code></p>
<p>Four Claude agents that hand work to each other, with tool calls sandboxed in Docker and budgets enforced across the whole delegation tree.</p>
</td>
<td width="50%" valign="top">
<p><b>Smaller projects</b></p>
<p><a href="https://github.com/singha105/mincut-segmentation">mincut-segmentation</a>: image segmentation with max-flow written from scratch. It <a href="https://singha105.github.io/mincut-segmentation/">runs in the browser</a>.</p>
<p><a href="https://github.com/singha105/phonepad">phonepad</a>: turns an iPhone into a game controller for a Mac.</p>
</td>
</tr>
</table>

### Tools I use

<img src="https://skillicons.dev/icons?i=go,py,ts,bash,kubernetes,docker,terraform,githubactions,aws,prometheus,grafana,postgres,redis,fastapi,react&perline=15" alt="Go, Python, TypeScript, Bash, Kubernetes, Docker, Terraform, GitHub Actions, AWS, Prometheus, Grafana, PostgreSQL, Redis, FastAPI, React" />

Also Helm, Argo CD, OpenTelemetry, LangGraph, MCP and the Claude API.
