Execution Steps:

Run : helm install project-name ./k8s-helm

Checks:

Run:
    kubectl get pods -o wide -l app=nginx
    kubectl get daemonset
    kubectl get statefulset


