---
title: "Transforming Your Data Lake: Implementing Slow Change Dimension with Synapse"
url: "https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/transforming-your-data-lake-implementing-slow-change-dimension/ba-p/3718996"
date: "2023-05-03"
author: "Liliam_C_Leme"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=azuresynapseanalyticsblog"
---
As organizations continue to collect and store large volumes of data in their data lakes, managing this data effectively becomes increasingly important. One key aspect of this is implementing Slow Change Dimension type 2, which allows organizations to track historical data by creating multiple records for a given natural key in the dimensional tables with separate surrogate keys and/or different version numbers. In this blog post we will address the following scenario: a customer wants to implement Slow Change Dimension type 2 on top of their data lake.
