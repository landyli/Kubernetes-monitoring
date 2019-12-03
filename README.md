# Kubernetes-monitoring
Prometheus+Granfana
### 由于prometheus属于第三方的解决方案，原生的k8s系统并不能对Prometheus的自定义指标进行解析，就需要借助于k8s-prometheus-adapter将这些指标数据查询接口转换为标准的Kubernetes自定义指标
![prom1](https://github.com/landyli/Kubernetes-monitoring/blob/master/diagrams/prom1.png)
![k8s-hpa](https://github.com/landyli/Kubernetes-monitoring/blob/master/diagrams/k8s-hpa.png)
![k8s-hpa-ms](https://github.com/landyli/Kubernetes-monitoring/blob/master/diagrams/k8s-hpa-ms.png)
