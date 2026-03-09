
# Compétences de Recherche (Search Skills)

Cette section couvre les compétences de recherche essentielles pour un professionnel en cybersécurité, apprises dans le cadre du parcours **Cyber Security 101** sur TryHackMe.

---

## 1. Évaluation des sources d'information

Sur Internet, tout le monde peut publier du contenu : blogs, articles, réseaux sociaux, wikis… Il est donc crucial de savoir évaluer les informations :

- **Source** : Identifier l’auteur ou l’organisation. Sont-ils réputés et fiables ?  
- **Preuves et raisonnement** : Les affirmations sont-elles appuyées par des faits ou des arguments solides ?  
- **Objectivité et biais** : Le contenu est-il impartial ou vise-t-il à promouvoir un produit ou attaquer un rival ?  
- **Corroboration** : Vérifier les informations auprès de plusieurs sources fiables et indépendantes.

⚠️ Attention aux méthodes ou produits de sécurité **"Snake oil"** : ce sont des solutions prétendument sécurisées mais **bogus ou frauduleuses**.

---

## 2. Utilisation efficace des moteurs de recherche

Les moteurs de recherche classiques comme **Google, Bing, DuckDuckGo** permettent des recherches avancées via des opérateurs :

- **"phrase exacte"** : Cherche la phrase exacte, ex. `"passive reconnaissance"`.  
- **site:nomdusite.com** : Limite la recherche à un domaine spécifique, ex. `site:tryhackme.com cyber security`.  
- **-mot** : Exclut un mot des résultats, ex. `pyramids -tourism`.  
- **filetype:extension** : Cherche des fichiers spécifiques, ex. `filetype:pdf cyber warfare report`.

---

## 3. Moteurs de recherche spécialisés

Certains moteurs sont conçus pour rechercher des types précis de ressources :

- **Shodan** : Recherche des appareils connectés à Internet (serveurs, routeurs, IoT).  
  Exemple : vérifier quels serveurs utilisent `lighttpd` et leur répartition par pays.  

- **Censys** : Recherche des hôtes, sites web, certificats et autres actifs Internet.  

- **VirusTotal** : Analyse des fichiers ou URL avec plusieurs antivirus.  
  Exemple : le fichier avec le hash `2de70ca737c1f4602517c555ddd54165432cf231ffc0e21fb2e23b9dd14e7fb4` est détecté comme **Android.Riskware.Agent.LHH** par BitDefenderFalx.  

- **Have I Been Pwned (HIBP)** : Vérifie si une adresse e-mail apparaît dans une fuite de données.

---

## 4. Commandes Linux utiles pour la recherche et la surveillance

- **ss (socket statistics)** : Remplace `netstat` sur Linux pour afficher les connexions réseau et ports d’écoute.  
- **cat** : Affiche le contenu d’un fichier dans le terminal.  
- **man commande** : Affiche le manuel d’une commande.  
- Exemple : `man ip` ou `man ss`.

---

## 5. Documentation technique

La documentation officielle est la source la plus fiable pour tout produit ou logiciel. Exemples :

- **Linux** : Pages man (`man commande`) pour chaque commande ou fonction.  
- **Windows** : Microsoft Technical Documentation, ex. `ipconfig`.  
- **Autres produits** : Snort, Apache, PHP, Node.js…  

---

## 6. Réseaux sociaux et veille

- Utiliser les réseaux sociaux (**LinkedIn, Twitter, Facebook**) pour trouver des informations publiques sur des personnes ou entreprises.  
- Vérifier les réponses à des questions secrètes ou indices pouvant compromettre la sécurité.  
- Suivre des groupes et sites d’actualité spécialisés pour rester à jour sur les tendances cybersécurité.

---

## 7. Exemples pratiques

- Recherche avancée Google : `filetype:pdf cyber warfare report` → limite la recherche aux PDF contenant ces termes.  
- Analyse d’un fichier suspect avec VirusTotal : détecté par **BitDefenderFalx** comme **Android.Riskware.Agent.LHH**.  
- Utilisation de `ss` pour obtenir les **socket statistics** et surveiller les connexions actives.  
- Lecture et inspection de fichiers `.xz` ou autres formats compressés pour vérifier leur contenu avant exécution.

---

### Conclusion

Maîtriser ces compétences de recherche permet de :

- Accéder rapidement à des informations fiables et pertinentes.  
- Réduire la surcharge d’information.  
- Découvrir vulnérabilités, exploits et ressources techniques efficacement.  

Ces compétences sont indispensables pour tout professionnel en **sécurité offensive et défensive**.
