# 🎮 Testeur de Manette 100%

Un testeur de manette **100% en HTML/JS**, dans un seul fichier — transportable sur clé USB, envoyable par mail, ou hébergeable n'importe où. Aucune installation.

👉 **Double-clique sur `index.html`** (de préférence avec **Chrome** ou **Edge**).

## Ce que ça teste

### Pour toutes les manettes (Gamepad API)
- ✅ Tous les **boutons** (avec valeur analogique)
- ✅ Les deux **sticks** analogiques (visualisation + valeurs X/Y)
- ✅ La **pression des gâchettes** L2/R2 en force 0–100 %
- ✅ Test de **vibration** (moteur fort / faible, durée réglable)
- ✅ Fréquence de rafraîchissement (Hz)

### Avancé — DualSense & DualShock 4 (WebHID, Chrome/Edge)
- ✅ **Gyroscope** (pitch / yaw / roll)
- ✅ **Accéléromètre** (X / Y / Z)
- ✅ **Pavé tactile** : position du/des doigt(s) en direct
- ✅ **Détection de quadrant au clic** : haut-gauche, haut-droite, bas-gauche, bas-droite
- ✅ **Batterie**
- ✅ **Résistance des gâchettes** (adaptive triggers, DualSense uniquement) : mode rigide ou pulsation, force et position réglables
- ✅ Couleur de la **barre lumineuse** (DualSense)

> ℹ️ Le gyroscope et le pavé tactile sont des **composants physiques** : seules les manettes **PlayStation (DualShock 4 et DualSense)** en sont équipées. Les manettes Xbox/génériques n'en ont pas.

## Conseils
- Branche la manette en **USB** de préférence (plus fiable, et indispensable pour la résistance des gâchettes ; le Bluetooth est géré avec CRC).
- WebHID (gyro, pavé tactile, résistance) ne fonctionne que sur **Chrome / Edge desktop**. La partie boutons/sticks/gâchettes/vibration marche dans tous les navigateurs récents.
- Clique sur « Connecter une manette » puis choisis la manette dans la fenêtre du navigateur.

## Compatibilité
| Fonction | Navigateur | Manettes |
|---|---|---|
| Boutons, sticks, gâchettes, vibration | Chrome, Edge, Firefox… | Xbox, PlayStation, génériques |
| Gyro, accéléromètre, pavé tactile + quadrant | Chrome, Edge (desktop) | DualShock 4, DualSense |
| Résistance des gâchettes, LightBar | Chrome, Edge (desktop) | DualSense / DualSense Edge |
