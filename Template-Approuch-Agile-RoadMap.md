###  **Roadmap Produit : Application de Gestion des Réclamations Bancaires**

| **Critères Produit**                | **Version MVP**                                                                       | **Version 1.0**                                                                                  | **Version 1.1**                                                       |
| ----------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| **Besoins adressés**                | Permettre au client de soumettre une réclamation et au service client de la consulter | Ajouter le suivi de réclamation pour le client + gestion interne complète (statuts, affectation) | Génération de rapports, export PDF/Excel, et indicateurs              |
| **Valeur créée pour l’utilisateur** | Dépôt rapide et digitalisé d’une réclamation avec preuve de réception                 | Suivi en temps réel de la réclamation, meilleure réactivité des agents                           | Vue analytique pour les responsables, accès facilité aux historiques  |
| **OKR concerné**                    | Simplifier la soumission des réclamations                                             | Améliorer la transparence et le traitement interne                                               | Offrir des outils de suivi et d’analyse puissants                     |
| **Hypothèses**                      | Les clients veulent éviter les déplacements ou appels pour déposer une réclamation    | Les clients veulent suivre leur demande sans recontacter la banque                               | Les managers ont besoin de rapports et les agents d’un suivi clair    |
| **Contraintes**                     | Formulaire simple, accessible sur mobile                                              | Authentification sécurisée, rôle utilisateur clair                                               | Données sensibles → sécurité, RGPD, traçabilité                       |
| **Initiatives**                     | Créer une interface de dépôt + base de données des réclamations                       | Interface agent complète + espace client de suivi                                                | Génération automatique de rapports, filtres, exportation              |
| **Epics**                           | Soumission de réclamation, accusé de réception, affichage de la liste côté agent      | Suivi client, workflow interne, affectation, commentaires                                        | Reporting, export, indicateurs temps de réponse et taux de résolution |

---

###  **Détails des Versions**

#### ** Version MVP**

* **Besoins adressés** : Permettre à un client de déposer une réclamation en ligne.
* **Valeur créée** : Digitalisation immédiate du dépôt, gain de temps pour les clients et agents.
* **OKR concerné** : Objectif 1 – Simplifier la soumission.
* **Hypothèses** : Les clients préfèrent déposer une réclamation en ligne plutôt que d’appeler.
* **Contraintes** : Interface claire, formulaire simple, base de données prête.
* **Initiatives** : Développement d’un formulaire web, interface agent pour consulter les réclamations.
* **Epics** : Création de la réclamation, consultation initiale, envoi d’un accusé automatique.


#### ** Version 1.0**

* **Besoins adressés** : Permettre au client de suivre l’état de sa réclamation ; offrir aux agents un système de traitement complet.
* **Valeur créée** : Visibilité, efficacité, responsabilisation des agents.
* **OKR concerné** : Objectif 2 et 3 – Transparence + Productivité.
* **Hypothèses** : Le client veut être informé sans relancer ; l’agent veut une vue claire des tâches.
* **Contraintes** : Suivi sécurisé, différenciation des rôles, logique de workflow (statuts, affectation).
* **Initiatives** : Interface de suivi client, tableau de bord agent, système d’assignation.
* **Epics** : Gestion des statuts, commentaires internes, affectation, interface de suivi client.

#### ** Version 1.1**

* **Besoins adressés** : Automatiser la génération de rapports et permettre des exports pour analyse ou audits.
* **Valeur créée** : Amélioration du pilotage, gain de temps pour les responsables, conformité RGPD.
* **OKR concerné** : Objectif 4 – Reporting et analyse.
* **Hypothèses** : Les managers veulent des KPI clairs ; les données doivent être exploitables sans requêtes complexes.
* **Contraintes** : Sécurité des données, gestion des accès, formats d’export standardisés.
* **Initiatives** : Intégration d’un module de reporting + bouton d’export PDF/Excel.
* **Epics** : Reporting mensuel, indicateurs temps de traitement, export des données.