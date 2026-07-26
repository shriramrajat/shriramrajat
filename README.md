<div align="center">
  <img src="dashboard.svg" alt="Telemetry Dashboard" width="100%" />
</div>

<br />

```python
class RajatShriram:
    def __init__(self):
        self.role       = "Systems & Backend Infrastructure Engineer"
        self.location   = "Pune, India 🇮🇳"
        self.focus      = ["High-Throughput APIs", "API Gateway Architecture", "SRE & Observability"]
        self.current    = "SentinelStack — High-Performance API Gateway with Auth & Rate Limiting"
        self.learning   = ["Database Internals", "Distributed Consensus (Raft)", "Linux Kernel & eBPF"]
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shriramrajat)
[![X](https://img.shields.io/badge/X-black.svg?style=flat-square&logo=X&logoColor=white)](https://x.com/shriramrajat)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=flat-square&logo=Instagram&logoColor=white)](https://instagram.com/shriramrajat)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rajatshriram7@gmail.com)

</div>

---

## 🛠️ Featured Project: SentinelStack

SentinelStack is a lightweight, high-performance API Gateway designed for rate-limiting, proxy-authentication, and telemetry extraction at the edge of backend microservices.

### ⚙️ Declarative Gateway Config (`gateway.yaml`)
```yaml
gateway:
  version: "1.2.0"
  port: 8080
  workers: 4

rate_limiting:
  enabled: true
  provider: redis
  strategy: token_bucket
  limits:
    - path: /api/v1/auth/*
      capacity: 10
      refill_rate: 2/s
    - path: /api/v1/data/*
      capacity: 100
      refill_rate: 10/s

observability:
  prometheus:
    metrics_path: /metrics
    port: 9090
  logging:
    level: info
    format: json
    destination: stdout
```

### 📈 SentinelStack Performance Benchmarks
*Tested under load using `wrk` on a 4-core, 8GB Ubuntu node.*

| Metric | Target | Result |
| :--- | :--- | :--- |
| **Max Throughput** | 10,000 RPS | **12,450 RPS** |
| **p95 Latency** | < 10ms | **6.2ms** |
| **p99 Latency** | < 25ms | **18.4ms** |
| **Memory Footprint** | Static < 50MB | **32MB (Idle) / 48MB (Peak)** |

### 🛰️ Telemetry & Observability Demo
The gateway monitors ingress request latency, token bucket depletion status, and proxies client credentials.



---

## 💻 Tech Stack & Tooling

| Category | Technologies |
| :--- | :--- |
| **Languages** | `C++`, `C`, `Go`, `Python`, `SQL` |
| **Infrastructure** | `Docker`, `Redis`, `PostgreSQL`, `Linux`, `Prometheus`, `Grafana` |
| **Frameworks & Libraries** | `FastAPI`, `Pydantic`, `SQLAlchemy`, `gRPC` |

---

## 📊 Developer Analytics

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shriramrajat&theme=midnight_purple" width="100%"/>
      </td>
      <td align="center" width="50%">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=shriramrajat&theme=midnight_purple" width="100%"/>
      </td>
    </tr>
    <tr>
      <td align="center" width="50%">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=shriramrajat&theme=midnight_purple" width="100%"/>
      </td>
      <td align="center" width="50%">
        <img src="https://streak-stats.demolab.com/?user=shriramrajat&theme=midnight-purple&hide_border=true&background=0a0a0f&stroke=4f6ef7&ring=a78bfa&fire=f59e0b&currStreakLabel=4f6ef7" width="100%"/>
      </td>
    </tr>
  </table>
</div>
