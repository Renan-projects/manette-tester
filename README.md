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

### Avancé — DualSense (WebHID, Chrome/Edge)
- ✅ **Résistance des gâchettes** (adaptive triggers) : mode rigide ou pulsation, force et position réglables
- ✅ **Gyroscope** (pitch / yaw / roll)
- ✅ **Accéléromètre** (X / Y / Z)
- ✅ **Pavé tactile** multi-touch (visualisation 2 doigts)
- ✅ **Batterie** et état de charge
- ✅ Couleur de la **barre lumineuse**

## Conseils
- Pour la **résistance des gâchettes**, branche la DualSense en **USB** (recommandé). Le Bluetooth est géré (CRC) mais moins fiable.
- WebHID (gyro, pavé tactile, résistance) ne fonctionne que sur **Chrome / Edge desktop**. La partie boutons/sticks/gâchettes/vibration marche dans tous les navigateurs récents.
- Clique sur « Connecter une DualSense » puis choisis la manette dans la fenêtre du navigateur.

## Compatibilité
| Fonction | Navigateur |
|---|---|
| Boutons, sticks, gâchettes, vibration | Chrome, Edge, Firefox… |
| Gyro, accéléromètre, pavé tactile, résistance | Chrome, Edge (desktop) |

Manettes : Xbox, PlayStation (DS4/DualSense), génériques compatibles XInput/DInput.
Fonctions avancées : **DualSense** et **DualSense Edge**.
