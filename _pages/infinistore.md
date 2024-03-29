---
title: "Yue Cheng: Harnessing Serverless Functions to Build Highly Elastic Cloud Storage Infrastructure"
layout: textlay
excerpt: "InfiniStore Project"
sitemap: false
permalink: /infinistore/
---

# CAREER: Harnessing Serverless Functions to Build Highly Elastic Cloud Storage Infrastructure

Crucial data-intensive applications such as big data analytics,
artificial intelligence, and scientific computing exhibit highly
dynamic and heterogeneous data access patterns. These applications
require a large data storage system that is fast, elastic,
cost-effective, and easy-to-use. Unfortunately, current cloud storage
offerings are unable to satisfy all of these requirements: big data
analytics applications can run up to 500X slower when they run as a
cloud-native application using a cloud object store; provisioning
more cloud storage resources does not solve the performance problem
and storage over-provisioning leads to millions of dollars of extra
cost. This project rethinks the design and implementation of
next-generation, cloud-native storage infrastructures via a new
approach. This approach is enabled by a novel take on the serverless
computing paradigm -- serverless functions are elastic and truly
pay-per-use, making them a fast and inexpensive storage medium. This
project aims to build InfiniStore, a new cloud storage system, which
elastically scales in response to constantly changing data access
patterns by orchestrating the collective memory of serverless
functions. Following an end-to-end, stacked approach, this project
will develop an elastic and inexpensive memory store using serverless
functions, techniques that provide strong consistency guarantees for
data replicated in serverless functions, fault tolerance mechanisms
to maximize the data availability in highly unreliable serverless
environments, and a scalable serverless file metadata service to
support file semantics.

This project has the potential to redefine cloud storage pricing
models -- InfiniStore enables memory-store-level pay-per-access that
lets cloud users pay for the data they access. This project will
enable, in a broad range of disciplines, the development of new,
stateful, serverless applications that have not been previously
possible. All artifacts will be open source to support the use and
development both in academia and industry. This project has an
integrated educational plan, which also harnesses serverless
computing but uses it to develop a new serverless notebook cloud
service, called InfiniCloud, for interdisciplinary education.
InfiniCloud will allow educators and students to write and run serial
or parallel Python programs at any scale, without needing to manage
servers or clusters. Moreover, this project will use InfiniStore and
InfiniCloud as a basis for various educational activities including
curriculum development, diversity building, undergraduate engagement,
and workshops.

This project is funded by an [NSF CAREER Award #2045680](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2045680).


# Related Publications

*FaaSNet: Scalable and Fast Provisioning of Custom Serverless Container Runtimes at Alibaba Cloud Function Compute*<br/>
Ao Wang, Shuai Chang, Huangshi Tian, Hongqi Wang, Haoran Yang, Huiba Li, Rui Du, Yue Cheng<br/>
[Paper]({{ site.url }}{{ site.baseurl }}/docs/atc21-faasnet.pdf),
[Talk](https://www.usenix.org/conference/atc21/presentation/wang-ao),
[Src & Dataset](https://github.com/mason-leap-lab/FaaSNet).

