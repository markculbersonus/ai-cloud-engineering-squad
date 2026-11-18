# Case study: Azure VM quota troubleshooting

**Task:** Analyze a user-reported Azure VM deployment failure attributed to regional vCPU quota limits. No Azure resource modifications permitted.

**Routing:** Talos (Azure SRE) for investigation, Sevatar for independent review, Konrad for revision coordination.

**Evidence:** The assistant loaded team/routing/charter context, invoked Azure-related quota and best-practice tools, and attempted specialist handoffs. Several model choices were unavailable; some shell/documentation calls were denied due to missing interactive approval.

**Reviewer finding:** Sevatar initially returned **CHANGES REQUIRED**, identifying that the exact error was missing and both regional-total and VM-family remaining quota needed comparison with requested cores.

**Revision:** Konrad incorporated these corrections; Sevatar returned **APPROVED** on the revised handoff.

**Conclusion:** Quota exhaustion remained a hypothesis. Without the target region, VM SKU/family, requested vCPUs, and exact deployment error, no deployment-specific live comparison was possible. No Azure resources were modified.

**Portfolio significance:** Evidence of agent handoff and a feedback/review loop, not evidence of a successful Azure repair.
