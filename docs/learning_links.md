# Learning Links for the 30-Day Azure + Terraform Plan



**Purpose:** This file contains the official Microsoft Learn modules and reference links mapped to the 30-day calendar. 



> **Reminder:** your Azure free trial expires. Destroy or deallocate non-essential resources by the expire date.



---



## Week 1 — Identity \& Governance 

- **AZ-104: Manage identities and governance (learning path)**  

&nbsp; https://learn.microsoft.com/en-us/training/paths/az-104-manage-identities-governance/  

&nbsp; *Use:* Core path covering Entra ID, RBAC, subscriptions, and governance. Run these modules on Days 1–3 of the sprint.



- **Module: Create, configure, and manage identities**  

&nbsp; https://learn.microsoft.com/en-us/training/modules/create-configure-manage-identities/  

&nbsp; *Use:* Hands-on lab to create users/groups and assign roles. Save screenshots to `docs/identity/`.



- **Exam-readiness video — Manage identities \& governance**  

&nbsp; https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-manage-azure-identities-and-governance-1-of-5  

&nbsp; *Use:* Short recap after completing identity modules.



---



## Week 2 — Compute (VMs), Storage \& Networking 

- **AZ-104: Deploy and manage Azure compute resources (learning path)**  

&nbsp; https://learn.microsoft.com/en-us/training/paths/az-104-manage-compute-resources/  

&nbsp; *Use:* Study VM selection, extensions, and compute best practices (Day 6–7).



- **AZ-104 prerequisites (refresher)**  

&nbsp; https://learn.microsoft.com/en-us/training/paths/az-104-administrator-prerequisites/  

&nbsp; *Use:* Install/confirm tools and core concepts before hands-on labs.



- **AZ-104: Implement and manage storage (learning path)**  

&nbsp; https://learn.microsoft.com/en-us/training/paths/az-104-manage-storage/  

&nbsp; *Use:* Storage account types, blob/file choices, and access tiers (Day 8).



- **Exam-readiness video — Implement and manage storage**  

&nbsp; https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-implement-and-manage-storage-2-of-5  

&nbsp; *Use:* Short review before/after storage labs.



- **AZ-104: Configure and manage virtual networks (learning path)**  

&nbsp; https://learn.microsoft.com/en-us/training/paths/az-104-manage-virtual-networks/  

&nbsp; \*Use:\* VNet, subnets, peering, connectivity (Day 9–10).



\- \*\*Module: Configure network security groups (NSGs)\*\*  

&nbsp; https://learn.microsoft.com/en-us/training/modules/configure-network-security-groups/  

&nbsp; \*Use:\* Hands-on NSG examples and rule testing; include results in `docs/network/`.



\- \*\*Exam-readiness video — Virtual networking\*\*  

&nbsp; https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-implement-and-manage-virtual-networking-4-of-5  

&nbsp; \*Use:\* Quick recap after networking lab and before Terraform networking automation.



---



\## Week 3 — Backup, Monitoring \& Cost 

\- \*\*Create Azure Recovery Services vaults (how-to)\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/backup/backup-create-recovery-services-vault  

&nbsp; \*Use:\* Step-by-step to create a Recovery Services vault (Day 11).



\- \*\*Back up Azure VMs in a Recovery Services vault (tutorial)\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-vms-prepare  

&nbsp; \*Use:\* Prepare and enable VM backup; capture screenshots for `docs/backup/` (Day 11–12).



\- \*\*Create a metric alert for an Azure resource (tutorial)\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/tutorial-metric-alert  

&nbsp; \*Use:\* Add a CPU alert for your VM and document thresholds (Day 13).



\- \*\*Azure Monitor alerts overview\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview  

&nbsp; \*Use:\* Design decisions for alerting and action groups (Day 13).



\- \*\*Azure Cost Management \& Billing (docs)\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/cost-management-billing/  

&nbsp; \*Use:\* Run Cost Management, set budgets \& alerts, and produce `cost-report.md` (Day 14).



\- \*\*Learning path: Control Azure spending and manage bills\*\*  

&nbsp; https://learn.microsoft.com/en-us/training/paths/control-spending-manage-bills/  

&nbsp; \*Use:\* Optional deeper dive into budgets and optimization techniques.



---



\## Supplemental / deeper study (reference)

\- \*\*AZ-104T00-A course (Azure Administrator instructor materials)\*\*  

&nbsp; https://learn.microsoft.com/en-us/training/courses/az-104t00  

&nbsp; \*Use:\* Instructor-led syllabus and deeper examples — reference for deeper troubleshooting.



\- \*\*Recovery Services vault overview (concepts)\*\*  

&nbsp; https://learn.microsoft.com/en-us/azure/backup/backup-azure-recovery-services-vault-overview  

&nbsp; \*Use:\* Background reading on RS vault behavior and supported workloads.



---



\## How to use this file

\- Each link above is mapped to the corresponding day(s) in the 30-day calendar. Open the linked module for the hands-on lab on the specified day.

\- After finishing a module, save at least one screenshot and a 2–4 sentence note in `docs/<module-name>/` and commit to the repo on the same day.

\- If a lab prompts you to create paid resources, stop and switch to the instructions that use free-tier or sandbox steps, or do `terraform plan` only and \*\*do not apply\*\* until you confirm SKUs and cost.





