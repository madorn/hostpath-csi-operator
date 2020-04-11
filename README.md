# HostPath CSI Operator

An Ansible Operator based off the non-production hostpath CSI driver

About
-------
This is a non-production Operator based off the [HostPath example CSI driver](https://github.com/kubernetes-csi/csi-driver-host-path).

It was created to provide CSI driver authors with an easy way to build an Operator with [Operator-SDK](https://github.com/operator-framework/operator-sdk) and manage its lifecycle via [Operator Lifeycle Manager](https://github.com/operator-framework/operator-lifecycle-manager).

If you are a CSI driver author and have previously developed Helm Charts for your driver, check out the [Operator SDK's Helm Operator](https://github.com/operator-framework/operator-sdk/tree/master/doc/helm).

Requirements
------------

A Kubernetes 1.17 cluster.

**TODO**: conditionals based off Kubenetes versions to ensure proper CSI sidecars are deployed.

Example Playbook
----------------

This role is meant to be used in an Ansible Operator inside a Kubernetes cluster, so it may not work as expected in typical Ansible playbooks.

License
-------

BSD
