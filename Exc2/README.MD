# Exc2

Лог Mimicube в файле [logs-from-kube-controller-manager-in-kube-controller-manager-minikube.log](./logs-from-kube-controller-manager-in-kube-controller-manager-minikube.log). 
См. строки:
```
I1121 11:07:42.664435       1 horizontal.go:886] "Successfully rescaled" logger="horizontal-pod-autoscaler-controller" HPA="default/scaletestapp-hpa" currentReplicas=2 desiredReplicas=3 reason="memory resource utilization (percentage of request) above target"
```

На всякий случай скриншоты в папке [images](./images)

Файлы для Minicube:
- [deployment.yml](./deployment.yaml)
- [service.yml](./service.yml)
- [hpa.yml](./hpa.yml)