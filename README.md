## Requirements

You need install vsphere module with this command:
```
packer plugins install github.com/hashicorp/vsphere
```

For proxmox, use Proxmox module.

```
packer plugins install github.com/hashicorp/proxmox v1.2.3
```

## Usage

For vSphere

```
packer build --var-file=./variables.json -var 'vcenter_server_password=PASSWORDHERE' ubuntu-22.04.json
```

For Proxmox

```
packer build --var-file=./variables.json -var 'proxmox_server_password=ROOTPASSWORDHERE' ubuntu-22.04.json
```

## Appendix
* https://ubuntu.com/server/docs/install/autoinstall

* https://github.com/hashicorp/packer-plugin-proxmox/issues/307#issuecomment-2887736543