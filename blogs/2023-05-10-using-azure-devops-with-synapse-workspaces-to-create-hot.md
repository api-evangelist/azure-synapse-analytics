---
title: "Using Azure DevOps with Synapse Workspaces to create hot fixes in production environments"
url: "https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/using-azure-devops-with-synapse-workspaces-to-create-hot-fixes/ba-p/3809631"
date: "2023-05-10"
author: "vysuopys"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=azuresynapseanalyticsblog"
---
Have you ever deployed a release to production only to find out a bug has escaped your testing process and now users are being severely impacted? In this post, I’ll discuss how to deploy a fix from your development Synapse Workspace into a production Synapse Workspace without adversely affecting ongoing development projects. This example uses Azure DevOps for CICD along with a Synapse extension for Azure DevOps: Synapse Workspace Deployment .
