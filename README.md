<!-- Header -->

<div align="center">

### Site Reliability Engineer · Cloud Architect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moideen-siraj/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:moideensiraj73@gmail.com)
[![Google Cloud Certified](https://img.shields.io/badge/GCP-Professional_Cloud_Architect-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://www.credly.com/badges/34faf5ac-4609-4a23-b1ec-e15fce183da1/linked_in_profile)

</div>

## `$ helm list --tech-stack`

<div align="center">

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## `$ kubectl get projects --field-selector=status=battle-tested`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🚀 <a href="https://github.com/SirajMoideen/uptime-monitor">Uptime Monitor</a></h3>
      <p><img src="https://img.shields.io/badge/Featured-Personal_Project-FF6B35?style=flat-square"/></p>
      <p>End-to-end showcase I built from scratch — Flask app with HTTP, ping & TCP checks, PostgreSQL storage, a complete CI/CD + GitOps pipeline, and full metrics & logging stacks on my private Kubernetes lab.</p>
      <p>
        <a href="https://github.com/SirajMoideen/uptime-monitor"><img src="https://img.shields.io/badge/App-uptime--monitor-3776AB?style=flat-square&logo=python&logoColor=white"/></a>
        <a href="https://github.com/SirajMoideen/uptime-monitor-gitops"><img src="https://img.shields.io/badge/GitOps-uptime--monitor--gitops-0F1689?style=flat-square&logo=helm&logoColor=white"/></a>
        <a href="https://github.com/SirajMoideen/kind-platform"><img src="https://img.shields.io/badge/Infra-kind--platform-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/></a>
        <img src="https://img.shields.io/badge/ArgoCD-auto--sync-EF7B4D?style=flat-square&logo=argo&logoColor=white"/>
        <img src="https://img.shields.io/badge/Metrics-Prometheus%20%2B%20Grafana-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
        <img src="https://img.shields.io/badge/Logging-ES%20%2B%20Kibana%20%2B%20Filebeat-005571?style=flat-square&logo=elasticsearch&logoColor=white"/>
      </p>
      <details open>
        <summary><b>⚙️ CI/CD & Architecture</b></summary>
        <br/>
        <ul>
          <li>🔨 <b>Build</b> — Self-hosted GitHub Actions runner builds & pushes to GHCR</li>
          <li>🔄 <b>GitOps</b> — Image tag auto-updated in <a href="https://github.com/SirajMoideen/uptime-monitor-gitops">uptime-monitor-gitops</a></li>
          <li>☸️ <b>Deploy</b> — ArgoCD syncs to <code>dev</code> (push to <code>dev</code>) or <code>prod</code> (push to <code>main</code>)</li>
          <li>🏗️ <b>Lab infra</b> — Kind cluster, ingress, monitoring & logging stacks in <a href="https://github.com/SirajMoideen/kind-platform">kind-platform</a></li>
          <li>📊 <b>Metrics</b> — Prometheus & Grafana deployed via ArgoCD</li>
          <li>📋 <b>Logging</b> — Elasticsearch, Kibana & Filebeat deployed via ArgoCD</li>
        </ul>
        <p><i>Personal lab setup — auto-deploy on both envs for demo. Production-grade would use manual approval gates.</i></p>
      </details>
      <br/>
      <a href="https://github.com/SirajMoideen/uptime-monitor#readme">
        <img src="https://img.shields.io/badge/Explore-Full_Architecture_&_Setup-326CE5?style=for-the-badge&logo=github&logoColor=white"/>
      </a>
    </td>
        <td width="50%" valign="top">
      <h3>📖 <a href="https://github.com/SirajMoideen/sre-runbooks">SRE Runbooks & Automation Toolkit</a></h3>
      <p>A living library of production-grade runbooks, automation scripts, and operational playbooks — built from real incidents, upgrades, and late-night war rooms.</p>
      <p>
        <img src="https://img.shields.io/badge/Shell-90%25-4EAA25?style=flat-square&logo=gnubash&logoColor=white"/>
        <img src="https://img.shields.io/badge/Python-10%25-3776AB?style=flat-square&logo=python&logoColor=white"/>
      </p>
      <details open>
        <summary><b>⚡ What's inside</b></summary>
        <br/>
        <ul>
          <li>🍃 <b>MongoDB on K8s</b> — Operator + version upgrade runbook (5.0 → 8.0), backup to GCS via CronJob</li>
          <li>🐘 <b>PostgreSQL DBA</b> — Cheatsheet for day-to-day administration & Cloud SQL ops</li>
          <li>☁️ <b>GCP Automation</b> — SA key rotation, service account audit, disk migration, resource inventory</li>
          <li>📊 <b>Prometheus + Grafana</b> — Kubernetes pod monitoring dashboard (JSON)</li>
          <li>🔒 <b>SSL Monitor</b> — Bulk cert expiry checker across multiple domains</li>
          <li>🔁 <b>Service Auto-Restarter</b> — HTTP health monitor with systemd restart + webhook alerts</li>
          <li>🐳 <b>Docker Ops</b> — Cleanup runbook, network conflict fix</li>
          <li>🏃 <b>GitLab Runner</b> — Install, manage, troubleshoot CI/CD runners</li>
          <li>📦 <b>StatefulSet Snapshots</b> — PV backup & restore procedures</li>
          <li>🐧 <b>CentOS → Rocky Linux 8</b> — Migration guide</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

---

## `$ ping me`

Open to SRE opportunities. Focused on Kubernetes, scaling, and production reliability.

---

<div align="center">

*"The goal of SRE is to make the whole lifecycle of software development, deployment, and operations faster, more reliable, and more efficient."*
</div>
