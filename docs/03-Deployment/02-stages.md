---
title: "Stages"
description: "This will guide to the Stages of apps on the Initializ Console."
---

# Deployments

## Navigate deployment stages with Ease

- ## Clone & Package

  App deployment starts with our platform cloning your code. After that we package it into an image, hence removing the hassle of application containerization at an individual level.

  ![clone](/assets/deploy_stages/clone.png)

  \*\* _Snippet of application undergoing Clone stage_.
  ![clone_logs](/assets/deploy_stages/clone_logs.png)

  If an error occurs, you can always refer to the logs under each stage.
  ![package](/assets/deploy_stages/package.png)
  ![package_logs](/assets/deploy_stages/package_logs.png)

  To verify if your application has been successfully packaged, you can refer to the app_image_url and app_image_digest.

- ## Scanning Your Code

  SCA stage creates a SBOM for your application which will be further utilized to assess vulnerabilities. SCA stage and Scan stage together ensure security of your application.
  ![sca_logs](/assets/deploy_stages/sca_logs.png)
  SCA logs display SBOM in tabular format, just like any CLI does, hence reducing your work.

  After SCA stage application undergoes Scan stage, where vulnerability assessment takes place and list those according to criticality.

  ![scan](/assets/deploy_stages/scan.png)
  ![sca_logs](/assets/deploy_stages/sca_logs.png)

  Watch out!!! Some vulnerabilities stand in your way.

- ## Addressing Vulnerabilities

  Vulnerabilities often arise due to older and exploitable dependencies. Most of these are easily fixable.

  To check Highly critical vulnerabilities, glance over on the Security meter.
  [**Security Page**](../04-security.md)

  ![addr_vulnerability](/assets/deploy_stages/addr_vulnerability.png)
  \*\* _Snippet of Security metrics for a newly deployed application_.

  Right after you spot CVEs, you can download a report for detailed analysis. When you fix your code, don’t worry about deploying again.

  Our platform automatically deploys the changes after you commit your code to your source.

- ## Test & Deploy Approval

  An application is deployed in different environments for multiple checks. This comes with layered approvals.

  Similarly, initializ.ai also implements two staged approvals. One in Test Environment, another in Production.

  ![test_appr](/assets/deploy_stages/test_appr.png)

  Make sure you approve your application in different environments and add remarks for reference.
  ![adding_test_appr](/assets/deploy_stages/adding_test_app.png)

  After Test approval, application goes to Stage state, and awaits production deployment and approval.

  ![staging](/assets/deploy_stages/staging.png)
  \*\* _Snippet of an application successfully completing stage state._.
  ![succ_prod_app](/assets/deploy_stages/succ_prod_app.png)
  ![succ_deployment](/assets/deploy_stages/succ_deployment.png)

  At each environment, you will receive corresponding endpoint on the console, so if you have different pipelines working together, it can communicate.

  Like this at the end of production deployment stage, you will have an endpoint of your deployed application.

  Let’s check that out, shall we?

- ## Verifying Endpoint

  To check out your deployed application click on the URL flashing on the top of your console, under the application name

  ![verify_endp](/assets/deploy_stages/verify_endp.png)
  You’ll be redirected to the application page.
  ![verified_ep](/assets/deploy_stages/verified_ep.png)
  There, see how easy it was. Sail with initializ.ai.
