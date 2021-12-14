Calculating the Cost of Downtime
========
Software vendors and analysts put the cost of downtime in the many thousands of dollars per minute on average.

Those numbers can be scary indeed; for example, Gartner quotes $5,400 per minuteas the cost borne by a medium to large-sized retailer.

Your company, however, is most likely not identical to the “typical” company on which the numbers are based. In fact, the cost of an outage can vary widely depending on a variety of factors specific to your organization.

In this article, we explain how you can calculate the cost of an outage for your particular organization. My goal is not to convince you that outages don’t actually cost that much – they certainly can, as you’ll see – but instead to help IT teams and managers determine the actual cost of an outage instead of relying on general calculations that are based on arbitrary circumstances.

Why calculate the per-minute cost?
====
Engineering, DevOps and SRE teams that feel they are underfunded are challenged to justify the value of critical technology services. They must be able to demonstrate to their business teams a return on investment.  Being able to calculate he per-minute cost for outages in an organization creates a compelling case in raw numbers for why certain systems need to be maintained, and how financial investment is required.

It is not enough to know a single number for the entire company  unless, of course, you are a small shop with only one application. Ideally, every service, whether or not it’s customer facing, should have at least a rough estimate on what it costs the organization per minute when it isn’t operational.

Calculating the per-minute cost
====
The average per-minute cost of an outage is not that complicated to calculate, but it does require a view outside of a pre-technology lens. The formula is:

Outage Cost = Potential Revenue + Lost Productivity Costs + Recovery Costs

Let’s go through the three key variables needed to calculate the outage cost.

Potential revenue is the top line number before any deductions for overhead, such as  inventory costs. This should be based on typical weekly or monthly revenue. It gives a reliable number that can be used regardless of the time of day of an outage.  If the service is only available a few hours per day or a few days per week, however, potential revenue figures should be calculated and tiered to reflect typical in-service periods.

The next factor is lost productivity costs, which are associated with normal operations that are idle, with nothing to do as a result of the outage. For example,  the contact center staff when the phone system is down, or inventory pickers when the order system is down, or the 100 nodes running on AWS when the application crashes.

The third factor is all the costs associated with recovering the service. In some organizations these costs are  minimized if their infrastructure and staffing levels are such that people are already working at 2 a.m. in the operations center and extra capacity is available for this exact purpose. Other recovery costs, however, could include replacement parts, consultants, overtime hours, and even discretionary items like mileage for drives to offsite storage facilities.

There is a potential for a fourth factor which is related to brand reputation and customer goodwill. Unless customer satisfaction metrics are in place, this can be difficult to quantify and translated into terms that  stand up to the scrutiny of the finance department.

An example calculation would be for a small SaaS firm that does $5,000,000 per year in sales.

    Potential Revenue:

$5,000,000 / 365 days / 24 hours / 60 minutes = $9.51

    Lost Productivity Costs:

50 D4s v4 Azure hosts (@ $0.4813 per hour) / 60 minutes = $0.40

4 Azure SQL Server instances (@ $2.5824 per hour) / 60 minutes = $0.17

10 Contact Center agents (@ $15/hour) / 60 minutes = $2.50

    Recovery Costs:

Azure DevOps consultant ($200 per hour) / 60 minutes = $3.33

Total per minute: $15.91

Conclusion
====
In this article we intentionally used a small firm as an example in order to show that every minute counts during an outage, and it does not take long to justify the cost of tools that will reduce the mean time to recovery. Those tools include centralized alerting (every minute in the example pays for a team member’s one-month subscription on AlertOps), incident management, and intelligent monitoring solutions, which can also detect trends before an outage impacts anyone.

Everyone in an organization has the same ultimate goal: to spend the organization’s money as wisely as possible to ensure a good customer experience through stable and feature-rich service offerings. Knowing the per-minute cost of a service outage is a valuable universal tool to assist with organizational planning and allocation of resources to achieve that ultimate goal.


source:
====
https://alertops.com/cost-of-downtime/

Read more:
====

https://alertops.com/noc-dashboard-examples/
https://alertops.com/major-outage-black-friday/
https://alertops.com/prediction-ai-itsm/
https://alertops.com/msp-cyber-attack/
https://alertops.com/msp-tools/
https://alertops.com/it-service-metrics/
https://alertops.com/five-more-reasons/
https://alertops.com/opsgenie-alternative/
https://alertops.com/msp-security-incident-response-steps/
https://alertops.com/five-things-business-continuity-management/
https://alertops.com/on-call-support/
https://alertops.com/devops-ci-cd/
https://alertops.com/on-call-management/
https://alertops.com/covid-remote-team/
https://alertops.com/improve-critical-incident-management/
https://alertops.com/devops-barriers/
https://alertops.com/devops-periodic-table/
https://alertops.com/alertops-integration-with-amazon-web-service-cloud-watch/
https://alertops.com/alertops-and-appdynamics-integration/
https://alertops.com/catchpoint-poor-web-performance-blog/
https://alertops.com/alertops-and-icinga-integration/
https://alertops.com/alertops-and-jira-integration/
https://alertops.com/alertops-and-librato-integration/
https://alertops.com/alertops-and-server-density-integration/
https://alertops.com/alertops-announces-new-coo/
https://alertops.com/alertops-announces-playbook-automation-focusing-on-critical-enterprise-needs-in-fast-growing-incident-response-market/
https://alertops.com/alertops-monitorama/
https://alertops.com/alertops-announces-connectwise-manage-integration/
https://alertops.com/alertops-automation/
https://alertops.com/alertops-expert-guidance/
https://alertops.com/alertops-flexibility/
https://alertops.com/alertops-and-apteligent-integration/
https://alertops.com/think-youre-cut-out-for-hipchat-integration/
https://alertops.com/why-we-love-slack-integration-and-you-should-too/
https://alertops.com/alertops-microsoft-azure-integration/
https://alertops.com/alertops-pingdom-integration/
https://alertops.com/pagerduty-comparison-alert-management/
https://alertops.com/pagerduty-comparison-analytics/
https://alertops.com/pagerduty-comparison-incidents/
https://alertops.com/pagerduty-comparison-alert-templates/
https://alertops.com/pagerduty-comparison-incident-management-workflow/
https://alertops.com/pagerduty-comparison-incident-api/
https://alertops.com/pagerduty-sla-incident-management/
https://alertops.com/pagerduty-comparison-flexibility/
https://alertops.com/pagerduty-comparison-itil-mttr/
https://alertops.com/alertops-paging-for-enterprise/
https://alertops.com/covid-19-business-continuity-alerting-plan/
https://alertops.com/alertops-service-management-for-enterprise/
https://alertops.com/alertops-software-appoints/
https://alertops.com/alertops-unveils-heartbeat-monitoring/
https://alertops.com/application-performance-monitoring/
https://alertops.com/best-practices-incident-resolution/
https://alertops.com/major-incident-management-best-practices/
https://alertops.com/on-call-rotation/
https://alertops.com/devops-team/
https://alertops.com/best-practices-high-performing-teams/
https://alertops.com/cost-of-downtime/
https://alertops.com/alertops-paging-feature/
https://alertops.com/collaboration-key/
https://alertops.com/covid-pandemic-business-continuity/
https://alertops.com/major-critical-incidents/
https://alertops.com/devops-automation/
https://alertops.com/devops-vs-agile/
https://alertops.com/reduce-downtime-digital-retail/
https://alertops.com/do-you-need-different-slas-for-each-customer/
https://alertops.com/msp-backup/
https://alertops.com/noc-data-center/
https://alertops.com/team-management/
https://alertops.com/gdpr-devops-team/
https://alertops.com/alertops-and-service-now-integration/
https://alertops.com/standardized-incident-response-process/
https://alertops.com/alertops-and-uptime-robot-integration/
https://alertops.com/msps-cloud-services/
https://alertops.com/alert-fatigue-teams/
https://alertops.com/continuous-delivery-impacts-devops/
https://alertops.com/outage-cost/
https://alertops.com/no-code-integrations/
https://alertops.com/on-call-schedule/
https://alertops.com/choose-incident-management-tool/
https://alertops.com/communicate-customers-outage/
https://alertops.com/create-incident-response-playbook/
https://alertops.com/building-management-system/
https://alertops.com/how-will-you-notify-your-customers-when-a-hipaa-data-breach-occurs/
https://alertops.com/proactive-vs-reactive-teams/
https://alertops.com/do-you-need-to-notify-your-customers-when-personal-information-is-leaked-due-to-a-data-breach-2/
https://alertops.com/do-your-strategic-partners-know-when-you-have-a-critical-outage/
https://alertops.com/replace-opsgenie-connectwise-manage/
https://alertops.com/reach-the-right-person/
https://alertops.com/devops-roadmap/
https://alertops.com/improve-itops-collaboration-and-reduce-mttr-with-splunk/
https://alertops.com/do-you-need-to-notify-your-customers-when-personal-information-is-leaked-due-to-a-data-breach/
https://alertops.com/incident-communication-business-partners/
https://alertops.com/incident-management-lifecycle-essentials/
https://alertops.com/incident-management-metrics/
https://alertops.com/incident-management-process/
https://alertops.com/incident-post-mortem/
https://alertops.com/major-incident-response-communications-plan/
https://alertops.com/incident-response-quality-quantity/
https://alertops.com/alertops-and-prtg-integration/
https://alertops.com/incident-management-schedule/
https://alertops.com/itnation/
https://alertops.com/it-process-automation-for-managed-service-providers/
https://alertops.com/implement-it-service-alerting/
https://alertops.com/check-itsm-article-rick-leopoldi/
https://alertops.com/alertops-and-copperegg-integration/
https://alertops.com/how-do-you-notify-customers-when-there-is-a-data-security-breach/
https://alertops.com/alertops-and-solarwinds-integration/
https://alertops.com/incident-management-predictions-2018/
https://alertops.com/msp-automation/
https://alertops.com/live-inbound-call-routing/
https://alertops.com/managed-service-provider/
https://alertops.com/modern-itsm-solutions-creativity-incident-response/
https://alertops.com/modern-it-flexibility-in-incident-response/
https://alertops.com/msp-security/
https://alertops.com/mttd-vs-mttf-vs-mtbf-vs-mttr/
https://alertops.com/noc-best-practices/
https://alertops.com/no-code-for-developers/
https://alertops.com/noc-vs-soc/
https://alertops.com/outage-or-breach/
https://alertops.com/best-pagerduty-alternative/
https://alertops.com/alertops-and-errorception-integration/
https://alertops.com/discover-how-powerful-the-new-relic-integration-is/
https://alertops.com/catchpoint-rage-and-lessons-from-outages/
https://alertops.com/alertops-and-netcrunch-integration/
https://alertops.com/alertops-and-nodeping-integration/
https://alertops.com/spiceworks-our-spiciest-integration/
https://alertops.com/red-canary-says-43-lack-readiness-to-notify-customers-of-a-security-breach/
https://alertops.com/alertops-runscope-integration/
https://alertops.com/stakeholder-communications-plan/
https://alertops.com/noc-team-engineers/
https://alertops.com/eliminate-alert-fatigue/
https://alertops.com/budget-technical-debt-reduction/
https://alertops.com/downtime-costs/
https://alertops.com/live-inbound-call-routing-2/
https://alertops.com/alertops-team-management-for-enterprises/
https://alertops.com/alertops-better-than-pagerduty-2/
https://alertops.com/alertops-better-than-pagerduty-10-2/
https://alertops.com/alertops-better-than-pagerduty-3/
https://alertops.com/alertops-better-than-pagerduty-4/
https://alertops.com/alertops-better-than-pagerduty-5/
https://alertops.com/alertops-better-than-pagerduty-6/
https://alertops.com/alertops-better-than-pagerduty-7/
https://alertops.com/alertops-better-than-pagerduty-8/
https://alertops.com/alertops-better-than-pagerduty-9/
https://alertops.com/network-operations-center/
https://alertops.com/blameless-post-mortems/
https://alertops.com/what-is-devops/
https://alertops.com/internet-of-things/
https://alertops.com/infrastructure-management/
https://alertops.com/it-monitoring/
https://alertops.com/on-call/
https://alertops.com/it-operations-management/
https://alertops.com/itil-incident-management/
https://alertops.com/mttr/
https://alertops.com/proactive-incident-management/
https://alertops.com/why-alertops-best-pagerduty-alternative/
https://alertops.com/alertops-workflows-3/
https://alertops.com/itsm/
https://alertops.com/benefits-incident-management-software-retailers/
https://alertops.com/alertops-slas/
https://alertops.com/incident-management-software/
https://alertops.com/do-you-need-to-meet-sla-targets/
https://alertops.com/alertops-integration-features/
https://alertops.com/black-friday-win/
