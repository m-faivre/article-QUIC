# Analyse du Protocole QUIC & HTTP/3

⚠️ **Note : Ce document est un travail en cours. Certaines sections sont encore à l'état d'ébauche.**

Dossier de recherche technique.

📄 **[Voir le document PDF](./QUIC.pdf)**

## Points abordés
* **Architecture :** Encapsulation UDP et structure des paquets (Long/Short Headers)
* **Performance :** Comparatif Latence/Débit face à TCP et mécanismes de Handshake (0-RTT)
* **Sécurité :** Intégration native de TLS 1.3 et chiffrement des métadonnées
* **Mobilité :** Le mécanisme de *Connection Migration* (changement d'IP sans coupure)
* **Benchmarks :** Analyse de l'impact CPU et du déchargement matériel (GRO/GSO)
