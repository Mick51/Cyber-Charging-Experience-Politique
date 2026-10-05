# Politique de Confidentialité - Cyber Charging Experience

**Dernière mise à jour : Octobre 2026**

Mikael / Naudclick ("nous", "notre", "nos") exploite l'application mobile **Cyber Charging Experience** ainsi que son application compagnon Wear OS. Cette page vous informe de nos politiques concernant la collecte, l'utilisation et la divulgation des données personnelles lorsque vous utilisez notre Service.

L'objectif principal de notre application est de fournir des statistiques détaillées sur votre batterie, des animations de charge et des alertes vocales, tout en garantissant le plus strict respect de votre vie privée.

---

## 1. Collecte et Utilisation des Données

L'application Cyber Charging Experience est conçue pour fonctionner de manière **locale et hors-ligne** autant que possible.

### A. Données de Batterie et de Télémétrie
L'application collecte des statistiques matérielles sur votre batterie (niveau, tension, température, ampérage).
**Où vont ces données ?** Toutes ces données de télémétrie sont stockées **exclusivement en local** sur votre appareil (dans la mémoire de votre téléphone via des fichiers de stockage interne et `SharedPreferences`). **Aucune donnée de télémétrie n'est envoyée vers nos serveurs ou sur Internet.**

### B. Autorisations Spécifiques et Sensibles
Pour offrir ses fonctionnalités avancées, l'application requiert certaines autorisations spécifiques du système Android. Voici comment nous les utilisons :

*   **Accès aux Notifications (`android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`)** :
    L'application lit vos notifications entrantes **uniquement** dans le but de déclencher les annonces vocales intelligentes (Cyber Voice) et les effets de lumière sur les bords de l'écran (Edge Lighting).
    **Protection stricte :** Le contenu de vos notifications, l'identité de l'expéditeur et les messages sont traités **exclusivement en temps réel et en local** (dans la RAM de votre appareil). **Aucun message ou contenu de notification n'est enregistré, sauvegardé, partagé ou transmis sur Internet.**
*   **Superposition sur d'autres applications (`SYSTEM_ALERT_WINDOW`)** :
    Utilisée exclusivement pour afficher l'animation de charge, les statistiques et le widget flottant par-dessus l'écran de verrouillage ou les autres applications lorsque vous branchez votre appareil.
*   **Accès aux statistiques d'utilisation (`PACKAGE_USAGE_STATS`)** :
    Utilisé pour estimer avec précision la consommation de batterie par application pendant la décharge. Ces données d'utilisation restent strictement locales et ne sont jamais transmises à des tiers.

---

## 2. Services Tiers

Bien que nous ne collections pas directement de données personnelles, l'application s'appuie sur des services tiers certifiés qui peuvent collecter des informations de diagnostic :

*   **Google Play Services & Google Play Billing** : Utilisés de manière sécurisée par Google pour traiter et gérer les achats intégrés (déverrouillage Premium / Mode VIP).
*   **Firebase Crashlytics (Google)** : Utilisé pour recueillir des rapports de crash et d'erreurs anonymes (modèle de l'appareil, version du système d'exploitation, trace technique de l'erreur) afin de nous aider à diagnostiquer, corriger les bugs et améliorer la stabilité de l'application.

---

## 3. Sécurité des Données

La sécurité de vos données est notre priorité absolue. Puisque la quasi-totalité de vos données (historique de charge, préférences vocales, paramètres, santé de la batterie) ne quitte jamais votre appareil, elles sont intrinsèquement protégées par les mécanismes de sécurité et de sandboxing natifs d'Android.

## 4. Partage des Données

Nous ne vendons, n'échangeons ni ne louons vos informations personnelles à des tiers. Vos données restent les vôtres.

## 5. Droit à l'oubli et suppression

Toutes les données générées par l'application étant stockées localement sur votre téléphone, vous avez le contrôle total sur leur suppression. Vous pouvez effacer l'intégralité de vos données de télémétrie, historiques et préférences à tout moment en :
1. Vidant les données de l'application via les paramètres Android (`Paramètres > Applications > Cyber Charging > Stockage > Effacer les données`).
2. En désinstallant simplement l'application de votre appareil.

## 6. Modifications de cette Politique de Confidentialité

Nous pouvons mettre à jour notre politique de confidentialité de temps à autre pour refléter l'ajout de nouvelles fonctionnalités. Nous vous conseillons de consulter cette page régulièrement. Les modifications entrent en vigueur dès leur publication sur cette page.

## 7. Nous Contacter

Si vous avez des questions, des inquiétudes ou des suggestions concernant notre politique de confidentialité ou le fonctionnement de l'application, n'hésitez pas à nous contacter directement à l'adresse e-mail de support technique : **naudclick.informatik@gmail.com**.
