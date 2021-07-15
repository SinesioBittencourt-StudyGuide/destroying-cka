# Destroying CKA

Collection of study notes and resources for preparing for [Certified Kubernetes Administrator](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/) Exam.

## Content

Organized accordingly to CKA Exam skill requirements.

- [Fundamentals](0.fundamentos.md) - Basic overall knowledge on concepts used by Kubernetes.
- [Storage - 10%](1.storage.md)

1. Understand storage classes, Persistent Volumes
2. Understand volume mode, access modes and reclaim policies for volumes
3. Understand persistent volume claims primitive
4. Know how to configure applications with persistent storage

- [Troubleshooting - 30%](2.troubleshooting.md)

1. Evaluate cluster and node logging
2. Understand how to monitor applications
3. Manage container stdout & stderr logs
4. Troubleshoot application failure
5. Troubleshoot cluster component failure
6. Troubleshoot networking

- [Workloads & Scheduling - 15%](3.workloads_&_scheduling.md)

1. Understand deployments and how to perform rolling update and rollbacks
2. Use ConfigMaps and Secrets to configure applications
3. Know how to scale applications
4. Understand the primitives used to create robust, self-healing, application deployments
5. Understand how resource limits can affect Pod scheduling
6. Awareness of manifest management and common templating tools

- [Cluster Architecture, Installation & Configuration - 25%](4.cluster_architecture_installation_&_configuration.md)

1. Manage role based access control (RBAC)
2. Use Kubeadm to install a basic cluster
3. Manage a highly-available Kubernetes cluster
4. Provision underlying infrastructure to deploy a Kubernetes cluster
5. Perform a version upgrade on a Kubernetes cluster using Kubeadm
6. Implement etcd backup and restore

- [Services & Networking - 20%](5.services_&_networking.md)

1. Understand host networking configuration on the cluster nodes
2. Understand connectivity between Pods
3. Understand ClusterIP, NodePort, LoadBalancer service types and endpoints
4. Know how to use Ingress controllers and Ingress resources
5. Know how to configure and use CoreDNS
6. Choose an appropriate container network interface plugin

## Tips and Considerations

1. Read the [Candidate Handbook](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook), it is a very important resource to understand all the nuances of the exam application, requirements and resources.

2. Applicant can use Kubernetes Documentation during the exam, so get familiarized with it.

3. The exam lasts 2 hours, so it is all about velocity and knowing where to found what, so practice a lot with exercises.

4. Matching topics with the documentation will help you to memorize where to find resources that you need during the exam.

5. Exam has 15 to 20 questions.

6. 6 clusters are used in the exam for problem solving.

7. You need to score 66% to pass the exam.

8. Every question on the exam, has its pontuation shown on the screen, so spend more time on questions that has a higher value.

9. One question does not relate with the other.

10. Every 3 months Kubernetes Version is updated, so it's important to review the official curriculum.

11. Focus on studying the most required topics on the exam.

12. Create alias for most used commands. E.g. alias k=kubectl
