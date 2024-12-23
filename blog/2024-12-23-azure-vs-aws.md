---
slug: azure-vs-aws
title: Azure vs AWS - from my perspective
authors: trung
tags: [aws, azure, cloud, devops]
---

Compare AWS and Azure, from my short experience.

<!--truncate-->

## They are the same

In basically everything. You can convert any AWS architectures to the equivalence in Azure, and vice versa.

## How's Azure different?

**Good thing**: Azure eliminates the necessity of resource policy. Resource group is a neat way of grouping and separating environments/divisions in single Azure subscription. In AWS either you'll need organization structure with multiple accounts, or manually grouping resources by tag.

**Bad thing**: There're no certificate manager like ACM in Azure, and Azure Key Vault cert manager is a walking disaster. And, there're no default domain for Azure application gateway (unlike AWS ALB).
