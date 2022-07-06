---
marp: true
theme: gaia
_class: lead
backgroundColor: #fff
paginate: true
backgroundImage: url(../../Projects/publications/images/foot4.jpg)
---

<!-- _paginate: -->

# Machine-level virtualization in 2022

**![width:700px](../../Projects/publications/images/fractal-veggie.jpg) <!-- Setting width to 700px -->**

## *Is there still a use for it?*

---

<style scoped> { font-size: 350%; }</style>

### *Table of Contents*

1. **Virtualization(s) in a nutshell**
2. **Assessment of machine-level virtualization**
3. **The future of virtualization**

---

<style scoped> { font-size: 650%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

1. **Virtualization(s) in a nutshell**

![bg 100%](../../Project/../Projects/publications/images/recursive.jpg)

---

## Multiple types of virtualization

* **Machine-level virtualization** allows the creation of virtual machines, which are software-based computers made of virtual hardware and software.  
  * Examples: QEMU/KVM; Xen; Hyper-V; VMware ESXi; etc 
* **Operating-system-level virtualization** allows the creation of containers, which are self-contained and isolated environments that are leveraging their host operating system's capabilities to function.
  * Examples: LXC and Docker on Linux; FreeBSD's Jails; Solaris Containers; etc 

---

![bg 100%](../../Project/../Projects/publications/images/nested-virtualization-2.png)

<style scoped> { font-size: 650%; }</style>

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

---

## **Virtual machines versus containers**

<style scoped>table { font-size: 80%; }</style>

|                                                 |   Virtual machines |         Containers |
| ----------------------------------------------- | -----------------: | -----------------: |
| Support for various operating systems           | :white_check_mark: | :white_check_mark: |
| Strong security boundaries between environments | :white_check_mark: | :white_check_mark: |
| Native support for GUI-driven environments      | :white_check_mark: | :white_check_mark: |
| Lightweight                                     | :white_check_mark: | :white_check_mark: |
| Portable                                        | :white_check_mark: | :white_check_mark: |
| Native orchestration                            | :white_check_mark: | :white_check_mark: |

---

![width:800px](../../Project/../Projects/publications/images/virtualization-in-a-nutshell.png)


---

## Open-source machine-level virtualization

* On common Linux distributions, virtualization is often driven by the KVM/QEMU or the Xen/QEMU duo.

* With this software stack deployed on virtualization-friendly hardware, an operating system running on a virtual machine can be become almost indistinguishable from an operating system running on a physical computer.

---

## Timeline from the 2000s

* 2003: Xen
* 2005?: QEMU
* 2005: First generation of hardware-assisted virtualization (x86)
* 2007: KVM
* ~2009: Second generation of hardware-assisted virtualization (x86, IOMMU-based)
* 2015: Commodification of hardware-assisted virtualization (x86)

---

2. **Assessment of machine-level virtualization**

---

## Use cases #1

* Run multiple guest operating systems concurrently
  * Plug in two screens, two sets of keyboards, and two mice to the same PC and spawn two machines to do graphic-intensive tasks such as gaming or 3D modeling. No need to buy another computer, just split the one you already have.

---

## Use cases #2

* Painlessly move to new hardware
  * When virtualized, your operating system is just a file on Phyllome OS' disk. You can move and restore it on another computer, provided that the targeted host runs Phyllome OS.

---

## Use cases #3

* Make your current hardware last longer
  * Most recent versions of modern operating systems require recent hardware to function, and may not work on otherwise perfectly functioning hardware. By providing modern virtual hardware, Phyllome OS allows users to receive operating system updates, even though their underlying may not officially be supported.

---

3. **The future of virtualization**

---

*New technologies such as Kata Containers or Firecraker, which powers Lambda functions. are blurring the distinction between the two. Git to manage containers ? CrossVM; 

Moving away from QEMU to adopt more specialized. Google is using project vanadium. MicroVM ; Fly.io is using microvm. Cloud Hypervisor

---

 <!-- virtio-gpu device with 3D acceleration -->

    <video>
      <model type='virtio' heads='1' primary='yes'>
        <acceleration accel3d='yes'/>
      </model>
      <address type='pci' domain='0x0000' bus='0x00' slot='0x01' function='0x0'/>
    </video>


