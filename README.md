# Azure For Developers Workshop

The Azure cloud is huge (so that’s why they call it the cloud!) and the vast service catalog may appear daunting at first. It doesn’t have to be!

- Learn the browser-based UI of the Azure portal
- Continue the journey with the built-in, ready-to-run cloud shell
- Explore various ways to deploy web apps written in any language, on any platform, from virtual machines and containers to serverless technologies
- Add intelligence to your apps using Microsoft Cognitive Services
- Protect your apps by applying Azure’s built-in security features
- Diagnose problems and apply automated machine learning analysis with Application Insights
- Connect your apps with messaging services, load files into cloud storage and discover managed databases for SQL and NoSQL scenarios
- Tie everything together in a continuous delivery pipeline with Azure DevOps projects

## Agenda

### 1 - Intro to Azure ([Jeremy Likness](https://twitter.com/jeremylikness))

* Getting started: signup/credits
* Computing types
* Docs
* Portal
* Cloud shell

[View Module](./presentation/01-Intro.pptx)

### 2 - Azure Storage (Jeremy)

* Storage accounts
* Blobs
* Files

[View Module](./presentation/02-Intro.pptx)

### 3 - Hosting in Azure ([Anthony Chu](https://twitter.com/@anthonychu))

* Hosting options
* Deploy to App Service
* App Insights

### 4 - Azure Serverless (Anthony)

* Intro to serverless
* Overview of serverless in Azure
* Lab

### 5 - DevOps (Anthony)

* Walkthrough an example DevOps pipeline
    * Doesn't need to be a hands-on lab

### [6 - Cognitive Services](/labs/06-cognitive_services.md) ([Brandon Minnick](https://twitter.com/TheCodeTraveler))

In this section we will add Sentiment Analysis to the reviews for our Hotels 360 app. For this, we will be leveraging the [Text Analytics API hosted by Cognitive Services](https://azure.microsoft.com/services/cognitive-services/text-analytics/?WT.mc_id=TechBash-github-bramin)

### [7 - Azure Security](/labs/07-azure_security.md) ([Brandon Minnick](https://twitter.com/TheCodeTraveler))

In this section we will learn how to leverage the security tools available in Azure.

We'll start by learning more about [Azure Security Center](https://azure.microsoft.com/services/security-center/?WT.mc_id=TechBash-github-bramin) and how to leverage its recommendations to add extra layers of security to our app service.

Next, we'll move the secrets out our code and into [Azure Key Vault](https://azure.microsoft.com/services/key-vault/?WT.mc_id=TechBash-github-bramin). Key Vault leverages HSMs (hardware security modules) to help us avoid storing secrets in our source code.

### [8 - Azure and Mobile]((/labs/08-azure_and_mobile.md)) (Brandon)

* High level overview of how .NET developers can leverage Xamarin

### Conclusion (Team)
