---
title: Allocate exclusive device
---

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: gcushare-pod-4
  namespace: kube-system
spec:
  terminationGracePeriodSeconds: 0
  containers:
    - name: pod-gcu-example3
      image: ubuntu:18.04
      imagePullPolicy: IfNotPresent
      command:
        - sleep
      args:
        - '100000'
      resources:
        limits:
          enflame.com/vgcu: 1
```