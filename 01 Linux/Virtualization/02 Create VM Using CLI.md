#virtualization #virtual_machines 

```bash
virt-install \
  --name ubuntu1804 \
  --ram 2048 \
  --disk path=/var/lib/libvirt/images/u19.qcow2,size=8 \
  --vcpus 2 \
  --os-type linux \
  --os-variant generic \
  --console pty,target_type=serial \
  --cdrom /var/lib/libvirt/isos/ubuntu-18.04.4-live-server-amd64.iso
```