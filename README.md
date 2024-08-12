# libvirt_as_code
automatically creates vms, installs libvirt, updates vault, signs ssh keys, creates passwords and facts, provisiones machines using cloudinit.

## Requirements:
***install:***
   ```bash
   § ansible-galaxy collection install community.general community.ansible-vault jm1.libvirt community.libvirt ji_podhead.host_prototypes ji_podhead.libvirt_as_code
   ```