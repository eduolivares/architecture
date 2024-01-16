# OpenStack K8S Operators Architectures

This repository may be used with to create validated
architectures ([VAs](examples/va)), represented as CRs for
[openstack-k8s-operators](https://github.com/openstack-k8s-operators).
It may also be used to create deployed topologies
([DTs](examples/dt)) which should only be used for testing.

## Requirements

The templating provided here requires [kustomize](https://kustomize.io/) version 5.0.1 or higher.

## Validated Architectures

The following VAs are available.

- [Hyperconverged OpenStack and Ceph](examples/va/hci/)
- [Network Functions Virtualization with SRIOV](examples/va/nfv/sriov/)
