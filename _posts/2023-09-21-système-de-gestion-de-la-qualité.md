---
layout: post
title: Système de gestion de la qualité
author: Jorge Cataño
---

La qualité des produits ou des services est un sujet vivement débattu depuis plusieurs décennies et a attiré l’attention de nombreux acteurs, dans le but d’atteindre un consensus à ce sujet.

Considérons les cas suivants :

- Pour un acheteur lambda, le prix peut être un indicateur de qualité.
- Pour un organisme public de contrôle, la sécurité du produit est un facteur de qualité.
- Pour un technicien de production, la faible variabilité des unités produites est un indicateur de qualité.
- Pour une entreprise de services, le faible nombre de réclamations des clients est un facteur de qualité.
- ...

Cette liste de critères de qualité peut être aussi longue que le nombre d’évaluateurs impliqués, et semble infinie.

Certains auteurs ont abordé ce sujet en profondeur, et bien que pour certains types de produits/services la définition soit assez mature (par exemple : les produits pharmaceutiques, les aliments, les dispositifs médicaux), dans d’autres domaines, la discussion se poursuit — c’est le cas actuel des critères de qualité pour les logiciels.


## Cadre historique et de référence
Au milieu du XXe siècle, le concept de qualité est devenu essentiel dans les secteurs pharmaceutique et alimentaire, en raison de son impact direct sur la santé des personnes. Cela a conduit à la création d’organismes spécialisés dans le débat et l’établissement de critères pour garantir la qualité de ces produits, comme <a href="https://www.who.int/" target="_blank">l’organisation mondiale de la santé</a> ou <a href="https://www.iso.org/" target="_blank">l’organisation internationale de normalisation</a>.

Dans les années 1990, l'utilisation de systèmes informatisés dans la fabrication de denrées alimentaires et de médicaments a pris de l'ampleur. En conséquence, ces systèmes sont devenus un sujet de discussion en matière de qualité, car les enregistrements générés et les données stockées dans ces systèmes servaient à prendre des décisions de qualité sur les produits destinés à la commercialisation.

En 1997, le gouvernement des États-Unis a publié le règlement fédéral <a href="https://www.fda.gov/medical-devices/medical-device-regulation-and-general-information/21-cfr-part-11" target="_blank">21 CFR part 11</a>, qui énonce les exigences que doivent respecter les systèmes informatiques qui conservent des enregistrements, gèrent les signatures numériques et servent de base à des décisions à fort impact.

En 2002, la FDA a créé <a href="https://www.fda.gov/media/73141/download" target="_blank"> le Guide de validation des logiciels</a>, afin d’établir les normes que doivent respecter les dispositifs médicaux ou les logiciels destinés à soutenir le processus de fabrication des produits médicaux.

Ces deux documents ont servi de cadre de référence dans l’évaluation et la validation des logiciels, et ont permis l’adoption des concepts suivants :

- Exigences des utilisateurs
- Vérification du logiciel
- Validation du logiciel

Ces documents ont été publiés aux États-Unis et définissent un cadre réglementaire pour les exigences de qualité logicielle, mais ils ne s’appliquent pas totalement à l’échelle mondiale.

L’Organisation internationale de normalisation (<a href="https://www.iso.org/" target="_blank">ISO</a>) est un organisme indépendant et non gouvernemental, qui a commencé ses activités au milieu des années 1940 et qui a une portée mondiale. Elle travaille à la définition de normes de qualité applicables à tous types d'organisations.

En 2015, la norme <a href="https://www.iso.org/obp/ui#iso:std:iso:9001:ed-5:v2:fr" target="_blank">ISO 9001 Systèmes de management de la qualité</a> a été publiée. Elle définit les exigences minimales à respecter par une entreprise pour mettre en place et maintenir un système de qualité auditable. Cette norme n’est pas limitée à un type ou à une taille d’entreprise spécifique.

En plus de la norme <a href="https://www.iso.org/standard/62085.html" target="_blank">ISO 9001</a>, d’autres normes autour de la Qualité des systèmes et logiciels (SQuaRE) ont été publiées par l’ISO, parmi lesquelles :

- <a href="https://www.iso.org/standard/80655.html" target="_blank">ISO/IEC 25059:2023 SQuaRE — Modèle de qualité pour les systèmes d’IA</a>
- <a href="https://www.iso.org/standard/61579.html" target="_blank">ISO/IEC 25051:2014 SQuaRE — Exigences de qualité pour les produits logiciels prêts à l’emploi (RUSP) et instructions de test</a>
- <a href="https://www.iso.org/standard/35735.html" target="_blank">ISO/IEC TS 25011:2017 SQuaRE — Modèles de qualité de service</a>


## Système de management de la qualité (SMQ)

La version actuelle ISO 9001:2015 est centrée sur l’établissement d’une philosophie où chaque personne dans l’entreprise prend conscience de son impact sur la qualité des produits et services.

Pour les techniciens directement impliqués dans la production, il est facile de comprendre comment leur gestion influe sur la qualité du produit. Mais pour d’autres collaborateurs, il est plus complexe de s’en rendre compte. C’est encore plus difficile quand l’entreprise vend des produits intangibles comme des logiciels ou des services.

Le Système de management de la qualité (SMQ) est un processus systématique dans lequel toutes les procédures nécessaires à la fourniture d’un produit de valeur au client sont clairement définies et évaluées.

Basé sur le cycle PDCA (Plan-Do-Check-Act), la norme ISO 9001:2015 propose une approche stratégique pour mettre en œuvre le SMQ, avec une logique d’amélioration continue intégrée à tous les processus.


<div style="display:flex; justify-content:center; margin-bottom:20px;margin-top:20px;"> 
    <img src="/assets/images/plan_do_check_act.webp" 
        alt="PDCA" 
        style="width:100%; max-width:600px;"/> 
</div>





Comme mentionné, le SMQ est présent dans toute l’organisation et chaque collaborateur a un impact sur ce système.

C’est pourquoi le SMQ nécessite certains éléments pour atteindre ses objectifs et garantir sa pérennité dans le temps :

- Documentation
- Formation
- Contrôle des changements
- Gestion des écarts et réclamations
- Évaluation des risques
- Standardisation et validation
- Contrôle de la qualité

L’assurance qualité (AQ) est le domaine responsable de piloter ces éléments et de déployer les efforts nécessaires pour toucher chaque personne dans l’entreprise, afin de créer une culture autour de la qualité.

## Références

\[1\] H.T. Garston., Software Quality Assurance - A guide for developers and auditors., CRC Press, 1997

\[2\] K. Naik et P. Tripathy., Software Testing and Quality Assurance - Theory and practice., John Wiley & Sons., 2008

\[3\] J. Tian., Software Quality Engineering - Testing, quality assurance and quantifiable improvement., John Wiley & Sons., 2005