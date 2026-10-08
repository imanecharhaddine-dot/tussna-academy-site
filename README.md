# Tussna Academy — site statique

Site vitrine de Tussna Academy, programme d'accompagnement IA porté par Adoulim Consulting.

## Structure

```
/
├── index.html          # redirige vers /fr/
├── fr/                  # version française (complète)
├── en/                  # version anglaise (placeholder, à traduire)
├── ar/                  # version arabe (placeholder RTL, à traduire)
└── assets/
    ├── css/style.css    # palette, typographie, composants
    └── js/main.js       # menu mobile, état actif de la navigation
```

## Déploiement sur Hostinger

1. Pousser ce dépôt sur GitHub.
2. Dans Hostinger (hPanel), utiliser "Git" sous l'hébergement pour connecter le dépôt, ou déployer via un pipeline GitHub Actions → FTP/SFTP.
3. Pointer le nom de domaine sur le dossier racine du site (celui qui contient `index.html`).

Aucune étape de build n'est nécessaire : HTML/CSS/JS statiques, prêts à l'emploi.

## À faire avant mise en ligne

- [ ] Remplacer la palette provisoire (variables CSS dans `assets/css/style.css`, section `:root`) par le moodboard définitif.
- [ ] Traduire les pages `en/` et `ar/` (actuellement des pages miroir avec bandeau "contenu à venir").
- [ ] Brancher les formulaires (`contact.html`, `devis-entreprise.html`, `devis-particulier.html`) à un service d'envoi (ex. Formspree, Resend, ou un backend propre) — actuellement `action="#"`.
- [ ] Ajouter le logo réel (actuellement texte "Tussna Academy").
- [ ] Vérifier les textes juridiques de la charte éthique avec un juriste avant publication.
