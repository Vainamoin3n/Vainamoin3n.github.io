---
# the default layout is 'page'
icon: fas fa-briefcase
order: 1
---

## Introduction
{: data-toc-skip='' .mt-4 .mb-0 }
Hey, I'm Clément Louarn — a Product Manager with 5+ years of experience. This is my portfolio.
Or rather: it's what my teams and I actually shipped. After all the ideas, experiments, trials, and prototypes that never make it to production, a portfolio can feel a bit thin (survivor bias?). Still, the shipped work tells a real story: what we were trying to solve, why we made certain bets, and what changed as a result.
If you landed on this page, I hope it gives you a clearer sense of who I am and how I think. And if you think I could be a good fit for your team, I'd be happy to connect.

### How I work
{: data-toc-skip='' .mt-4 .mb-0 }
- **Discovery-first:** hypothesis-driven discovery to reduce value/usability/feasibility/business risk.
- **Explain the why:** clear rationale for bets and trade-offs.
- **Build with teams:** tight collaboration with engineering/design on most aspects of discovery and delivery.
- **Customer close:** regular customer conversations; pilot-customer practice.
- **Story-driven:** I use customer and colleague stories to align people, make trade-offs tangible, and keep the team grounded in reality.
- **Ways of working:** I continuously improve how I and the team works. There is always something to move to the next level.
- **Team multiplier:** I mentor teammates and colleagues toward product thinking (from “what/how to build” to “why” and “for whom”).
- **Relationship-driven:** I build trust across functions and seniority levels, which makes alignment and execution easier.
- **Commercialization aware:** partner with product marketing and sales on GTM elements.



---
## Content table:
{: data-toc-skip='' .mt-4 .mb-0 }
- [Eficode Connectors](#product-eficode-connectors)
- [Eficode Journey](#product-eficode-journey)
- [Wiztivi Gaming Content Management System](#product-wiztivi-gaming-content-management-system)

---

## Eficode
{: data-toc-skip='' .mt-4 .mb-0 }
- **Company:** Eficode is a B2B software and DevOps services company, providing expert consulting and managed services around DevOps, platform engineering, cloud, and enterprise service management, with strong partnerships and license management for major tool vendors (e.g., Atlassian, GitHub, GitLab, AWS, Microsoft).
- **Role:** Product Manager
- **Team:** 1 Product Manager, 1 Engineering Team Lead, 4 Software Engineers, 1 Product Designer, 1 Product Marketeer (shared)

---
### Product: Eficode Connectors

- **Users:** Eficode customers, Eficode employees
- **Time period:** November 2024 to now

#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
Eficode Connectors are a set of plugins deployed in their respective tool vendors' cloud marketplaces. Their purpose, combined with Eficode's cloud architecture, is to capture metrics from customers' tool environments.
Thanks to the metrics gathered, Eficode can perform analyses for multiple use cases. The main use is found in combination with [Eficode Journey](#product-eficode-journey) to analyze the customer's platform engineering, IT and software engineering practices with their toolset and, with that information at hand, advise and support them in addressing discrepancies and helping the organization reach its goals. You'll find its use mostly in [Advanced Metrics](#3-advanced-metrics) and [Lens](#1-lens).
A second use is to give back the information to customers and the industry, in the form of reports on the state of DevOps, platform engineering and AI adoption in companies.
As of today, there are three connectors deployed: (1) Atlassian Cloud (Jira, Jira Service Management, and Confluence), (2) Atlassian Cloud Bitbucket, and (3) GitHub/GitHub Copilot (available for both Cloud and Data Center). Two more are in progress: GitLab (Data Center) and Azure. Many more are planned on the roadmap to support the Eficode customer base.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Helped multiple organizations get more value out of their toolset.
- Led Eficode to new engagements with existing and new customers.
- Reinforced Eficode's relationships with its partners, especially with GitHub and Microsoft.
- Changed the way Eficode advises its customers towards a more tailored approach.

#### Customer value (Shared)
{: data-toc-skip='' .mt-4 .mb-0 }
Customers get a secure, vendor-native way to unlock cross-tool analytics without exposing intellectual property or personal data. Through Eficode Journey, they gain visibility into how their toolchain is used, where bottlenecks and risks are building up, and how initiatives (AI adoption, migrations, or process changes) impact outcomes over time. Customers reap most of the benefits when sitting with an Eficode advisor, who helps translate signals into concrete actions. The connectors are built to be complementary to each other, each covering at least one aspect of modern tool stacks: project management, software development pipelines, cloud orchestration, and more.

#### Capabilities built over time 
{: data-toc-skip='' .mt-4 .mb-0 }

##### 1) Eficode Connector for Jira Cloud, Confluence Cloud and Jira Service Management Cloud (JSM)
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** March 2025
- **Problem:** When an Eficode customer moves to Atlassian Cloud, Eficode loses the ability to extract analytics from the environment and, as a result, is impaired in its ability to advise.
- **What we shipped:** An Atlassian Plugin, living in the Atlassian marketplace, that gathers data from the customer environment to Eficode in a secure way, without compromising intellectual property (IP) or personal data (PII).
- **Eficode business value:** Analytics on Atlassian tools become possible, for a single organization as well as at scale for studying the market.
- **Connector focus:** Enables visibility over work throughput, operational load, and service-management hygiene, so that teams can target process bottlenecks and support effectiveness with evidence.

**Link:** <https://marketplace.atlassian.com/apps/1231800/eficode-connector-for-jira-and-confluence>

##### 2) Eficode Connector for GitHub and GitHub Copilot (Cloud and Data Center)
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** June 2025
- **Problem:** As organizations moved to GitHub Copilot, many wondered whether employees actually used it, what they used it for, and whether it affected the organization's bottom line. This is what we intended to solve.
- **What we shipped:** The GitHub plugin captures data about the customers' software pipelines without looking at the content of these pipelines. It also captures information about GitHub Copilot usage at the enterprise and organization levels. Again, we wanted to keep any IP or PII in the customer environment and focus on the "metadata". The plugin was launched both for Cloud and Data Center, as organizations were very active in both.
- **Eficode business value:** Analytics on GitHub and GitHub Copilot, for single organization purpose as well as at scale for studying the market. In an age where everyone is moving towards AI-assisted software development, this is extremely valuable information.
- **Connector focus:** Adds pipeline metrics, security signals (Dependabot and GitHub Advanced Security), and GitHub Copilot adoption signals so customers can evaluate whether AI changes outcomes, not just activity.

**Link (Cloud):** <https://github.com/marketplace/eficode-root-connector>
**Link (Data Center):** Not public


##### 3) Eficode Connector for Bitbucket Cloud
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** October 2025
- **Problem:** Multiple customers were using GitHub Copilot with Atlassian Bitbucket, so this became our next target to measure the impact of AI and transformation in customer organizations.
- **What we shipped:** The Bitbucket plugin captures information about customer pipelines in Bitbucket Cloud, with the intent to produce the same insights as the GitHub Connector.
- **Eficode business value:** Since Eficode has traditionally been a really strong Atlassian partner, a significant portion of the customer base has been users of Bitbucket. Offering the metrics we did for GitHub for these customers enabled better support and advisory from Eficode.
- **Connector focus:** Enables Copilot + Bitbucket cross-tool views for Atlassian-heavy organizations, enabling them to see the impact of GitHub Copilot on their software organization.

**Link:** <https://marketplace.atlassian.com/apps/2310380027/eficode-connector-for-bitbucket>

---

### Product: Eficode Journey
- **Users:** Eficode customers, Eficode employees
- **Time period:** October 2022 to now

#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
Eficode Journey is the Eficode customer portal. It was built from scratch by Eficode R&D, where I was the Product Manager.
It enables transparent access to Eficode's activity, easier reporting, and analytics on the state of software engineering, IT, and platform engineering in the customer's environment.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Reporting went from hours or days per month per customer to minutes per month per customer
- Human error in reporting dropped to a minimum
- Customer trust in the Managed Services organization increased significantly after Eficode Journey was introduced.
- Enabled a new product line, Eficode Advisory & Support, likely to become a main offering for Eficode in 2026.
- 50–60% of Managed Services customer organizations were monthly active.

#### Capabilities built over time (reverse order)
{: data-toc-skip='' .mt-4 .mb-0 }
##### 1) Lens
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** November 2025 
- **Problem:** [Advanced Metrics](#3-advanced-metrics) is focused on the present and doesn't show trendlines over time. This makes it difficult to see the impact of AI adoption or Eficode's work over time, and to understand when changes happen and what triggers them.
- **What we shipped:** This is probably the feature I'm most proud of. With the core product trio (PM, design, and engineering), we realized that by defining the x-axis as a specific unit of time, we could have multiple graphs displayed at the same time, regardless of the tool or the metric on the y-axis. This enabled us to build Lens, where one can, for example, see the impact of GitHub Copilot adoption in software teams on the amount of Jira epics closed (so more value reaches end customers, in an ideal case), and moments later look at how many security issues / UX issues it introduced, visible through GitHub security findings or Atlassian Service Desk bugs.
- **Eficode business value:** The business potential of this feature is enormous. It is built to support most of Eficode's business (Consulting, License, Managed Services) and could bring a change to the whole consulting market, where customers expect such metrics to be in place to ensure impact. Unfortunately, the timing was a bit off, as Eficode is having a really large organization overhaul (ongoing still as of January 2026), and the organization didn't have the bandwidth for me to run go-to-market activities with the Product Marketing Manager, so the reach stayed limited to my close network. The adoption of that close network has been fast and strong though, and it really landed when they presented it to their customers, leading to multiple new engagements for Eficode.
- **Customer value:** For the customer that enjoyed the feature, this is transformational. They now can directly see the impact of Eficode and their AI adoption (or any other transformation) over time. This led to quite a few “wow” moments with customers when they discovered their graphs.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Lens1.png" alt="Impact of GH Copilot on PR volume" style="width: 100%;">
  <img src="/assets/img/Journey/Lens2.png" alt="Impact of GH Copilot on the volume of work going through Jira" style="width: 100%;">
</div>

##### 2) Recommendations
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** April 2025 
- **Problem:** Recommendations from Eficode towards the customer go through many different channels, and many different persons. There is duplicate recommendations, information loss, and sometimes the customer gets lost as to what the right thing to focus on now is.
- **What we shipped:** A simple feature that enables standardization of the recommendations, with automations added to it so that the recommendations reach the right people (through email and Slack). Each recommendation features three parts: "What is the situation?", "What happens if it's not addressed?", and "What Eficode recommends", as well as impact and effort estimations.
- **Eficode business value:** This feature hasn't seen strong adoption yet, but it is starting to pick up with more and more Eficode Advisory and Support being sold. The problem stated above is not yet solved with this. In the instances where the customers got the recommendations through the feature, they usually continued the discussion with their main point of contact at Eficode.
- **Customer value:** Thanks to having one single place to find the recommendations and each having a reasoning and a clear impact and effort, the decision-making is simplified, and there is less risk of fear of missing out (FOMO).

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Recommendations.png" alt="Recommendations" style="width: 100%;">
</div>

##### 3) Advanced metrics
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** December 2024 but the majority of the UI only appeared in September 2025
- **Problem:** As customers move to tool vendors' cloud offerings, Eficode loses its visibility on the customer tool health, and this impairs its ability to act as a trusted advisor.
- **What we shipped:** (Requires Eficode Connector) Advanced Metrics enable us to see, at a glance, the current state of an organization's tool adoption and usage. Using their expertise, Eficode experts can spot discrepancies and work with the customer to address those.
- **Eficode business value:** This is a true game changer for Eficode. It now has access to the same metrics across its customer base (for those who have the connectors) and can provide very precise, context-relevant advisory and support for its customers. And there is direct feedback on the impact through the metrics. This leads to more advisory engagements sold, happier customers and differentiating value compared to all consulting companies, as Eficode is continuously measuring whether the goals are being reached and addressing areas where teams are struggling.
- **Customer value:** Customers get a lot of actionable information around license consumption and usage, GitHub runner costs and cost centers, and plugin security, for example. But most of the value is realized when sitting down with their Eficode advisor, looking at the numbers together and planning the next moves.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/AdvancedMetrics_GitHub3.png" alt="Example of advanced metrics with GitHub" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Gitlab4.png" alt="Example of advanced metrics with GitLab" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_Jira3.png" alt="Example of advanced metrics with Jira" style="width: 100%;">
  <img src="/assets/img/Journey/AdvancedMetrics_JSM2.png" alt="Example of advanced metrics with Jira Service Management" style="width: 100%;">
</div>

##### 4) Dashboard
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** June 2024
- **Problem:** Eficode ROOT, the flagship of Eficode Managed Services, lacked a visual interface. Eficode Journey also had no landing page and it was difficult to direct customers to where action was needed.
- **What we shipped:** The dashboard was built as a central place to guide the user (customer or internal) to where their action is required. It went through many iterations and would still need more but currently it's good enough.
- **Eficode business value:** For the first time, both internal and external users could see the total Eficode ROOT coverage at once without going to the contract. The displaying of important information to the customer also helped increase adoption of Journey and centralize information sharing in Eficode Journey.
- **Customer value:** Less time spent in the portal as now they could know at a glance where new info was available and where their attention was needed. Enabled acting on important information that was missed before because it was under a menu they did not visit.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Dashboard.png" alt="Dashboard" style="width: 100%;">
</div>

##### 5) Billing page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** September 2023
- **Problem:** Every Service Manager reported work logs and billing details differently. There was an intense rush from every Service Manager at the start of the month to complete billing. No easy way to cover for a colleague during billing.
- **What we shipped:** Built a few-click billing report, consistent across all Service Managers, with additional data to enable checks (including automated checks) for issues. We extended the feature multiple times to add a yearly view, a current month estimate, and more improvements for both customers and Service Managers.
- **Eficode business value:** First feature that really impacted the Monthly Active Users (MAU), a requirement to add more features. Drove the adoption of Journey widely across Eficode Managed Services customers. Service Managers' stress levels dropped significantly during the billing period thanks to this feature. They also could finally cover for each other. Significantly reduced human errors thanks to automation leading to higher customer trust.
- **Customer value:** Enabled the same quality report, whether you are a small, medium or large customer. Enabled full transparency on the work done, up to the tasks done for a ticket and how long they took. Enabled checking progress during the current month to optimize budget usage. Enabled easier budget calculations thanks to the yearly view. 

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/Billing1.png" alt="Main report for billing" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport1.png" alt="Monthly report part 1" style="width: 100%;">
  <img src="/assets/img/Journey/BillingReport2.png" alt="Monthly report part 2" style="width: 100%;">
</div>

  
##### 6) Status page
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** Some of the “tool down” issues reported by customers were happening on their network and both sides wasted time investigating.
- **What we shipped:** Built on the same tool as the uptime SLA, there is now a live Status page showing whether the tool is working from inside the customer's network, based on our uptime monitoring system. We also added planned outages as a reminder when downtime is expected.
- **Eficode business value:** Low investment feature with fairly low usage. It saved us time in trying to debug issues on the customer network side, which was the original goal.
- **Customer value:** An easy first check when employees report a tool behaving unexpectedly before deciding whether a ticket to Eficode is warranted.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/StatusPage1.png" alt="Main status page" style="width: 100%;">
  <img src="/assets/img/Journey/StatusPage2.png" alt="Incidents events" style="width: 100%;">
</div>

##### 7) Uptime SLA
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

  
##### 8) Tickets SLA
{: data-toc-skip='' .mt-4 .mb-0 }
- **Introduced:** Spring 2023
- **Problem:** No systematic way to report the SLAs on tickets leading to time-consuming operations and mistakes, or simply being skipped.
- **What we shipped:** Service Managers can now do the reports in two clicks, and the portal automatically shares them with the customer and emails them once the report is approved by the Service Manager.
- **Eficode business value:** The effort dropped to almost null, reports became systematic across the whole customer base and mistakes were easily found and fixed.
- **Customer value:** Thorough, credible monthly reporting on how Eficode met the contract's ticket SLA.

<div style="display: flex; gap: 1rem; margin-bottom: 1.5rem;">
  <img src="/assets/img/Journey/TicketSLA.png" alt="SLA report" style="width: 100%;">
  <img src="/assets/img/Journey/TicketSLAReport1.png" alt="SLA report details" style="width: 100%;">
</div>

---
## Wiztivi Gaming
{: data-toc-skip='' .mt-4 .mb-0 }
- **Company:** Wiztivi Gaming (B2B2C) is the cloud gaming organization behind Streamava, a white-label, multi-screen cloud gaming solution designed for telecom and service providers. Its roots trace back to long-running “gaming-on-demand” deployments (SFR since 2010, Orange since 2012). Wiztivi's cloud gaming capability was reinforced through the acquisition of G-cluster Europe (2016).
- **Roles:** Product Manager and Project Manager, Customer success manager, Backend Team lead and Backend engineer.
- **Team:** Varied by project—from 2 to 10 engineers plus QA, Scrum Masters, and IT

### Product: Wiztivi Gaming Content Management System
- **Users:** Partner marketing team, Wiztivi Gaming employees
- **Time period:** October 2021 to May 2022
- **Team:** 1 Product/Project Manager, 1 Scrum Master, 1 QA Engineer, ~10 engineers

#### Summary
{: data-toc-skip='' .mt-4 .mb-0 }
The Wiztivi Gaming Content Management System (CMS) is the delivery backbone that powers the content displayed in the cloud gaming portal.
It drives the interface through which players discover and launch games, and it is designed to deliver highly personalized content reliably under sustained high-traffic conditions typical of large-scale consumer platforms.

#### Problem
{: data-toc-skip='' .mt-4 .mb-0 }
The content of the portal was originally fairly static, delivered the same across the whole customer base for performance optimization reasons. 
This caused issues because any partner-led marketing campaign (at least weekly) was forcing the portal team to build and deploy new packages for every change. This was too slow and too cumbersome for everyone involved.

#### What we shipped
{: data-toc-skip='' .mt-4 .mb-0 }
A highly scalable, microservices-based content management system, configured by partners themselves, that could update the portal experience for everyone with the click of a button.

#### Outcomes
{: data-toc-skip='' .mt-4 .mb-0 }
- Made all portal content fully dynamic: all the UI is now entirely defined in the CMS, including menus, games, images, videos and text.
- Enabled significantly more partner-led marketing campaigns.
- Enabled A/B testing of portal content.
- Enabled highly personalized content delivery per player.
- Did not degrade user experience during the transition, which was a key success criterion.