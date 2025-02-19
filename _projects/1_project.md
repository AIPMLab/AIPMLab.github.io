---
layout: page
title: Project 1
description: Federated learning for medical image classification (Served as PI)
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

### Project Background
This project focuses on the deployment of federated learning (FL) systems in healthcare domain. The main challenges are related to the **resource-costs** and the **data heterogeneity** existed in the hospitals and institutions (a.k.a., FL clients).

---

### Proposals
To solve these issues, we propose a novel feature attention module (FAM) as the communnication module for global aggregation, while freeze the deep models to save computation overhead. This FAM is a plug and play module that inserted after the deep model encoders. Furthermore, we introduced domain adaptation (DA) (i.e., local maximum mean discrepancies) to reduce the feature shifts among the clients. This adaptation is achieved by assuming there exist a public source domain data that can be used for feature adaptation.

### Results
The proposed approach demonstrated the superior performance compard to state-of-the-art methods. More details can be viewed in our publication: **FACMIC: Federated Adaptative CLIP Model for Medical Image Classification**.




{% endraw %}
