---
title: 'Operator as a Service: Stateful Serverless Complex Event Processing'
date: '2020-01-01'
draft: false
publishDate: '2022-01-12T12:03:28.958601Z'
authors:
- Manisha Luthra
- Sebastian Hennig
- Kamran Razavi
- Lin Wang
- Boris Koldehofe
publication_types:
- '1'
abstract: 'Complex Event Processing (CEP) is a powerful paradigm for scalable data management that is employed in many real-world scenarios such as detecting credit card fraud in banks. The so-called complex events are expressed using a specification language that is typically implemented and executed on a specific runtime system. While the tight coupling of these two components has been regarded as the key for supporting CEP at high performance, such dependencies pose several inherent challenges as follows. (1) Application development atop a CEP system requires extensive knowledge of how the runtime system operates, which is typically highly complex in nature. (2) The specification language dependence requires the need of domain experts and further restricts and steepens the learning curve for application developers.In this paper, we propose CEPless, a scalable data management system that decouples the specification from the runtime system by building on the principles of serverless computing. CEPless provides "operator as a service" and offers flexibility by enabling the development of CEP application in any specification language while abstracting away the complexity of the CEP runtime system. As part of CEPless, we designed and evaluated novel mechanisms for in-memory processing and batching that enable the stateful processing of CEP operators even under high rates of ingested events. Our evaluation demonstrates that CEPless can be easily integrated into existing CEP systems like Apache Flink while attaining similar throughput under high scale of events (up to 100K events per second) and dynamic operator update in ~238 ms.'
featured: false
publication: '*IEEE BigData 2020*'
url_pdf: https://ieeexplore.ieee.org/document/9378142
doi: 10.1109/BigData50022.2020.9378142
url_code: https://luthramanisha.github.io/CEPless
tags:
- '"serverless computing"'
- '"complex event processing"'
- '"stream processing"'
---
