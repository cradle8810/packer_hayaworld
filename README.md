## Requirements

You need install vsphere module with this command:
```
packer plugins install github.com/hashicorp/vsphere
```

## Usage

```
packer build --var-file=./variables.json -var 'vcenter_server_password=PASSWORDHERE' ubuntu-22.04.json
```

## Appendix
* https://ubuntu.com/server/docs/install/autoinstall
