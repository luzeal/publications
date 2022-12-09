---
marp: true
theme: gaia
_class: lead
backgroundColor: #fff
paginate: true
backgroundImage: url(./images/foot4.jpg)
---

<!-- _paginate: -->

<style scoped> h2{ font-size: 700%; font-weight: }</style>
<style scoped> h3{ font-size: 300%; font-weight: }</style>

## Qube OS
### Un OS orientée sécurité

<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _paginate: -->

![bg 100%](./images/recursive.jpg)

---

<style scoped> { font-size: 350%; }</style>

### *Au menu*

1. *Introduction*
2. *La sécurité de l'info deux maux (sic)*
3. *Démonstration*

---

## Qubes OS?

Qube OS est un système d'exploitation ouvert et libre qui scelle l'information générée par chaque application dans des silos étanches.

* Ces silos étanches sont appelés **domaines** ou Qubes
* Ces domaines sont associés à **des niveaux de confiance**

Première version sortie en 2012. Créé par Joanna Rutkowska et Rafal Wojtczuk, du Invisible Things Lab, en Pologne.

Plus d'information: **https://www.qubes-os.org/**

---

## Quelques notions autours de la sécurité
- **Sécurité de l'information**: confidentialité, intégrité et disponibilité de l'information (CIA Triad)
- **Sécurité holistique**: sécurité physique, opérationnelle et informatique
- **Sécurité par l'obscurité**: *cacher pour protéger*
- **Sécurité par l'ouverture**: *soumettre à la lumière pour renforcer*
- **Sécurité par l'isolation**: *isoler pour préserver*

---

### Comparaison avec d'autres systèmes d'exploitation

<style scoped>table { font-size: 90%; }</style>

|                          | Windows NT et macOS | Windows NT (Hyper-V) |       QubeOS (Xen) |
| ------------------------ | ------------------: | -------------------: | -----------------: |
| Sécurité par l'obscurité |  :white_check_mark: |   :white_check_mark: |                :x: |
| Sécurité par l'ouverture |                 :x: |                  :x: | :white_check_mark: |
| Sécurité par l'isolation |                 :x: |   :white_check_mark: | :white_check_mark: |


---

<style scoped> { font-size: 500%; }</style>

Sécurité par l'ouverture +
Sécurité par l'isolation  =
QubeOS

---

![bg 70%](./images/qubes-trust-level-architecture.png)

---

<style scoped> h2{ font-size: 500%; font-weight: }</style>

## Demo time!

---

Acknowledgements:
* Diagram courtesy of the Qubes OS Project website (© 2022 The Qubes OS Project and others)