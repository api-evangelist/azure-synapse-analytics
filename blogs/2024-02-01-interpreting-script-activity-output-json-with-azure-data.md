---
title: "Interpreting Script activity output json with Azure Data Factory\\Synapse analytics"
url: "https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/interpreting-script-activity-output-json-with-azure-data-factory/ba-p/4030594"
date: "2024-02-01"
author: "Subashri_Vasu"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=azuresynapseanalyticsblog"
---
Script activity in Azure Data Factory\ Synapse analytics is very helpful to run queries against data sources mentioned here in this document. When we use two or more queries in the script activity, it is important to understand the output json of script activity to write expressions based on the output in the subsequent activities. Consider the below Pipeline design: We have two select queries as follows in script activity, and each of which will give a resultSet.
