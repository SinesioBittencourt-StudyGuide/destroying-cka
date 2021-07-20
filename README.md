# Destroying CKA

Collection of study notes and resources for preparing for [Certified Kubernetes Administrator](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/) Exam.

## Content

Organized accordingly to CKA Exam skill requirements.

- [Fundamentals](0.fundamentos.md) - Basic overall knowledge on concepts used by Kubernetes.
- [Storage - 10%](1.storage.md)

    1. [Understand storage classes, Persistent Volumes](https://github.com/justjhon/destroying-cka/blob/main/1.storage.md#1-understand-storage-classes-persistent-volumes)
    2. [Understand volume mode, access modes and reclaim policies for volumes](https://github.com/justjhon/destroying-cka/blob/main/1.storage.md#2-understand-volume-mode-access-modes-and-reclaim-policies-for-volumes)
    3. [Understand persistent volume claims primitive](https://github.com/justjhon/destroying-cka/blob/main/1.storage.md#3-understand-persistent-volume-claims-primitive)
    4. [Know how to configure applications with persistent storage](https://github.com/justjhon/destroying-cka/blob/main/1.storage.md#4-know-how-to-configure-applications-with-persistent-storage)

- [Troubleshooting - 30%](2.troubleshooting.md)

    1. [Evaluate cluster and node logging](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#1-evaluate-cluster-and-node-logging)
    2. [Understand how to monitor applications](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#2-understand-how-to-monitor-applications)
    3. [Manage container stdout & stderr logs](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#3-manage-container-stdout--stderr-logs)
    4. [Troubleshoot application failure](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#4-troubleshoot-application-failure)
    5. [Troubleshoot cluster component failure](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#5-troubleshoot-cluster-component-failure)
    6. [Troubleshoot networking](https://github.com/justjhon/destroying-cka/blob/main/2.troubleshooting.md#6-troubleshoot-networking)

- [Workloads & Scheduling - 15%](3.workloads_&_scheduling.md)

    1. [Understand deployments and how to perform rolling update and rollbacks](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#1-understand-deployments-and-how-to-perform-rolling-update-and-rollbacks)
    2. [Use ConfigMaps and Secrets to configure applications](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#2-use-configmaps-and-secrets-to-configure-applications)
    3. [Know how to scale applications](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#3-know-how-to-scale-applications)
    4. [Understand the primitives used to create robust, self-healing, application deployments](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#4-understand-the-primitives-used-to-create-robust-self--healing-application-deployments)
    5. [Understand how resource limits can affect Pod scheduling](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#5-understand-how-resource-limits-can-affect-pod-scheduling)
    6. [Awareness of manifest management and common templating tools](https://github.com/justjhon/destroying-cka/blob/main/3.workloads_%26_scheduling.md#6-awareness-of-manifest-management-and-common-templating-tools)

- [Cluster Architecture, Installation & Configuration - 25%](4.cluster_architecture_installation_&_configuration.md)

    1. [Manage role based access control (RBAC)](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#1-manage-role-based-access-control-rbac)
    2. [Use Kubeadm to install a basic cluster](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#2-use-kubeadm-to-install-a-basic-cluster)
    3. [Manage a highly-available Kubernetes cluster](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#3-manage-a-high-availability-kubernetes-cluster)
    4. [Provision underlying infrastructure to deploy a Kubernetes cluster](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#4-provision-underlying-infrastructure-to-deploy-a-kubernetes-cluster)
    5. [Perform a version upgrade on a Kubernetes cluster using Kubeadm](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#5-perform-a-version-upgrade-on-a-kubernetes-cluster-using-kubeadm)
    6. [Implement etcd backup and restore](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#6-implement-etcd-backup-and-restore)

- [Services & Networking - 20%](5.services_&_networking.md)

    1. [Understand host networking configuration on the cluster nodes](https://github.com/justjhon/destroying-cka/blob/main/4.cluster_architecture_installation_&_configuration.md#1-manage-role-based-access-control-rbac)
    2. [Understand connectivity between Pods](https://github.com/justjhon/destroying-cka/blob/main/5.services_%26_networking.md#2-understand-connectivity-between-pods)
    3. [Understand ClusterIP, NodePort, LoadBalancer service types and endpoints](https://github.com/justjhon/destroying-cka/blob/main/5.services_%26_networking.md#3-understand-clusterip-nodeport-loadbalancer-service-types-and-endpoints)
    4. [Know how to use Ingress controllers and Ingress resources](https://github.com/justjhon/destroying-cka/blob/main/5.services_%26_networking.md#4-know-how-to-use-ingress-controllers-and-ingress-resources)
    5. [Know how to configure and use CoreDNS](https://github.com/justjhon/destroying-cka/blob/main/5.services_%26_networking.md#5-know-how-to-configure-and-use-coredns)
    6. [Choose an appropriate container network interface plugin](https://github.com/justjhon/destroying-cka/blob/main/5.services_%26_networking.md#6-choose-an-appropriate-container-network-interface-plugin)

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


## Resources

[Rudi Martinsen CKA Notes](https://rudimartinsen.com/cka-resources/)
[Kubernetes by Example](https://www.kubernetesbyexample.com/)
[Killer Sh](https://killer.sh/)
[150 CKAD Questions](https://medium.com/bb-tutorials-and-thoughts/practice-enough-with-these-questions-for-the-ckad-exam-2f42d1228552)
[What is Kubernetes?](https://www.redhat.com/en/topics/containers/what-is-kubernetes)