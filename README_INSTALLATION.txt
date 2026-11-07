LA LERMUZE – SUIVI HACCP (PWA)

CONTENU
- index.html : application actuelle, adaptée à une installation PWA
- manifest.webmanifest : identité de l’application
- sw.js : cache hors connexion de l’interface
- icon.svg : icône

PARAMÉTRAGE PRÉCHARGÉ
- Eric, Adrien, Nicolas, Émeline, Noé
- Frigo cuisine tropicalisé : 0 à 4 °C
- Frigo Marbre : 0 à 4 °C
- Congélateur réserve : -30 à -18 °C
- Frigo réserve : 0 à 4 °C
- Congélateur laitière : -30 à -15 °C

INSTALLATION
L’application doit être publiée sur une adresse HTTPS (un simple fichier HTML ouvert depuis le téléphone ne suffit pas pour l’installation PWA ni pour le service worker). Une fois publiée : ouvrir l’adresse dans Chrome sur Android > menu ⋮ > Installer l’application / Ajouter à l’écran d’accueil. Répéter sur la tablette.

IMPORTANT – SYNCHRONISATION
Cette version conserve encore les relevés localement sur chaque appareil et fonctionne hors connexion après le premier chargement. Elle n’effectue PAS encore de synchronisation entre téléphone et tablette. Pour partager les données de manière fiable et sécurisée, il faut raccorder un stockage cloud avec authentification et règles d’accès. Ne pas utiliser les deux appareils en production en pensant que les relevés se synchronisent avant cette étape.
