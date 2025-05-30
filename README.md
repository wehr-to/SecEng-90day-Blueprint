# 🛡️ seceng-90day-blueprint

This project simulates a 90-day onboarding experience for a **Security Engineer or Analyst** in a midsize-to-enterprise environment. It reflects how I would approach ramping up, identifying risks, and contributing to a defensive security team from day one.

## 🎯 Objectives

- Rapidly understand the environment
- Identify and close visibility or tooling gaps
- Tune detection logic to reduce alert fatigue
- Build repeatable playbooks for response
- Propose automation, hardening, and detection improvements

## 🗓️ Phase Breakdown

### ✅ Day 0–30: Orientation + Discovery
- Toolchain review (SIEM, EDR, ticketing, cloud logs)
- Shadowing alert triage
- Walking through the asset inventory
- Noting logging gaps and unmonitored services
- Reflecting on onboarding experience (good/bad/friction)

### 🔍 Day 31–60: Maturity & Detection
- Proposing hardening tasks and patch reminders
- SIEM tuning experiments (noise vs signal)
- Reviewing EDR deployment and config gaps
- Conducting mini purple-team tabletop
- Building “first response” triage templates

### 🧠 Day 61–90: Contribution & Optimization
- Reviewing internal threat models
- Documenting automation/alerting wishlist
- Running a simulated phishing or ransomware tabletop
- Linking IOCs to dashboards + queries
- Writing a final impact report

## 🧰 Tooling Simulated

- **SIEM**: Wazuh, Splunk, or Elastic
- **EDR**: Falcon, Defender for Endpoint
- **Infra**: Ubuntu, Windows 10/Server 2019
- **Logs**: Sysmon, auditd, DNS, firewall, auth
- **Triage**: MITRE ATT&CK, Sigma rules, open IOCs

## 📄 Sample Artifacts

- IOC to Sigma query conversion
- DNS tunneling detection walkthrough
- Purple team gaps logged in `purple-team-ideas.md`
- `triage-playbook-template.md` for initial alert handling
- Dashboard screenshots of key detection logic

## 💡 Intended Value

This project is a **realistic simulation of early-career success**. It’s a way to show:
- Strategic ramp-up thinking
- Technical and procedural awareness
- Real deliverables you’d contribute in the first 90 days




