# k8s-nginx
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm repo update
helm install my-release ingress-nginx/ingress-nginx -n <namespace>
# update svc change type from LoadBalancer to NodePort
