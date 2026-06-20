# Imagerie générale — téléchargements

Application desktop pour les équipes marque : préparer un package visuel étape par étape et exporter un ZIP prêt pour l’import Apollo.

Ce dépôt public ne contient **que les installateurs publiés**. Le code source et la CI restent dans un dépôt privé ; seuls les binaires et les métadonnées de mise à jour sont publiés ici.

---

## Télécharger

**[→ Dernière version](https://github.com/the-boj/imagerie-packager-releases/releases/latest)**

Choisissez l’installateur correspondant à votre machine sur la page de release. Les noms de fichiers incluent la plateforme (`aarch64`, `x64`, etc.).

| Plateforme | Format | Remarques |
|------------|--------|-----------|
| macOS (Apple Silicon) | `.dmg` (`aarch64`) | Signé et notarisé |
| macOS (Intel) | `.dmg` (`x64`) | Signé et notarisé |
| Windows | `.msi` ou `.exe` (NSIS) | Non signé — SmartScreen peut afficher un avertissement ; cliquez sur « Informations complémentaires » puis « Exécuter quand même » |

---

## Mises à jour automatiques

L’application installée vérifie les nouvelles versions via ce dépôt. Aucune action manuelle n’est nécessaire une fois l’app installée : une notification propose d’installer la mise à jour lorsqu’elle est disponible.

---

## Liens utiles

| Usage | URL |
|-------|-----|
| Page de téléchargement | https://github.com/the-boj/imagerie-packager-releases/releases/latest |
| Manifeste updater | https://github.com/the-boj/imagerie-packager-releases/releases/latest/download/latest.json |

---

## À propos de ce dépôt

- **Visibilité :** public — téléchargement sans compte GitHub
- **Contenu :** releases GitHub uniquement (DMG, MSI, EXE, bundles updater, `latest.json`)
- **Source :** non disponible ici ; ce dépôt sert uniquement de canal de distribution

Pour signaler un problème avec l’application, contactez votre administrateur Imagerie ou l’équipe qui vous a fourni l’accès.
