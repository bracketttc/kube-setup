# Kubernetes experimentation

Attempting to install Google's k8s on RHEL7.
Following [this guide][installing-kubeadm] as well as [this guide][calico-hard-way].

## Requirements

- Hashicorp Vagrant
- Ansible
- Internet access

## Instructions

- Fill in Red Hat username/password in [`roles/kube/tasks/main.yml`](./roles/kube/tasks/main.yml)
- Run `vagrant up`
- Experiment with Kubernetes

<!-- links -->
[installing-kubeadm]: https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/
[calico-hard-way]: https://docs.projectcalico.org/getting-started/kubernetes/hardway/
