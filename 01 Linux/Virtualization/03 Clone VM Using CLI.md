#virtualization #virtual_machines 

- `virt-clone` command is included in `virt-install` package.
- iso-images for VMs can be located in `/var/lib/libvirt/isos/`
- VM-images are located in `/var/lib/libvirt/images/*.qcow2`

```bash
virt-clone \
	--original original.vm.name \
	--name target.vm.name \
	--file /var/lib/libvirt/images/target-vm-name.qcow2

```

```
-o, --original ORIGINAL_GUEST
Name of the original guest to be cloned (as in Virtual Machine Manager). This  guest must be shut off.

-n, --name NAME
Name  of  the  new  guest virtual machine instance. This must be unique amongst all guests known to  the  hypervisor connection, including those not currently active.

-f, --file PATH
Path to the file, disk partition, or logical volume  to  use  as the backing store for the new guest's virtual disk. If the original  guest  has multiple disks, this parameter must be repeated multiple times, once per disk in the original virtual machine.
```