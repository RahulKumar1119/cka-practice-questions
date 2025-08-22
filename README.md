# cka-practice-questions

This repository contains 16 hands-on Kubernetes tasks designed to help candidates prepare for the Certified Kubernetes Administrator (CKA) exam.
Each question is mapped to the official CKA curriculum (v1.33) and covers the five major domains:

Cluster Architecture, Installation & Configuration (25%)

Workloads & Scheduling (15%)

Services & Networking (20%)

Storage (10%)

Troubleshooting (30%)

What’s Inside

✅ Q1–Q16: Practical CKA-style exam questions

✅ Step-by-step solutions & commands

✅ Covers tasks like:

Creating Deployments, Services, and Ingress

Configuring NetworkPolicies & HPAs

Managing Storage with PVCs & StorageClasses

Fixing broken clusters & troubleshooting pods/nodes

🔹 Who is this for?

CKA aspirants who want real exam-style practice

Kubernetes engineers revising core concepts hands-on

Anyone who wants to test and improve troubleshooting skills

📌 Questions (Q1–Q16)

| Q#  | Topic                                                                  | Domain                                 | K8s Docs                                                                                                                                                                         |
| --- | ---------------------------------------------------------------------- | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Q1  | Create a `busybox` pod with resource limits                            | Workloads & Scheduling                 | [Pods](https://kubernetes.io/docs/concepts/workloads/pods/)                                                                                                                      |
| Q2  | Create a `Deployment` and scale replicas                               | Workloads & Scheduling                 | [Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)                                                                                             |
| Q3  | Expose Deployment with `ClusterIP` Service                             | Services & Networking                  | [Services](https://kubernetes.io/docs/concepts/services-networking/service/)                                                                                                     |
| Q4  | Expose app with `NodePort` Service                                     | Services & Networking                  | [Service Types](https://kubernetes.io/docs/concepts/services-networking/service/#publishing-services-service-types)                                                              |
| Q5  | Configure `Ingress` for HTTP traffic                                   | Services & Networking                  | [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)                                                                                                      |
| Q6  | Create PersistentVolume & PVC                                          | Storage                                | [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)                                                                                            |
| Q7  | Attach PVC to Pod                                                      | Storage                                | [Persistent Volume Claims](https://kubernetes.io/docs/concepts/storage/persistent-volumes/#persistentvolumeclaims)                                                               |
| Q8  | Create & use a ConfigMap                                               | Workloads & Scheduling                 | [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)                                                                                                       |
| Q9  | Create & use a Secret                                                  | Workloads & Scheduling                 | [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)                                                                                                             |
| Q10 | Setup HorizontalPodAutoscaler (HPA)                                    | Workloads & Scheduling                 | [Horizontal Pod Autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)                                                                          |
| Q11 | Apply NetworkPolicy for restricted traffic                             | Services & Networking                  | [Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)                                                                                    |
| Q12 | Upgrade Kubernetes cluster with `kubeadm`                              | Cluster Architecture                   | [kubeadm Upgrade](https://kubernetes.io/docs/tasks/administer-cluster/kubeadm/kubeadm-upgrade/)                                                                                  |
| Q13 | Create `PriorityClass` and patch Deployment                            | Workloads & Scheduling                 | [Pod Priority](https://kubernetes.io/docs/concepts/scheduling-eviction/pod-priority-preemption/)                                                                                 |
| Q14 | Configure Resource Requests & Limits                                   | Workloads & Scheduling                 | [Resource Management](https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/)                                                                            |
| Q15 | Enable frontend ↔ backend communication with restrictive NetworkPolicy | Services & Networking                  | [Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)                                                                                    |
| Q16 | Fix broken single-node cluster with external etcd                      | Troubleshooting / Cluster Architecture | [Troubleshooting Clusters](https://kubernetes.io/docs/tasks/debug/debug-cluster/), [Operating etcd](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/) |
