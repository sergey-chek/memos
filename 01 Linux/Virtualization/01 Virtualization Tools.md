#virtualization #virtual_machines #hypervisor

## Key Tools
**[KVM](https://www.linux-kvm.org/page/Main_Page)** "Kernel-based Virtual Machine" is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module, kvm-intel.ko or kvm-amd.ko. Using KVM, one can run multiple virtual machines with private virtualized hardware: a network card, disk, graphics adapter, etc.

**[QEMU](https://www.qemu.org/)** A generic and open source machine emulator and virtualizer.

**[libvirt](https://libvirt.org/)** is a toolkit and API to manage [virtualization platforms](https://libvirt.org/platforms.html). It is accessible from C, Python, Perl, Go and supports KVM, Hypervisor.framework, QEMU, Xen, Virtuozzo, VMWare ESX, LXC, BHyve and [more](https://libvirt.org/drivers.html)

## User/Client Tools
**[virsh](https://libvirt.org/manpages/virsh.html)** Command-line tools for communicating with libvirt.

**[virt-manager](https://virt-manager.org)** (Virtual Machine Manager). GUI to manage KVM, qemu/kvm, xen, and lxc. Contains a [VNC](https://en.wikipedia.org/wiki/Virtual_Network_Computing) and [SPICE](https://en.wikipedia.org/wiki/Simple_Protocol_for_Independent_Computing_Environments) client for direct graphical access to VMs. 

**[virt-install](https://linux.die.net/man/1/virt-install)** Helper tools for creating new VM guests (includes `virt-install` and `virt-clone`). Part of the `virt-manager` project.

**[virt-viewer](https://linux.die.net/man/1/virt-viewer)** UI for interacting with VMs via VNC/SPICE. Part of the `virt-manager` project.