---
title: 'FA2: Fast, Accurate Autoscaling for Serving Deep Learning Inference with SLA Guarantees'
subtitle: 'IEEE Real-Time and Embedded Technology and Applications Symposium 2022'
date: '2022-01-01'
draft: false
publishDate: '2022-12-02T16:30:22.415750Z'
authors:
- Kamran Razavi
- Manisha Luthra
- Boris Koldehofe
- Max Mühlhäuser
- Lin Wang
publication_types:
- '1'
abstract: 'Deep learning (DL) inference has become an essential building block in modern intelligent applications. Due to the high computational intensity of DL, it is critical to scale DL inference serving systems in response to fluctuating workloads to achieve resource efficiency. Meanwhile, intelligent applications often require strict service level agreements (SLAs), which need to be guaranteed when the system is scaled. The problem is complex and has been tackled only in simple scenarios so far.This paper describes FA2, a fast and accurate autoscaler concept for DL inference serving systems. In contrast to related works, FA2 adopts a general, contrived two-phase approach. Specifically, it starts by capturing the autoscaling challenges in a comprehensive graph-based model. Then, FA2 applies targeted graph transformation and makes autoscaling decisions with an efficient algorithm based on dynamic programming. We implemented FA2 and built and evaluated a prototype. Compared with state-of-the-art autoscaling solutions, our experiments showed FA2 to achieve significant resource reduction (19% under CPUs and 25% under GPUs, on average) in combination with low SLA violations (less than 1.5%). FA2 performed close to the theoretical optimum, matching exactly the optimal decisions (with the least required resources) in 96.8% of all the cases in our evaluation.'
featured: false
publication: '*28th IEEE Real-Time and Embedded Technology and Applications Symposium*'
url_pdf: https://ieeexplore.ieee.org/document/9804606
doi: 10.1109/RTAS54340.2022.00020
---
