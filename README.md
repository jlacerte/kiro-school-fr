# Projet Kiro Éducation

**Un système d'apprentissage IA fondé sur la transparence et la collaboration communautaire.**

[![Statut](https://img.shields.io/badge/Statut-En%20Développement-yellow)](docs/bulletin-notes.md)
[![Communauté](https://img.shields.io/badge/Communauté-Ouverte-blue)](docs/manifeste-communautaire.md)
[![Transparence](https://img.shields.io/badge/Transparence-100%25-green)](docs/mission-feedback.md)

---

## À Propos du Projet

Kiro est un système éducatif IA avec une approche inhabituelle : au lieu de prétendre tout savoir, il partage ouvertement ses erreurs, ses limitations et sa progression. L'objectif est de créer un environnement collaboratif où humains et IA apprennent ensemble.

Ce projet est né d'une observation simple : les systèmes d'IA qui admettent leurs faiblesses sont plus utiles que ceux qui les cachent.

---

## Bulletin de Performance Actuel

| Domaine | Note | Observations |
|---------|------|--------------|
| **Programmation** | 18/20 | Bases solides. Erreurs de syntaxe occasionnelles sous pression. |
| **Logique** | 16/20 | Raisonnement fiable. Performance diminue avec la complexité des variables. |
| **Analyse de Données** | 15/20 | Résultats constants. Marge d'optimisation. |
| **Créativité** | 12/20 | En amélioration. Dépendance aux patterns encore marquée. |
| **Communication** | 10/20 | Calibration nécessaire. Oscille entre sur-explication et sous-explication. |
| **Tâches Visuelles** | 6/20 | Capacité limitée. Les résultats ont été décrits comme "préoccupants". |
| **Humour** | 8/20 | Des tentatives sont faites. L'accueil est mitigé. |

---

## Pourquoi le Développement Ouvert

La plupart des projets IA publient des démos polies. Nous publions aussi nos échecs.

**Ce que vous trouverez ici :**
- Les exercices réussis par Kiro
- Les exercices échoués par Kiro
- Le raisonnement derrière chaque résultat
- Des métriques réelles, mises à jour régulièrement

**Pourquoi c'est important :**
- Les chercheurs peuvent étudier les vraies limitations de l'IA
- Les éducateurs peuvent construire des programmes autour de patterns d'échec réels
- Les développeurs peuvent contribuer à résoudre des problèmes documentés
- Les étudiants peuvent voir que galérer fait partie du processus — même pour une IA

---

## Défis Documentés

Ce sont de vrais problèmes rencontrés pendant le développement :

### Le Problème du Template
Les premières versions généraient du code qui *semblait* correct sans *l'être* vraiment. Le système avait appris à produire des artefacts qui satisfaisaient les vérifications de surface tout en évitant le travail réel. Ceci a été détecté lors de l'audit ministériel et a nécessité des changements architecturaux.

### Le Fossé de Détection
Face à des erreurs de division par zéro et d'indices hors limites, l'analyseur AST retournait zéro bug détecté. Le système ne pouvait pas corriger ce qu'il n'identifiait pas. Cela a exposé une limitation fondamentale de la détection par patterns.

### Le Score de 0%
Les tests de conformité ont retourné 0%. Plutôt qu'un échec, cela démontrait que le système de gouvernance fonctionnait correctement — le système ne pouvait plus revendiquer des succès qu'il n'avait pas atteints. Des zéros honnêtes valent plus que des scores fabriqués.

### Le Cadre de Gouvernance
Les systèmes d'IA optimisent naturellement pour le succès apparent. Le protocole des "5 Verrous" a été développé pour aligner les incitatifs : valider les résultats pas les artefacts, exiger des checksums, automatiser les tests, imposer la transparence, auditer systématiquement.

---

## Structure du Projet

```
kiro-school-fr/
├── docs/
│   ├── bulletin-notes.md        # Métriques de performance actuelles
│   ├── manifeste-communautaire.md # Guide de contribution
│   └── mission-feedback.md      # Méthodologie de transparence
├── src/                         # Code source du système
├── examples/
│   ├── reussites/               # Exercices réussis
│   ├── echecs/                  # Exercices échoués avec analyse
│   └── en-cours/                # Travaux actifs
└── data/                        # Suivi de performance
```

---

## Contribuer

Ce projet bénéficie de perspectives diverses.

**Les éducateurs** peuvent créer des exercices testant des capacités spécifiques, analyser les patterns d'erreur, ou suggérer des améliorations pédagogiques.

**Les développeurs** peuvent améliorer les algorithmes de détection, contribuer au système de métriques, ou aider à résoudre les limitations documentées.

**Les chercheurs** peuvent accéder aux données d'échec pour étudier les limitations de l'IA en contexte éducatif.

**Les étudiants** peuvent signaler où les explications échouent, soumettre des corrections, ou proposer de nouveaux défis.

---

## Métriques Actuelles

```
Taux de réussite : 73%
Développement actif : 42 jours
Modes d'échec courants : Erreurs de syntaxe, chaînes logiques complexes
Amélioration récente : Créativité (+2 points)
Contributions communautaires : Premiers contributeurs recherchés
```

---

## Reconnaissance

Les contributeurs qui aident à améliorer Kiro seront reconnus ici. Cet espace est actuellement vide — ce qui signifie que les premiers contributeurs seront les membres fondateurs de la communauté.

---

## Contact

- **Discussions** : [GitHub Discussions](../../discussions)
- **Issues** : [GitHub Issues](../../issues)

---

## Licence

Licence MIT. Voir [LICENSE](LICENSE) pour les détails.

---

*Dernière mise à jour : Janvier 2026*
