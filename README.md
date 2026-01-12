# Analyse du Protocole QUIC & HTTP/3

⚠️ **Note : Ce document est un travail en cours (WIP). Certaines sections sont encore à l'état d'ébauche.**

Dossier de recherche technique réalisé dans le cadre de ma formation d'Administrateur Systèmes et Réseaux. L'objectif est d'analyser le fonctionnement de QUIC (RFC 9000) et ses différences avec TCP.

📄 **[Voir le document PDF](./QUIC.pdf)**

## Points abordés
* [cite_start]**Architecture :** Encapsulation UDP et structure des paquets (Long/Short Headers)
* [cite_start]**Performance :** Comparatif Latence/Débit face à TCP et mécanismes de Handshake (0-RTT)
* [cite_start]**Sécurité :** Intégration native de TLS 1.3 et chiffrement des métadonnées
* [cite_start]**Mobilité :** Le mécanisme de *Connection Migration* (changement d'IP sans coupure)
* [cite_start]**Benchmarks :** Analyse de l'impact CPU et du déchargement matériel (GRO/GSO)
