---
# the default layout is 'page'
icon: fas fa-briefcase
order: 1
---

## Under construction (2026-01-13)

## Eficode
{: data-toc-skip='' .mt-4 .mb-0 }

### Eficode Journey
{: data-toc-skip='' .mt-4 .mb-0 }

- **Role:** Product Manager
- **Team:** 1 Product Manager, 1 Engineering Team Lead, 4 Software Engineers, 1 Product Designer, 1 Product Marketeer (shared)
- **Users:** Eficode customers, Eficode employees
- **Time period:** October 2022 to now


#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
Eficode Journey is the Eficode customer portal. It was built from scratch by Eficode R&D, where I was the Product Manager.
It enables transparent access to Eficode’s activity, easier reporting, and analytics on the state of software engineering, IT, and platform engineering in the customer’s environment.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Reporting went from hours or days per month per customer to minutes per month per customer
- Human error in reporting dropped to a minimum
- Customer trust in the Managed Services organization increased significantly after Eficode Journey was introduced.
- Enabled a new product line, Eficode Advisory & Support, likely to become a main offering for Eficode in 2026.
- 50-60% Monthly Active organizations in Managed Services customer base

#### Capabilities built over time 
{: data-toc-skip='' .mt-4 .mb-0 }
##### 1) Tickets SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** No systematic way to report the SLAs on tickets leading to time-consuming operations and mistakes, or simply being skipped
- **What we shipped:** Service Managers can now do the reports in two clicks, and the portal automatically shares them with the customer and emails them once the report is approved by the Service Manager
- **Eficode business value:** The effort dropped to almost null, reports became systematic across the whole customer base and mistakes were easily found and fixed.
- **Customer value:** Thorough, credible monthly reporting on how Eficode met the contract’s ticket SLA.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/TicketSLA.png" alt="SLA report" style="width: 100%;">
  <img src="/assets/img/Journey/TicketSLAReport1.png" alt="SLA report details" style="width: 100%;">
</div>

##### 2) Uptime SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** The Uptime SLA (how well Eficode kept the customer's tool available and working) was an incredibly time-consuming report to produce, and the data was unreliable in many cases. As a result, reports were usually not produced unless requested, even though they were included in the contract.
- **What we shipped:** Service Managers can now do the reports in two clicks and highlight issues and root causes for customers when relevant. The Monthly Maintenance Breaks and security patch updates are automatically removed from the uptime target percentage.
- **Eficode business value:** All customers now get their monthly reports in the portal. Usage started strong but dropped over time as customers trusted us and knew we were actively monitoring these reports.
- **Customer value:** Thorough and credible monthly report on how Eficode kept the platform engineering tools of the customer up and running.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/UptimeSLA.png" alt="Uptime report menu" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport1.png" alt="Uptime report details" style="width: 100%;">
  <img src="/assets/img/Journey/UptimeSLAReport2.png" alt="Incidents and downtime events report" style="width: 100%;">
</div>

##### 3) Status page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** Some of the “tool down” issues reported by customers were happening on their network and both sides wasted time investigating.
- **What we shipped:** Built on the same tool as the uptime SLA, there is now a live Status page showing whether the tool is working from inside the customer’s network, based on our uptime monitoring system. We also added the planned outages there to remind in case something is expected.
- **Eficode business value:** Low investment feature with fairly low usage. It saved us time in trying to debug issues on the customer network side, which was the original goal.
- **Customer value:** An easy first check when employees report a tool behaving unexpectedly before deciding whether a ticket to Eficode is warranted.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/StatusPage1.png" alt="Main status page" style="width: 100%;">
  <img src="/assets/img/Journey/StatusPage2.png" alt="Incidents events" style="width: 100%;">
</div>

##### 4) Billing page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** September 2023
- **Problem:** Every Service Manager reported work logs and billing details differently. There was an intense rush from every Service Manager at the start of the month to complete billing. No easy way to cover for a colleague during billing.
- **What we shipped:** Built a few-click billing report, consistent across all Service Managers, with additional data to enable checks (including automated checks) for issues. We extended the feature multiple times to add a yearly view, a current month estimate, and more improvements for both customers and Service Managers.
- **Eficode business value:** First feature that really impacted the Monthly Active Users (MAU), a requirement to add more features. Drove the adoption of Journey widely across Eficode Managed Services customers. Service Managers’ stress levels dropped significantly during the billing period thanks to this feature. They also could finally cover for each other. Significantly reduced human errors thanks to automation leading to higher customer trust.
- **Customer value:** Enabled the same quality report, whether you are a small, medium or large customer. Enabled full transparency on the work done, up to the tasks done for a ticket and how long they took. Enabled checking progress during the current month to optimize budget usage. Enabled easier budget calculations thanks to the yearly view. 

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Billing1.png" alt="Main report for billing" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport1.png" alt="Monthly report part 1" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport2.png" alt="Monthly report part 2" style="width: 100%;">
</div>

##### 5) Dashboard
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** June 2024
- **Problem:** Eficode ROOT, the flagship of Eficode Managed Services, lacked a visual interface. Eficode Journey also had no landing page and and it was difficult to direct customers to where action was needed.
- **What we shipped:** The dashboard was built as a central place to guide the user (customer or internal) to where their action is required. It went through many iterations and would still need more but currently it's good enough.
- **Eficode business value:** For the first time, both internal and external users could see the total Eficode ROOT coverage at once without going to the contract. The displaying of important information to the customer also helped increase adoption of Journey and centralize information sharing in Eficode Journey.
- **Customer value:** Less time spent in the portal as now they could know at a glance where new info was available and where their attention was needed. Enabled acting on important information that was missed before because it was under a menu they did not visit.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Dashboard.png" alt="Dashboard" style="width: 100%;">
</div>


##### 6) Advanced metrics
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** December 2024 but the majority of the UI only appeared in September 2025
- **Problem:** As customers move to tool vendors’ cloud offerings, Eficode loses its visibility on the customer tool health, and this impairs its ability to act as a trusted advisor.
- **What we shipped:** (Requires Eficode Connector) Advanced Metrics enable us to see, at a glance, the current state of an organization’s tool adoption and usage. Using their expertise, Eficode experts can spot discrepancies and work with the customer to address those.
- **Eficode business value:** This is a true game changer for Eficode. It now has access to the same metrics across its customer base (for those who have the connectors) and can provide very precise, context-relevant advisory and support for its customers. And there is direct feedback on the impact through the metrics. This leads to more advisory engagements sold, happier customers and differentiating value compared to all consulting companies, as Eficode is continuously measuring whether the goals are being reached and addressing areas where teams are struggling.
- **Customer value:** Customers get a lot of actionable information around license consumption and usage, GitHub runner costs and cost centers, and plugin security, for example. But most of the value is realized when sitting down with their Eficode advisor, looking at the numbers together and planning the next moves.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/AdvancedMetrics_GitHub3.png" alt="Example of advanced metrics with GitHub" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Gitlab4.png" alt="Example of advanced metrics with GitLab" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Jira3.png" alt="Example of advanced metrics with Jira" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_JSM2.png" alt="Example of advanced metrics with Jira Service Management" style="width: 100%;">
</div>

##### 7) Recommendations
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** April 2025 
- **Problem:** Recommendations from Eficode towards the customer go through many different channels, and many different persons. There is duplicate recommendations, information loss, and sometimes the customer gets lost as to what the right thing to focus on now is.
- **What we shipped:** A simple feature that enables standardization of the recommendations, with automations added to it so that the recommendations reach the right people (through email and Slack). Each recommendation features three parts: "What is the situation?", "What happens if it's not addressed?", and "What Eficode recommends", as well as impact and effort estimations.
- **Eficode business value:** This feature hasn’t seen strong adoption yet, but it is starting to pick up with more and more Eficode Advisory and Support being sold. The problem stated above is not yet solved with this. In the instances where the customers got the recommendations through the feature, they usually continued the discussion with their main point of contact at Eficode.
- **Customer value:** Thanks to having one single place to find the recommendations and each having a reasoning and a clear impact and effort, the decision-making is simplified, and there is less risk of fear of missing out (FOMO).

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Recommendations.png" alt="Recommendations" style="width: 100%;">
</div>

##### 8) Lens
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** November 2025 
- **Problem:** Advanced Metrics is focused on the present and doesn’t show trendlines over time. This makes it difficult to see the impact of AI adoption or Eficode's work over time, and to understand when changes happen and what triggers them.
- **What we shipped:** This is probably the feature I'm most proud of. With the core product trio (PM, design, and engineering), we realized that by defining the x-axis as a specific unit of time, we could have multiple graphs displayed at the same time, regardless of the tool or the metric on the y-axis. This enabled us to build Lens, where one can, for example, see the impact of GitHub Copilot adoption in software teams on the amount of Jira epics closed (so more value reaches end customers, in an ideal case), and moments later look at how many security issues / UX issues it introduced, visible through GitHub security findings or Atlassian Service Desk bugs.
- **Eficode business value:** The business potential of this feature is enormous. It is built to support most of Eficode's business (Consulting, License, Managed Services) and could bring a change to the whole consulting market, where customers expect such metrics to be in place to ensure impact. Unfortunately, the timing was a bit off, as Eficode is having a really large organization overhaul (ongoing still as of January 2026), and the organization didn’t have the bandwidth for me to run go-to-market activities with the Product Marketing Manager, so the reach stayed limited to my close network. The adoption of that close network has been fast and strong though, and it really landed when they presented it to their customers, leading to multiple new engagements for Eficode.
- **Customer value:** For the customer that enjoyed the feature, this is transformational. They now can directly see the impact of Eficode and their AI adoption (or any other transformation) over time. This led to quite a few “wow” moments with customers when they discovered their graphs.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Lens1.png" alt="Impact of GH Copilot on PR volume" style="width: 100%;">
  <img src="/assets/img/Journey/Lens2.png" alt="Impact of GH Copilot on the volume of work going through Jira" style="width: 100%;">
</div>

