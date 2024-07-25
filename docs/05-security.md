---
title: "Security"
description: "This will guide to the security of the apps on  the Initializ Console."
sidebar_position: 5
---

# Security

## Health Monitor

- ## Scan Compliance

  A compliance scan is like a check-up for software code. It looks at the code to see if it follows all the rules and standards are met.

  Our platform will check compliance for all your applications under one roof and you can view it in a Gauge format. You don’t need any separate configurations to create this visualization. .

  ![Compliance_scan](/assets/Security/Compliance_scan.png)
  \*\* _Snippet of a compliance scan for 6 applications under one workspace_.

  Furthermore, you can organize these scans according to your workspace and environment of the applications.

  **Tip**💡
  **_A compliance scan is super useful. It gives a clear picture of how well the code meets the standards. This helps developers know what needs fixing or improving_**.

- ## CVE Chart

  A CVE (Common Vulnerabilities and Exposures) scan looks for weaknesses or holes that hackers could exploit to cause problems. These weaknesses are called vulnerabilities. The scan rates these vulnerabilities based on how serious they are, which helps the developers understand which ones need fixing urgently.

  Once you add your codebase and deploy your code, automatic scanning will start with each version change. You don’t need any separate configurations to create this visualization.

  ![CVE_Scan](/assets/Security/CVE_Scan.png)
  \*\* _Snippet of a CVE scan for 6 applications under one workspace for non-prod_.

  Furthermore, you can organize these scans according to your workspace and environment of the applications.

- ## Report

  Security report gives you the overall view of underlying problems that could harm your application.

  You can download SBOM/CVEs from the platform and fix it. Don’t worry about deploying again, because as soon as you commit changes, it will trigger automatically.

  ![scan_report](/assets/Security/scan_report.png)
  \*\* _Snippet of a scan report for 6 applications under one workspace for non-prod_.
