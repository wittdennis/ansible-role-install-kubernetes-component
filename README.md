# wittdennis.install_kubernetes_component

Ansible role to install kubernetes components

## Role Variables

```yaml
install_kubernetes_component_version: v1.30.3
install_kubernetes_component_kubectl: true
install_kubernetes_component_kubeadm: true
install_kubernetes_component_kubelet: true
```

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wittdennis.install_kubernetes_component }

## License

MIT
