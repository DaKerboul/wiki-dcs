---
title: AV8B
description: 
published: true
date: 2025-07-15T17:53:13.524Z
tags: 
editor: markdown
dateCreated: 2025-07-15T02:25:13.414Z
---

# **AV‑8B N/A Harrier II**

---

## Introduction

Le McDonnell Douglas AV‑8B Harrier II, dans sa version N/A (Night Attack), est un avion d’attaque au sol V/STOL (Vertical/Short Take‐Off and Landing) monoplace développé à la fin des années 1970 pour remplacer l’AV‑8A. Entré en service en janvier 1985 au sein du USMC, il reçoit dès 1989 des capteurs infrarouges et un cockpit modernisé pour les opérations de nuit, devenant l’AV‑8B N/A. Le module **DCS: AV‑8B Night Attack V/STOL by RAZBAM** recrée fidèlement cette variante, offrant un Custom Flight Model poussé, un cockpit 6 DOF cliquable, des systèmes complets et plus d’une vingtaine de pylônes d’armement et de capteurs ([Wikipedia][1], [Digital Combat Simulator][2]).

---

## Historique et caractéristiques techniques

| Caractéristique             | Détail                                                                                           |
| --------------------------- | ------------------------------------------------------------------------------------------------ |
| **Premier vol**             | YAV‑8B : 9 novembre 1978 • AV‑8B : 5 novembre 1981 ([Wikipedia][1])                              |
| **Mise en service**         | janvier 1985 ([Wikipedia][1])                                                                    |
| **Constructeurs**           | McDonnell Douglas / British Aerospace (aujourd’hui Boeing / BAE) ([Wikipedia][1])                |
| **Unités construites**      | 337 AV‑8B (hors prototypes) ([Wikipedia][1])                                                     |
| **Équipage**                | 1 pilote                                                                                         |
| **Dimensions**              | Longueur 14,12 m • Envergure 9,25 m • Hauteur 3,55 m ([Primidi][3])                              |
| **Surface alaire**          | 22,61 m²                                                                                         |
| **Masse à vide**            | 6 340 kg                                                                                         |
| **Masse max. au décollage** | 14 100 kg (roulant) • 9 415 kg (vertical) ([Primidi][3])                                         |
| **Moteur**                  | 1 × Rolls‑Royce Pegasus F402‑RR‑408 vectored‑thrust turbofan, 23 500 lbf (105 kN) ([Primidi][3]) |
| **Vitesse maxi**            | Mach 0,9 (673 mph, 1 083 km/h) ([Primidi][3])                                                    |
| **Rayon d’action**          | 1 200 nmi (2 200 km) ([Primidi][3])                                                              |
| **Plafond opérationnel**    | 15 240 m                                                                                         |
| **Taux de montée**          | 14 700 ft/min (4 485 m/min) ([Primidi][3])                                                       |
| **Armement d’origine**      | 1 × pod GAU‑12 Equalizer 25 mm, 6 pylônes (9 200 lb)                                             |

Conçu pour pallier les limites de l’AV‑8A (charge, rayon, motorisation), l’AV‑8B adopte un aile supercritique agrandie, une verrière surélevée, un fuselage redessiné et un central numérique de mission. La version Night Attack (NA) introduit un capteur NAVFLIR Marconi dans le nez, un HUD élargi, des MFD couleur et des lunettes de vision nocturne Cat’s Eyes, ainsi qu’un système de contre‐mesures renforcé ([Digital Combat Simulator][4], [Digital Combat Simulator][2]).

---

## Développement du module DCS World

* **Éditeur :** RAZBAM Simulations
* **Statut :** Early Access (DCS v2.8.3+)
* **Prix :** 59,99 USD (E‑Shop DCS World)
* **Page officielle** : [DCS: AV-8B Night Attack V/STOL](https://www.digitalcombatsimulator.com/en/shop/modules/av8bna/) ([Digital Combat Simulator][2])
* **Support & communauté** : forums.eagle.ru/c/razbam/av-8b ([Digital Combat Simulator][2])
* **Installation** : via DCS Module Manager, 2,25 Go requis.

### Objectifs de simulation

1. **Fidélité du vol** : Custom Flight Model simulant la poussée vectorielle, les effets VTOL/STOL et la réponse dynamique du Pegasus.
2. **Cockpit immersif** : 6 DOF, textures haute résolution, bump‑mapping, commandes cliquables, HUD et MFDs couleur.
3. **Systèmes complets** : DECS, carburant, hydraulique, ECS, OBOGS, TACAN, ADF, radio, UFC, ODU, VREST, ADC.
4. **Guerre électronique & capteurs** : NAVFLIR, LITENING‑pod, AN/ALE‑39, ALQ‑164 ECM, RWR.
5. **Armement réaliste** : GAU‑12, Sidewinder, Maverick, Mk 80, Paveway, JDAM, CBUs, Harpoon, HARM.

---

## Modèle de vol & avioniques

### Custom Flight Model

* Simulations de vectoring du flux d’échappement, buffeting transsonique, instabilités en VTOL.
* Prise en compte de la poussée auxiliaire, des inverseurs, et de l’inertie caractéristique du Harrier.

### Cockpit & systèmes

* **Cockpit 6 DOF cliquable** avec HUD élargi, 2× MPCD couleur, UFC, ODU et VREST Computer.
* **Avioniques** : DECS (Digital Engine Control System), ADF, TACAN, transpondeur, INS alignable, intercom.
* **Énergie & environnement** : Air Refueling, OBOGS, ECS, système hydraulique et électrique détaillés.
* **Guerre électronique** : AN/ALE‑39, ALQ‑164 ECM Pod, RWR, alertes et localisation.
* **Capteurs** : NAVFLIR Marconi, LITENING‑pod AN/AAQ‑28V. ([Digital Combat Simulator][2])

---

## Armement disponible

| Catégorie              | Munitions principales                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Canons**             | 1 × GAU‑12 Equalizer 25 mm (300 coups)                                                                                      |
| **Missiles air‑air**   | AIM‑9L/M Sidewinder                                                                                                         |
| **Missiles ASM**       | AGM‑65 Maverick TV/IR, AGM‑84 Harpoon (Plus), AGM‑88 HARM                                                                   |
| **Bombes**             | Mk 82/83/84, Paveway II/III, GBU‑38/32/54 (JDAM), CBU‑100/97                                                                |
| **Rockets**            | LAU‑5003 pods (19× CRV7/70 mm), APKWS                                                                                       |
| **Disperseurs & pods** | 6× avions‑moteur AN/ALE‑39, ALQ‑164 ECM, AN/AAQ‑28 LITENING, réservoirs 300–370 gal                                         |
| **Charge utile max.**  | 4 200 kg (9 200 lb) sur 6 pylônes                                             ([Digital Combat Simulator][2], [Primidi][3]) |

---

## Versions & feuille de route

* **v1.0 Early Access** : vol de base, cockpit, armement principal.
* **v1.1–v1.3** : corrections système, retours communauté, nouvelles armes (Harpoon, HARM).
* **À venir** : simulation approfondie du APG‑65 radar (Plus), intégration du LITENING‑pod, campagne navale USMC.

---

## Documentation & ressources

* **Manuel complet** : inclus dans `Mods/aircraft/AV-8B NA/Docs/AV-8B_Harrier_Manual.pdf`.
* **Guides communautaires** : [Chuck’s Guides – AV-8B](https://chucksguides.com/aircraft/dcs/av-8b/) ([chucksguides.com][5])
* **Paintkit** : disponible sur navair.navy.mil (archive).
* **Forums** : [forum.dcs.world – AV-8B N/A](https://forum.dcs.world/topic/348747-harrier-futher-development/) ([ED Forums][6])

---

## Références

* **McDonnell Douglas AV‑8B Harrier II**, *Wikipedia* : [https://en.wikipedia.org/wiki/McDonnell\_Douglas\_AV-8B\_Harrier\_II](https://en.wikipedia.org/wiki/McDonnell_Douglas_AV-8B_Harrier_II) ([Wikipedia][1])
* **DCS: AV‑8B Night Attack V/STOL**, *DCS World E‑Shop* : [https://www.digitalcombatsimulator.com/en/shop/modules/av8bna/](https://www.digitalcombatsimulator.com/en/shop/modules/av8bna/) ([Digital Combat Simulator][2])
* **Specifications AV‑8B Harrier II Plus**, *Technology Trends* : [https://www.primidi.com/.../specifications\_av-8b\_harrier\_ii\_plus](https://www.primidi.com/.../specifications_av-8b_harrier_ii_plus) ([Primidi][3])
* **DCS AV‑8B Harrier II Review**, *Skyward FM* : [https://www.skywardfm.com/post/review-dcs-av8b-harrier-by-razbam-simulations](https://www.skywardfm.com/post/review-dcs-av8b-harrier-by-razbam-simulations) ([skywardfm.com][7])

[1]: https://en.wikipedia.org/wiki/McDonnell_Douglas_AV-8B_Harrier_II "McDonnell Douglas AV-8B Harrier II - Wikipedia"
[2]: https://www.digitalcombatsimulator.com/en/shop/modules/av8bna/ "DCS: AV-8B Night Attack V/STOL by RAZBAM"
[3]: https://www.primidi.com/mcdonnell_douglas_av-8b_harrier_ii/specifications_av-8b_harrier_ii_plus?utm_source=chatgpt.com "McDonnell Douglas AV-8B Harrier II - Specifications (AV-8B Harrier II Plus) | Specifications (AV-8B Harrier II) | Technology Trends"
[4]: https://www.digitalcombatsimulator.com/en/shop/modules/av8bna/?utm_source=chatgpt.com "DCS: AV-8B Night Attack V/STOL by RAZBAM"
[5]: https://chucksguides.com/aircraft/dcs/av-8b/?utm_source=chatgpt.com "AV - Chuck's Guides"
[6]: https://forum.dcs.world/topic/348747-harrier-futher-development/?utm_source=chatgpt.com "Harrier futher development - AV-8B N/A - DCS World Forums"
[7]: https://www.skywardfm.com/post/review-dcs-av8b-harrier-by-razbam-simulations?utm_source=chatgpt.com "Review: DCS AV-8B N/A Harrier II by Razbam Simulations"
