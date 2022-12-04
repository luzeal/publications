---
marp: true
theme: gaia
_class: lead
backgroundColor: #fff
paginate: true
backgroundImage: url(/publications/presentations/images/foot4.jpg)
---

<!-- _paginate: -->

# Machine-level virtualization in 2022

**![width:700px](/publications/presentations/images/fractal-veggie.jpg) <!-- Setting width to 700px -->**

## *Is there still a use for it?*

---

<style scoped> { font-size: 350%; }</style>

### *Table of Contents*

1. *Virtualization(s) in a nutshell*
2. *Use cases for machine-level virtualization*
3. *The future of virtualization.*

---

<style scoped> { font-size: 900%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

**Virtualization(s) in a nutshell**

![bg 100%](/publications/presentations/images/recursive.jpg)

---

## Types of virtualization

* **Machine-level virtualization** allows the creation of virtual machines, which are software-based computers made of virtual hardware and software
  * Examples: QEMU/KVM; Xen; Hyper-V; VMware ESXi; etc
* **Operating-system-level virtualization** allows the creation of containers, which are self-contained and isolated environments that are leveraging their host operating system's capabilities to function
  * Examples: LXC and Docker on Linux; FreeBSD's Jails; Solaris Containers; etc.

---

## Virtual machines versus containers

<style scoped>table { font-size: 80%; }</style>

|                                                 |   Virtual machines |         Containers |
| ----------------------------------------------- | -----------------: | -----------------: |
| Support for various operating systems           | :white_check_mark: |                :x: |
| Strong security boundaries between environments | :white_check_mark: |                :x: |
| Native support for GUI-driven environments      | :white_check_mark: |                :x: |
| Lightweight                                     |                :x: | :white_check_mark: |
| Portable                                        |                :x: | :white_check_mark: |
| Native orchestration                            |                :x: | :white_check_mark: |

---

## Timeline: open-source machine-level virtualization

* 2003: Xen
* 2005?: QEMU
* 2005: First generation of hardware-assisted virtualization (x86)
* 2007: KVM
* ~2009: Second generation of hardware-assisted virtualization (x86, IOMMU-based)
* 2015: Commodification of hardware-assisted virtualization (x86).

---

<style scoped> { font-size: 900%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

**Use case for machine-level virtualization**

![bg 100%](/publications/presentations/images/recursive.jpg)

---

## Use case #1:

* **Running multiple operating systems concurrently**
  * Plug in two screens, two sets of keyboards, and two mice to the same PC and spawn two machines to do graphic-intensive tasks such as gaming or 3D modeling
  * No need to buy another computer, just split the one you already have!

---

![bg 100%](/publications/presentations/images/nested-virtualization-2.png)

<style scoped> { font-size: 650%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

---

<style scoped> { font-size: 170%; }</style>

## Use case #2

* **Painlessly move to new hardware**
  * When virtualized, your operating system is just a file on your physical disk
  * You can move and restore your entire system on any other virtualization-friendly computer.

![bg width:700px right:60%](/publications/presentations/images/virtualization-in-a-nutshell.png)

---

## Use case #3

* **Make your current hardware last longer**
  * Most recent versions of modern operating systems require recent hardware to function, and may not work on otherwise perfectly functioning hardware
  * By providing modern virtual hardware, desktop oriented machine-level virtualization  allows users to receive operating system updates, even though their underlying silicon-based hardware may not officially be supported.

---

## Use case #4

* **Define everything in code**
  * A virtual machine is more flexible than a silicon-based computer, as it is made out of code
  * Just as with other software, your imagination is the only limit, not the expensive hardware you may or may not possess.


---

*Need a new graphics card for your virtual machine? Here is one for you*

```
<devices>
  <video>
    <model type='virtio' heads='1' primary="yes">
      <acceleration accel3d='yes'/>
    </model>
    <address type="pci" domain="0x0000" bus="0x00" slot="0x01" function="0x0"/>
  </video>
</devices>
```

* *How to define a virtual machine*: https://libvirt.org/formatdomain.html

---

<style scoped> { font-size: 950%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

**The future of virtualization**

![bg 100%](/publications/presentations/images/recursive.jpg)

---

## Towards hybridization: the rise of container-like virtual machines

* New technologies such as Kata Containers or Firecracker are blurring the distinction between virtual machines and containers
  * Fly.io, which allows for the easy distribution of applications around the world, is using Firecracker in production.
  * [AWS Lambda](https://aws.amazon.com/lambda/) functions are also leveraging Firecracker.

*After all, it might be possible to have the best of both worlds*...

---

## That's all folks: thank you for your attention!

Let me know if you have any questions

* Lukas Greve
* :envelope: please@refre.ch


*Made with :heart: and free software. [Hack](https://github.com/luzeal/publications/blob/master/virtualization.md) this presentation now!*
