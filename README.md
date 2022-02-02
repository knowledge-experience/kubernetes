# kubernetes

- [Oficial website](https://kubernetes.io/)
- [Kubernetes docs](https://kubernetes.io/docs/home/)
- [What is kubernetes?](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)
- [Kubernetes components](https://kubernetes.io/docs/concepts/overview/components/)
- [Kubernetes objects](https://kubernetes.io/docs/concepts/overview/working-with-objects/kubernetes-objects/)
- [Workloads](https://kubernetes.io/docs/concepts/workloads/controllers/)

- [Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [Deploy App](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [Pods and nodes](https://kubernetes.io/docs/tutorials/kubernetes-basics/explore/explore-intro/)
- [Expose your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/)
    - [LoadBalancer](https://kubernetes.io/docs/tasks/access-application-cluster/create-external-load-balancer/)
    - [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
    - [Ingress Controllers](https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/)
      - [nginx](https://www.nginx.com/products/nginx-ingress-controller/)
- [Scale your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/scale/scale-intro/)
- [Autoscaling](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)
- [Update your app](https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/)

## Bônus:

- [Kubernetes cheatsheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
- [12 factor](https://12factor.net/pt_br/)
- [Namespaces](https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/)
- [Access control](https://kubernetes.io/docs/reference/access-authn-authz/)
- [Volumes](https://kubernetes.io/docs/concepts/storage/volumes/)
- SSL: Load balancer ou CertManager + LetsEncrypt
- [Dashboard](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)

## Bônus 2.0
- [Descomplicando kubernetes](https://github.com/badtuxx/DescomplicandoKubernetes/tree/main/pt)
- [Kubernetes course](https://github.com/wardviaene/kubernetes-course)

## Exemplo prático

Iremos utilizar os arquivos da pasta resources
- Apply deployment `kubectl apply -f deployment.yaml`
- Apply service `kubectl apply -f service.yaml`
- Scale deployment `kubectl scale --replicas=5 deployment app1`
- Apply ingress `kubectl apply -f service.yaml`
- Acessem a URL `db1.dflourusso.com.br/app1`
- Update deployment `kubectl edit deployment app1`