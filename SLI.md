Kubernetes : Scale - SLI/SLO  
========================================


[https://github.com/kubernetes/community/tree/master/sig-scalability](https://github.com/kubernetes/community/tree/master/sig-scalability)

[https://www.youtube.com/watch?v=UddabF9SE78](https://www.youtube.com/watch?v=UddabF9SE78)
  

![](attachments/1500402/1542552.png?height=250)

![](attachments/1500402/1542551.png?height=250)

https://www.youtube.com/watch?v=t_Ww6ELKl4Q

^ 11:05 Pod Density

^ 19:30 pod churn - 20 per sec

https://www.youtube.com/watch?v=CpD_ttrXqfs

^ 25:17 pod density

points to container runtime and kubelet as bottlenecks

References
==========

*   [https://docs.openshift.com/container-platform/4.1/scalability\_and\_performance/using-cluster-loader.html](https://docs.openshift.com/container-platform/4.1/scalability_and_performance/using-cluster-loader.html)
*   [https://docs.openshift.com/container-platform/4.1/scalability\_and\_performance/recommended-host-practices.html](https://docs.openshift.com/container-platform/4.1/scalability_and_performance/recommended-host-practices.html)
*   [https://github.com/kubernetes/community/blob/master/sig-scalability/slos/slos.md](https://github.com/kubernetes/community/blob/master/sig-scalability/slos/slos.md)
*   [https://github.com/kubernetes/community/blob/master/sig-scalability/slos/pod\_startup\_latency.md](https://github.com/kubernetes/community/blob/master/sig-scalability/slos/pod_startup_latency.md)
*   [https://github.com/kubernetes/community/blob/master/sig-scalability/slos/api\_call\_latency.md](https://github.com/kubernetes/community/blob/master/sig-scalability/slos/api_call_latency.md)
*   [https://github.com/kubernetes/community/blob/master/sig-scalability/configs-and-limits/thresholds.md](https://github.com/kubernetes/community/blob/master/sig-scalability/configs-and-limits/thresholds.md)  
    Get Red Hat to weigh in here ^
*   [http://perf-dash.k8s.io](http://perf-dash.k8s.io/)
*   [https://kubernetes.slack.com/archives/CEUR3HY5A/p1560410565024600](https://kubernetes.slack.com/archives/CEUR3HY5A/p1560410565024600)

Conclusion
==========

Kubernetes only publishes 2 SLOs today so that's where we should start.  Everything else is a work in progress.  If we want to support additional SLIs, we should get involved upstream.

*   API Call Latency - [https://github.com/kubernetes/community/blob/master/sig-scalability/slos/api\_call\_latency.md](https://github.com/kubernetes/community/blob/master/sig-scalability/slos/api_call_latency.md)
*   Pod Startup Latency - [https://github.com/kubernetes/community/blob/master/sig-scalability/slos/pod\_startup\_latency.md](https://github.com/kubernetes/community/blob/master/sig-scalability/slos/pod_startup_latency.md)
