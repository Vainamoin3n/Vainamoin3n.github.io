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
- **Team:** 1 product manager, 1 engineering team lead, 4 software engineers, 1 product designer, 1 product marketeer (shared)
- **Users:** Eficode customers, Eficode employees
- **Timeperiod**: October 2022-> Now


#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
Eficode Journey is Eficode's customer portal. It was built from scratch by Eficode R&D for which I was the product manager.
It enables transparency on Eficode's activity, ease of reporting and analytics on the state of software engineering, IT and Platform engineering at the customer's.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Reporting went from "hours-days per month per customer" to "minutes per month per customer"
- Human error in reporting dropped to very minimal
- Enabled a new product line, Eficode Advisory & Support, likely to become a main product of Eficode in the year 2026.
- 50-60% Monthly Active organizations in Managed Services customer base
- The customer trust in the Managed Services organization increased significantly after Eficode Journey was introduced

#### Capabilities built over time 
{: data-toc-skip='' .mt-4 .mb-0 }
##### 1) Tickets SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** No systematic way to report the SLAs on tickets leading to time consuming operations and mistakes, or simply skipped
- **What we shipped:** Service Managers can now do the reports in 2 clicks and it automatically shares to the customer and sends them an email when they approve it.
- **Eficode business value:** The effort dropped to almost null, reports became systematic across the whole customer base and mistakes were easily found and fixed.
- **Customer value:** Thorough and credible monthly report on Eficode fulfilled the contract's ticket SLA.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/TicketSLA.png" alt="SLA report" style="width: 100%;">
  <img src="/assets/img/Journey/TicketSLAReport1.png" alt="SLA report details" style="width: 100%;">
</div>

##### 2) Uptime SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** The Uptime SLA (How well has Eficode kept the customer's tool available and working) was an incredibly time consuming reports to make and the data was unreliable in many cases, so the reports were mostly not made, unless requested, even though stated to be provided in the contract
- **What we shipped:** Service Managers can now do the reports in 2 clicks and highlight to the customers the issues and their reasons if such exist. The Monthly Maintenance Breaks and vulnerabilities updates are automatically removed from the % target.
- **Eficode business value:** All the customer get their monthly reports in the portal. The usage started correct but dropped over time as customers trusted us and knew that we are doing looking at these reports actively.
- **Customer value:** Thorough and credible monthly report on how Eficode kept the platform engineering tools of the customer up and running.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/UptimeSLA.png" alt="Uptime report menu" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport1.png" alt="Uptime report details" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport2.png" alt="Incidents and downtime events report" style="width: 100%;">
</div>

##### 3) Status page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** A part of the tool down issues reported by the customer are happening on their network and both lose time investigating.
- **What we shipped:** Built on the same tool as the uptime SLA, there is now a live Status page telling if the tool is working from inside the customer network, according to our uptime. We added the planned outages there to remind in case something is expected.
- **Eficode business value:** Low investment feature with fairly low usage. It saved us time in trying to debug issues on the customer network side, which was the original goal.
- **Customer value:** An easy place to check first if employees report a tool misbehaving.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/StatusPage1.png" alt="Main status page" style="width: 100%;">
  <img src="/assets/img/Journey/StatusPage2.png" alt="Incidents events" style="width: 100%;">
</div>

##### 4) Billing page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** September 2023
- **Problem:** Every service manager reporting the worklog & billing details differently. Intense rush from every service manager at the start of the month to do billing. No easy way to replace one's colleague during billing.
- **What we shipped:** Built a few clicks billing report, systematic across all Service Managers, with additional data to enable checking (& checking automatically) if there are issues. We extended the feature multiple times to add a yearly view, a current month estimate, and many more features for both the customers and service managers.
- **Eficode business value:** First feature that really impacted the Monthly Active Users (MAU), a requirement to add more features. Drove the adoption of Journey widely across Eficode Managed Services customers. Service Managers stress level dropped significantly during billing period thank to this feature. They also could finally cover for each other. Reduce significantly human errors thanks to automation leading to higher trust of the customers.
- **Customer value:** Enabled the same quality report, whether you are a small, medium or large customer. Enabled full transparency on the work done, up to the tasks done for a ticket and how long they took. Enabled checkups of work during during current month to optimize the budget usage. Enabled easier budget calculations thanks to the yearly view. 

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Billing1.png" alt="Main report for billing" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport1.png" alt="Monthly report part 1" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport2.png" alt="Monthly report part 2" style="width: 100%;">
</div>

##### 5) Dashboard
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** June 2024
- **Problem:** Eficode ROOT, the flagship of Eficode Managed Services, is missing a visual interface. Eficode Journey also has no landing page and it's difficult to direct the customer where their action is needed.
- **What we shipped:** The dashboard was built as a central place to guide the user (customer or internal) to where their action is required. It shows information at a glance and clear indicators where action is needed. It saw many interations and would still need more but currently it's good enough.
- **Eficode business value:** For the first time, both internal and external could see the total Eficode ROOT coverage at once without going to the contract. The displaying of important information to the customer also helped increase both adoption of Journey and centralize the information sharing to Eficode Journey. 
- **Customer value:** Less time spent in the portal as now they could know at a glance where new info was available and where their attention was needed. Enabled acting on important information that was missed before because it was under a menu they didn't visit.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Dashboard.png" alt="Dashboard" style="width: 100%;">
</div>


##### 6) Advanced metrics
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** December 2024 but the majority of the UI only appeared in September 2025
- **Problem:** As customer move to (Atlassian) Cloud, Eficode loses its visibility on the customer tool health and is impaired in its ability to act as a trusted advisor for its customers.
- **What we shipped:** (Requires Eficode Connector) Advanced Metrics enable to see, at a glance, what is the current situation of an organization tool adoption and usage. Using their expertise, Eficodeans can spot discrepancies and work with the customer to address those.
- **Eficode business value:** This is a true game changer for Eficode. It has now access to the same metrics across all its customer base (the one who have the connectors) and can provide very precise, context relevant advisory and support for its customers. And there is direct feedback on the effect gotten thanks to the metrics. This leads to more gigs sold, happier customers and differenciating value compared to all consulting companies, as Eficode is continously measuring if the goals of the mission are being reached and address where the difficulties are met.
- **Customer value:** Customers get a lot of actionable information,  around license consumption and usage, GitHub runners costs and cost centers and plugin security for example. But most of the value is acquired when sitting down with their Eficode advisor, looking at the numbers together and planning the next moves.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/AdvancedMetrics_GitHub3.png" alt="Example of advanced metrics with GitHub" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Gitlab4.png" alt="Example of advanced metrics with GitLab" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Jira3.png" alt="Example of advanced metrics with Jira" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_JSM2.png" alt="Example of advanced metrics with Jira Service Management" style="width: 100%;">
</div>

##### 7) Recommendations
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** April 2025 
- **Problem:** Recommendations from Eficode towards the customer go through many different channels, and many different persons. There is overlapping recommendations, information loss, and sometimes the customer gets lost as to what is the right thing to focus now
- **What we shipped:** A simple feature that enables standardization of the recommendations, with automations added to it so that the recommendations reach the right persons (through email and Slack). Each recommendations features 3 parts : "What is the situation?", "What happens if it's not addressed", "What Eficode recommends" as well an Impact and Effort estimations.
- **Eficode business value:** This feature hasn't enjoyed a good adoption rate up to now, but it starting picking up with more and more Eficode Advisory and Support being sold. The problem stated above is not yet solved with this.In the instances where the customers got the recommendations through the feature, they usually continued the discussion with their main point of contact at Eficode.
- **Customer value:** Thanks to having, one unique place to find the recommendations and each having a reasoning and a clear impact and effort, the decision making is simplified, and there is less risk of Fear Of Missing Out (FOMO).

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Recommendations.png" alt="Recommendations" style="width: 100%;">
</div>

##### 7) Lens
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** November 2025 
- **Problem:** Advanced metrics is very snapshot and doesn't enable to see trendlines over time. This makes it difficult to see what is the impact of AI adoption or Eficode's work over time.
- **What we shipped:** This is probably the feature I'm most proud of. With the product trio, we realized that by defining the X axis as a specific unit of time, we could have multiple graphs displayed at the same time, regardless of the tool or metric in Y axis. This enabled us to build Lens where one can for example see the impact of GitHub Copilot adoption in software team on the amount of Jira Epic closed (so more value reaching end customers in an ideal case), and a second later look at how many security issues / UX issues it introduced seen through GitHub security or Atlassian Service Desk bugs.
- **Eficode business value:** The business potential of this feature is enormous. It is built to support most of Eficode's business (Consulting, License, Managed Services) and could bring a change on the whole consulting market, where customers expect such metrics to be in place to ensure impact. Unfortunately the timing was a bit off, as Eficode is having a really large organization rehaul still happening (as of January 2026), and I did not get any organization bandwidth in 2025 to launch any Go To Market activity, so the reach stayed limited to my close network. The adoption of that close network has been very impressive though, and it has really hit strong when they presented it to customers.
- **Customer value:** For the customer that enjoyed the feature, this is transformational. They now can directly see the impact of Eficode and their AI adoption (or any transformation) over time. (This led to a few 😍 moments with customers). 

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Lens1.png" alt="Lens" style="width: 100%;">
</div>