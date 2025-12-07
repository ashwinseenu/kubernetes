This project demonstrates Deployment, Replicaset, Daemonset, Statefulset of Nginx, Splunk, Kafka, monitoring Tools by templating using helm charts with reusability.


Execution Steps:

Run : helm install project-name ./k8s-helm

Checks:

Run:

    kubectl get pods -o wide -l app=nginx

    kubectl get daemonset

    kubectl get statefulset


