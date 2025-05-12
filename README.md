# 🛡️ Serveurs Proxy – Introduction et Concepts Clés

## 🔍 Qu’est-ce qu’un serveur proxy ?

Un **serveur proxy** agit comme un **intermédiaire** entre un utilisateur (client) et Internet (serveur). Il reçoit les requêtes du client, les traite, puis les transmet au serveur cible. Ensuite, il renvoie les réponses au client.

### Objectifs :
- Masquer l’adresse IP réelle du client
- Contrôler ou filtrer l’accès au réseau
- Améliorer la performance (mise en cache)
- Renforcer la sécurité ou la confidentialité

---

## ⚙️ Fonctionnement d’un proxy

1. Le client envoie une requête au proxy (ex: demande d'une page web).
2. Le proxy traite cette requête et peut :
   - **Filtrer**, **modifier**, ou **enregistrer** la requête.
   - **Bloquer** ou **rediriger** selon des règles définies.
3. Le proxy relaie la requête au serveur final.
4. Le serveur répond → le proxy intercepte la réponse → la transmet au client.

---

## 🧱 Types de serveurs proxy

| Type                  | Description |
|-----------------------|-------------|
| **Forward Proxy**     | Intermédiaire pour le client, masque son IP. |
| **Reverse Proxy**     | Intermédiaire pour les serveurs, masque l’architecture interne. |
| **Transparent Proxy** | Invisible pour l’utilisateur, utilisé pour surveillance/filtrage. |
| **Anonymous Proxy**   | Cache l’identité du client, mais révèle qu’il s’agit d’un proxy. |
| **Elite Proxy**       | Masque complètement le fait qu’un proxy est utilisé. |

---

## 🧰 Cas d’utilisation courants

- 🕵️ **Anonymat en ligne** : Masquer son IP, éviter la surveillance.
- 🌐 **Contourner la censure** : Accéder à des contenus géo-bloqués.
- 🧑‍💼 **Contrôle d’entreprise** : Surveiller ou restreindre l’accès à certains sites.
- 🚀 **Optimisation** : Mise en cache pour accélérer les accès web.
- 📊 **Surveillance réseau** : Journalisation des activités.

---

## ⚠️ Inconvénients et risques

- 🔓 **Fuite de données** si le proxy est mal configuré ou public.
- 🐢 **Ralentissement du trafic** : surcharge ou latence.
- 🧱 **Blocage de contenu** : certains services détectent les proxies.
- ❌ **Pas de chiffrement** si utilisé sans HTTPS.

---
![Image](https://github.com/user-attachments/assets/377149b6-52b7-4a77-8096-09d3db5ec119)
