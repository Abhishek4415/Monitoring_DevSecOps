
#Lab 3: Monitoring, Logging & DevSecOps
Overview
This lab demonstrates an automated, observable, and secure
infrastructure workflow. It combines infrastructure provisioning and
configuration management with monitoring, centralized logging, security
checks, feature flags, load testing, and automated browser testing.

Tools: Terraform, Ansible, Prometheus, Grafana, Elasticsearch,
Logstash, Kibana (ELK), Selenium, GitHub.
Run experiments only in the authorized laboratory environment. Do not
scan, load-test, or modify systems without permission.

Objectives
- Provision infrastructure using Terraform.
- Configure systems and services using Ansible.
- Collect metrics with Prometheus and visualize them in Grafana.
- Centralize and inspect logs using the ELK stack.
- Integrate DevSecOps practices such as pipeline security scanning.
- Demonstrate feature flags, load testing, and automated browser
  testing.
- Keep configuration files, dashboards, logs, screenshots, and
  observations in a GitHub repository with regular commits.
Suggested Repository Structure
lab3-monitoring-logging-devsecops/
├── README.md
├── .gitignore
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   ├── providers.tf
│   └── terraform.tfvars.example
├── ansible/
│   ├── ansible.cfg
│   ├── inventory/
│   │   └── hosts.ini
│   ├── playbooks/
│   │   └── site.yml
│   └── roles/
│       └── app/
│           ├── tasks/
│           │   └── main.yml
│           └── templates/
├── monitoring/
│   ├── prometheus/
│   │   └── prometheus.yml
│   └── grafana/
│       ├── dashboards/
│       └── provisioning/
├── logging/
│   ├── logstash/
│   │   └── pipeline.conf
│   └── kibana/
│       └── README.md
├── security/
│   ├── pipeline-security.md
│   └── scan-results/
├── feature-flags/
│   └── README.md
├── load-testing/
│   ├── test-plan.md
│   └── results/
├── selenium/
│   ├── tests/
│   │   └── test_smoke.py
│   └── README.md
└── evidence/
    ├── screenshots/
    ├── logs/
    ├── observations.md
    └── experiment-record.md
