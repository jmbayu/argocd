https://medium.com/devopsturkiye/deploy-kube-prometheus-stack-the-correct-way-using-argocd-444d846cd643

Workaround from...:-

https://www.frakkingsweet.com/argocd-and-kube-prometheus-stack/


kubectl delete -f https://raw.githubusercontent.com/prometheus-operator/prometheus-operator/main/example/prometheus-operator-crd/monitoring.coreos.com_prometheuses.yaml

then

kubectl create -f https://raw.githubusercontent.com/prometheus-operator/prometheus-operator/main/example/prometheus-operator-crd/monitoring.coreos.com_prometheuses.yaml


