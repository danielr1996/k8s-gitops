argocd app create apps \
    --dest-namespace argocd \
    --dest-server https://kubernetes.default.svc \
    --repo https://github.com/danielr1996/k8s-argo \
    --path apps  
argocd app sync apps  