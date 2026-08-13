# prototype-site-agence

[![Netlify Status](https://img.shields.io/badge/Netlify-deployed-brightgreen?logo=netlify)](https://deploy-preview-1--mgc-inc.netlify.app)

Site vitrine pour une agence digitale (prototype).

Déploiement

- Branche de déploiement: `jcdurce-legendary-garbanzo`
- Netlify: connecté au repo ; voir le deploy preview pour vérifier les changements.

Formulaire

Le formulaire utilise Netlify Forms (data-netlify). Les soumissions sont gérées par Netlify. Pour notifier par email ou webhook, configurez les notifications dans le tableau de bord Netlify (Project > Forms).

Analytics (optionnel)

Ajoutez votre snippet d'analytics (Google Analytics, Plausible, etc.) dans le `<head>` de `index.html`. Exemple (GA4) :

<!--
<!-- Google Analytics 4 example (replace G-XXXXXXX) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);} gtag('js', new Date());
  gtag('config', 'G-XXXXXXX');
</script>
-->

Contribuer

1. Créez une branche depuis `main` ou la branche de travail.
2. Ouvrez une PR et demandez une revue.

Licence

MIT
