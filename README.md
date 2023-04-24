---
marp: true
paginate: true
style: |
    section.lead {
        background-color: #243a5e;
    }
    section.lead h1 {
      color: white;
    }
    section.lead h2 {
      color: white;
    }
#footer: '![image](img/microsoft-logo.png)'

---
<!--
_class: lead invert
-->

# How to Win with Transactable Containers

### Presented by: Tommy Falgout | Cloud Solution Architect

---
# Agenda

- What is Transactable Container / K8s Apps in the Marketplace?
- Candidates
- Examples
- Next Steps

---

# What is Transactable Container / K8s Apps in the Marketplace (aka. TCon / K8sApps)

- Self-service marketplace for Kubernetes based applications
  - Deploy to AKS via portal
  - Transacts through the Marketplace (IP-Co Sell)
  - Software bundled via Helm Chart
- See: https://aka.ms/k8sapps
- Prerequisite: 
  - [How to Partner with Microsoft](https://lastcoolnameleft.github.io/how-to-partner-with-microsoft/)

---

# Candidates

- ISV Solution
- Solution runs in customer's AKS
- ISV does not need to manage app hands-on after deployment

---

# Examples

- Service Mesh
- Container Network Interface (CNI)
- Data Backup/Recovery
- Network Appliance (e.g. Ingress, API Gateway, Firewall, etc.)
- ML Ops (e.g. Kubeflow)

---

# Architecture

![img](img/customer-only-deployment.png)

---

# End to End Flow

![img](img/end-to-end-flow.png)