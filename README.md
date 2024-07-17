# Data Infrastructure Concept

This repo will be used to document a popular solution for data management using opensource projects running on kubernetes

## Solutions

| Function            | Name                   | Version          | Source           | Format                                                |
| ------------------- | ---------------------- | ---------------- | ---------------- | ----------------------------------------------------- |
| Data Integration    | apache kafka           | 3.7.1            | bitnami          | [helm](https://bitnami.com/stack/kafka/helm)          |
| Data Integration    | apache nifi            | X.Y.Z            |           |      |
| Data Transormation  | apache spark           | 3.5.1            | bitnami          | [helm](https://bitnami.com/stack/spark/helm)          |
| Data Transormation  | apache spark streaming | 3.5.1            |                  | included in the spark chart                           |
| Data Transormation  | jupyter hub            | 4.1.5            | bitnami          | [helm](https://bitnami.com/stack/jupyterhub/helm)     |
| Analytics           | trino                  | X.Y.Z            |           |      |
| Visualisation       | apache supersets       | X.Y.Z            |           |      |
| AI/ML               | kubeflow               | X.Y.Z            |           |      |
| Observability       | opensearch             | 2.15.0           | bitnami          | [helm](https://bitnami.com/stack/opensearch/helm)     |
| Monitoring          | grafana                | 11.1.0           | bitnami          | [helm](https://bitnami.com/stack/grafana/helm)        |
| Monitoring          | prometheus             | 2.53.1           | bitnami          | [helm](https://bitnami.com/stack/prometheus/helm)     |
| Orchestration       | apache airflow         | 2.9.2            | bitnami          | [helm](https://bitnami.com/stack/apache-airflow/helm) |
