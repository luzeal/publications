# <p class="fragment highlight-red">La matériel</p> 
<p class="fragment highlight"> Nouvelle frontière du libre?</p>

<!-- .slide: data-transition="zoom" -->

Note:

- There is also a speaker view, with notes - press '`s`'
- Press '`?`' with focus on the presentation for shortcuts
- <em>You can use html when necessary</em>
- Share the 'Present' URL with anyone you like!

---

Pad collaboratif:
https://mensuel.framapad.org/p/libreetvous

---

## L'âge d'or des logiciels libres


Constat n°1 : 
<!-- .element: class="fragment fade-up" -->



```
Les logiciels libres sont la règle plutôt que l'exception ```
<!-- .element: class="fragment fade-up" -->

---

### Quatre domaines à fortes croissance

|*Apprentissage automatique*|*Informatique d'infrastructure*| *Informatique embarquée* | *Chaîne de bloc*
|:-:|:--:| -:|
|Tensorflow (Google)|Xen (AWS; OVH) KVM (GCE)|Linux (Android)| Bitcoin | 
|Caffe2 (Facebook) | Kubernetes (Google, Microsoft)| Busybox | Ethereum |

---

### Microsoft <3 cancer

>Linux is a cancer
<!-- .element: class="fragment fade-up" -->
--

Steve Ballmer (2001)

![Image of Ballmer](https://upload.wikimedia.org/wikipedia/commons/2/21/Steve_Ballmer_at_CES_2010_cropped.jpg)

*CC BY 2.0 Microsoft Sweden*

--

### Aujourd'hui (Post-2014)

![Image of Linux and Microsoft](https://cloudblogs.microsoft.com/uploads/prod/2018/03/ms_loves_linux.png)</p>
<!-- .element: class="fragment fade-up" -->

 Source: Microsoft
<!-- .element: class="fragment fade-up" -->

--

Nadya Nadella (2014)

![Image of Nadella](https://upload.wikimedia.org/wikipedia/commons/1/19/Satya_smiling-print.jpg)


*CC BY 4.0 Brian Smale and Microsoft*


---
## Tout va pour le mieux dans le meilleur des mondes?

#### Non, loin de là
<!-- .element: class="fragment fade-up" -->

--

* L'informatique bureautique
<!-- .element: class="fragment fade-up" -->

* La centralisation des données (cf. Chenal)
<!-- .element: class="fragment fade-up" -->

* Fracture numérique (cf. Intergen)
<!-- .element: class="fragment fade-up" -->

---

## Matériel, l'âge des ténèbres

Constat n°2 :

```
Le matériel libre est l'exception plus que la règle
```
<!-- .element: class="fragment fade-up" -->

* Le matériel est essentiel, c'est le composant fondamental sur lequel on cronstruit l'univers numérique. Sans confiance dans la matériel, pas de confiance possible dans le logiciel.
<!-- .element: class="fragment fade-up" -->

---

* Le matériel embarque des composants logiciels qui échappent à l'autorité et à la vigilance du système d'exploitation. 
<!-- .element: class="fragment fade-up" -->

---

#### Que sont-ils?

Micrologiciels, microprogrammes, logiciels embarqués ou microcodes (firmware)
<!-- .element: class="fragment fade-up" -->

---

#### Par rapport à l'ordinateur, ils sont:

* *Internes*: Intel Active Management Technology; UEFI
<!-- .element: class="fragment fade-up" -->

* *Externes*: logiciels pour périphériques (disques durs; SSD; etc)
<!-- .element: class="fragment fade-up" -->

---

![rings](https://drive.google.com/open?id=1t1IaDnslpR7Y3b-qL9BW7J7kdF4XPjOD)

---

### Welcome to *Ring -3* Hell

* What the f*** is MINIX? 
<!-- .element: class="fragment fade-up" -->

 * MINIX = Intel Management Engine
<!-- .element: class="fragment fade-up" -->

 * Système d'exploitation avec micro-noyau
<!-- .element: class="fragment fade-up" -->

 * Son père, c'est Andrew Tannebaum, le professeur de Torvald.
<!-- .element: class="fragment fade-up" -->

* Qui a gagné entre MINIX et Linux?
<!-- .element: class="fragment fade-up" -->
 
 * MINIX domine Linux
<!-- .element: class="fragment fade-up" -->

---

## Démo time

```dmesg```

--- 
Le système d'exploitation se fait exploiter.

---

![iceberg](https://drive.google.com/opssen?id=1B-levKNoHgmGP--f9cIV002qExkWwbIo)

---


* Le matériel est très complexe, et propriétaire </p>
<!-- .element: class="fragment fade-up" -->

|*Apprentissage automatique*|*Informatique d'infrastructure*| *Informatique embarquée* | *Chaîne de bloc*
|:-:|:--:| -:|
|GPU (Nvidia), TPU (Google) | CPU (Intel) | CPU (ARM)| CPU (Intel) & GPU (NVIDIA)

---

Récapitualif:

|Type|Degrées de liberté|
|:-:|:--:| 
|Logiciel (software)|Grande|
|Micrologiciel (firmware)| Limitée |
|Matériel (hardware)| Anecdotique |

---

* Le matériel a trahi notre confiance
* Il mérite notre défiance

---

#### What to do? 
* Axe n°1. Sauver les meubles: neutraliser le matériel existant
<!-- .element: class="fragment fade-up" -->

* Axe n°2 : Créer des nouveaux composants matériels
<!-- .element: class="fragment fade-up" -->

---
### Neutraliser

* Coreboot 
    * Projet pour remplacer le BIOS & l'UEFI 
    * Disponible par défaut chez Puri.sm & System 76

---
### Neutraliser

* Neutraliser le *Intel Mangement Engine*
    * https://github.com/corna/me_cleaner

* Project NERF (Google)
    * Projet pour neutraliser d'autres éléments, comme le Intel Management Engine. 
    * "*Replace your exploit-ridden
firmware with a Linux kernel*"

---
### Neutraliser

* Untrust the CPU
   * https://media.ccc.de/v/33c3-8014-untrusting_the_cpu
---

### Créer 

* CPU 
   * RISC V
   * https://riscv.org/

---

### Créer 

* Open Compute Project (GAFAM)
   * http://www.opencompute.org/
---

### Le futur

* GPU ?
* TPU ?
* Quantum computing?

---

## Conclusion
### Question ouverte

* Il faut soutenir le libre car c'est bon moralement, économiquement, écologiquement
<!-- .element: class="fragment fade-up" -->

* Les GAFAM sont très investis dans le libre (logiciel et matériel)
<!-- .element: class="fragment fade-up" -->

* Peut-on soutenir le libre sans que cela ne bénéficie pas aux GAFAM, et si oui, comment?
<!-- .element: class="fragment fade-up" -->

---

## Licence 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" />

</a>Lukas à Porta<br />

Cette œuvre est mise à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Licence Creative Commons Attribution 4.0 International</a>.


Note:
https://refrech.sandcats.io/shared/zR16LGW-IM60NaEPfQniKOgPQ2VSajZDGb1NZTIGfol

https://tinyurl.com/libreetvous

