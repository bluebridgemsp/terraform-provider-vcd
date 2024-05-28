* Fix [Issue #1248](https://github.com/vmware/terraform-provider-vcd/issues/1248) that prevents CSE Kubernetes clusters from being upgraded to an OVA with higher Kubernetes version but same TKG version, and to an OVA with a higher patch version of Kubernetes [GH-1247] 
* Fix [Issue #1248](https://github.com/vmware/terraform-provider-vcd/issues/1248) that prevents CSE Kubernetes clusters from being upgraded to TKG v2.5.0 with Kubernetes v1.26.11 as it performed an invalid upgrade of CoreDNS [GH-1247]
* Fix [Issue #1252](https://github.com/vmware/terraform-provider-vcd/issues/1248) that prevents reading the SSH Public Key from provisioned CSE Kubernetes clusters [GH-1247]