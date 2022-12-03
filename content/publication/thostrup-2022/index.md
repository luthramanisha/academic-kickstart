---
title: Distributed GPU Joins on Fast RDMA-capable Networks
subtitle: 'Proceedings of the ACM SIGMOD/PODS International Conference
  on Management of Data (SIGMOD 2023)'
date: '2023-06-23'
draft: false
publishDate: '2022-12-02T16:30:22.075366Z'
authors:
- Lasse Thostrup
- Gloria Doci
- Nils Boeschen
- Manisha Luthra
- Carsten Binnig
publication_types:
- '1'
abstract: 'In this paper, we present a novel pipelined GPU join that accelerates the performance of distributed DBMSs by leveraging GPU resources on fast networks. A key insight is that we enable pipelined join execution by overlapping the network shuffling with the build and probe phases, thereby significantly reducing the GPU idle time. To demonstrate this, we propose novel algorithms for distributed pipelined GPU joins with RDMA and GPUDirect for both arbitrarily large probe- and build-side tables. In our evaluation, we show our pipelined distributed GPU join can reduce the overall runtime of a full query by up to 6× against a state-of-the-art CPU-only join.'
featured: false
publication: '*To appear in ACM SIGMOD 2023*'
---
