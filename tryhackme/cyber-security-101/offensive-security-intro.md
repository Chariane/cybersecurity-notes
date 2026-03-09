# Offensive Security Introduction

## Qu'est-ce que la sécurité offensive ?

La sécurité offensive consiste à **chercher et exploiter les vulnérabilités dans les systèmes** pour identifier les failles avant que de vrais hackers ne le fassent.
C’est la base du **pentesting** et elle est souvent réalisée par la **Red Team**.

---

## Objectifs de la sécurité offensive

* Identifier les failles dans un système
* Comprendre comment les attaques sont réalisées
* Tester les protections existantes
* Apprendre à sécuriser les systèmes après avoir trouvé des failles

---

## Outils et concepts clés

* **Dirb** : scanner de répertoires web pour trouver des routes cachées
* **Gobuster** : similaire à dirb, utilisé pour trouver des dossiers et fichiers cachés
* **SQLMap** : outil pour tester les injections SQL sur des bases de données
* **Hydra** : outil de force brute pour tester la sécurité des mots de passe

---

## Exercice pratique : FakeBank (Attaque)

Dans le laboratoire FakeBank, j’ai appliqué les concepts suivants :

1. **Découverte de routes cachées** :

   * Utilisation de `dirb` pour scanner le site web
   * Identification de routes sensibles ou non protégées

2. **Accès aux routes sensibles** :

   * Accès aux pages administratives simulées
   * Exploration des fonctionnalités disponibles

3. **Exploitation simulée** :

   * Simulation de l’ajout de fonds sur un compte dans un environnement sûr

4. **Analyse des résultats** :

   * Comprendre ce qui a fonctionné et pourquoi
   * Identifier les vulnérabilités exploitables

---

## Ce que j'ai appris

* la différence entre sécurité offensive et défensive
* comment trouver des failles dans un site web
* l’utilisation pratique des outils `dirb`
* comment simuler des attaques dans un environnement sûr
* la nécessité de toujours documenter ses découvertes

---

## Conclusion

La sécurité offensive est cruciale pour **anticiper les attaques** et améliorer la sécurité des systèmes.
Elle permet aux professionnels de **prévenir les risques** en découvrant les failles avant que de vrais hackers ne les exploitent.

https://tryhackme.com/room/offensivesecurityintrokK?utm_campaign=social_share&utm_medium=social&utm_content=share-completed-room&utm_source=copy&sharerId=69160a2145533efb57e9c9a2
