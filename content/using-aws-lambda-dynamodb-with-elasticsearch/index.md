---
title: "Using AWS lambda, Dynamodb with Elasticsearch"
description: "Concept"
date: "2019-07-23T07:28:18.171Z"
categories: []
published: false
---

  

#### Concept

#### Goal 

  

-   AWS dynamodb is an awesome/ fast/cheap scalable No SQL database. However it lacks capabilities. like advanced search function (geospatial queries, data pagination etc ). Of course it can still be done using a mix of secondary index, composite keys and post processing, but at the end the code become quickly complicated. Consequently, I like to use the combination of dynamodb and search power of elastic search
-   What I am going to use here
