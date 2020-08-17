# GitHub Readme + WebTrends

To best understand which topics are popular and which subjects are trending in our developer communities, we can leverage [Web Trends](https://www.webtrends.com).

This is an automated tool created using [Azure Functions](https://docs.microsoft.com/azure/azure-functions/?WT.mc_id=githubreadmewebtrends-github-bramin) that double checks each Readme to ensure every repository is leveraging [Web Trends](https://www.webtrends.com).

[Web Trends](https://www.webtrends.com) does not collect any Personally Identifiable Information and cannot be traced back to any individual user.

## Architecture

![](https://user-images.githubusercontent.com/13558917/89959435-40dc4480-dbf1-11ea-8c30-a4811fe819e9.png)

## QA 

How do I opt-in to the tool? (Prerequisite: You must be a Microsoft employee)
- Add a `yml` file to the [Cloud Developer Advocates GitHub repository](https://github.com/MicrosoftDocs/cloud-developer-advocates/tree/live/advocates) 
- This also adds you to the [Cloud Advacates Webpage](https://developer.microsoft.com/advocates/?WT.mc_id=githubreadmewebtrends-github-bramin)

How do I opt-out from the tool? 
- Remove your `yml` file from the [Cloud Developer Advocates GitHub repository](https://github.com/MicrosoftDocs/cloud-developer-advocates/tree/live/advocates) 
