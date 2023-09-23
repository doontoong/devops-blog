---
title: Scaling My Kubernetes Deployment
date: 2019-02-02
tags: ["kubernetes", "code"]
---

Scaling my Kubernetes deployment

<!--more-->

```sh
    $ kubectl scale deployments/kubernetes-bootcamp --replicas=4
```

Now, check whether it is scaled up:
```sh
    $ kubectl get pods

    $ kubectl get pods - o wide
```
