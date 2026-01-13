---
# the default layout is 'page'
icon: fas fa-briefcase
order: 1
---

## (Under construction 2026-01-13)

## Eficode
{: data-toc-skip='' .mt-4 .mb-0 }

### Eficode Journey
{: data-toc-skip='' .mt-4 .mb-0 }

- **Role:** Product Manager
- **Team:** 1 product manager, 1 engineering lead, 4 software engineers, 1 product designer, 1 product marketing manager
- **Users:** Eficode customers, Eficode employees
- **Timeperiod**: October 2022-> Now


#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
Eficode Journey is Eficode's customer portal. It was built from scratch by Eficode R&D for which I was the product manager
It enables transparency on Eficode's activity, ease of reporting and visibility on the state of software engineering, IT and Platform engineering at the customer's.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Reporting went from "hours-days per month per customer" to "minutes per month per customer"
- Enabled a new product line - Eficode Advisory & Support
- 50-60% Monthly Active organizations in Managed Services customer base
- The customer trust in the Managed Services organization increased significantly after Eficode Journey was introduced

#### Capability timeline 
{: data-toc-skip='' .mt-4 .mb-0 }
##### 1) Tickets SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Problem:** No systematic way to report the SLAs on tickets leading to time consuming operations and mistakes, or simply skipped
- **What we shipped:** Service Managers can now do the reports in 2 clicks and it automatically shares to the customer and sends them an email when they approve it.
- **Impact:** The effort dropped to almost null, reports became systematic across the whole customer base and mistakes were easily found and fixed.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/TicketSLA.png" alt="SLA report" style="width: 100%;">
  <img src="/assets/img/Journey/TicketSLAReport1.png" alt="SLA report details" style="width: 100%;">
</div>

##### 2) Uptime SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Problem:** The Uptime SLA (How well has Eficode kept the customer's tool available and working) was an incredibly time consuming reports to make and the data was unreliable in many cases, so the reports were mostly not made, unless requested, even though stated to be provided in the contract
- **What we shipped:** Service Managers can now do the reports in 2 clicks and highlight to the customers the issues and their reasons if such exist. The Monthly Maintenance Breaks and vulnerabilities updates are automatically removed from the % target.
- **Impact:** All the customer get their monthly reports in the portal. The usage started correct but dropped over time as customers trusted us and knew that we are doing looking at these reports actively.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/UptimeSLA.png" alt="Uptime report menu" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport1.png" alt="Uptime report details" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport2.png" alt="Incidents and downtime events report" style="width: 100%;">
</div>

##### 3) Status page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Problem:** A part of the tool down issues reported by the customer are happening on their network and both lose time investigating.
- **What we shipped:** Built on the same tool as the uptime SLA, there is now a live Status page telling if the tool is working from inside the customer network, according to our uptime. We added the planned outages there to remind in case something is expected.
- **Impact:** Low investment feature with fairly low usage. It saved us time in trying to debug issues on the customer network side, which was the original goal.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/StatusPage1.png" alt="Main status page" style="width: 100%;">
  <img src="/assets/img/Journey/StatusPage2.png" alt="Incidents events" style="width: 100%;">
</div>

##### 4) Billing page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Problem:** Every service manager reporting the worklog & billing details differently. Intense rush from every service manager at the start of the month to do billing. No easy way to replace one's colleague during billing.
- **What we shipped:** Built a few clicks billing report, systematic across all Service Managers, with additional data to enable checking (& checking automatically) if there are issues. We extended the feature multiple times to add a yearly view, a current month estimate, and many more features for both the customers and service managers.
- **Impact:** First feature that really impacted the Monthly Active Users (MAU). Drove the adoption of Journey widely across Eficode Managed Services customers. Service Managers stress level dropped significantly during billing period thank to this feature. They also could finally cover for each other.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Billing1.png" alt="Main report for billing" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport1.png" alt="Monthly report part 1" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport2.png" alt="Monthly report part 2" style="width: 100%;">
</div>

##### 5) Dashboard
{: data-toc-skip='' .mt-4 .mb-0 }
- **Problem:** Eficode ROOT, the flagship of Eficode Managed Services, is missing a visual interface. Eficode Journey also has no landing page and it's difficult to direct the customer where their action is needed.
- **What we shipped:** The dashboard was built as a central place to guide the user (customer or internal) to where their action is required. It shows information at a glance and clear indicators where action is needed. It saw many interations and would still need more but currently it's good enough.
- **Impact:** For the first time, both internal and external could see the total Eficode ROOT coverage at once without going to the contract.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Billing1.png" alt="Main report for billing" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport1.png" alt="Monthly report part 1" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport2.png" alt="Monthly report part 2" style="width: 100%;">
</div>
