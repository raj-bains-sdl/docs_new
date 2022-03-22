---
title: "Product Feature Matrix"
linkTitle: "Product Feature Matrix"
weight: 2
description: >
  Prophecy versions with the features in each version
---

{{<alert>}} Prophecy has an Enterprise Trial using the Prophecy Databricks environment for a 14-day trial {{</alert>}}

Prophecy comes in two versions:

{{< table caption="Product Versions" class="table-borderless">}}
|                        |  Option                                                    | Standard                      | Enterprise                     |
|------------------------|------------------------------------------------------------|-------------------------------|--------------------------------|
| Spark Support          |   Databricks                                               | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Cloud EMR, Dataproc                                      | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
|                        |   On-Premise - Cloudera, Hortonworks, MapR                 | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
| Spark Development Gems |   Standard Spark (sources, targets, transforms, UDFs ... ) | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Delta Lake Gems (merge, scd, ...)                        | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Tests                                                    | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Prophecy Gem Packages (fixed format, ...)                | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
|                        |   User Defined Libraries (Gems, UDFs, UDAFs)               | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
| Scheduling             |   Databricks Jobs                                          | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Apache Airflow                                           | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
| Git                    |   Branches                                                 | <img src="/images/yes.png">   |  <img src="/images/yes.png">  |
|                        |   Forks                                                    | <img src="/images/no.png">    |  <img src="/images/yes.png">  |
| Deployment             |   SaaS (Prophecy VPC)                                      | <img src="/images/yes.png">   |  <img src="/images/no.png">    |
|                        |   Customer VPC                                             | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   On-Premise (for large Enterprise deployments)            | <img src="/images/no.png">    |  <img src="/images/yes.png">   |
| Catalog                |   Search                                                   | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
|                        |   Column-level Lineage                                     | <img src="/images/yes.png">   |  <img src="/images/yes.png">   |
{{</ table >}}
