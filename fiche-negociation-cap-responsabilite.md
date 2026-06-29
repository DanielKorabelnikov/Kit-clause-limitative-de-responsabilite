# Fiche de négociation — Calibrer un plafond de responsabilité

Cette fiche propose une méthode simple pour déterminer si un plafond de responsabilité est adapté à un contrat IT, SaaS ou numérique.

## 1. Ne pas commencer par le montant

La négociation commence souvent par une position de principe :

- côté fournisseur : plafond limité aux sommes payées sur douze mois ;
- côté client : plafond élevé ou responsabilité illimitée ;
- côté achats : alignement sur une politique interne ;
- côté juridique : recherche d’un équilibre contractuel.

Mais le bon point de départ n’est pas le montant. Le bon point de départ est le risque.

## 2. Les critères à regarder

### Nature du service

Un outil accessoire ne justifie pas nécessairement le même plafond qu’un service critique, une infogérance, une plateforme centrale ou un composant intégré au système d’information.

### Prix du contrat

Un plafond indexé sur le prix payé peut être logique, mais il devient insuffisant si le prix est faible alors que le risque opérationnel est élevé.

### Données traitées

Plus les données sont sensibles, stratégiques ou volumineuses, plus le plafond doit être relu avec les obligations de sécurité, confidentialité et réversibilité.

### Niveau de dépendance

Si le client ne peut pas facilement remplacer le service, récupérer ses données ou maintenir son activité sans le fournisseur, un plafond standard peut être inadapté.

### Obligations essentielles

Le plafond doit rester cohérent avec le cœur du contrat. Si l’obligation principale est la disponibilité, la sécurité, l’intégration ou la sauvegarde, la clause ne doit pas neutraliser toute conséquence utile d’un manquement à cette obligation.

### Assurance

Les montants assurés ne doivent pas dicter mécaniquement le plafond, mais ils constituent un élément utile de discussion.

## 3. Exemples de calibration

### Service accessoire ou faible criticité

Plafond possible : sommes payées au cours des douze derniers mois.

À vérifier : que les exclusions ne rendent pas la réparation illusoire.

### SaaS métier important

Plafond possible : 12 à 24 mois de redevances, avec exceptions ou plafond renforcé pour confidentialité, sécurité, données ou propriété intellectuelle.

À vérifier : cohérence avec les SLA, la réversibilité et les engagements de support.

### Service critique ou fortement intégré

Plafond possible : multiple du prix annuel, plafond spécifique par obligation sensible, ou montant minimum garanti.

À vérifier : continuité de service, sortie, réversibilité, sécurité, preuve, sauvegarde, données et sous-traitance.

### Projet d’intégration complexe

Plafond possible : montant du projet ou pourcentage significatif du prix, avec traitement particulier des retards, non-conformités, abandon de projet et réversibilité.

À vérifier : gouvernance, recette, dépendances client, change requests, preuves et responsabilités partagées.

## 4. Les mauvaises pratiques fréquentes

- Un plafond unique appliqué à tous les contrats sans tenir compte du service.
- Un plafond très bas combiné à une exclusion très large des préjudices.
- Une exclusion totale de la perte de données alors que le fournisseur gère les sauvegardes.
- Une clause qui ne distingue pas les manquements ordinaires et les manquements sensibles.
- Une clause qui ne dit pas si le plafond est global, annuel, par sinistre ou par événement.
- Une clause qui oublie les exceptions légalement nécessaires ou contractuellement sensibles.

## 5. Proposition de matrice simple

| Critère | Faible risque | Risque moyen | Risque élevé |
|---|---:|---:|---:|
| Criticité du service | Accessoire | Important | Critique |
| Données | Peu sensibles | Données métier | Données sensibles ou stratégiques |
| Dépendance | Faible | Moyenne | Forte |
| Remplacement | Simple | Possible avec effort | Difficile |
| Réversibilité | Peu sensible | À organiser | Essentielle |
| Plafond indicatif | 12 mois | 12 à 24 mois ou cap renforcé | Multiple / cap renforcé / minimum garanti |

Cette matrice ne remplace pas l’analyse du contrat. Elle sert à objectiver la discussion.

## 6. Question de clôture

Le plafond proposé est-il compréhensible pour un opérationnel qui devra l’assumer si le projet échoue ?

Si la réponse est non, la clause doit être simplifiée, expliquée ou renégociée.
