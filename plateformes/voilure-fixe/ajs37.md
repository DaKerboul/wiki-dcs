---
title: AJS37
description: 
published: true
date: 2025-07-15T17:51:52.743Z
tags: 
editor: markdown
dateCreated: 2025-07-15T02:25:10.919Z
---

# **AJS‑37 Viggen**

---

## Introduction

Le **Saab AJS‑37 Viggen** est un avion multirôle supersonique à décollage et atterrissage courts (STOL), développé par le suédois Saab AB dans le cadre du projet STRIL‑60 pour répondre aux besoins de la Flygvapnet (Armée de l’air suédoise) durant la Guerre froide. Entré en service en 1971 puis modernisé dans les années 1990 sous la désignation AJS‑37, il allie une conception innovante (aile delta à plans canards, inversion de poussée) à un central numérique embarqué pionnier pour l’époque. Dans **DCS World**, le module **DCS: AJS‑37 Viggen**, développé par Heatblur Simulations en partenariat avec Eagle Dynamics et The Fighter Collection, offre une reproduction extrêmement détaillée du chasseur‑bombardier : modèle de vol fidèle, cockpit 6‑DOF cliquable, systèmes avioniques complets et armement « smart » ([Wikipedia][1], [Heatblur Store][2]).

---

## Historique et caractéristiques techniques

|                        |                                                                                                                         |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Premier vol**        | 8 février 1967 ([Wikipedia][1])                                                                                         |
| **Mise en service**    | 21 juin 1971 (AJ 37) ([Wikipedia][1])                                                                                   |
| **Retrait du service** | 25 novembre 2005 (dernier AJ 37) ([PlaneHistoria][3])                                                                   |
| **Constructeur**       | Saab AB (Suède) ([Wikipedia][4])                                                                                        |
| **Unités produites**   | 329 exemplaires (1970–1990) ([Wikipedia][1])                                                                            |
| **Équipage**           | 1 pilote                                                                                                                |
| **Dimensions**         | Long. 16,4 m • Envergure 10,6 m • Haut. 5,9 m ([WikiMili.com][5], [Wikipedia][4])                                       |
| **Masse à vide**       | 9 500 kg • Masse max 19 274 kg ([WikiMili.com][5])                                                                      |
| **Moteur**             | 1× Volvo RM8B turbofan (125 kN PC) ([Wikipedia][1])                                                                     |
| **Performances**       | Vitesse maxi Mach 2,1 (2 231 km/h) • Plafond 18 000 m • Rayon d’action 1 820 km ([WikiMili.com][5], [PlaneHistoria][3]) |
| **Surface alaire**     | 46 m²                                                                                                                   |
| **Armement d’origine** | 1× canon Oerlikon KCA 30 mm • 7 000 kg de charges externes ([WikiMili.com][5])                                          |

Conçu pour remplacer simultanément le Saab 32 Lansen (attaque) et le Saab 35 Draken (chasse), le Viggen intègre un central numérique CK37 — premier du genre à circuits intégrés — ainsi qu’un système de navigation TERNAV (terrain‑following radar) pour des raids à très basse altitude ([Wikipedia][1]). Son profil double‑delta couplé à des plans canards offre une portance élevée à basse vitesse, tandis que son inverseur de poussée pneumatique autorise des atterrissages sur pistes réduites d’à peine 500 m ([Wikipedia][1]).

---

## Développement du module DCS World

* **Éditeur** : Heatblur Simulations, en collaboration avec Eagle Dynamics et The Fighter Collection ([Heatblur Store][2], [Digital Combat Simulator][6])
* **Statut** : Early Access (DCS v2.9.17+)
* **Prix** : 59,99 USD sur Heatblur Store et plateformes (non compatible Steam pour licence directe) ([Heatblur Store][2])
* **Site officiel** : [Heatblur Store – DCS: AJS‑37 Viggen](https://store.heatblur.com/products/dcs-ajs37-viggen)
* **Forum & support** : [ED Forums – Viggen Development Updates](https://forum.dcs.world/topic/183950-dcs-ajs-37-development-update-manual-rc1-release/)
* **Dépôt communautaire** : [viggen.training](https://www.viggen.training) pour ressources supplémentaires et tutoriels

### Objectifs de simulation

1. **Fidélité extrême** : flight model basé sur données réelles, y compris effets transsoniques, traînées et inversion de poussée.
2. **Cockpit interactif** : modélisation 6‑DOF avec textures PBR, instruments authentiques (HUD, TID, indicateurs du CK37).
3. **Systèmes complets** : gestion du CK37 (cartouches de mission, time‑on‑target, calcul carburant), navigation inertielle, TACAN, TILS, ADF, transpondeur.
4. **Radar & EW** : PS‑37/A air‑sol avec modes obstacle, mémoire, air‑air ; guerre électronique avec Rb modes homing/warning.
5. **Communauté engagée** : actualisations trimestrielles (versions 1.x → 1.5 …), corrections et enrichissements (AJSF/SH variantes, campagnes). ([Steam Store][7])

---

## Modèle de vol & systèmes avioniques

### Modèle de vol

* **Custom Flight Model** appuyé sur les performances du RM8B, simulations de sursauts de compresseur et de poussée.
* **STOL avancé** : inverseur de poussée pré‑armé, train rétractable renforcé, flaps automatiques.
* **Comportement transsonique** : buffeting, instabilités canard‑delta, inertie notable en virages serrés. ([Wikipedia][1])

### Cockpit et avioniques

* **Central CK37** : interface cartes à puce, calcul de carburant et navigation, MPE pour armes « smart ».
* **HUD** : symbologie TILS, ciblage au sol, guidage missiles, indicateur de vitesse et altitude.
* **TACAN & ADF** : positionnement RADAR et navigation conventionnelle, compatible re‑fueling buddy.
* **Radar PS‑37/A** : modes multi‑amplification, filtrage doppler, recherche air‑sol et détection de cibles navales.
* **Guerre électronique** : module APR‑37 (RWR), alertes sonores, localisation d’émetteurs. ([Steam Store][7])

---

## Armement disponible

| **Catégorie**          | **Exemples (DCS World)**                                                                               |
| ---------------------- | ------------------------------------------------------------------------------------------------------ |
| **Canons**             | 1× Oerlikon KCA 30 mm (125 coups)                                                                      |
| **Missiles air‑air**   | 2× Rb 24J (AIM‑9P) / Rb 74 (AIM‑9L)                                                                    |
| **Missiles ASM**       | RB‑15F antinavire (programmable en waypoints)                                                          |
| **Missiles TV/IR**     | RB 75 (AGM‑65 Maverick) TV‑guidé                                                                       |
| **Disperseur**         | 1× BK 90 Mjölner (cluster munitions)                                                                   |
| **Bombes**             | SB M71 120 kg, Mk 82 227 kg, CBU‑97 (sub‑munitions US)                                                 |
| **Rockets**            | 6× ARAK M/70B 135 mm, pods LAU‑3/A 19× 2,75″                                                           |
| **Pods & équipements** | Pod canon MK 4 HIPEG 20 mm, U95 ECM, éclairage d’atterrissage                                          |
| **Capacité d’emport**  | 7 000 kg sur 9 points (3 fuselage, 6 voilure)                   ([QA Education][8], [WikiMili.com][5]) |

---

## Versions & feuille de route

* **v1.0 Early Access** : vol basique, cockpit, armement principal.
* **v1.2 – v1.5** : raffinement du CK37, intégration BK 90, modes PS‑37/A supplémentaires.
* **v1.6+** : support AJSF/SH variantes, campagne NTTR, scénarios d’exportation à l’étranger (Grèce, Émirats).
* **Futur** : simulation des systèmes ECS, APU, améliorations visuelles et audio, tutoriels vocaux en français.

---

## Équipe de développement & contributeurs

* **Heatblur Simulations** : design, flight model, avioniques
* **Eagle Dynamics** : intégration moteur DCS, tests QA
* **The Fighter Collection** : documentation historique, manuels originaux
* **Communauté** : traducteurs, créateurs de liveries, mission designers (viggen.training)

---

## Documentation & ressources

* **Manuel complet (400 pages)** : inclus dans `Mods/A-37Viggen/Docs/FlightManual.pdf`
* **Paintkit** : `Mods/A-37Viggen/Skins/PaintKit_AJS37.zip`
* **Tutoriels & campagnes** : [viggen.training](https://www.viggen.training)
* **Forum officiel** : [ED Forums – AJS‑37 Viggen](https://forum.dcs.world/topic/183950-dcs-ajs-37-development-update-manual-rc1-release/)
* **Boutique** : [Heatblur Store](https://store.heatblur.com/products/dcs-ajs37-viggen) • [Steam](https://store.steampowered.com/app/411930/DCS_AJS_37_Viggen)

---

## Références

1. **Saab 37 Viggen**, *Wikipedia EN* : [https://en.wikipedia.org/wiki/Saab\_37\_Viggen](https://en.wikipedia.org/wiki/Saab_37_Viggen) ([Wikipedia][1])
2. **Saab 37 Viggen**, *Wikipedia FR* : [https://fr.wikipedia.org/wiki/Saab\_37\_Viggen](https://fr.wikipedia.org/wiki/Saab_37_Viggen) ([Wikipedia][4])
3. **DCS: AJS‑37 Viggen**, *Heatblur Store* : [https://store.heatblur.com/products/dcs-ajs37-viggen](https://store.heatblur.com/products/dcs-ajs37-viggen) ([Heatblur Store][2])
4. **Key Features**, *Steam* : [https://store.steampowered.com/app/411930/DCS\_AJS\_37\_Viggen](https://store.steampowered.com/app/411930/DCS_AJS_37_Viggen) ([Steam Store][7])
5. **DCS AJS‑37 Development Update**, *ED Forums* : [https://forum.dcs.world/topic/183950-dcs-ajs-37-development-update-manual-rc1-release/](https://forum.dcs.world/topic/183950-dcs-ajs-37-development-update-manual-rc1-release/) ([forum.dcs.world][9])

[1]: https://en.wikipedia.org/wiki/Saab_37_Viggen?utm_source=chatgpt.com "Saab 37 Viggen"
[2]: https://store.heatblur.com/products/dcs-ajs37-viggen?utm_source=chatgpt.com "DCS: AJS-37 Viggen – Heatblur Store"
[3]: https://planehistoria.com/saab-37-viggen/?utm_source=chatgpt.com "Saab 37 Viggen: Sweden's Skies Thunderbolt"
[4]: https://fr.wikipedia.org/wiki/Saab_37_Viggen?utm_source=chatgpt.com "Saab 37 Viggen"
[5]: https://wikimili.com/en/Saab_37_Viggen?utm_source=chatgpt.com "Saab 37 Viggen - WikiMili, The Best Wikipedia Reader"
[6]: https://www.digitalcombatsimulator.com/en/shop/modules/viggen/?utm_source=chatgpt.com "DCS: AJS-37 Viggen by Heatblur Simulations"
[7]: https://store.steampowered.com/app/411930/DCS_AJS_37_Viggen?utm_source=chatgpt.com "Save 50% on DCS: AJS-37 Viggen on Steam"
[8]: https://qa.edu.vn/en/Saab_37_Viggen?utm_source=chatgpt.com "Saab 37 Viggen : Name, Development, Design, Operational history Wikipedia, the free encyclopedia » Wiki"
[9]: https://forum.dcs.world/topic/183950-dcs-ajs-37-development-update-manual-rc1-release/?utm_source=chatgpt.com "** DCS AJS-37 Development Update + Manual RC1 Release ** - DCS: AJS37 Viggen - ED Forums"
