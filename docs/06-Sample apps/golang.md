---
title: "Golang"
description: "This guide will walk you through the process of creating and deploying a Golang app on the Initializ Console."
---

## Getting Started

We provide a sample app using [**Golang**](https://github.com/initializ-templates/sample-golang) that you can deploy on App Platform. These steps will get this sample application running for you using App Platform.

### Requirements

- You need an Initializ account. If you don't already have one, you can sign up at [**signup**](https://console.initializ.ai/register).

- Also make sure to fork the [**sample-golang**](https://github.com/initializ-templates/sample-golang) repository to your GitHub account.

## Source Code Configuration

1. **Create an App**:

   - Click on the **Create App** button located on the top left of the dashboard.

   ![CreateApp](/assets/golang/source_code.png)

2. **Authorize Your GitHub Repo**:

   - Connect your GitHub repository by authorizing access.

3. **Provide App Name**:

   - During the creation process, provide a name for your app.

4. **Select GitHub Repositories**:

   - Choose the specific repositories from your GitHub account for this app, slect a branch and click on next

5. **Configure Environment Variables and Ports**:

   ![Environment](/assets/golang/config.png)

   - Set up necessary environment variables and configure port settings.

6. **Click on Next**:
   - Proceed to the next step in the creation process and verify the configurations.
     ![Environment](/assets/golang/review.png)

## Testing and Approval

1. **Test Approval**:

   - Before deploying to production, ensure your app passes necessary tests.

     ![Approval](/assets/golang/testapp.png)

2. **Production Approval**:

   - After successful testing, approve for deployment to the production environment.

   ![Approval](/assets/golang/prodapp.png)

## Deployment

1. **App Creation**:

   - Wait for a short amount of time as your app is being created.

   ![Deploy](/assets/golang/deployed.png)

2. **Deployment Completed**:
   - Once deployed, your app is accessible at the URL displayed on the app's **Overview** page.

## Verifying Deployment

1. **Verify Link**:

   - Check the URL provided on the app's **Overview** page to access your deployed app.

   ![Overview](/assets/golang/verified.png)

2. **Final Checks**:

   - Ensure all functionalities work as expected in the deployed app.

3. **Completion**:
   - Congratulations! Your Golang app is now successfully deployed on the Initializ Console.
