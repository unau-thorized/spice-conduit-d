# spice-conduit-d

> [!IMPORTANT]
> **Archived — part of [Charon](https://github.com/unau-thorized/Charon-ClientSideMultimedia)**, a proof of concept (2020–2021) for client-side multimedia playback over SPICE. The concept was tested and worked. This repository contains the guest-side Windows service. See the Charon README for architecture, security & risk assessment, and possible improvements.

> [!CAUTION]
> **Use entirely at your own risk.** Experimental, unmaintained code provided "AS IS", without warranty of any kind and without support. It has known security weaknesses and is not suitable for production. The author shall not be liable for any claim, damage, or other liability arising from its use. See the [full disclaimer](https://github.com/unau-thorized/Charon-ClientSideMultimedia#disclaimer).

This software is a prototype not suitable for production.

The purpose of this software is to implement the 'Conduit' concept in the VM side (see wiki https://github.com/720k/virt-viewer/wiki ). 

spice-conduit-d windows service redirect data to system port \\.\global\io.bplayer.data.0 to \\.\pipe\io.bplayer.data.0 

Context: Inside Windows virtual machine connected with Spice protocol to KVM/QEMU ( https://libvirt.org/drvqemu.html ) .


Building:
-  project built by QtCreator, QT framework https://www.qt.io/

Dependencies:
- QtService ( https://github.com/Skycoder42/QtService )

  

License:
- [MIT](LICENSE)
