---
marp: true
theme: gaia
_class: lead
backgroundColor: #fff
paginate: true
backgroundImage: url(./images/foot4.jpg)
footer: 'Cyber Security Awareness Training, 2023, CC BY SA, Lukas Greve'
---

<!-- _paginate:  -->
<!-- _backgroundImage:  -->
<!-- _color: white  -->
<!-- _footer: . -->

<style scoped> h2{ font-size: 400%; font-weight: }</style>
<style scoped> h3{ font-size: 250%; font-weight: }</style>

## Cyber Security
### Awareness training 
### 2023

![bg 100%](./images/recursive.jpg)

---

<style scoped> { font-size: 350%; }</style>


### *Plan*

1. *Introduction*
2. *Crash course on information security*
3. *The threat landscape*
4. *How to improve your security posture*

---

# 1. Introduction

---

<!-- _header: 1. Introduction -->

## Questions driving this presentation

- *What is information security?*
- *What should I be aware of when it comes to cyber-security threats?* 
- *How can I improve my personal security posture and mitigate cyber-security threats?*

<!--
Who I am?: I am Lukas Greve, from Geneva. During the day, I work for an IT company. During the night, I sleep.
Audience: this training has been designed to be consumed by members of an organization that are not part of the IT department (e.g. project managers; recruiters; communication specialists; etc)
Just like articles in Wikipedia, this presentation is free and open: you are free to copy it, to modify it and to share it
-->

---

# 2. Infosec crash course

---

<!-- _header: 2. Infosec crash course -->

## Terminology
- **Information security**: the study of how to maintain the confidentiality, the integrity and the availability of digital information 
  - Information security is often abreviated as *infosec*
- [**Holistic security**](https://holistic-security.tacticaltech.org/): blend physical, psycho-social and information security together. 
  - Concept introduced by the German-based NGO [Tactical Tech](https://tacticaltech.org/) 
- **Encryption**: a process to make a discrete piece of information undecipherable without a specific method

<!--
In this training, the cyber and information suffixes are used interchangeability (e.g information security and cyber security). Both suffixes refers to what is happening online.

Threats and risks are used interchangeability.

A robust defense exists when risk mitigation tactics are used both online and offline.

In this training, we will focus on information security threats.
-->

---

<!-- _header: 2. Infosec crash course -->

## Guidelines

- Information OR security 
  - Information security is a process not an end state 
  - There is always a non-zero risk
- Information that doesn't exist as bits of data does not need to be secured
  - See also [*Data Is a Toxic Asset*](https://www.schneier.com/blog/archives/2016/03/data_is_a_toxic.html)

---

<!-- _header: 3. The threat landscape -->

## Cyber Powers: a ranking

<style scoped>table { font-size: 55%; width: 70%}</style>

| Rank |        2020 |        2022 |
| ---- | ----------: | ----------: |
| 1    |          US |          US |
| 2    |       China |       China |
| 3    |          UK |      Russia |
| 4    |      Russia |          UK |
| 5    | Netherlands |   Australia |
| 6    |      France | Netherlands |
| 7    |     Germany | South Korea |
| 8    |      Canada |     Vietnam |
| 9    |       Japan |      France |
| 10   |   Australia |        Iran |
| 11   |      Israel |     Germany |
| 12   |       Spain | **Ukraine** |


<!--
Ukraine from number 25 in 2020 to number 12 in 2022
-->

---

<!-- _header: 3. The threat landscape -->

### Russia's Advanced Persistent Threats (APTs) actors

| Name |        Affilation | Known for |
| ---- | ----------: | ----------: |
| [Sandworm](https://en.wikipedia.org/wiki/Sandworm_(hacker_group)) or Voodoo Bear | GRU | [NotPetya](https://en.wikipedia.org/wiki/Petya_and_NotPetya), 2017 cyber attack on Ukraine |
| [Fancy Bear](https://en.wikipedia.org/wiki/Fancy_Bear) or APT28 | GRU | US elections medling |
| [Cozy Bear](https://en.wikipedia.org/wiki/Cozy_Bear), or APT29 | SVR or FSB | US elections medling  |

<!--
APTs operating in the West are lesser known, and less studied. The Equation Group is believed to be associated to the NSA.

Fancy Bear + Cozy Bear = Grizzly Steppe

Other examples: black hat hackers
-->

---

<!-- _header: 3. The threat landscape -->

## Part of NSA's toolkit in 2009

![width:700px](./images/NSA_COTTONMOUTH-I-cropped.png)

- Now [available online](https://shop.hak5.org/products/omg-cable) for less than 200$ (in 2023)


---

<!-- _header: 3. The threat landscape -->

## Threats categorized

---

<!-- _header: 3. The threat landscape -->

## Attack vectors


| **Threats**    |Advanced                                                                                                                                                                                                                                                                                                                                                                 | Simple                                                                                            |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| *Targeted*     | E.g. Zero-click remote exploits (i.e [Pegasus spyware](https://en.wikipedia.org/wiki/Pegasus_%28spyware%29)); coordinated [smear campaigns](https://en.wikipedia.org/wiki/Smear_campaign#:~:text=A%20smear%20campaign%2C%20also%20referred,applied%20to%20individuals%20or%20groups.) fueled by a [Troll farm](https://en.wikipedia.org/wiki/Troll_farm) | E.g. [Spear phishing](https://en.wikipedia.org/wiki/Phishing)                                     |
| *Non-targeted* | E.g. [Ransomware](https://en.wikipedia.org/wiki/Ransomware) attacks                                                                                                                                                                                                                                                                                                      | E.g. Generic phishing email or [Advance-fee](https://en.wikipedia.org/wiki/Advance-fee_scam) scam |


<!--
As time passes, what was considered an advanced threat is becoming a simple one (e.g. ransomware as a service)

One could add one temporal dimension, differentiating between persisting and transient threat. See for instance APTs.

See the ANT Catalog https://en.wikipedia.org/wiki/ANT_catalog
-->


---

<!-- _header: 3. The threat landscape -->

## Petya ransomware message

![width:800px](./images/Petya-Random.png)

---

<!-- _header: 4. Learn how to tackle online threats -->

## Phishing email: sanity checks

<style scoped>table { font-size: 70%; width: 90%}</style>


| Checks |  | Action |
| --- | --- | --- |
| *Does it ask you to act **quickly** to execute a **sensitive** operation?* | :white_check_mark: | **Contact the person directly to verify, using another mean of communication** |
| *Is it poorly written?* | :white_check_mark: | **Common mistakes might be indicative of a scam. Confirm with the sender and report it.**  |
| *Has it been sent using the domain of the company associated to the sender?* | :x: |  **If not, it most likely a scam. Report it**  |
| *If the message asks you to login or reset your password, can you be sure that you initiated the request?* |  :x:   |  **If not, it is most likely a phishing attempt. Report it** |

---

<!-- _header: 4. Learn how to tackle online threats -->

## Phishing email example

![Trusted Bank phishing email](./images/Trusted-Bank-phishing-email.png)

---

<!-- _header: 4. Learn how to tackle online threats -->
<style scoped> { font-size: 160%}</style>

### How to surf online safely

- Separate your professional life from your personal one
- Don't log to personnal account online using your company laptop. 
  - If you do need to so, use the private mode
- Use an ad blocker (e.g. *uBlock Origin*) if allowed by your company policy
  - Targeted ads may be used for nefarious purposes  
- If you have a company-provided password manager, don't let allow your browser to store your passwords
- Use second factor authentication wherever available
- Only browse on known and previously vetted websites

---

<!-- _header: 4. Learn how to tackle online threats -->

### How share information online

- Emails are rarely not end-to-end encrypted (E2EE)
- Most real-time messaging applications are not end-to-end encrypted
- Mobile applications such as WhatsApp or Signal are end-to-end crypted

---

<!-- _header: 4. Learn how to tackle online threats -->

### How to encrypt sensitive data, and use full disk encryption

---

<!-- _header: 4. Learn how to tackle online threats -->

### Your computer

Don't delay updates. Especially for your Internet Browser.

Use only one Internet Browser

---

## Sources

- https://en.wikipedia.org/wiki/Fancy_Bear#/media/File:APT28_APT29_Techniques_-_Malware.png
- https://commons.wikimedia.org/wiki/File:Petya.Random.png
- *National Cyber Power Index 2020 & National Cyber Power Index 2022 by the Belfer Center from Hardware Kennedy School*

---

## Resources

<style scoped>table { font-size: 60%; width: 100%}</style>

| Type       |                                                     Nom et URL                                                      |                                                                                      Description |
| ---------- | :-----------------------------------------------------------------------------------------------------------------: | -----------------------------------------------------------------------------------------------: |
| Resources  |                                 https://privacytools.is                                | “Privacy Tools” est un site web avec une bonne liste d’outils et de services orientés vie privée |
| Resources |                                https://prism-break.org/                              | “Privacy Tools” est un site web avec une bonne liste d’outils et de services orientés vie privée |
| Logiciel |    https://f-droid.org   | F-droid est un magasin d’applications pour téléphones Android. C’est une alternative au Play Store de Google |
| ONG  | [The Privacy Lab](https://privacylab.yale.edu/)|      Ce laboratoire sur la vie privée propose notamment un guide sur la vie privée en ligne |
| ONG  | [Hermes](https://www.hermescenter.org) | Hermes développe plusieurs outils, dont “Globaleaks”, une plateforme pour lanceurs d’alerte |
| ONG  | [Hermes](https://www.hermescenter.org) | Hermes développe plusieurs outils, dont “Globaleaks”, une plateforme pour lanceurs d’alerte |

