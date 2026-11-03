# JARVIS Lite V1 — gratuit sur iPhone / iPad

## Ce que fait la V1
- Tableau de bord et briefing des tâches
- Assistant à commandes (pas une IA générative)
- Tâches, notes, suivi manuel des revenus et dépenses
- Préférences enregistrées localement
- Export / import JSON des données
- Application web installable (PWA), cache hors ligne après première visite

## Installation avec iPhone ou iPad uniquement
1. Télécharge et décompresse `jarvis-lite.zip` dans l'application **Fichiers**.
2. Crée un compte gratuit GitHub si tu n'en as pas.
3. Dans Safari, ouvre github.com, crée un dépôt **public** nommé `jarvis-lite` (sur GitHub gratuit, Pages pour ce cas est disponible avec un dépôt public).
4. Dans le dépôt, utilise **Add file > Upload files** (si nécessaire, active « Version pour ordinateur » dans Safari). Téléverse les **quatre fichiers** `index.html`, `manifest.webmanifest`, `sw.js` et `icon.svg` à la racine du dépôt, puis valide.
5. Dans **Settings > Pages**, sélectionne **Deploy from a branch**, branche `main`, dossier `/(root)`, puis enregistre.
6. Attends le déploiement. Ouvre l'adresse fournie par GitHub Pages, typiquement `https://TON_IDENTIFIANT.github.io/jarvis-lite/`.
7. Dans Safari : **Partager > Sur l'écran d'accueil > Ajouter**.
8. Ouvre JARVIS depuis l'icône. Il fonctionnera hors ligne après une première visite réussie (et tant que le cache n'est pas supprimé).

### Important : confidentialité
GitHub Pages publie le **code source**, pas les notes et tâches que tu saisis : elles restent dans le stockage local de Safari sur chaque appareil. **N'ajoute jamais tes données personnelles dans les fichiers du dépôt.** Le stockage navigateur peut être effacé. Utilise régulièrement **Réglages > Exporter mes données** pour conserver une sauvegarde dans Fichiers. Les données ne sont pas synchronisées entre appareils ; tu peux transférer une sauvegarde manuellement.

### Limites
- Pas de modèle IA génératif, d'accès Gmail ou Calendar, de notifications système ni de surveillance en arrière-plan dans cette V1.
- Pas de compte, de synchronisation ni de serveur.
- GitHub Pages est un hébergement public pour le code, pas un serveur privé.
- Le solde affiché est la somme des opérations saisies, pas le solde bancaire réel.
- Pour une V2 avec IA, il faudra ajouter une source de modèle et gérer les clés et quotas sans les exposer dans le frontend public.
