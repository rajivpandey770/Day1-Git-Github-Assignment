Category: Cluster Management
Environment: K8s v1.23, On-prem bare metal, Systemd cgroups
Scenario Summary: Node drain stuck indefinitely due to unresponsive terminating pod.
What Happened: A pod with a custom finalizer never completed termination, blocking kubectl drain. Even after the pod was marked for deletion, the API server kept waiting because the finalizer wasn’t removed.