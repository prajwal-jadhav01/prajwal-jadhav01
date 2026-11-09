### Hi, I'm Prajwal 👋

Data engineer in Pune. I build streaming data pipelines and the .NET services and CI/CD around them.

- **Streaming data:** Apache Flink jobs feeding Apache Pinot for real-time analytics, orchestrated with Airflow, on PostgreSQL and Oracle sources, mostly in healthcare (HIPAA-aware handling of patient data).
- **Backend:** ASP.NET Core APIs with Camunda workflows for approvals.
- **Delivery:** Docker, Jenkins, Grafana/Prometheus.

**Open source:** I opened a fix in [apache/pinot#20121](https://github.com/apache/pinot/pull/20121) so the Flink → Pinot sink can talk to clusters that have authentication turned on (in review). I hit that gap at work when enabling Pinot auth broke 80+ Flink jobs at once.

#### Projects

| | |
|---|---|
| [**realtime-health-analytics**](https://github.com/prajwal-jadhav01/realtime-health-analytics) | Kafka → Flink (Java) → Pinot with auth on every Pinot component, dead-letter queue for bad records, Grafana dashboards. Starts with one `make up`. |
| [**approval-workflow-api**](https://github.com/prajwal-jadhav01/approval-workflow-api) | ASP.NET Core 10 + Camunda 8 expense-approval API: role-based JWT, manager/finance approval paths, cancel at any step, idempotent workers, PostgreSQL. |
| [**jenkins-pipeline-library**](https://github.com/prajwal-jadhav01/jenkins-pipeline-library) | One Jenkins shared library that replaces per-app, per-environment Jenkinsfiles: build, push, approval-gated prod deploys, automatic rollback. |

#### Stack

`Java` `C# / .NET` `SQL` · `Apache Flink` `Apache Pinot` `Kafka` `Airflow` · `PostgreSQL` `Oracle` · `ASP.NET Core` `Camunda` · `Docker` `Jenkins` `Grafana` `Prometheus` `Superset`

📫 [LinkedIn](https://www.linkedin.com/in/prajwal-jadhav-3ab508257)
